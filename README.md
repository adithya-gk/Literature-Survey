# Spatial Domain Digital Watermarking and Steganalysis: A Comprehensive Review

This repository contains research and documentation based on the literature survey: **"The Evolution of Spatial Domain Digital Watermarking and Steganalysis: A Comprehensive Review of Robust Frameworks."**

The project explores advanced methodologies in **Spatial Domain Digital Watermarking**, focusing on computational efficiency, high imperceptibility, and robust data integrity for digital media and cultural heritage protection.

---

## 🛠 Key Methodologies

* **DC Coefficient Modification**: Calculating DC coefficients directly in the spatial domain using pixel intensity means to achieve frequency-level resilience with lower computational overhead
* **Human Visual System (HVS) Integration**: Utilizing pixel-based saliency maps and compass edge detection to identify visually insignificant regions for data embedding
* **Data Hiding Capacity**: Leveraging histogram equalization to redistribute pixel intensities, maximizing the available space for hidden payloads. 
* **Reversible Data Hiding (RDH)**: Utilizing Prediction-Error Expansion (PEE) to embed large data volumes (up to 130,050 bits) while maintaining minimal image distortion
* **Advanced Steganalysis**: Implementing optimized Convolutional Neural Networks (CNNs) with Spatial Rich Model (SRM) filter banks to detect hidden payloads with high accuracy.

---

## 📊 Performance Benchmarks

The surveyed frameworks demonstrate the following high-performance metrics:

| Metric | Range / Value |
| :--- | :--- |
| **Visual Transparency (PSNR)** |40.08 dB – 58.30 dB |
| **Structural Integrity (SSIM)** | Consistently near 1.0 |
| **Hiding Capacity** |Up to 4.302 bits per pixel (bpp)|
| **Detection Accuracy** |2.1% – 3.6% improvement over state-of-the-art models|

---

## 🏛 Applications

* **Cultural Heritage (CH) Protection**: Specialized blind and robust schemes for verifying the ownership of colored cultural images.
* **Real-Time Security**: Low-complexity solutions like the "Save Algorithm" for grayscale images and rapid color watermarking with processing times as low as **0.7239 seconds**. 
