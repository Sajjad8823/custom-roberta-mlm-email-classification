# custom-roberta-mlm-email-classification
Custom RoBERTa-style Transformer encoder pretrained from scratch using Masked Language Modeling (MLM) and fine-tuned for 6-class email classification in TensorFlow/Keras (98.96% test accuracy).
• Overview: End-to-end NLP pipeline that trains a Byte-Level BPE tokenizer and a compact 2-layer RoBERTa encoder from scratch on 10,780 emails.
• Pretraining: Uses Dynamic Masked Language Modeling (MLM) with an 80/10/10 masking strategy over 20 epochs, reaching ~79.9% validation masked token accuracy.
• Fine-Tuning & Results: Fine-tuned across 6 categories (forum, promotions, social_media, spam, updates, verify_code), achieving 98.96% test accuracy and a 0.9896 Macro F1-score on 2,697 test emails.
• Tech Stack: Python, TensorFlow, Keras 3, Hugging Face tokenizers & datasets, Scikit-learn.
