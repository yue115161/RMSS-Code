<div align="center">

<h1>Multimodal Remote Sensing Image Matching Considering Structural Saliency</h1>

<p>
  <b>Li Xue, Yehua Sheng, Shuwen Yang, Xiangqiang Min, and Xiu Lu</b>
</p>

</div>

---

## 📖 Overview

This repository provides the implementation of the **RMSS** algorithm, as described in the paper:

> *Multimodal Remote Sensing Image Matching Considering Structural Saliency*

Experimental comparisons between RMSS and seven state-of-the-art algorithms, using six types of multimodal remote sensing images, demonstrate that RMSS is:

- ✅ Simple to implement
- ✅ Highly robust to rotation in multimodal images
- ✅ Able to substantially improve the **number** and **localization accuracy** of matching points
- ✅ Able to improve the **correct matching rate**

---

## ✨ Contributions

The main contributions of this work are outlined as follows:

1. **Structural Saliency Representation.** We propose a novel method for expressing structural saliency. Unlike phase congruency-based approaches, we represent structural information through the **relative dispersion of neighborhood information** and **structural orientation**, which enables stable and efficient representation of structural intensity and directional information in images. This provides resilience to **NRD** and **directional reversal** in multimodal remote sensing imagery to a certain extent.

2. **Structural Saliency Descriptor.** Feature points are extracted using a **structural intensity map**, and the **GLOH** framework is optimized to construct a structural saliency descriptor vector, which enhances the rotational invariance of the descriptor.

3. **Coarse-to-Fine Matching Strategy.** A coarse-to-fine matching strategy is designed to increase the number and accuracy of matched pairs, and the **FSC** algorithm is optimized to improve the stability of mismatch pruning.

4. **Two-Stage Subpixel Refinement.** A two-stage subpixel refinement strategy that combines **Gaussian fitting** and **similarity metrics** is designed to further improve the number of matched points and localization accuracy.

Experimental results demonstrate that the proposed method exhibits **high robustness to NRD and image rotation**, and can significantly increase the number of matching points and the matching accuracy.

---

## 🚀 Run

This code is written in **C#**.

### Option 1: Just run it (image matching only)

If you only use this code for image matching, simply run:***RMSS\RMSS\bin\x64\Debug\g\RMSS.exe




### Option 2: Modify the code

If you need to change the code, please use the **Visual Studio** platform.

> Developed with **Visual Studio 2019**.

The code implements the **RMSS** algorithm (paper: *Multimodal Remote Sensing Image Matching Considering Structural Saliency*).

---

## 📊 Result


<img width="1100" height="600" alt="reslut-pair1" src="https://github.com/user-attachments/assets/5e72a855-9048-4f75-98c0-e3c612fae1f4" />

---

## 📌 Notes

- ⚠️ **Commercial use of this code is prohibited.**
- I wish you all a happy life and successful scientific research! 🎉

---

## 📝 Cite

If you find this repository useful in your research, please consider giving a star ⭐ and a citation.

**Email:** [1151617653@qq.com](mailto:1151617653@qq.com)

---

<div align="center">

<b>⭐ If this project helps you, please give it a star! ⭐</b>

</div>
