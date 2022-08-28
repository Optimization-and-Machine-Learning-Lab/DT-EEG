# DT-EEGNet

The implementation of EEGNet and DTNet+EEGNet for the paper, 'Towards a Digital Twin of Cognitive Processes' (link to be added)

Abstract:
In recent years, the field of digital twins has witnessed rapid developments due to the advancement in industry~4.0
technologies such as the internet of things and artificial intelligence. However, with a wide range of applications from manufacturing to engineering, there still lies an opportunity to explore its full potential in health and well-being. In particular, the field of cognitive health could benefit from a personalized approach to patient care. In this paper, we propose a reproducible framework that integrates deep learning with digital twin concepts to address an electroencephalography (EEG) signal classification problem. Our method extends a simple convolutional neural network (CNN) architecture to integrate an individualized model that learns a latent representation of the subject's experience. Moreover, it enables the development of a digital twin that learns over time and can be utilized in various ways, such as analysis of cognitive psychology, lifestyle habits, or an individual's most effective learning style. Finally, we demonstrate the effectiveness of our proof of concept in tackling raw EEG signal classification using datasets related to two cognitive tasks: motor imagery and event-related potential. Besides incorporating personalization, our approach achieves marginal improvement in accuracy on the baseline. 

Original EEGNet Paper: [Source](https://arxiv.org/abs/1611.08024#:~:text=In%20this%20work%20we%20introduce,feature%20extraction%20concepts%20for%20BCI.)

## Prerequisites:
- The code is based on Python 3.8
- The code was run on [NVIDIA RTX A6000](https://www.nvidia.com/en-us/design-visualization/rtx-a6000/) (CUDA 11.7)

## Dataset:
- Motor imagery task: BCI Competition IV 2a available at [Source](https://www.bbci.de/competition/iv/)
  - Upon downloading it, make sure to save it in the following path, "BCI Competition IV/Dataset2/2a/"
- Loaded using: [Get_data](https://github.com/MultiScale-BCI/IV-2a/blob/master/get_data.py)


## Usage:
- EarlyStopping : [pytorchtools](https://github.com/Bjarten/early-stopping-pytorch/blob/master/pytorchtools.py)


### Contact:
- Shahd AlShamsi: shahd.alshamsi@mbzuai.ac.ae
- Martin Takáč: martin.takac@mbzuai.ac.ae
- Abdulmotaleb El Saddik: a.elsaddik@mbzuai.ac.ae

