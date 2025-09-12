# 🛡️ Model Inversion Attack Papers Collection 

> 📚 **A comprehensive collection of research papers on Model Inversion Attack in machine learning.**  
> 🎓 **Maintained by**: Dr. [Shanzhong Lei] | [Chongqing University of Posts and Telecommunications] | [szhonglason@gmail.com]

## 📖 About This Repository

This repository serves as a curated collection of academic papers focusing on **attack methods and defense mechanisms** in machine learning. Our goal is to provide researchers, practitioners, and students with a comprehensive overview of the current state-of-the-art in this critical security domain.

## 💡What is the model inversion attack?

A model inversion attack is a privacy attack where the attacker is able to reconstruct the original samples that were used to train the synthetic model from the generated synthetic data set. (Mostly.ai)

The goal of model inversion attacks is to recreate training data or sensitive attributes.
(Chen et al, 2021.)

In model inversion attacks, a malicious user attempts to recover the private dataset used to train a supervised neural network. A successful model inversion attack should generate realistic and diverse samples that accurately describe each of the classes in the private dataset. (Wang et al, 2021.)


### 🎯 **Repository Purpose:**
- 🏆 **Quality Focus**: Emphasis on high-impact venues. [CCF-Rankings](https://www.ccf.org.cn/en/About_CCF/Media_Center/) now marked with different colors(![arXiv](https://img.shields.io/badge/CCF_A-dc3545) ![Static Badge](https://img.shields.io/badge/CCF_B-ffc107) ![Static Badge](https://img.shields.io/badge/CCF_C-28a745) ![Static Badge](https://img.shields.io/badge/CCF_None-6c757d))
- 🔄 **Regular Updates**: Continuously updated with latest research developments
- 🌐 **Easy Access**: Direct links to papers, code repositories, and supplementary materials

### 📊 **Each paper includes the following evaluation metrics (out of 5 stars):**
- **💡 Motivation**: How well-motivated and significant is the research problem? ⭐⭐⭐⭐⭐ (5/5)
- **🔧 Method**: How novel and technically sound is the proposed approach? ⭐⭐⭐⭐⭐ (5/5)

<h2 id="awesome-papers"> 👑 Awesome Papers List </h2>

<h3 id="attacks"> 2025 </h3>

* **[2025.04.28]** **[Diffusion-Driven Universal Model Inversion Attack for Face Recognition](https://openreview.net/forum?id=s56xikpD92)** ![Static Badge](https://img.shields.io/badge/CVPR'25-6c757d)(![arXiv](https://img.shields.io/badge/CCF_A-dc3545)) 
  * Hanrui Wang , Shuo Wang , Chun-Shien Lu , Isao Echizen
  * **📝 Summary**: This paper propose a novel method called DiffUMI, a training-free diffusion-driven universal model inversion attack for face recognition systems. DiffUMI is the first approach to apply a                           diffusion model for unconditional image generation in model inversion.
  * **💡 Motivation**: ⭐⭐⭐⭐⭐ (5/5) - Solved the critical challenges of relying on datasets for training, poor open-set adaptability, and limited reconstruction quality.
  * **🔧 Method**: ⭐⭐⭐⭐ (4/5) - The methods include DiffUMI and OODD. DiffUMI adapts to any open-set face recognition model through a fixed framework, innovatively analyzes the impact of latent codes, proposes a highly reliable latent code selection method, and introduces a ranking adversary strategy to optimize attack effectiveness. OODD distinguishes between face and non-face inputs solely based on feature embeddings.

 * **[2025.03.20]** **[From Head to Tail: Efficient Black-box Model Inversion Attack via Long-tailed Learning](https://openreview.net/forum?id=s56xikpD92)** ![Static Badge](https://img.shields.io/badge/CVPR'25-6c757d) [![GitHub stars](https://img.shields.io/github/stars/L1ziang/SMILE?style=social)](https://github.com/L1ziang/SMILE) ![arXiv](https://img.shields.io/badge/CCF_A-dc3545)
  * Ziang Li, Hongguang Zhang, Juan Wang, Meihui Chen, Hongxin Hu, Wenzhe Yi, Xiaoyang Xu, Mengda Yang, Chenjun Ma
  * **📝 Summary**: This paper analyzes the limitations of existing MIAs and introduce Surrogate Modelbased Inversion with Long-tailed Enhancement (SMILE), a high-resolution oriented and query-efficient MIA for the black-box setting.
  * **💡 Motivation**: ⭐⭐⭐⭐ (5/5) - Addressed the limitations of existing black-box MIAs from two perspectives: the targeted datasets and the number of queries.
  * **🔧 Method**: ⭐⭐⭐⭐⭐ (5/5) - The work proposes a long-tailed surrogate training method to obtain highquality initial points, and then enhance the attack’s effectiveness by employing the gradient-free black-box optimization algorithm selected by NGOpt.
<h3 id="attacks"> 2024 </h3>
