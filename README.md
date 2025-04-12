# 🎨 Image Colorization using Conditional GANs

This project explores the use of **Conditional Generative Adversarial Networks (cGANs)** for automatic colorization of grayscale images. We implement a Pix2Pix-style model using a **UNet-based generator** and **PatchGAN discriminator**, enhanced further with pre-trained backbones (like ResNet18). The approach is trained and evaluated on a subset of the **ImageNet-1000** dataset.

> 📄 **Full Report Available**  
> For complete details, methodology, loss functions, results, and architecture diagrams, please refer to the report:  
> 👉 **[Download Image_Colorization.pdf](./Image_Colorization_using_Conditional_Generative_Adversarial_Networks.pdf)**

---

## 🧠 Project Highlights

- ✅ Conditional GAN (Pix2Pix) with UNet Generator
- ✅ PatchGAN Discriminator with 70x70 receptive field
- ✅ Training on Lab color space (L → input, ab → target)
- ✅ Optional ResNet18 pre-trained backbone
- ✅ L1 + GAN combined loss for sharper results
- ✅ Evaluation with real grayscale photos and COCO dataset

---

## 🗂 Project Structure

```bash
.
├── Image_Colorization_CLEANED.ipynb    # Main Colab code with training + visualization
├── Image_Colorization_using_Conditional_Generative_Adversarial_Networks.pdf  # Full report
├── results/                            # (Optional) Folder to save generated outputs
└── README.md                           # You're here
