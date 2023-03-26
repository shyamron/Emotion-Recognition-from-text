# Emotion-Recognition-from-text

This is a project for Text Emotion Recognizer using Python and Machine learning algorithms. The datasets are collected from multiple sources.
It classifies 5 basic emotions from texts:
1. Sad
2. Angry
3. Happy
4. Neutral
5. Fear
6. Disgust

Data Sources:
  1. https://huggingface.co/datasets/go_emotions
  2. https://huggingface.co/datasets/dair-ai/emotion
  3. https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp

Machine Learning algorithms used and their Accuracy and Macro-f1 score:
  1. Random Forest: Acc-65.72% & MacroF1-65%
  2. SVM: Acc-62.15% & MacroF1-62%
  3. MultinomialNB: Acc-59.99% & MacroF1-59%
  4. Voting Classifier: Acc-64.25% & MacroF1-60%

Run
1. data_preprocessing.ipynb
2. Model_training.ipynb
3. evaluating.ipynb
