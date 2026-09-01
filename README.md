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

### Model Download
 (https://github.com/jankoping/SVC_ai_voice_model_Iroha/releases)

### Disclaimer
This project is intended solely for technical exchange, academic research, and personal entertainment. As the author is still learning, feedback, suggestions, and constructive discussions are always welcome. All copyrights and intellectual property rights for the training datasets and inference materials belong entirely to their original owners. The author does not claim any ownership or copyright over these assets. This AI voice model is strictly intended for fan-made, non-commercial, and non-profit derivative works. Any commercial monetization, illicit activities, or illegal uses of this project (including code, configurations, and model weights) are strictly prohibited. Users assume full legal responsibility for any consequences arising from non-compliant use.

<a name="chinese"></a> 

## 中文说明

本仓库包含 Iroha 歌声 AI 语音模型 的配置文件、推理脚本及数据集处理工作流。

- **数据预处理**: 完成原始人声音频样本的采集、切分与降噪处理，涵盖响度归一化（Loudness Normalization）、静音切除（Silence Removal）以及音高范围校准（Pitch Range Calibration）。
- **模型训练**: 基于 RVC 融合架构与 DDSP 6.3 模型进行训练构建
- **参数调优与优化**: 持续监控损失函数收敛曲线，微调变调参数，并优化特征检索索引比率，实现音色相似度与发声自然度的平衡。
- **推理测试与应用**: 针对多种曲风进行歌声转换（SVC）测试，验证模型在不同音区/音域下的表现力与稳定性。训练效果演示请参阅以下链接：https://www.bilibili.com/video/BV1iw8p6KEp2/ 和 https://www.bilibili.com/video/BV1bPun6YEkR/?vd_source=e5c30178e4ac410cbe9415975fd9f5d1

### 模型下载
 (https://github.com/jankoping/SVC_ai_voice_model_Iroha/releases)

### 声明
本项目仅供交流学习和娱乐，本人尚为初学者，如有不足欢迎切磋指教。训练数据和推理素材版权全部归原版权所有者所有，本人不拥有其版权声明。AI声音模型仅适用于同人非商业盈利二创，任何使用者不得将至用于商业盈利或违法犯罪行为。
