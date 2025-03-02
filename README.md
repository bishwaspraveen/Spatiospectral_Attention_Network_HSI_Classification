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

## Pictorial Representation of the Classification Methodology

### Overall Pipeline
<img src="https://user-images.githubusercontent.com/79660080/109743578-8dd83600-7b96-11eb-8c73-a1f1a30f04b2.PNG" width="650" height="350">

### Spectral Attention Module
<img src="https://user-images.githubusercontent.com/79660080/109743662-b2cca900-7b96-11eb-8a66-4bd4ed1f30c2.PNG" width="650" height="350">

### Spatial Attention Module
<img src="https://user-images.githubusercontent.com/79660080/109743803-ee677300-7b96-11eb-8118-2adbaca2f800.png" width="750" height="350">

## Results

### Classification Map (10% Training Data - Accuracy : 98.49%)
<img src="https://user-images.githubusercontent.com/79660080/109744711-61251e00-7b98-11eb-9387-c46ef86d642a.PNG" width="250" height="250">

### Classification Accuracy Table (10% Training Data)
<img src="https://user-images.githubusercontent.com/79660080/109745525-9e3de000-7b99-11eb-8b38-19da5f8b4713.PNG" width="700" height="300">

### Training v/s Validation Loss and Accuracy plot (10% Training Data)
<img src="https://user-images.githubusercontent.com/79660080/109744965-ce38b380-7b98-11eb-823f-49aabcea16de.PNG" width="450" height="600">


