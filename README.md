# 🧮 Awesome Object Counting: Methods, Papers, Datasets, and Code

A comprehensive, up-to-date collection of **object counting** resources from the computer vision community, covering a wide spectrum including:
- 🔢 **Crowd counting**
- 🚗 **Vehicle counting**
- 🧬 **Cell & microscopy counting**
- 🖼️ **Few-shot & zero-shot counting**
- 🧠 **Prompt-based CLIP models**
- 🌀 **MAE & diffusion-powered counting**

This repository is intended for **researchers, engineers, and students** working on object counting problems in computer vision.

---

## 🔍 What is Object Counting?

Object counting refers to estimating the **number of instances of an object** in an image or video without necessarily detecting every instance. It differs from object detection by focusing on *quantity over localization*.

**Why is it important?**
- Counting people in crowds or protests  
- Estimating vehicle density in traffic  
- Analyzing biological cells in medical images  
- Counting wildlife in aerial imagery  
- Zero-shot counting in open-world scenarios  

---

## 📚 Recent and Notable Papers

### 🧠 Vision-Language & Zero-Shot Counting

| Title | Method | Year | Links |
|-------|--------|------|-------|
| **CLIP-Count: Text-Guided Zero-Shot Object Counting** | Vision-Language + Prompting | 2023 | [📄 Paper](https://arxiv.org/abs/2305.07304) |
| **Training-Free Object Counting with Prompts** | Prompt + CLIP without training | 2023 | [📄 Paper](https://github.com/shizenglin/training-free-object-counter) |
| **Zero-Shot Counting** | Region-CLIP + attention map decoding | 2023 | [📄 Paper](https://github.com/cvlab-stonybrook/zero-shot-counting) |

### 🌀 MAE, Diffusion & Transformer-Based Counting

| Title | Method | Year | Links |
|-------|--------|------|-------|
| **Efficient MAE for Video Object Counting** | Masked AutoEncoder + Temporal Aggregation | 2024 | [📄 Paper](https://arxiv.org/abs/2411.13056) |
| **Diffusion-based Data Augmentation for Counting** | Diffusion-based semantic augmentation | 2024 | [📄 Paper](https://arxiv.org/abs/2411.13056) |

### 📏 Classical and Regression-Based Counting

| Title | Method | Year | Links |
|-------|--------|------|-------|
| **YOLOTC: You Only Need to Look at One** | Lightweight anchor-free counter | 2021 | [📄 Paper](https://arxiv.org/abs/2112.05993) |
| **Heatmap Regulation for Object Counting** | Regression + regularized density maps | 2018 | [📄 Paper](https://arxiv.org/abs/1803.05494) |
| **OmniCount** | Semantic-Geometric Priors + Segmentation | 2024 | [📄 Paper](https://arxiv.org/abs/2403.05435) |
| **Point, Segment and Count (PseCo)** | Joint Point + Segmentation prediction | 2022 | [🧠 Code](https://github.com/Hzzone/PseCo) |

---

## 📂 Object Counting Datasets

| Dataset | Domain | Description | Link |
|---------|--------|-------------|------|
| **FSC-147** | Generic | Few-shot object counting, 147 classes | [GitHub](https://github.com/IDKiro/FSC147) |
| **ShanghaiTech A/B** | Crowd | Crowd counting with Part A (dense) and B (sparse) | [Link](https://github.com/desenzhou/MCNN-pytorch) |
| **UCF-QNRF** | Crowd | Ultra-dense real-world scenes | [Site](https://crcv.ucf.edu/data/ucf-qnrf/) |
| **CARPK / PUCPR+** | Vehicle | Car counting from drone views | [Link](https://github.com/Guanghan/GCC-CL) |
| **JHU-CROWD++** | Crowd | Challenging dataset with occlusion, weather | [Site](https://www.crowdbenchmark.com/) |
| **Cell Counting Datasets** | Microscopy | Cell images from histopathology | [Various] |

---

## 🧪 Evaluation Metrics

| Metric | Description |
|--------|-------------|
| **MAE** | Mean Absolute Error |
| **RMSE** | Root Mean Squared Error |
| **F1-score / Acc@k** | Used in few-shot and point-based methods |
| **Rel Error (%)** | Used in zero-shot and visual-language counting |
| **MAPE** | Mean Absolute Percentage Error (less common) |

---

## 🧰 Benchmarks & Tools

- 🔬 [gjy3035/Awesome-Crowd-Counting](https://github.com/gjy3035/Awesome-Crowd-Counting): Crowd-focused methods and data
- 🧠 [IDKiro/FSC147](https://github.com/IDKiro/FSC147): Benchmark code for few-shot counting
- 📊 [Zero-Shot Counting](https://github.com/cvlab-stonybrook/zero-shot-counting): RegionCLIP-based counting
- 🖼️ [CLIP-Count](https://github.com/raoyongming/clip-count): Text-guided general counter

---

## 🔍 Categories of Methods

### 1️⃣ **Regression-Based (Density Map)**  
- **Pros**: Smooth training, works in dense occlusion  
- **Examples**: MCNN, CSRNet, SANet, Heatmap Regulation

### 2️⃣ **Detection-Based**  
- **Pros**: Interpretable, useful in sparse scenes  
- **Examples**: YOLO-based methods, CARPK detectors

### 3️⃣ **Few-shot / Meta-Learning**  
- **Pros**: Requires only few annotations per class  
- **Examples**: FSC-147 baselines (FamNet, TransCrowd)

### 4️⃣ **Vision-Language & Prompt-Based**  
- **Pros**: Zero-shot generalization  
- **Examples**: CLIP-Count, Training-Free Counter

### 5️⃣ **MAE / Diffusion-Based**  
- **Pros**: Exploits generative pretraining for perception  
- **Examples**: MAE-VideoCounter, Diffusion-Augmented

---

## 🤝 Contributing

We welcome contributions of:
- New papers
- Codebases
- Datasets
- Tools and evaluations

**To add a new paper**, open a PR and update the table in this format:

```markdown
| **Your Paper Title** | Method Type | Year | [📄 Paper](link) / [💻 Code](link) |
