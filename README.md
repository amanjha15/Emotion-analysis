Emotion-analysis
Text Classification with BiLSTM + Attention
This project implements a multi-class text classification system using a Bidirectional LSTM with an Attention mechanism in PyTorch.  
The model uses pretrained GloVe embeddings for semantic representation, applies text preprocessing, and employs weighted sampling and early stopping to handle class imbalance and overfitting.  

BiLSTM architecture with Attention for contextual representation  
GloVe embeddings (100d) for semantic understanding  
Preprocessing: tokenization, stopword removal, sequence padding  
Class imbalance handling with Weighted Random Sampling  
Early stopping for improved generalization  
Evaluation using accuracy, precision, recall, and F1-score  


Dataset
The project uses a text classification dataset (`train-00000-of-00001.csv`) with labeled text samples.  
Labels are encoded using LabelEncoder.  

Model Architecture
1. Embedding Layer initialized with pretrained GloVe vectors  
2. Bidirectional LSTM to capture dependencies  
3. Attention Mechanism to focus on informative tokens  
4. Fully Connected Layer for classification  

Results
The model achieved strong accuracy and generalization, with detailed evaluation using precision, recall, and F1-score.  
