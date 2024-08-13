# Replicating "Distributed Representation of n-gram Statistics for Boosting SOM with Hyperdimensional Computing"

This Jupyter Notebook contains the implementation of the paper titled *"Distributed Representation of n-gram Statistics for Boosting Self-Organizing Maps with Hyperdimensional Computing"* by Denis Kleyko et al. The notebook replicates the experiments and findings presented in the paper, focusing on enhancing Self-Organizing Maps (SOMs) with hyperdimensional computing techniques applied to n-gram statistics.

## Table of Contents

- [Introduction](#introduction)
- [Paper Summary](#paper-summary)
- [Usage](#usage)
- [Experiments](#experiments)
- [Results](#results)
- [References](#references)
- [License](#license)

## Introduction

Self-Organizing Maps (SOMs) are a type of unsupervised machine learning algorithm widely used for dimensionality reduction and data visualization. However, the computational complexity of SOMs increases significantly when dealing with symbolic data represented using n-gram statistics. This notebook implements the approach proposed in the paper to address this issue by using hyperdimensional computing (HDC) to generate distributed representations of n-gram statistics, thereby reducing the computational load while preserving the performance of SOMs.

## Paper Summary

The paper introduces a novel method that reduces the dimensionality of n-gram statistics using HDC. The key contributions of the paper include:

- **Distributed Representations:** The use of high-dimensional vectors to represent n-grams, reducing the exponential growth of the vector size with the increase in n.
- **Enhanced SOM Performance:** SOMs trained with these distributed representations require less computation and memory while maintaining or improving classification accuracy.
- **Applications:** The method is demonstrated on a language recognition task involving European languages, showing significant improvements in training time and resource efficiency.

## Usage

To replicate the experiments, open the `Replicating_SOM_HDC.ipynb` notebook and run the cells in sequence. 

## Experiments

The experiments replicate the language recognition task described in the paper. 

## Results

The results of the experiments demonstrate that using distributed representations with hyperdimensional computing can significantly reduce the computational burden of training SOMs without compromising their performance. Detailed results, including accuracy metrics, training time, and memory usage, are provided within the notebook.

## References

- Kleyko, D., Osipov, E., De Silva, D., Wiklund, U., Vyatkin, V., & Alahakoon, D. (2019). Distributed Representation of n-gram Statistics for Boosting Self-Organizing Maps with Hyperdimensional Computing. *In Proceedings of the 2019 International Conference on Neural Information Processing*.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). 

(c) MICAELA KULESZ, 2024.
