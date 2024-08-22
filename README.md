# Bangla & English Named Entity Recognition (NER) with MISTRAL, BERT, and FLAN T5

This repository contains a Name Entity Recognition (NER) system implemented using <b>MISTRAL, BERT, and FLAN T5</b> models. The system can identify and classify:
1. For English: Software and Security Entities such as Software Versions, Programming Languages, Files or Functions, Applications or Software Names, Operating Systems etc.
2. For Bangla:  Persons name, Organizations, and Locations, Email, Phone number, Digit, Objects.

<h2>Features</h2>
MISTRAL: Multi-task Intent, Slot, for robust NER.<br>
BERT: Bidirectional Encoder Representations from Transformers, for contextual word representations.<br>
FLAN T5: Fine-tuned Language-Agnostic NER with Text-To-Text Transfer Transformer.<br>

Load these model from  <a href="https://huggingface.co/models">Hugging Face</a>
```bash
# LLModel's
google-bert/bert-base-uncased # For English
sagorsarker/bangla-bert-base # For Benglai
google/flan-t5-base #For English
mistralai/Mistral-7B-v0.1 #For English
```
For fine-tune Mistral has been used <a href="https://github.com/unslothai/unsloth">Unsloth</a> for faster training.

# #ML #GENAI #LLM #BERT #DL #CV #NLP #PROMPT #MB
