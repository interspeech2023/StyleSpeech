
# Abstract

The distribution of style expression in an audiobook dataset is usually unbalanced, which brings the challenge to the modeling of style representation and the expressiveness of synthesized speech. In this paper, we propose a self-supervised style enhancing method with VQ-VAE-based pre-training for expressive audiobook speech synthesis. Firstly, a text style encoder is pre-trained with a large amount of unlabeled text-only data. Secondly, a spectrogram style extractor based on VQVAE is pre-trained in a self-supervised manner, with plenty of audio data that covers complex style variations. Then a special model architecture is designed with two encoder-decoder paths to model the pronunciation and high-level style expressiveness separately with the guidance of style extractor. Both objective and subjective evaluations demonstrate that our proposed method can significantly improve the naturalness and expressiveness of the synthesized speech in audiobook synthesis. 


