# Transformative-LLM-Collection

Welcome to the Transformative LLM Collection! This repository hosts a diverse set of Natural Language Processing (NLP) projects utilizing Transformer-based models. From text summarization to named entity recognition, each project explores different aspects of NLP leveraging cutting-edge techniques and models.

## Efficient Transformer Project

- **Model:** Teacher-Student Model
- **Architectures:** `distilbert-base-uncased-finetuned-clinc`, `distilbert-base-uncased`
- **Approach:** Utilized hyperparameter optimization with Optuna
- **Techniques:** Quantization for model optimization

## Multilingual Named Entity Recognition

- **Model:** Fine-Tuning XLM-RoBERTa
- **Techniques:**
  - Error analysis for model improvement
  - Cross-Lingual Transfer learning
  - Multilingual learning evaluation using fine-tuning on multiple languages simultaneously
  - Evaluation metrics: F1 score
  
## Summarization

- **Evaluation:**
  - PEGASUS evaluated on the CNN/DailyMail Dataset
  - PEGASUS evaluated on SAMSum
- **Techniques:**
  - Fine-Tuning PEGASUS
  - Generating Dialogue Summaries

## Dealing with Few to No Labels

- **Techniques:**
  - Macro and Micro Scores evaluation
  - Zero-shot learning exploration
  - Utilization of MNLI model for zero-shot classification
  - Handling few labels through data augmentation
  - Fine-Tuning a Vanilla Transformer
  - Pretrained BERT model fine-tuning with masked language modeling on unlabeled dataset portion

### Text Classification

- **Model:** Utilized Transformer-based architecture
- **Approach:** Fine-tuned the model specifically for classification tasks on the dataset

### Question Answering

- **Model:** Employed a Transformer-based architecture
- **Approach:** Fine-tuned the model to excel in question answering tasks

### Text Generation

- **Model:** Leveraged a Transformer-based architecture
- **Approach:** Tailored fine-tuning techniques to optimize the model for generating text

---

Feel free to explore each project folder for more details, including code implementation, datasets, and experiment results. If you have any questions or suggestions, please don't hesitate to reach out!

Enjoy exploring the transformative power of Transformers in NLP!
