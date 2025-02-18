# Exploring-SqueezeBERT

Mobile devices (especially smartphones) stand out as crucial platforms for implementing NLP models. However, smaller devices cannot afford the enormous computational costs associated with existing high-accuracy NLP models, such as BERT and RoBERTa. We propose an analysis of the SqueezeBERT model, starting from the results presented in some papers that address computer vision techniques applied to NLP tasks.

The folder *Codes* contains three notebook files, each dedicated to a specific natural language processing task:

1. **Sequence_Classification**
   - This notebook contains the code for fine-tuning models on a news article sequence classification task. The models are fine-tuned using the [News Articles Categorization dataset](https://huggingface.co/datasets/valurank/News_Articles_Categorization).

2. **Token_Classification**
   - This notebook contains the code for fine-tuning models on a Named Entity Recognition (NER) task. The models are fine-tuned using the [CoNLL-2003 dataset](https://huggingface.co/datasets/eriktks/conll2003).

3. **Fill_Mask**
   - This notebook contains the code for fine-tuning models on a masked language modeling task focused on human conversations. The models are fine-tuned using the [Better Daily Dialog dataset](https://huggingface.co/datasets/benjaminbeilharz/better_daily_dialog).

For each task, we start with pre-trained models: [SqueezeBERT](https://huggingface.co/squeezebert/squeezebert-uncased) and [BERT](https://huggingface.co/google-bert/bert-base-uncased).

### Notebook Structure

Each notebook is divided into three main sections:

1. **Loading Dataset**
2. **Fine-Tuning**
3. **Testing**
