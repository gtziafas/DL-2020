
# PyTorch NLP Tutorials

You will find here two Jupyter Notebooks, one containing an introduction to the PyTorch deep learning framework and one using PyTorch to train a Recurrent Neural Network (RNN) model on real language data for the task of Part-Of-Speech (POS) tagging. You can find more about this task, along with papers for all tasks conserned in Natural Language Processing (NLP), in [NLPProgress](http://nlpprogress.com/)

The Into notebook works as a heavy intro to the PyTorch toolbox. It starts with an introduction to tensor processing (as an extention of array processing with the `numpy` module) and it proceeds with the mechanics of PyTorch concerning automatic differentiation, loss functions, gradient-descent based optimization and feed-forward neural network models. It is a usefull low-level walkthrough throughout the `torch.tensor, torch.autograd, torch.nn, torch.data`, which are the core modules of PyTorch.

The POS-RNN notebook is aimed at explaining the workings of RNNs, as well as how to apply them for extracting part-of-speech tags on real language data. It includes all steps that are found in any deep learning pipeline for NLP (data preparation, word embeddings, training and validation of the RNN model etc.).

Extentions of the RNN model, the [sequence-to-sequence](https://arxiv.org/abs/1409.3215) encoder-decoder architectures, as well as the [Transformer](https://arxiv.org/abs/1706.03762) architecture, are currently the state-of-the-art in any NLP task (machine translation, text generation, dialogue systems etc.) and is probably the place to go if you choose to do your second practical project in deep learning for NLP. We will try to add a new notebook for an intro to self-attention, but a very detailed tutorial is ["The Annotated Transformer"](https://nlp.seas.harvard.edu/2018/04/03/attention.html).

All content of these tutorials was made by the fellow student Konstantinos Kogkalidis, 2018-2019. 

