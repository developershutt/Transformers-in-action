# Transformers-in-action

## Prerequisite
* Tensorflow 2.x
* CUDA capable GPU
* 4 Cores processor

## 1. Intro to Transformers

* Implemented using Single-head self attention with positional encoding on IMDB sentiment classification [dataset](https://drive.google.com/file/d/140xsu_Cw-ZkPZWKIWdXRPu2VRWKWw7Wd/view?usp=sharing)
* Watch explanation video [here](https://youtu.be/5YEvHdGP9x4) or explore code [here](/1%20-%20Transformers%20from%20scratch.ipynb)

## 2. Language Translation with Multi-head Attention and Positional Encoding

The [notebook](./2%20-%20Language%20Translation%20with%20Transformers.ipynb) contains the implementation of a language translation model using multi-head attention with positional encoding. The model is trained on an English-French dataset, which can be found [here](./dataset/eng_-french.csv).

To better understand the implementation, you can watch a video explanation [here](https://www.youtube.com/watch?v=81LeULNc2_c&pp=ygUmbGFuZ3VhZ2UgdHJhbnNsYXRpb24gdXNpbmcgdHJhbnNmb3JtZXI%3D).

The goal of this project is to provide a comprehensive and easy-to-understand implementation of language translation using state-of-the-art techniques. The use of multi-head attention and positional encoding helps enhance the model's ability to capture relationships between words and maintain the positional information.

Please refer to the code files and documentation provided in this repository for detailed explanations and instructions on how to run and use the model effectively. Feel free to explore and modify the code according to your needs.

## 3. Text Summarization Model

This repository contains the implementation of a text summarization model using the Keras NLP library and TensorFlow. The model is trained on a conversation dataset which can be found in the `dataset/summarization/` directory of this repository.

To understand the concept and implementation of the text summarization model, you can watch a video tutorial [here](https://youtu.be/9t1Lr4luGqk).

## Contributing

If you have any improvements or bug fixes, feel free to contribute. Just submit a pull request with your changes and we will review it.