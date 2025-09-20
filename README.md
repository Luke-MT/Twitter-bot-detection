# Twitter-bot-detection
Machine learning system for detecting bot accounts using temporal patterns, tweet embeddings, and user metadata. 
# Models
ML Models: XGBoost with Optuna optimization, Multi-input Neural Network
NLP: RoBERTa-based sentence transformers for tweet embeddings, BERT-base sentence transformers for profile descriptions embeddings
Features: 47 temporal/behavioral features + 384D description embeddings + 768D tweet embeddings
# Features
Temporal Analysis: Posting patterns, inter-tweet intervals, burst detection, Fourier analysis of timing gaps
Content Processing: Mean embeddings from top-10 recent tweets per user
Class Imbalance Handling: Weighted training and threshold optimization 

## Setup
```bash
git clone <repository-url>
cd twitter-bot-detection

pip install -r requirements.txt
```
