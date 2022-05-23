# Language Detection

__This repository aims at implementing a method to identify the language a document is written in.__

It supports 20 different langauges:

```
arabic (ar), bulgarian (bg), german (de), modern greek (el), english (en), spanish (es), french (fr), hindi (hi), italian (it), japanese (ja), dutch (nl), polish (pl), portuguese (pt), russian (ru), swahili (sw), thai (th), turkish (tr), urdu (ur), vietnamese (vi), and chinese (zh).

```


A jupyter notebook is provided to implement this task. It can be directly launched in Google Colab from here:

- <a href="https://colab.research.google.com/github/dinalzein/LanguageDetection/blob/main/language_identification.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 


## Datasets
Download the train, valid, and test data files from [here](https://huggingface.co/datasets/papluca/language-identification/tree/main) and assert them in [data](./data) in the same directory of the jupyter notebook.


### Citation
To cite this work in your publications in BibTeX format:

```
@inproceedings{wolf2020transformers,
  title={Transformers: State-of-the-art natural language processing},
  author={Wolf, Thomas and Debut, Lysandre and Sanh, Victor and Chaumond, Julien and Delangue, Clement and Moi, Anthony and Cistac, Pierric and Rault, Tim and Louf, R{\'e}mi and Funtowicz, Morgan and others},
  booktitle={Proceedings of the 2020 conference on empirical methods in natural language processing: system demonstrations},
  pages={38--45},
  year={2020}
}
```

### Used materials and 3rd party code
The experiments are based on the [*huggingface*](https://github.com/huggingface/transformers) library.
