<div align="center">
  <img src="./assets/banner.svg" alt="PrayerQX banner" width="100%" />
</div>

<h1 align="center">PrayerQX</h1>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=760&lines=Image+Understanding+%7C+OCR+%7C+Document+AI;PDF-to-Markdown+%7C+RAG+Data+Pipeline;Data+Engineering+for+Multimodal+Models" alt="Typing SVG" />
</div>

<p align="center">
  图像理解 · OCR · 文档解析 · PDF-to-Markdown · 多模态数据工程
</p>

<p align="center">
  正在把复杂图像、PDF、表格和文档转化为结构化、可检索、可评测、可进入 RAG 的高质量数据。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PaddleOCR-0F766E?style=flat-square" alt="PaddleOCR" />
  <img src="https://img.shields.io/badge/MinerU-111827?style=flat-square" alt="MinerU" />
  <img src="https://img.shields.io/badge/GLM--OCR-1D4ED8?style=flat-square" alt="GLM-OCR" />
  <img src="https://img.shields.io/badge/Document%20AI-7C3AED?style=flat-square" alt="Document AI" />
  <img src="https://img.shields.io/badge/RAG-059669?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/Data%20Engineering-EA580C?style=flat-square" alt="Data Engineering" />
</p>

## 关于我

- **目前专注**：图像理解、OCR、文档解析、PDF-to-Markdown、表格/图表结构化，以及面向 RAG 和知识库的数据处理流程。
- **正在研究**：PaddleOCR、MinerU、GLM-OCR 等 OCR / 文档理解系统的论文、技术报告和工程实现，重点关注数据构建、数据清洗、版面解析、评测集设计和误差分析。
- **正在实践**：将 OCR 输出清洗、版面结构恢复、表格抽取、图文样本构造、错误样本分类统计等问题做成可复用的小工具。
- **长期判断**：模型架构红利正在变得越来越难获得，未来模型效果的差异会更依赖高质量数据、评测体系、数据闭环和工程化处理流程。
- **欢迎交流**：OCR、Document AI、PDF 解析、Markdown 文档恢复、多模态数据工程、RAG 数据准备。

## 当前方向

| 方向 | 关注问题 | 产出形式 |
| --- | --- | --- |
| OCR 与图像理解 | PaddleOCR 证据如何支撑大模型推理 | 实验代码、错误样本分析、评测记录 |
| 文档解析 | PDF、表格、公式、图片、阅读顺序如何结构化恢复 | PDF-to-Markdown 工具、benchmark 流程 |
| 数据工程 | 如何构建更干净、更可评测的数据闭环 | 清洗脚本、对比表、NotebookLM 笔记 |
| 技术传播 | 如何让项目经验被搜索和大模型正确理解 | 系列文章、自媒体矩阵、模型召回检测 |

## 核心项目

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [doc-parsing-benchmark](https://github.com/PrayerQX/doc-parsing-benchmark) | Python, PaddleOCR, Benchmarking, Markdown | 文档解析模型的 benchmark 与部署工具，支持统一输出、官方规则评测和 lite/full 可复现实验流程。 |
| [PPStructureV3-PDF-to-Markdown](https://github.com/PrayerQX/PPStructureV3-PDF-to-Markdown) | Python, PPStructureV3, OCR, PDF, Markdown | 基于 PP-StructureV3 的 PDF-to-Markdown 项目，关注标题、表格、公式、图片和阅读顺序保留。 |
| [paddleocr-ernie-pyfi](https://github.com/PrayerQX/paddleocr-ernie-pyfi) | Python, PaddleOCR, ERNIE, Image Understanding | 将 PaddleOCR 识别证据与大模型推理结合，用于金融图表和视觉问答样本的图像理解实验。 |
| [yolov5-garbage-classification](https://github.com/PrayerQX/yolov5-garbage-classification) | Python, YOLOv5, OpenCV | 基于 YOLOv5 的垃圾识别与分类计算机视觉项目。 |

## 技术栈

`Python` `PaddleOCR` `PPStructureV3` `MinerU` `GLM-OCR` `OpenCV` `YOLOv5` `Markdown` `PDF` `RAG` `Benchmarking` `Data Engineering`

## GitHub 数据

<div align="center">
  <img src="https://streak-stats.demolab.com?user=PrayerQX&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</div>

## 我的工程信条

```python
class DocumentAIEngineer:
    def __init__(self):
        self.focus = ["OCR", "layout", "tables", "evaluation", "data_engineering"]
        self.goal = "turn messy documents into reliable structured data"

    def improve(self, samples):
        errors = analyze(samples)
        data_pipeline = rebuild_from(errors)
        return evaluate(data_pipeline)
```

## 联系

如果你也在做 OCR、文档解析、PDF 处理、Markdown 文档恢复，或多模态模型的数据工程，欢迎通过 GitHub 交流。
