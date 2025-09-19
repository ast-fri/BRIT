# BRIT: Bidirectional Retrieval over Unified Image-Text Graph

Welcome! This repository contains the tech-blog code explaining **BRIT** method for multi-modal RAG on enterprise-specific proprietary documents.

## 🔍 Overview

Retrieval-Augmented Generation (RAG) has emerged as a promising technique for enhancing the quality and relevance of large language model responses. However, current RAG systems face significant limitations when applied to multi-modal enterprise documents. These documents, which combine text and images while containing proprietary terminology and company-specific names, often cause traditional embedding-based RAG approaches to fail due to poor similarity matching with pre-trained models that lack domain-specific knowledge.

## 📊 BRIT

BRIT addresses the issue through a novel multi-modal RAG framework that constructs unified text-image graphs from documents and retrieves query-relevant subgraphs without requiring fine-tuning. By capturing both semantic and spatial relationships between textual and visual elements, BRIT enables effective cross-modal retrieval on enterprise-specific content. We introduce the MM-RAG test set to evaluate multi-modal question answering capabilities that require understanding complex text-image relationships.

## 🎯 MM-RAG Benchmark

MM-RAG test set is a new test set we built based on WikiWeb2M and contains 500 questions for 100 Wikipedia page samples. There are 3 types of questions, Text-Image questions, Image-Text questions, and Image-Image questions. MM-RAG covers a wide variety of topics and images, containing not only natural images but also drawings and diagrams. This new test set allows us to evaluate RAG on various settings.

## 🖼️ Qualitative Examples

Check out some qualitative results:

- [Text-Image Example](images/example-1.png)
- [Image-Text Example](images/example-2.png)

## 🚀 Getting Started

To explore the benchmark and see our method in action, you can:

1. **View the interactive demo**: Open [`index.html`](index.html) in your browser to see detailed explanations
2. **Access the dataset**: Visit our [Hugging Face dataset](https://huggingface.co/datasets/ainulla/mmrag)
3. **Read the paper**: Check out our research on [arXiv](https://arxiv.org/abs/2505.18450) 

## 📄 Citation

If you find our work helpful, please consider citing our paper:

```bibtex
@article{khan2025brit,
  title={BRIT: Bidirectional Retrieval over Unified Image-Text Graph},
  author={Khan, Ainulla and Moyuru, Yamada and Akella, Srinidhi},
  journal={arXiv preprint arXiv:2505.18450},
  year={2025}
}
```
---

© 2025 Research Project | BRIT: Bidirectional Retrieval over Unified Image-Text Graph
