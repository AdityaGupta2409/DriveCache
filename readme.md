# Road Scenario Dataset – Visual Similarity & Caching Experiments

This repository contains road scenario data used for evaluating **DriveCache-style visual similarity and caching mechanisms** in autonomous vehicle (AV) settings.

---

## 📁 Dataset Organization

The dataset is organized into **multiple folders**, where **each folder corresponds to a distinct road scenario**, such as:

- Straight roads  
- Curvy roads  
- High-traffic roads  
- Night-time scenarios  

Each scenario folder contains videos, extracted frames, annotations, or processed outputs relevant to that specific road condition.

> 📌 **Folder name = one road scenario**

---

## 🎥 Video Capture Details

- **Camera device:** *Moto Edge 50 Fusion*  
- Videos were captured directly using the mobile camera mounted on the vehicle.
- The recordings reflect **real-world driving conditions**, including varying traffic density, lighting, and road geometry.

---

## 📷 Image Descriptions

- **`AV_goPro.jpeg`**  
  Shows the **Autonomous Vehicle (AV) setup with the GoPro camera mounted** for forward-facing road capture.

- **`GoPro.jpeg`**  
  Shows the **GoPro camera device alone**, used in the AV setup.

These images are provided to visually document the experimental setup.

---

## 🔍 Intended Use

The dataset is intended for:
- Visual similarity analysis across temporal road frames
- Cache hit/miss behavior evaluation
- Ablation studies (e.g., with/without temporal windowing)
- Latency and offloading behavior analysis in AV–edge systems

---

## ⚠️ Notes

- Metadata has been stripped from shared images for privacy and reproducibility.
- The dataset is scenario-centric; users should treat each folder independently during evaluation.
- Frame indices are preserved to allow temporal analysis.

---

## 📄 Citation / Usage

If you use this dataset or setup in academic or industrial work, please cite the associated **DriveCache / vehicular edge computing study** or contact the authors for clarification.

---

For questions or clarifications, please open an issue or contact the repository maintainers.
