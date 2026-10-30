# Attention-Guided YOLOv11 for Object Detection in Unstructured Bangladeshi Traffic (AG-YOLOv11)

Official repository for the paper: **"Attention-Guided YOLOv11 for Object Detection in Unstructured Bangladeshi Traffic"**.

---

## 📌 Overview

In South Asian contexts, traffic is highly unstructured and chaotic due to extreme vehicle density, non-standard local transports (e.g., rickshaws, CNGs, auto-rickshaws), erratic road conditions, and severe occlusion. Standard object detectors trained on Western datasets (KITTI, Cityscapes, COCO) fail to generalize to these regional scenarios.

This project proposes an **Attention-Guided YOLOv11** architecture by integrating the **Convolutional Block Attention Module (CBAM)** into deep feature maps (P5) to improve core feature extraction under severe occlusion and complex backgrounds.

---

## 🚀 Key Highlights

- **Custom Regional Dataset**: Curated and standardized from the Mendeley Bangladeshi Traffic Flow Dataset, with over 265,000 annotated instances covering 9 classes.
- **CBAM Integration**: Sequential channel and spatial attention injected into deep layers of YOLOv11m.
- **Performance**:
  - Baseline YOLOv11m: **75.1% mAP@50**
  - AG-YOLOv11m: **75.7% mAP@50**
  - Rickshaw Detection: **90.8% mAP@50**
  - Real-time Edge Inference: **~4.7 ms/frame**

---

## 📁 Repository Structure

```text
├── conference_101719.tex   # LaTeX source file of the paper
├── conference_101719.pdf   # Compiled paper PDF
├── rf.bib                  # BibTeX bibliography
├── IEEEtran.cls            # IEEE conference class file
├── fig1.png                # Representative figure
├── Images/                 # Qualitative results, architecture diagram, curves
├── .gitignore              # Configured ignore rules for LaTeX & Python/PyTorch
└── README.md               # Project documentation
```

---

## 📜 Citation

```bibtex
@inproceedings{agyolo11_bangladeshi_traffic,
  title={Attention-Guided YOLOv11 for Object Detection in Unstructured Bangladeshi Traffic},
  author={...},
  booktitle={...},
  year={2026}
}
```
