# Rice-Disease-Detection-With-ResNet-ans-Self_Attention

## Project Description

This project is solving the crisis of rice leaf diseases by building a classifier that can early classify rice leaf diseases for better treatment. The implementation is a merge between the implementation of two research papers. The first paper is [Designing self attention-based ResNet architecture for rice leaf disease classification](https://link.springer.com/article/10.1007/s00521-022-07793-2) which adds two layers of self-attention in between the layers of a pre-trained ResNet-34 for better feature extraction. The second paper is [Learn to pay attention](https://www.robots.ox.ac.uk/~tvg/publications/2018/LearnToPayAttention_v5.pdf) which add three self-attention layers outside a pre-trained Vgg-16, and then adds the classification layers after thoso attention layers. 

My implementation adds two self-attention layers (The second paper) outside a pre-trained ResNet-34 (The first paper). The model architecture is shown in the figure below. 

![Untitled Diagram (1)](https://github.com/mx-297/Rice-Disease-Detection-With-ResNet-and-Self_Attention/assets/106694589/ddbe78ab-151d-408f-8b3b-f9c92ba96d30)

