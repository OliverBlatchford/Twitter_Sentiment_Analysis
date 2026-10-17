# Twitter Sentiment Analysis: Machine Learning vs. Deep Learning

This project compares two different ways to read tweets and figure out the emotion behind them: a lightweight traditional model (Logistic Regression) and a advanced smart model (DistilBERT).
It was programmed primarily on Google Colab to make use of the GPU as my computer was not powerful to run the transformer.

# What This Project Does
- **Data Cleaning:** Cleans up noisy tweet text by removing links, symbols, and extra characters.
- **Fast Baseline Model:** Uses a simple model (`NLP_Coursework.ipynb`) that runs in seconds and highlights the top words linked to each emotion.
- **Smart Deep Learning Model:** Uses a fine-tuned DistilBERT transformer (`NLP_Coursework2.ipynb`) to read full sentence context and improve overall accuracy.
- - **Built-in Model Evaluation:** Automatically prints a classification report after training, showing precision, recall, and F1-scores across all 6 emotion categories (achieving 93% overall accuracy on GPU in ~5 minutes).
- **Full Report:** Includes a complete project write-up (`NLP Report3.pdf`) breaking down performance, speed trade-offs, and final results.

# Google Colab Links
Click either link below to open and run the code directly in Google Colab:
- [Logistic Regression](https://colab.research.google.com/drive/1JD9ycV07DCm7vgHlihoKYMVl79LwBzpI?usp=sharing)
- [DistilBERT Transformer](https://colab.research.google.com/drive/1T5n24d7opD2KlXkOgEU1PSXvRqcoue7h?usp=sharing)

# How to Run on Google Colab

1. Open the notebook in Google Colab using the link at the top of the repository.
2. In the top menu, click **Runtime** > **Change runtime type** and select **T4 GPU** for faster training.
3. Click the **Folder icon** on the left menu bar to open the Files panel.
4. Drag and drop `Option 1-Training Dataset.csv` directly into that Files panel.
5. Click **Runtime** > **Run all** (or press `Ctrl + F9`).


