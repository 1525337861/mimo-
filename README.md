# 我的半监督学习图像分类项目列表

## 1. [JanMarcelKezmann/Semi-Supervised-Learning-Image-Classification](https://github.com/JanMarcelKezmann/Semi-Supervised-Learning-Image-Classification)
- **描述**：该项目实现了多种半监督学习算法（如 FixMatch、Mean Teacher、Pseudo-Label 等），专注于图像分类任务，使用 TensorFlow 2.x 和 Python 3.x 开发，结构简洁，易于理解和扩展。
- **特点**：
  - 高层次 API，适合快速实验。
  - 支持 CIFAR-10、ImageNet 等数据集。
  - 包含常见 CNN 模型（如 ResNet、WideResNet）的实现。
  - 支持 Jupyter Notebook 和命令行运行。
- **代码结构**：
  - `ssl_image_classification/algorithms/`：包含各半监督算法的实现，如 `fixmatch.py`。
  - `ssl_image_classification/models/`：包含模型定义。
  - `ssl_image_classification/data/`：数据加载和预处理。
  - `ssl_image_classification/utils/`：工具函数，如日志记录、学习率调度等。
- **适用场景**：如果你想快速实现并实验各种半监督学习算法，可以参考这个项目。非常适合对半监督学习算法进行对比和测试。

## 2. [leaderj1001/Billion-scale-semi-supervised-learning](https://github.com/leaderj1001/Billion-scale-semi-supervised-learning)
- **描述**：该项目实现了 Facebook AI 提出的“大规模半监督学习”方法，使用 PyTorch 开发，适用于大规模图像分类任务。
- **特点**：
  - 针对百万级数据集的半监督学习。
  - 实现了教师-学生模型架构。
  - 支持数据爬取、预处理和模型训练。
- **代码结构**：
  - `image_crawler/`：图像数据爬取。
  - `preprocess/`：数据预处理。
  - `model.py`：模型定义。
  - `student_train.py`：学生模型训练。
  - `main.py`：主程序入口。
- **适用场景**：如果你处理的是大规模数据集，并且需要处理数百万个图像，可以参考这个项目。特别适用于高效的半监督学习和数据爬取任务。

## 3. [aillaud/Semi-Supervised-Learning-CIFAR10](https://github.com/aillaud/Semi-Supervised-Learning-CIFAR10)
- **描述**：该项目实现了 FixMatch 算法，专注于 CIFAR-10 数据集，使用 PyTorch 开发，适合初学者学习和实验。
- **特点**：
  - 实现了 FixMatch 算法。
  - 专注于 CIFAR-10 数据集。
  - 代码简洁，易于理解。
- **代码结构**：
  - `fixmatch.py`：FixMatch 算法实现。
  - `train.py`：训练脚本。
  - `utils.py`：工具函数。
- **适用场景**：如果你是初学者，并且想专注于 FixMatch 算法在小数据集（如 CIFAR-10）上的实现和实验，可以参考这个项目。

## 4. [microsoft/Semi-supervised-learning](https://github.com/microsoft/Semi-supervised-learning)
- **描述**：该项目是微软提出的统一半监督学习代码库（USB），使用 PyTorch 开发，支持多种半监督学习算法和任务。
- **特点**：
  - 实现了 14 种半监督学习算法。
  - 支持计算机视觉、自然语言处理和语音任务。
  - 易于扩展和修改。
- **代码结构**：
  - `ssl/`：半监督学习算法实现。
  - `tasks/`：任务定义。
  - `utils/`：工具函数。
  - `configs/`：配置文件。
- **适用场景**：适合需要对多种半监督学习算法进行实验和调试的场景，特别适合想要处理多个任务（如视觉、语言处理等）的人。

