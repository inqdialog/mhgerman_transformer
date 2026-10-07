# mhgerman_transformer
A transformer fine-tuned for Middle High German linguistic analysis

Based on [hmBERT: Historical Multilingual Language Models for Named Entity Recognition](https://huggingface.co/dbmdz/bert-base-historic-multilingual-cased), a BERT-based language model.

Adaptations:
1. Creation of a customized wordpiece-style tokenizer based on a large corpus of edited and diplomatic MHG texts.
2. Domain-adaptive pre-training using masked-language modelling.
3. Task-adaptive training for part-of-speech and morphological analysis.

The .safetensors file is available on request. (Upload to Hugging Face is planned.)
