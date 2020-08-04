---
layout: quickpost
author: Minh Le
title: The road to True AI
---

## Two modes of AI research

1. Two modes of AI research are expanding and shaping.
    1. The first mode tries to expand the hypothesis space that AI can effectively learn.
    1. The second mode tries to restrict the hypothesis space in a way that eliminates invalid generalizations while keeping valid ones, i.e. encoding the right inductive bias.
2. Both modes are necessary and can be carried out in parallel.
    1. Deep learning is advancing AI research by expanding the tratable hypothesis space.
    1. But the most likely path to true AI also passes through encoding more and better inductive biases.
    1. [Gary Marcus (2020). The Next Decade in AI: Four Steps Towards Robust Artificial Intelligence.](https://arxiv.org/abs/2002.06177)
3. The two modes of AI research favors different approaches.
    1. The expanding mode favors engineering methodologies and leader board-style competition.
    1. The shaping mode favors scientific methodologies and hypothesis-driven research.
4. The two modes of AI research favors different organizational structures.
    1. The expanding mode favors big teams with lots of supporting resources.
    1. The shaping mode favors small teams and requires little resources.

## The most likely path to true AI

1. Nobody knows this for sure until it's done. What's below is my best guess.
2. Neural-symbolic hybrid
    1. Different types of concepts have affinity to different types of representations.
    2. Sensorimotor concepts (e.g. the visual appearance of a vase) are better captured by neural networks.
    3. Abstract concepts (e.g. rectangles) are better captured by symbolic representations.
    4. Variable binding is most natural when expressed in symbols
3. Concepts come first
    1. We need quality concepts: those that are connected to others with various relations, not just similarity.
    2. We need a lot of them: for perspective, the number of words in English is estimated to be ~1m.
    3. Having enough quality concepts enables many lines of research. For example, look at what Word2vec enables while being just a similarity model.
4. Induce propositional, first-order, and higher-order knowledge automatically
    1. Create an exponential number of concepts from atomic concepts.
    2. Turn o.o.d. examples into i.i.d. examples by selecting different perspective of the input.
5. Learn from natural stimuli
    1. Natural stimuli include photos, videos, recording, stories.
    2. Natural stimuli are information-rich
6. Learn from human knowledge
    1. Read dictionaries
    2. Read books
    3. Watch instructional videos