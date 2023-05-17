# Waveform-based Audio Classification of Environmental Sounds

This project focuses on the classification of environmental sounds using a deep learning approach. The goal is to compare the effectiveness of waveform-based inputs for audio classification with that of spectrogram-based inputs. The research has been conducted using the UrbanSound8k dataset and deep learning techniques to evaluate the accuracy, computational efficiency, and interpretability of both approaches.

## Abstract
The findings of this study show that waveform-based audio classification achieves an accuracy of 80%, slightly lower than the 84% accuracy achieved with spectrogram-based inputs. However, waveform-based inputs offer advantages such as preserving temporal information and reducing preprocessing steps. This makes them a promising alternative in scenarios where precise timing and temporal dynamics are crucial. More details can be found in the research paper.

## Model Architecture
The model, defined by the AudioToVisualModel class, comprises several convolutional layers (conv1, conv2, conv3, conv4) for feature extraction, recurrent layers (rnn) for capturing temporal dependencies, and a fully connected layer (fc1) for classification.

## Dataset
The UrbanSound8k dataset, a widely used benchmark dataset for audio classification tasks, has been used for this study. It consists of 8,732 labeled sound excerpts from urban environments, spanning ten different classes.

## Training Parameters
The model utilizes the `nn.CrossEntropyLoss()` function for multi-class classification tasks. The training procedure employs the Adam optimizer with a learning rate (lr) of 0.001. The recurrent layers have been set to 2 with 512 hidden units each.

## Results
The model achieved a validation accuracy of and test accuracy of 79.62%. Detailed results including the confusion matrix and training validation curve can be found in the research paper.

## Authors
- Bhanu Gupta(bvg9468)
- Pranav Narayan(pn2229)
- Purvav Punyani(psp8474)

## Institution
New York University Tandon School of Engineering

## License
This project is licensed under the AAAI Press. All rights reserved. For more information, please see the AAAI copyright notice in the research paper.

## References
Details about the references used in this project can be found in the research paper.

## Acknowledgments
The authors would like to acknowledge the support and resources from their institution and the contributors of the UrbanSound8k dataset.
