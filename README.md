# 🗣️ Bemba ASR Model Evaluation with Wav2Vec2-BERT

This project evaluates multiple **Wav2Vec2-BERT** models on a **5-hour Bemba language speech dataset**. It uses Hugging Face pipelines to transcribe speech, computes **Word Error Rate (WER)** and **Character Error Rate (CER)**, and exports detailed CSV reports per model.

---

## 🎯 Objectives

- Load pre-trained Wav2Vec2-BERT ASR models from Hugging Face Hub
- Perform inference on Bemba audio using the `Beijuka/Bemba_test_5hr` dataset
- Compute WER and CER for each utterance and model
- Save detailed predictions and error scores to CSV

---

## 🧰 Dependencies

Install all required packages:

```bash
pip install transformers datasets torchaudio librosa jiwer evaluate pandas tqdm
