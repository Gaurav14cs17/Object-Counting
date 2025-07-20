# 🧮 Awesome Object Counting (Selected Works)

![PP-YOLOE Demo](https://github.com/Gaurav14cs17/YOLOE/blob/main/images/yoloe.png)

A focused collection of **recent and impactful papers** on object counting using modern computer vision techniques — including **masked autoencoders**, **diffusion models**, **prompt-based zero-shot learning**, and **semantic priors**.

> 📌 This list includes **9 top papers** across video, crowd, prompt-based, and semantic counting.

---

## 📚 Papers & Code

| Title | Summary | Year | Link |
|-------|---------|------|------|
| **Efficient Masked AutoEncoder for Video Object Counting and A Large-Scale Benchmark** | MAE-based encoder with temporal modeling and new large-scale benchmark for object counting in video | 2024 | [📄 arXiv:2411.13056](https://arxiv.org/abs/2411.13056) |
| **Diffusion-based Data Augmentation for Object Counting Problems** | Uses diffusion models to generate semantically consistent augmented images for improving counting models | 2024 | [📄 arXiv:2411.13056](https://arxiv.org/abs/2411.13056) |
| **CLIP-Count: Towards Text-Guided Zero-Shot Object Counting** | Leverages CLIP and class prompts (e.g., “count the apples”) to perform zero-shot counting without retraining | 2023 | [📄 arXiv:2305.07304](https://arxiv.org/abs/2305.07304) |
| **Object Counting: You Only Need to Look at One (YOLOTC)** | Introduces a fast anchor-free counting model using a simple regression head — efficient for deployment | 2021 | [📄 arXiv:2112.05993](https://arxiv.org/abs/2112.05993) |
| **Improving Object Counting with Heatmap Regulation** | Classic regression-based method using heatmap supervision to improve the quality of predicted density maps | 2018 | [📄 arXiv:1803.05494](https://arxiv.org/abs/1803.05494) |
| **OmniCount: Multi-label Object Counting with Semantic-Geometric Priors** | Uses semantic maps and geometric priors for simultaneous multi-class counting in complex scenes | 2024 | [📄 arXiv:2403.05435](https://arxiv.org/abs/2403.05435) |
| **Point, Segment and Count (PseCo)** | A unified framework combining point supervision and segmentation for better spatial awareness in counting | 2022 | [💻 GitHub](https://github.com/Hzzone/PseCo) |
| **Training-free Object Counting with Prompts** | Prompt-based CLIP model that counts objects from natural language queries without training | 2023 | [💻 GitHub](https://github.com/shizenglin/training-free-object-counter) |
| **Zero-shot Object Counting (ZSOC)** | Open-vocabulary counter using RegionCLIP and attention-guided density estimation for zero-shot counting | 2023 | [💻 GitHub](https://github.com/cvlab-stonybrook/zero-shot-counting) |

---

## 🧪 Categories

### 🎥 Video-Based Counting
- **Efficient MAE for Video Counting**  
  > Temporal-aware Masked AutoEncoder architecture  
- **Diffusion-based Augmentation**  
  > Training-time image synthesis to improve model generalization  

### 🧠 Vision-Language / Prompt-Based
- **CLIP-Count**  
  > Text-driven, zero-shot counting with CLIP  
- **Training-Free Object Counting**  
  > No training required — works with simple prompts  
- **Zero-Shot Object Counting (ZSOC)**  
  > Open-vocabulary approach using RegionCLIP and attention maps

### 📈 Classical / Regression-Based
- **YOLOTC (You Only Need to Look at One)**  
  > Anchor-free, simple regression model  
- **Heatmap Regulation**  
  > Enhancing density maps with heatmap losses  
- **PseCo (Point, Segment and Count)**  
  > Uses point-level and segmentation cues  
- **OmniCount**  
  > Combines semantics + geometry for multi-label object counting

---

## 📊 Evaluation Metrics

- **MAE**: Mean Absolute Error  
- **RMSE**: Root Mean Squared Error  
- **F1-score**: Often used for localization-based methods  
- **Relative Error**: In prompt-based or zero-shot methods  
- **Per-class accuracy**: For multi-label counting models like OmniCount

---

## 🧠 Recommended Reading Order

If you're just getting started:
1. 🔢 Start with **YOLOTC** or **Heatmap Regulation** for classical foundations
2. 🎓 Learn about **PseCo** and **OmniCount** for modern segmentation and multi-label approaches
3. 🖼️ Explore **CLIP-Count** and **ZSOC** for vision-language, zero-shot capabilities
4. 🧪 Finally, dive into **MAE** and **Diffusion-based** approaches for generative and video-specific enhancements

---

## 🙌 Contributions

Want to suggest new papers or improvements?  
Feel free to submit a [Pull Request](https://github.com/your-repo/pulls) or open an [Issue](https://github.com/your-repo/issues).

---

## 📄 License

This repository is released under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

This list is inspired by the structure of [Awesome Crowd Counting](https://github.com/gjy3035/Awesome-Crowd-Counting) and the work from researchers in the object counting field.

---
