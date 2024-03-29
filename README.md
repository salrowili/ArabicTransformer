# ArabicTransformer: Efficient Large Arabic Language Model with Funnel Transformer and ELECTRA Objective 

# Abstract

Pre-training Transformer-based models such
as BERT and ELECTRA on a collection
of Arabic corpora, demonstrated by both
AraBERT and AraELECTRA, shows an impressive
result on downstream tasks. However,
pre-training Transformer-based language
models is computationally expensive, especially
for large-scale models. Recently, Funnel
Transformer has addressed the sequential
redundancy inside Transformer architecture by
compressing the sequence of hidden states,
leading to a significant reduction in the pretraining
cost. This paper empirically studies
the performance and efficiency of building
an Arabic language model with Funnel Transformer
and ELECTRA objective. We find that
our model achieves state-of-the-art results on
several Arabic downstream tasks despite using
less computational resources compared to
other BERT-based models.

# Pre-Trained Models ( PyTorch + PT + TensorFlow )

- ArabicTransformer small (B4-4-4) [Link](https://huggingface.co/sultan/ArabicTransformer-small)
- ArabicTransformer intermediate (B6-6-6) [Link](https://huggingface.co/sultan/ArabicTransformer-intermediate)
- ArabicTransformer large (B8-8-8) [Link](https://huggingface.co/sultan/ArabicTransformer-large)

# Google Colab Examples
- Text Classification with ArabicTransformer with PyTorchXLA on TPU or with PyTorch on GPU (Better reproducibility but slower). 

[![Open In Colab][COLAB]](https://colab.research.google.com/github/salrowili/ArabicTransformer/blob/main/Examples/Text_Classification_with_ArabicTransformer_with_PyTorchXLA_on_TPU_or_with_PyTorch_on_GPU.ipynb) 
- Text Classification with ArabicTransformer and TPU and Keras API (Faster but reproducibility is not better than PyTorchXLA). 

[![Open In Colab][COLAB]](https://colab.research.google.com/github/salrowili/ArabicTransformer/blob/main/Examples/Text_Classification_with_ArabicTransformer_and_TPU_and_Keras_API.ipynb) 
- Question Answering ( TyDi QA / Quran QA dataset) with ArabicTransformer. 

[![Open In Colab][COLAB]](https://colab.research.google.com/github/salrowili/ArabicTransformer/blob/main/Examples/FineTuning_ArabicTransformers_on_TyDi_QA_and_Quran_QA_Dataset.ipynb) 
# 
```bibtex
@inproceedings{alrowili-shanker-2021-arabictransformer-efficient,
    title = "{A}rabic{T}ransformer: Efficient Large {A}rabic Language Model with Funnel Transformer and {ELECTRA} Objective",
    author = "Alrowili, Sultan  and
      Shanker, Vijay",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2021",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.findings-emnlp.108",
    pages = "1255--1261",
    abstract = "Pre-training Transformer-based models such as BERT and ELECTRA on a collection of Arabic corpora, demonstrated by both AraBERT and AraELECTRA, shows an impressive result on downstream tasks. However, pre-training Transformer-based language models is computationally expensive, especially for large-scale models. Recently, Funnel Transformer has addressed the sequential redundancy inside Transformer architecture by compressing the sequence of hidden states, leading to a significant reduction in the pre-training cost. This paper empirically studies the performance and efficiency of building an Arabic language model with Funnel Transformer and ELECTRA objective. We find that our model achieves state-of-the-art results on several Arabic downstream tasks despite using less computational resources compared to other BERT-based models.",
}
```

[COLAB]: https://colab.research.google.com/assets/colab-badge.svg
[HuggingFace]: https://huggingface.co/front/assets/huggingface_logo-noborder.svg
