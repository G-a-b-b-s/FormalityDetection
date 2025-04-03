# FormalityDetection
A repository that aims to investigate more into the world of formality detection.

DATASETS:    
X-FORMAL   
GYAFC  
https://huggingface.co/datasets/osyvokon/pavlick-formality-scores   
https://www.kaggle.com/datasets/changwooyoo/informal-to-formal?select=generated_from_tweet.json
https://www.kaggle.com/datasets/jef1056/discord-data   

PAPERS:   
https://arxiv.org/pdf/2204.08975 
https://medium.com/analytics-vidhya/formalizing-informal-text-using-natural-language-processing-dd2032a0fc2b
https://arxiv.org/pdf/2010.12742v4
Formalstyler: GPT-Based Model for Formal Style Transfer with Meaning Preservation   
MODELS    
https://huggingface.co/s-nlp/xlmr_formality_classifier
https://huggingface.co/s-nlp/mdeberta-base-formality-ranker
https://huggingface.co/s-nlp/deberta-large-formality-ranker   
https://huggingface.co/s-nlp/roberta-base-formality-ranker   
https://huggingface.co/s-nlp/xlmr_formality_classifier    
https://huggingface.co/LenDigLearn/formality-classifier-mdeberta-v3-base   
https://huggingface.co/hallisky/lora-formality-informal-llama-3-8b   
https://huggingface.co/Minaaan/roberta_formality_model   
Rule-Based Approaches

Hemingway Editor, Grammarly: Use predefined grammar and style rules.

LIWC (Linguistic Inquiry and Word Count): A lexicon-based tool to assess formality.

Fine-tuned Transformer Models

BERT (Fine-tuned for Formality Detection): A custom-trained version of BERT using labeled formal/informal text.

T5 or GPT Variants: Fine-tuned on datasets like GYAFC (GYAFC: GYAFC Corpus for formal-informal text).

LLMs (Large Language Models like GPT-4, Claude, PaLM 2, etc.)

Prompt Engineering: Using zero-shot, few-shot, or chain-of-thought prompting.

Fine-Tuning/OpenAI Custom GPTs: Fine-tuned on formality datasets.


NOTEBOOKS   
https://github.com/s-nlp/formality?tab=readme-ov-file
https://github.com/YahooArchive/formality-classifier
https://github.com/aashnadoshi2/Formality-Classification-NLP/blob/main/GYAFC_Corpus_Fomality_Classification.ipynb

METRICS   
Style accuracy  : 
Classifier-Based Metrics: Train a formality classifier (e.g., using mBERT) to auto-score outputs 16.

Content Preservation:

BLEU, ROUGE, or METEOR scores to compare generated text with reference translations 5.

Semantic Similarity: Use embeddings (e.g., BERTScore) to measure meaning retention 5.

Fluency:

Perplexity Scores: Evaluate grammatical correctness via language models 5.

Readability Metrics: Flesch-Kincaid Grade Level for simplified or formal texts 17.
