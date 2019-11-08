# VQA-System

This repository contains code for the task of Visual Question Answering: given an image and a question related to the image in natural language, the systems answer the question in natural language from the image scene.

This is the baseline model given in the paper VQA: Visual Question Answering (https://arxiv.org/pdf/1505.00468.pdf). It encodes the image by a CNN and the question by an LSTM and then combines these for VQA task. It uses pretrained vgg16 to get the image embedding (may be further normalised), and a 1 or 2-layered LSTM for the question embedding.

# Usage
First download the datasets from http://visualqa.org/download.html. Run ''' VQA.py''' changing the test Image and question parameters
