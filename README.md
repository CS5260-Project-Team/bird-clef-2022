# BirdCLEF 2022
## Kaggle Competition
[https://www.kaggle.com/c/birdclef-2022](https://www.kaggle.com/c/birdclef-2022)
## ViT and ResNet-50 Model with Novel Data Augmentation Approaches for Bird Sounds Imbalanced Classification Problem
[Code](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/birdclef.ipynb)
## SpecAugment
[Code](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/SpecAugment.ipynb) - A spectrogram augmentation technique use to generate additional training data via warping spectrogram along the time direction, masking blocks of consecutive frequency channels, and masking blocks of utterances in time.
## Noise Reduction using Low Pass Filter
[Code](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/bird-sound-experiment/noise-reduction-using-low-pass-filter.ipynb) - To reduce bassy environmental noise.
## MixIT Bird Sound Separation
[Code](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/bird-sound-experiment/mixit-bird-sound-separation.ipynb) - To separate target bird sound from other noise components (e.g. human, environental, different bird species noise).
Sample of separated sounds are available as follows:
* https://github.com/CS5260-Project-Team/bird-clef-2022/tree/main/bird-sound-experiment/dataset/train_audio/hawhaw
* https://github.com/CS5260-Project-Team/bird-clef-2022/tree/main/bird-sound-experiment/dataset/train_audio/houfin
* https://github.com/CS5260-Project-Team/bird-clef-2022/tree/main/bird-sound-experiment/dataset/train_audio/yefcan

Manual labeled of separated sounds: [Original Metadata](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/train_metadata.csv) vs. [Manual Labeled Metadata](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/train_metadata_v2.csv)
## Silent Sound Removal
[Code](https://github.com/CS5260-Project-Team/bird-clef-2022/blob/main/bird-sound-experiment/silent-sound-removal.ipynb) - To remove silent sound when generating 5 seconds mel spectrogram.
