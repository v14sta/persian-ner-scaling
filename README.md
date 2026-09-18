# Persian NER: Tokenization Dynamics & Corpus Scaling

Official repository for evaluating Persian Named Entity Recognition (NER) across three architectural generations:
1. **Multilingual Baseline:** `xlm-roberta-base`
2. **Legacy Monolingual Baseline:** `HooshvareLab/bert-fa-base-uncased` (ParsBERT)
3. **Modern Monolingual State-of-the-Art:** `PartAI/TookaBERT-Base`

## Repository Structure
```text
persian-ner-scaling/
├── data/                  # Instructions to retrieve ArmanPersoNERCorpus
├── results_ner/           # Saved metrics (.csv) and prediction logits (.npz)
├── requirements.txt       # Dependencies
└── README.md              # Project overview
