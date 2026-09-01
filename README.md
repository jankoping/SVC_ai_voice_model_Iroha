# SVC AI Voice Model - Iroha (酒寄彩叶自定义声音模型)

[English](#english) | [中文说明](#chinese)

---

<a name="english"></a>
## 🇬🇧 English Description

### Project Overview
This repository contains the configuration, inference scripts, and dataset processing workflow for the **Iroha** Singing Voice AI voice model. 

### Learning & Project Experience
- **Data Preprocessing**: Collected, segmented, and denoised raw vocal audio samples (loudness normalization, silence removal, and pitch range calibration).
- **Model Training**: Trained using the RVC fusion framework with DDSP 6.3 model.
- **Optimization & Tuning**: Monitored loss convergence curves, fine-tuned pitch shift parameters, and adjusted feature index ratio to balance vocal similarity and natural timbre.
- **Inference & Application**: Conducted multi-genre singing voice conversion to verify expressiveness and stability across different pitch registers. See the training outcomes in the links below:https://www.bilibili.com/video/BV1iw8p6KEp2/ and https://www.bilibili.com/video/BV1bPun6YEkR/?vd_source=e5c30178e4ac410cbe9415975fd9f5d1

### Repository Structure
- `configs/`: Model hyperparameters and training configuration files.
- `demos/`: Audio samples showcasing original vs. converted singing voices.
- `weights/`: Instructions and download links for pre-trained model weights (`.pth` & `.index`).

### Model Download
Due to GitHub file size limitations, large pre-trained weights are hosted externally:
- **Model Checkpoint (`.pth`)**: [Download from Hugging Face / Release Link](https://github.com/jankoping/SVC_ai_voice_model_Iroha/releases)
- **Feature Index (`.index`)**: Included in the release asset package.

### Quick Start
1. Clone this repository:
   ```bash
   git clone [https://github.com/jankoping/SVC_ai_voice_model_Iroha.git](https://github.com/jankoping/SVC_ai_voice_model_Iroha.git)
   cd SVC_ai_voice_model_Iroha
