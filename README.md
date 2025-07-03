# Pix2Pix: Implementation from Scratch

This repository contains a **from-scratch implementation of the Pix2Pix Conditional GAN** for image-to-image translation tasks, specifically trained on the Cityscapes dataset.

---

## 🏙️ Dataset

We use the preprocessed Cityscapes dataset formatted for Pix2Pix, available on Kaggle:

- 📂 [Cityscapes Pix2Pix Dataset on Kaggle](https://www.kaggle.com/datasets/balraj98/cityscapes-pix2pix-dataset/data?select=val)

This dataset provides paired images (`label` and `photo`) needed for supervised translation.

---

## 📝 Reference Paper

This work is based on the seminal paper:

> **Image-to-Image Translation with Conditional Adversarial Networks**  
> Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros.  
> [[arXiv:1611.07004](https://arxiv.org/abs/1611.07004)]

### 📚 Citation

If you use or build on this implementation, please cite the original paper:

```bibtex
@misc{isola2018imagetoimagetranslationconditionaladversarial,
      title={Image-to-Image Translation with Conditional Adversarial Networks},
      author={Phillip Isola and Jun-Yan Zhu and Tinghui Zhou and Alexei A. Efros},
      year={2018},
      eprint={1611.07004},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/1611.07004}
}
