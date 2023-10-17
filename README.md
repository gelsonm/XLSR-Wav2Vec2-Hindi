# Fine-Tuning XLSR-Wav2Vec2 for Hindi Speech Recognition

![xlsr_wav2vec2](https://github.com/gelsonm/XLSR-Wav2Vec2-Hindi/assets/37416550/3ce4060e-929f-4b1e-9043-e1d3e95cffcd)

<a target="_blank" href="https://colab.research.google.com/github/gelsonm/XLSR-Wav2Vec2-Hindi/blob/main/Fine_Tune_XLSR_Wav2Vec2_on_Hindi_ASR_with_Transformers.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Wav2Vec2, a pretrained model designed for Automatic Speech Recognition (ASR), was first proposed in September 2020 by Alexei Baevski, Michael Auli, and Alex Conneau. Following its impressive performance on the English ASR dataset LibriSpeech, Facebook AI unveiled XLSR-Wav2Vec2. The "XLSR" in its name stands for cross-lingual speech representations, indicating XLSR-Wav2Vec2's capability to acquire speech representations that are applicable across multiple languages.

Similar to Wav2Vec2, XLSR-Wav2Vec2 uses the power of speech representations from over 50 languages and hundreds of thousands of hours of unlabeled speech data. It employs a method similar to BERT's masked language modeling, where it learns contextualized speech representations by randomly masking feature vectors before feeding them into a transformer network. The official paper can be found [here](https://ai.facebook.com/blog/xls-r-self-supervised-speech-processing-for-128-languages).

In this notebook, we'll look into how we can fine-tune XLSR-Wav2Vec2's pretrained model for low-resource ASR datasets for Hindi language.
