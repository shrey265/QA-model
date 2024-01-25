
## TRANSFORMER-BASED QUALITY ASSESSMENT MODEL FOR GENERALIZED USER-GENERATED MULTIMEDIA AUDIO CONTENT

Contributers<br />
Vikram Aditya Singh (2020UCS0080)<br />
Shrey Sharma (2020UCS0085)<br />
Dev Jain (2020UCS0079)<br />
Arpit Tiwari (2020UEE0137)<br />
Ankit Hooda (2020UME0215)<br />



## Introduction

In this repository, we have trained different models on IIT-JMU-UGM Audio Dataset-2 and many different comprehensive quality assessment models for generalized user-generated multimedia audio content. Our work builds upon the paper titled "TRANSFORMER-BASED QUALITY ASSESSMENT MODEL FOR GENERALIZED USER-GENERATED MULTIMEDIA AUDIO CONTENT."

## Original Dataset

The IIT-JMU-UGM Audio Dataset-2 served as the foundation for our research. Our database contains a total of 2075 audio clips. This extensive dataset forms the backbone of our research and is designed to empower quality assessment model development for a wide array of multimedia audio applications.

## Model Comparison and Evaluation Metrics

In the pursuit of advancing quality assessment for multimedia audio content, our research endeavour involved the training and evaluation of several distinct models. These models encompassed a spectrum of deep learning architectures, each tailored to address the intricate challenges posed by user-generated multimedia audio content. The models we explored include:

**Long Short-Term Memory (LSTM)**: A fundamental recurrent neural network architecture known for its ability to capture sequential dependencies in data.

**Bidirectional LSTM**: An extension of LSTM that considers both past and future contexts to enhance the understanding of audio content.

**Bidirectional LSTM with Self-Attention**: Combining the bidirectional LSTM with self-attention mechanisms to focus on relevant features and context.

**Transformer-Based Models**: A cutting-edge architecture that excels in handling sequential data, equipped with self-attention mechanisms that allow for robust feature extraction and context understanding.

## Evaluation Metrics

To rigorously assess the performance of these models, we employed a set of standardized evaluation metrics:

**Pearson Linear Correlation Coefficient (PLCC)**: PLCC quantifies the linear relationship between predicted quality scores and ground truth scores, measuring the models' ability to capture linear dependencies in the data.

**Spearman Rank Correlation Coefficient (SRCC)**: SRCC evaluates the models' ability to capture non-linear relationships by assessing the monotonic relationship between predicted quality scores and ground truth scores.

**Kendall Rank Correlation Coefficient (KRCC)**: KRCC complements SRCC by quantifying the models' capability to capture ordinal relationships between predicted quality scores and ground truth scores, making it particularly valuable for quality assessment tasks.

These metrics collectively offer a comprehensive evaluation of the models' performance, shedding light on their suitability for assessing the quality of user-generated multimedia audio content across a range of scenarios and applications.


| Metric | PLCC | SRCC | KRCC |
|----------|----------|----------|----------|
| Long Short-Term Memory | 0.766 | 0.770 | 0.574 |
| Bidirectional LSTM | 0.779 | 0.784 | 0.596 |
| Bidirectional LSTM with Self-Attention | 0.793 | 0.783 | 0.591 |
| Transformer-Based Models | 0.796 | 0.783 | 0.588 |
| GRU Based Model | 0.750 | 0.748 | 0.567 |
| dm_transformer_3_layers | 0.801 | 0.794 | 0.599 |
| dm_transformer_5_layers | 0.800 | 0.791 | 0.597 |
| dm_transformer_6_layers | 0.791 | 0.782 | 0.588 |


