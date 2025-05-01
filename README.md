📢 Robust Low-Resource Speech Recognition using Wav2Vec 2.0
This repository contains the implementation of an Automatic Speech Recognition (ASR) system designed specifically for low-resource languages. Leveraging Wav2Vec 2.0 by Facebook AI and Hugging Face Transformers, the model is fine-tuned on a filtered Common Voice dataset with extensive data augmentation (SpecAugment, pitch shift, noise injection) to enhance performance.

🔧 Technologies Used
Python, PyTorch, Hugging Face Transformers, Torchaudio, Librosa

Google Colab (training environment)

Evaluation: WER, CER metrics

Model Inference: Custom audio transcription using TESTVOICE.wav

🚀 Highlights
Achieved 6.84% WER and 3.92% CER in a low-data setting

Fully reproducible in Google Colab with minimal compute resources

Real-time inference on unseen custom audio included

📁 Includes training notebook, inference script, evaluation graphs, and results summary.
