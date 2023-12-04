# yandex-cup-recsys-2023

My Machine Learning competition results

Yandex Cup 2023 ML Recommendation Systems Track took place in november of 2023 and introduced multi-label classification task.

As input there were 768-dimensional embeddings of soundtrack data, and the requirement was to label genres.

See more inside of `YandexML_2023.ipynb` notebook. TensorFlow was used for model training. DNNs were learned using following techniques:
- Zero Padding of input data
- Layer Normalization
- Gated Recurrent Units
- [MaskBlocks](https://arxiv.org/abs/2102.07619)
