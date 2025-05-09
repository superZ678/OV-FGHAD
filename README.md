<h1 align="center"> Open-Vocabulary Fine-Grained Hand Action Detection </h1>

<p align="center">
  <a href="#news">News</a> |
  <a href="#abstract">Abstract</a> |
  <a href="#overview">Overview</a> |
  <a href="#model zoo">Model Zoo</a> |
   <a href="#citation">Citation</a> |
</p>

<img src="docs/ovdino_framework.png" width="800">

## :fire: News

**2025.04.29**

- The paper "Open-Vocabulary Fine-Grained Hand Action Detection" has been accepted by the 34th International Joint Conference on Artificial Intelligence (IJCAI-25). We will release the related code soon.


## :rocket: Introduction
This is the official repository of the paper Open-Vocabulary Fine-Grained Hand Action Detection.


## :page_facing_up: Abstract
In this work, we address the new challenge of open-vocabulary fine-grained hand action detection, which aims to recognize hand actions from both known and novel categories using textual descriptions. Traditional hand action detection methods are limited to closed-set detection, making it difficult for them to generalize to new, unseen hand action categories. While current open-vocabulary detection (OVD) methods are effective at detecting novel objects, they face challenges with fine-grained action recognition, particularly when data is limited and heterogeneous. This often leads to poor generalization and performance bias between base and novel categories. To address these issues, we propose a novel approach, Open-FGHA (Open-vocabulary Fine-Grained Hand Action), which learns to distinguish fine-grained features across multiple modalities from limited heterogeneous data. It then identifies optimal matching relationships among these features, enabling accurate open-vocabulary fine-grained hand action detection. Specifically, we introduce three key components: Hierarchical Heterogeneous Low-Rank Adaptation, Bidirectional Selection and Fusion Mechanism, and Cross-Modality Query Generator. These components work in unison to enhance the alignment and fusion of multimodal fine-grained features. Extensive experiments demonstrate that Open-FGHA outperforms existing OVD methods, showing its strong potential for open-vocabulary hand action detection.

## :page_facing_up: Overview

<img src="docs/ovdino_framework.png" width="800">

## :sparkles: Model Zoo


## :blush: Statement

This project is for research purposes only. For further questions, please contact Ting Zhe at zheting@whu.edu.cn.



## :pushpin: Citation
