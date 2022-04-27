---
date: 2022-04-27T06:45
tags:
  - modelling
  - connected
---

# Pairs are connected to each other

In [[25a1009e]], we have pairs that are referenced with round brackets (`(` and `)`). The components of a pair are related to each other. So the model is not allowed to choose one of the elements in a pair. It must take both!

## Example

A model for playing cards could be named `P`. This model describes a pair of picture and number. Each element of the pair (picture and number) must be present for a playing card. Otherwise, the playing card would not exist. Hence, the model is formally described as follows:

```
P = { (Hearth, 1), (Hearth, 2), ..., (Spade, 5), (Spade, 6), ... }
```
