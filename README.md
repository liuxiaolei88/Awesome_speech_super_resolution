# Awesome_speech_super_resolution
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 

## Overviews
The mainstream of speech super-resolution tasks is categorized into three approaches, frequency domain, time domain, and time-frequency domain. From early mapping approaches to subsequent generative network-based approaches.

## Related papers
<!--  -->
[A deep neural network approach to speech bandwidth expansion](https://ieeexplore.ieee.org/abstract/document/7178801/)  ICASSP 2015

Method: Prediction with DNN, MMSE as loss function, input 9 frames of logarithmic magnitude spectrum, need to do norm, ensure phase using -filp.
<!--  -->
[Speech Super Resolution Generative Adversarial Network](https://ieeexplore.ieee.org/document/8682215) ICASSP 2019

Method: A CRN was used as the generator, a CNN was used as the discriminator, and loss penalized the generator for gradient.
<!--  -->
[Time-Frequency Loss for CNN Based Speech Super-Resolution](https://ieeexplore-ieee-org-443.webvpn.sysu.edu.cn/document/9053712)  ICASSP 2020 

Method: The authors propose that the performance improvement of TFNet stems from the simultaneous use of information in the network in both the time and frequency domains, but it also consumes computational resources. In this paper, we propose to use MAE loss in both time and frequency domains, and only magnitude information is used in the frequency domain, due to the fact that the magnitude spectrum can be observed with time-frequency information while the frequency spectrum cannot. The two are balanced with a grid search parameter when added together.

<!--  -->
[Low-Complexity Streaming Speech Super-Resolution](https://ieeexplore.ieee.org/abstract/document/10285965)2023 IEEE 33rd International Workshop on Machine Learning for Signal Processing (MLSP)

Method: MLP was used for the model structure and TF loss was used, where Kaiming uniform initialization was used for network initialization.