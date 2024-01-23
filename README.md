# SyntheticAiVoice
**Dataset**
  - https://drive.google.com/drive/folders/1-6SszeC3unvNlZF2nJWoVhn0RpN6tAF1?usp=sharing ASVspoof 2021 (LA) (Dataset ขนาดใหญ่ที่เอาไว้แข่ง จะมีเสียงคนพูดจริงกับเสียงปลอมที่ถูกสร้างขึ้น (ปลอม 90%, จริง 10%) 60,000 ไฟล์ หรือ 7.23 GB)
  - https://commonvoice.mozilla.org/th/datasets เสียงภาษาไทยจาก Mozilla (ของจริง) 10000 ไฟล์
  - เสียงภาษาไทย TTS (ของปลอม) 10000 ไฟล์

**Feature**

  - **Handcrafted Feature**
    - Mel spectrogram
    - Mel Frequency Cepstral Coefficient (MFCC)
    - Short-Time Fourier Transform (STFT)

  - **Feature Extractor**
    - Wav2vec
    - VGGish
    - OpenL3


    
**Method**

  - Rawnet (CRNN)
  - Wavenet
  - Sample CNN
  - DNN
  - LSTM, RNN
  - CNN
  - GMM
  - HMM

**Metric**
  - t-DCF
  - EER (Target < 10%)

**Baseline**
  - https://github.com/asvspoof-challenge/2021
    
    ![image](https://github.com/TakdanaiG/SyntheticAiVoice/assets/112264938/ac0a47b2-ce93-4e3e-834e-888c3757f179)


**Deploy** 
  - HTML, CSS, FLASK

**Cloud**
  - AWS
