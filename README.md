# DPMS-YOLOv8

**DPMS-YOLOv8** 是基于煤矿井下图像数据，对 YOLOv8 网络结构进行改进的目标检测模型，在公开 DSLMF 数据集上取得了 **98% 的准确率**。  
该项目旨在提升井下异常检测的精度与鲁棒性，适用于智能化煤矿安全监测场景。

---

## 📂 数据集

- **DSLMF 数据集下载**：[点击获取](https://springernature.figshare.com/articles/dataset/An_open_dataset_for_intelligent_recognition_and_classification_of_abnormal_condition_in_longwall_mining/22654945)

---

## 🏗️ 模型架构

### 整体结构
<img width="558" height="241" alt="DPMS-YOLOv8架构图" src="https://github.com/user-attachments/assets/052e6e9c-f65a-4317-9339-d4d8f4ce8c77" />

---

## ⚙️ 环境配置
| CUDA 版本   | 12.1 |
| Python 版本 | 3.11 |

安装依赖：
```bash
pip install -r requirements.txt
pip install -e .
---

## 🚀 快速开始
运行推理：
```bash
python detect.py --source test.jpg --weights DPMS-Yolov8.pt
---

## 🚀 快速开始
运行推理：
```bash
python detect.py --source test.jpg --weights DPMS-Yolov8.pt


