# Reframing the Gilded Rose kata into a DSPy program

This repository contains notebooks that I wrote while learning [DSPy](https://dspy.ai/). It explains:
- How to define a [Language Model](https://dspy.ai/learn/programming/language_models/), [Signature](https://dspy.ai/learn/programming/signatures/) and a [Module](https://dspy.ai/learn/programming/modules/)
- How to define a dataset of [Examples](https://dspy.ai/learn/evaluation/data/) and a [Metric](https://dspy.ai/learn/evaluation/metrics/) to [Evaluate](https://dspy.ai/learn/evaluation/overview/) your module
- How to [optimize](https://dspy.ai/learn/optimization/overview/) your module using [DSPy's internal optimizers](https://dspy.ai/learn/optimization/optimizers/)

### What is DSPy ?

DSPy is a declarative framework for building modular AI software. Read more on their [docs](https://dspy.ai/).

### What is the Gilded Rose Kata ?

The [Gilded Rose kata](https://github.com/emilybache/GildedRose-Refactoring-Kata) is originally a refactoring exercise. The goal is to refactor some [questionable inventory updater code](https://github.com/emilybache/GildedRose-Refactoring-Kata/blob/main/python/gilded_rose.py) that encompass a set of [inn rules](https://github.com/emilybache/GildedRose-Refactoring-Kata/blob/main/GildedRoseRequirements.md).

We propose a different approach: give the rules and an item to a LM and let it provide its updated version.

More info in the notebooks !