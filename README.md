# Branched Spatial Spectral Attention and Classification Methodolgy for Hyperspectral Data Classification

## Introduction
Deep learning based hyperspectral data analysis methodologies have made significant advancements over the past few years. Despite their success, most deep learning methods tend to suffer in terms of computational efficacy as the data size increases. This is largely due to their equal emphasis criteria on the rich spectral and spatial information present in the data, albeit all of the spectraland spatial information not being essential for hyperspectral data analysis. On the contrary, this redundant information present in the spectral bands can deter the performance of hyperspectral data analysis techniques. Therefore, in this work, we propose a novel branched spatial-spectral attention mechanism, which is computationally efficient and capable of adaptive spectral-spatial information diversification through selective emphasis on spectral bands that comprises more informative and suppress the ones with lesser information content. The concept of 3D-convolutions in tandem with bi-directional long short-term memory (LSTM) and ResNet is used in the proposed architecture for spectral and spatial attention mechanism. A feed-forward neural network (FNN)-based supervised classification is then performed to validate the performance of our proposed approach. Experimental results reveal that the proposed hyperspectral data analysis model with spectral-spatial attention mechanism outperforms other spatial and spectral information extraction based hyperspectral data analysis techniques compared.

## Dataset
**Name :** Indian Pines

**Size :** (145 x 145 x 200) pixels or 4,205,000 pixels

### Ground Truth (Labels)
<img src="https://user-images.githubusercontent.com/79660080/109741619-0937e880-7b93-11eb-85bc-c669356dd027.PNG" width="250" height="250">

### Input Raw Data
<img src="https://user-images.githubusercontent.com/79660080/109742886-72206000-7b95-11eb-9b41-ab9bdff7c0fd.PNG" width="250" height="250">


