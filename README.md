# AG News Text Classification (TF-IDF, LSTM, DistilBERT)

This project implements three NLP models on the AG News dataset:

- Logistic Regression + TF-IDF  
- LSTM Neural Network  
- DistilBERT Fine-Tuning (HuggingFace Transformers)

## Results
| Model | Accuracy |
|-------|----------|
| TF-IDF | ~88% |
| LSTM | ~91% |
| DistilBERT | ~94% |

## Confusion Matrix (DistilBERT)
<img width="592" height="547" alt="download" src="https://github.com/user-attachments/assets/21872167-cf17-4552-a289-451dfceab14f" />


## Project Files
- `AG_News_Classification.ipynb` — full code  
- `README.md` — project documentation

## How to Run
- pip install transformers torch scikit-learn
- jupyter notebook AG_News_Classification.ipynb
