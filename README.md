# Playground for CLIP-like models
## GradCAM implementations for Vision Transformer CLIP variants

Original `clip_playground` repo now updated with new notebooks on GradCAM methods for ViT CLIP variants. 

| Demo  | Colab Link |
| ------------- | ------------- |
| GradCAM Visualization  |  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/boolean-jiang/clip_playground/blob/main/CLIP_GradCAM_Visualization.ipynb)  |
| GradCAM Visualization (Hugging Face ViTs) |  [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/boolean-jiang/clip_playground/blob/main/CLIP_GradCAM_Visualization_ViT_HuggingFace.ipynb)  |
| Naive Zero-shot Detection  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/boolean-jiang/clip_playground/blob/main/CLIP_Patch_Detection.ipynb)  |
| Smarter Zero-shot Detection  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/boolean-jiang/clip_playground/blob/main/CLIP_Zero_shot_Detector.ipynb)  |
| Captcha Solver  | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/boolean-jiang/clip_playground/blob/main/CLIP_reCAPTCHA.ipynb) |

If you find this playground useful, consider citing it!

**For ViT GradCAMs:**

```bibtex
@software{zakka2021clipplayground,
    author = {Jiang, Bowen},
    month = {12},
    title = {{A Playground for CLIP-like Models - GradCAM implementations for Vision Transformer CLIP variants }},
    url = {https://github.com/boolean-jiang/clip_playground},
    version = {0.0.1},
    year = {2022}
}
```

**For everything else:**

```bibtex
@software{zakka2021clipplayground,
    author = {Zakka, Kevin},
    month = {7},
    title = {{A Playground for CLIP-like Models}},
    url = {https://github.com/kevinzakka/clip_playground},
    version = {0.0.1},
    year = {2021}
}
```

## Changelog

### 2022-12-30

* Added a new notebook for GradCAM visualization with ViT variants of CLIP (HuggingFace implementations).

### 2021-07-28

* Better plotting for reCAPTCHA.

### 2021-07-27

* Allow multiple captions in detection query, colon separated.
* Allow the user to resize an image during selective search.
* Tuned the rejection parameters of selective search.
* Minor bugfix in naive patch detector.
