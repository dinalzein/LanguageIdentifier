# Language Detection

__This repository aims at implementing a method to identify the language a document is written in. A simple demo is available [here](https://huggingface.co/spaces/dinalzein/LanguageIdentifier)__

It supports 20 different languages:

* Arabic (ar)
* Bulgarian (bg)
* German (de)
* Modern greek (el)
* English (en)
* Spanish (es)
* French (fr)
* Hindi (hi)
* Italian (it)
* Japanese (ja)
* Dutch (nl)
* Polish (pl)
* Portuguese (pt)
* Russian (ru)
* Swahili (sw)
* Thai (th)
* Turkish (tr)
* Urdu (ur)
* Vietnamese (vi)
* Chinese (zh)

A jupyter notebook to implement this task is provided and can be directly launched in Google Colab from here: <a href="https://colab.research.google.com/github/dinalzein/LanguageDetection/blob/main/language_identification.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Datasets
Download the train, valid, and test data files from [here](https://huggingface.co/datasets/papluca/language-identification/tree/main) and assert them in [data](./data) in the same directory of the jupyter notebook.

## Model Used
The model used in this task is [XLM-RoBERTa](https://huggingface.co/xlm-roberta-base) transformer model with a classification head on top.

## Fine-tuned Model
You can download it from [here](https://huggingface.co/dinalzein/xlm-roberta-base-finetuned-language-identification)

## Demo
You can try it [here](https://huggingface.co/spaces/dinalzein/LanguageIdentifier)

### Used materials and 3rd party code
The experiments are based on the [*huggingface*](https://github.com/huggingface/transformers) library.
