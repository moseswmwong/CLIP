# CLIP Reproduced on Colab - 2021.09.14

[[Blog]](https://openai.com/blog/clip/) [[Paper]](https://arxiv.org/abs/2103.00020) [[Model Card]](model-card.md) [[Colab]](https://colab.research.google.com/github/openai/clip/blob/master/notebooks/Interacting_with_CLIP.ipynb)


# Overview

The OpenAI CLIP model is designed to use for zero-shot tasks, trained on large dataset, it is able to achieve accuracy as good as supervised learning model without limited to the number of classes being trained, for instance, a 1000 classied from ImageNet means the computer vision model is as good as recognizing only 1000 classes max. The CLIP model is easy extensible for new class and can be used readily for predicting objects already pre-trained.

# Colab replication

The colab version CLIPv1.ipynb is designed to deploy on colab, as of 2021.09.14 default colab library works fine, and don't forget to set processor to GPU before you start running the notebook.

