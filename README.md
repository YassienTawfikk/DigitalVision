## DigitalVision Toolkit

---

### Overview

**DigitalVision** is a curated umbrella repository containing four advanced computer vision projects developed using Python and OpenCV. Each project is modular, interactive, and designed as a standalone submodule. Together, they demonstrate expertise in edge detection, image segmentation, feature matching, and image filtering, making this toolkit ideal for educational use, research prototypes, and computer vision benchmarking.

Each project also contains its own folder structure and a detailed `README.md` file showcasing feature comparisons, visual examples, and technical explanations. Notably, over **95% of all features are implemented manually**, without relying on OpenCV’s built-in processing functions — reinforcing deep algorithmic understanding.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0aa92ef3-5098-45b9-a77f-ede290870fc6" width="49%" alt="Pixelizer">  
  <img src="https://github.com/user-attachments/assets/b6d5490e-700e-4fbe-94b2-1ecf6a6bbc2c" width="49%" alt="SegmaVision"> 
  <img src="https://github.com/user-attachments/assets/c9dced42-db09-4306-a60b-84c498ebf52c" width="49%" alt="SIFT-See">
  <img src="https://github.com/user-attachments/assets/00d25199-949f-4fe5-b372-7c593e2dcccc" width="49%" alt="EdgeEnhance"> 
</p>

---

## Included Projects

| Project         | Description                                                                   | Link                                                         |
| --------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| **EdgeEnhance** | Edge and boundary detection using Canny, Hough Transform, and Active Contours | [EdgeEnhance](https://github.com/YassienTawfikk/EdgeEnhance) |
| **SIFT-See**    | Feature detection, descriptor matching (SSD/NCC), and SIFT visualization      | [SIFT-See](https://github.com/YassienTawfikk/SIFT-See)       |
| **Pixelizer**   | GUI-based image filtering, noise simulation, histogram equalization           | [Pixelizer](https://github.com/YassienTawfikk/Pixelizer)     |
| **SegmaVision** | Thresholding and unsupervised segmentation (K-Means, Region Growing, etc.)    | [SegmaVision](https://github.com/YassienTawfikk/SegmaVision) |

Each project is integrated as a **Git submodule**. To clone this repository and initialize all modules:

```
git clone --recurse-submodules https://github.com/YassienTawfikk/DigitalVision.git
```

---

### Key Features

* **Edge Detection & Shape Extraction (EdgeEnhance/)**
  * Canny, Hough Line/Circle/Ellipse, Active Contour Models

* **Feature Detection & Matching (Sift-See/)**
  * Harris Corner, SIFT Descriptors, SSD and NCC Matching

* **Noise & Filtering Tools (Pixelizer/)**
  * Uniform noise simulation, Median Filter, Prewitt operator, Histogram Equalization

* **Segmentation & ML Techniques (SegmaVision/)**
  * Otsu, Spectral, Optimal Thresholding
  * K-Means, Mean Shift, Agglomerative Clustering, Region Growing

---

### Setup Instructions

After cloning:

```
# Choose a project to explore
cd EdgeEnhance  # or SIFT-See, Pixelizer, SegmaVision

# Install dependencies
pip install -r requirements.txt

# Run the app
python main.py
```

---

### Authors & Contributors

This unified toolkit is collaboratively developed by:

<div>
  <table align="center">
    <tr>
      <td align="center">
        <a href="https://github.com/YassienTawfikk" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/126521373?v=4" width="120px;" alt="Yassien Tawfik"/><br/>
          <sub><b>Yassien Tawfik</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/madonna-mosaad" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/127048836?v=4" width="120px;" alt="Madonna Mosaad"/><br/>
          <sub><b>Madonna Mosaad</b></sub>
        </a>
      </td>      
      <td align="center">
        <a href="https://github.com/nancymahmoud1" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/125357872?v=4" width="120px;" alt="Nancy Mahmoud"/><br/>
          <sub><b>Nancy Mahmoud</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/nariman-ahmed" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/126989278?v=4" width="120px;" alt="Nariman Ahmed"/><br/>
          <sub><b>Nariman Ahmed</b></sub>
        </a>
      </td>      
    </tr>
  </table>
</div>

---
