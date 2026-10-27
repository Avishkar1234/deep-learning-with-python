# Chapter 1 — What Is Deep Learning?

## Overview

This chapter introduces artificial intelligence, machine learning, and deep learning. It explains how deep learning models learn representations from data and introduces the basic ideas behind neural networks, optimization, generative AI, and foundation models.

## Learning Objectives

- Distinguish artificial intelligence, machine learning, and deep learning.
- Understand how neural networks learn representations from data.
- Explain the roles of loss functions, optimizers, and backpropagation.
- Understand the basic ideas behind generative AI and foundation models.

## 1. AI, Machine Learning, and Deep Learning

Artificial intelligence (AI) is the broad field of building systems that perform tasks associated with intelligence.

Machine learning (ML) is a subset of AI in which systems learn patterns from data rather than relying entirely on explicitly programmed rules.

Deep learning is a subset of machine learning that uses neural networks with multiple layers to learn increasingly useful representations of data.

The relationship can be represented as:

**Artificial Intelligence → Machine Learning → Deep Learning**

For example, an image classifier can learn from labeled images to distinguish cats from dogs. A deep learning model can learn useful visual features directly from the training data.

## 2. Learning Representations from Data

A representation is a way of expressing information that helps a model perform a task.

In deep learning, successive layers can transform raw inputs into increasingly useful representations. For example, an image model may learn simple visual patterns in earlier layers and more complex combinations of features in later layers.

The important idea is that the model learns these representations from data during training rather than requiring every feature to be manually specified.

## 3. Neural Networks and Learning

A neural network processes input data through layers of mathematical operations to produce a prediction.

During training:

1. The model receives input data.
2. It computes a prediction.
3. A loss function measures how well the prediction matches the target.
4. An optimization algorithm updates the model's parameters.
5. The process repeats to improve performance on the training objective.

The model's parameters, such as weights and biases, determine how inputs are transformed into predictions.

## 4. Loss Functions and Optimization

A loss function quantifies the discrepancy between a model's prediction and the desired target.

An optimizer uses information about the loss and its gradients to update the model's parameters.

Training generally aims to minimize the chosen loss function. However, a low training loss alone does not guarantee good performance on unseen data.

## 5. Backpropagation

Backpropagation calculates gradients of the loss with respect to the model's parameters by applying the chain rule of calculus through the network.

These gradients indicate how changes in parameters affect the loss. An optimizer uses them to determine parameter updates.

Backpropagation computes gradients; the optimizer uses those gradients to update parameters. They are related but distinct parts of the training process.

## 6. Generative AI and Foundation Models

Generative AI refers to models that can generate new content, such as text, images, audio, or other data.

Foundation models are trained on broad data and can be adapted to a variety of downstream tasks. Large language models are an important example of foundation models.

Modern language models connect to the foundational concepts in this chapter: they learn representations from data and use neural network training procedures to learn patterns that support tasks such as text generation.

## 7. Connections to Modern AI

Topics to explore in later chapters and independent experiments:

- How gradient descent updates neural network parameters.
- How tensors represent batches of numerical data.
- How embeddings represent tokens and other objects.
- How attention and transformer architectures process sequences.
- How large language models learn and generate text.

These are future learning questions, not implementations covered by this chapter summary.

## 8. What I Learned

Complete this section in your own words after reviewing the chapter.

- **Most important concept:**
- **Concept I found difficult:**
- **Question I still have:**
- **Connection to another topic:**

## 9. Revision Questions

1. How are AI, machine learning, and deep learning related?
2. What does it mean for a model to learn a representation?
3. What is the difference between a loss function and an optimizer?
4. Why are gradients useful during training?
5. What is a foundation model?
6. What is the difference between backpropagation and an optimizer?
7. Why does a low training loss not necessarily guarantee good performance on unseen data?

## Reference

Chollet, François. _Deep Learning with Python_, Third Edition. Chapter 1.

These notes are an original summary written for personal learning. Refer to the book for the complete explanations and examples.
