<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<h1 align="center">
    <a href='https://en.wikipedia.org/wiki/Mahmud_al-Kashgari'>Kashgari</a>
</h1>

<p align="center">
    <a href="https://github.com/BrikerMan/kashgari/blob/master/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/BrikerMan/kashgari.svg?color=blue&style=popout">
    </a>
    <a href="https://join.slack.com/t/kashgari/shared_invite/enQtODU4OTEzNDExNjUyLTY0MzI4MGFkZmRkY2VmMzdmZjRkZTYxMmMwNjMyOTI1NGE5YzQ2OTZkYzA1YWY0NTkyMDdlZGY5MGI5N2U4YzM">
        <img alt="Slack" src="https://img.shields.io/badge/chat-Slack-blueviolet?logo=Slack&style=popout">
    </a>
    <a href="https://travis-ci.com/BrikerMan/Kashgari">
        <img src="https://travis-ci.com/BrikerMan/Kashgari.svg?branch=master"/>
    </a>
    <a href='https://coveralls.io/github/BrikerMan/Kashgari?branch=master'>
        <img src='https://coveralls.io/repos/github/BrikerMan/Kashgari/badge.svg?branch=master' alt='Coverage Status'/>
    </a>
     <a href="https://pepy.tech/project/kashgari">
        <img src="https://pepy.tech/badge/kashgari"/>
    </a>
    <a href="https://pypi.org/project/kashgari/">
        <img alt="PyPI" src="https://img.shields.io/pypi/v/kashgari.svg">
    </a>
</p>

<h4 align="center">
    <a href="#overview">Overview</a> |
    <a href="#performance">Performance</a> |
    <a href="#installation">Installation</a> |
    <a href="https://kashgari.readthedocs.io/">Documentation</a> |
    <a href="https://kashgari.readthedocs.io/about/contributing/">Contributing</a>
</h4>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

🎉🎉🎉 We released the 2.0.0-alpha0 version with Seq2Seq Support. 🎉🎉🎉

## Overview

Kashgari is a simple and powerful NLP Transfer learning framework, build a state-of-art model in 5 minutes for named entity recognition (NER), part-of-speech tagging (PoS), and text classification tasks.

- **Human-friendly**. Kashgari's code is straightforward, well documented and tested, which makes it very easy to understand and modify.
- **Powerful and simple**. Kashgari allows you to apply state-of-the-art natural language processing (NLP) models to your text, such as named entity recognition (NER), part-of-speech tagging (PoS) and classification.
- **Built-in transfer learning**. Kashgari built-in pre-trained BERT and Word2vec embedding models, which makes it very simple to transfer learning to train your model.
- **Fully scalable**. Kashgari provides a simple, fast, and scalable environment for fast experimentation, train your models and experiment with new approaches using different embeddings and model structure.
- **Production Ready**. Kashgari could export model with `SavedModel` format for tensorflow serving, you could directly deploy it on the cloud.

## Our Goal

- **Academic users** Easier experimentation to prove their hypothesis without coding from scratch.
- **NLP beginners** Learn how to build an NLP project with production level code quality.
- **NLP developers** Build a production level classification/labeling model within minutes.

## Supporting the project

**You can support the project by checking out our sponsor page. It takes only one click:**

<!-- markdownlint-disable -->
<a href="https://tracking.gitads.io/?repo=Kashgari">
  <img alt="Sponsor banner" src="https://images.gitads.io/Kashgari" />
</a>
<br>
<i>
  This advert was placed by <a href="https://tracking.gitads.io/?repo=Kashgari">GitAds</a>
</i>
<!-- markdownlint-enable -->

## Performance

Welcome to add performance report.

| Task (with code link)      | Language | Dataset                   | Score   |
| -------------------------- | -------- | ------------------------- | ------- |
| Named Entity Recognition   | Chinese  | People's Daily Ner Corpus | // TODO |
| Text Classification        | -        | -                         | // TODO |
| Neural machine translation | -        | -                         | // TODO |

## Installation

The project is based on Python 3.6+, because it is 2019 and type hinting is cool.

| Backend          | pypi version                           | desc                         |
| ---------------- | -------------------------------------- | ---------------------------- |
| TensorFlow 2.x   | `pip install 'kashgari>=2.0.0a0'`      | TF2 tf.keras - alpha version |
| TensorFlow 1.14+ | `pip install 'kashgari>=1.0.0,<2.0.0'` | TF1.14+ tf.keras version     |
| Keras            | `pip install 'kashgari<1.0.0'`         | keras version                |

## Tutorials

Here is a set of quick tutorials to get you started with the library:

- [Tutorial 1: Text Classification](./docs/tutorial/text-classification.md)
- [Tutorial 2: Text Labeling](./docs/tutorial/text-labeling.md)
- [Tutorial 3: Seq2Seq](./docs/tutorial/seq2seq.md)
- [Tutorial 4: Language Embedding](./docs/embeddings/index.md)

There are also articles and posts that illustrate how to use Kashgari:

- [15 分钟搭建中文文本分类模型](https://eliyar.biz/nlp_chinese_text_classification_in_15mins/)
- [基于 BERT 的中文命名实体识别（NER)](https://eliyar.biz/nlp_chinese_bert_ner/)
- [BERT/ERNIE 文本分类和部署](https://eliyar.biz/nlp_train_and_deploy_bert_text_classification/)
- [五分钟搭建一个基于BERT的NER模型](https://www.jianshu.com/p/1d6689851622)
- [Multi-Class Text Classification with Kashgari in 15 minutes](https://medium.com/@BrikerMan/multi-class-text-classification-with-kashgari-in-15mins-c3e744ce971d)

Examples:

- [Neural machine translation with Seq2Seq](./examples/translate_with_seq2seq.ipynb)

## Contributors ✨

Thanks goes to these wonderful people. And there are many ways to get involved.
Start with the [contributor guidelines](./docs/about/contributing.md) and then check these open issues for specific tasks.
