# AI-ML-Based-Two-Speaker-Speech-Separation-With-Noise-Reduction
# ABSTRACT
Speech separation in multi-speaker environments remains a critical challenge
in speech processing, particularly in scenarios with background noise and
overlapping voices that reduce intelligibility. The development of new techniques
for effective speech separation is crucial for applications such as automatic
transcription, teleconferencing, and assistive hearing devices. These techniques
must be precise, efficient, and capable of real-time processing to enhance speech
clarity. In this work, an AI-driven speech separation system is proposed with
integration of Mel-Frequency Cepstral Coefficients (MFCC) for feature
extraction, Fast Independent Component Analysis (FastICA) for blind speech
separation, and K-Nearest Neighbors (KNN) for noise classification and
reduction. The system aims to improve the quality of speech signals by effectively
separating mixed speech sources and filtering out background noise. A speech
dataset using the LibriSpeech "dev-clean" subset, covering various real-life
speech conditions are utilized. Experiments are conducted on this dataset,
demonstrating that our approach achieves a speech separation accuracy of 92%
and a noise reduction efficiency of 88%, outperforming traditional Fourier-based
filtering and standalone ICA techniques while maintaining low computational
cost. 
# INTRODUCTION
Speech separation in multi-speaker environments is a significant challenge in
speech processing. When multiple speakers talk simultaneously, distinguishing
individual voices becomes difficult, especially in noisy environments. This
challenge is critical for applications such as voice-controlled systems,
teleconferencing, and automatic transcription [1]. Traditional methods like
Fourier-based filtering and basic Independent Component Analysis (ICA)
struggle in dynamic environments where noise levels and speaker positions vary.
Deep learning models offer improved performance but require large datasets and
high computational power, making them impractical for real-time applications
[2]. This work proposes an AI-based speech separation system that integrates
Mel-Frequency Cepstral Coefficients (MFCC) for feature extraction, Fast
Independent Component Analysis (FastICA) for blind speech separation, and KNearest Neighbors (KNN) for noise classification. MFCC transforms raw audio
signals into a spectral domain for better feature extraction. FastICA separates
mixed speech signals without prior information, while KNN classifies and filters
background noise [3]. KNN is a supervised learning algorithm used to identify
and reduce noise based on the nearest feature space points. The combination of
FastICA and KNN enhances the performance of speech separation systems by
improving clarity and intelligibility [4]. Additionally, normalization techniques
improve the accuracy and consistency of speech separation across different noise
conditions. The combination of unsupervised and supervised learning enhances
the system's ability to handle complex speech mixtures, improving real-time
performance [5].

