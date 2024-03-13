# AI Voice Detector
- The system focuses on comparing metric outputs from Transformer models.

## Dataset

### English
- [ASVspoof 2021](https://www.asvspoof.org/index2021.html) (Large-scale dataset used for AI voice detection competitions, containing both genuine and spoofed voices, totaling over 60,000 files or 7.23 GB)
  
### Thai
- [Mozilla Common Voice Corpus 16.1](https://commonvoice.mozilla.org/th/datasets) (First Validated 10000 Files) (Bonafide)
- [AI For Thai](https://aiforthai.in.th/corpus.php) (Spoof)
  - **Text-to-Speech**: 1000 Files
  - **F0-10**: 1000 Files
  - **F0-40**: 1000 Files
  - **F0-160**: 1000 Files
  - **F0-320**: 1000 Files
  - **Pitch-Shift +4%**: 1000 Files
  - **Pitch-Shift +10%**: 1000 Files
  - **Pitch-Shift +20%**: 1000 Files
  - **Pitch-Shift -4%**: 1000 Files
  - **Pitch-Shift -10%**: 1000 Files
  - **Pitch-Shift -20%**: 1000 Files

  **Total: 11000 Files**

## Feature

- **Handcrafted Feature**
  - LFCC

- **Feature Extractor**
  - VGGish
  - Wav2vec (facebook/mms-lid-126)
  - AST (MIT/ast-finetuned-audioset-10-10-0.4593)

## Classifier
- RawNet2

## Metric
- accuracy
- t-DCF
- EER (Target < 10%)

## Baseline

- [ASVspoof Challenge 2021](https://github.com/asvspoof-challenge/2021)

  ![Baseline](https://github.com/TakdanaiG/SyntheticAiVoice/assets/112264938/ac0a47b2-ce93-4e3e-834e-888c3757f179)

## Deploy
- ?

## Cloud
- ?

## Web Example
- https://aivoicedetector.com/
- https://play.ht/voice-classifier-detect-ai-voices/
- https://elevenlabs.io/ai-speech-classifier
