# Andromeda-X1
This is my final year project that I made for my dissertation.

- Deep CNN (ResNet-18) trained on ~145,000 galaxy images.
- Data augmentation and normalization for robust learning.
- Grad-CAM++ visualizations to understand model decisions.
- Accuracy: **64.08%** on a held-out test set of ~21,000 images.
- Evaluation with precision, recall, F1-score, and confusion matrix.
# lessons 
This is my final year project that I made for my dissertation.
- Deep CNN (ResNet-18) trained on ~145,000 galaxy images.
- Data augmentation and normalization for robust learning.
- Grad-CAM++ visualizations to understand model decisions.
- Accuracy: **64.08%** on a held-out test set of ~21,000 images.
- Evaluation with precision, recall, F1-score, and confusion matrix.


## Dataset and Requirements 

Python 3.11

PyTorch 2.0.1

NumPy, matplotlib, scikit-learn

NVIDIA RTX 3060 (GPU with CUDA 11.8)

Image Dataset that was used can be found as [images_gz2.zip](https://zenodo.org/records/3565489#.Y3vFKS-l0eY)

The corresponding lables to the image data is labled as [gz2_filename_mapping.csv](https://zenodo.org/records/3565489#.Y3vFKS-l0eY)
## Authors

- **Smit Chaudhari** Computer Science student at University Of Sussex.
- Project Supervisor: **Dr.James Bannett** - Lecturer in Computer Science and AI, University of Sussex.




## Acknowledgements
- Andromeda-X1 dataset classification labels come from [Galaxy Zoo](https://data.galaxyzoo.org/#section-7)
- Andromeda-X1 dataset images come from [Sloan Digital Sky Survey (SDSS)](https://zenodo.org/records/3565489#.Y3vFKS-l0eY)

- The heatmaps are genreated using [GradCAM++](https://arxiv.org/abs/1710.11063). click the link for more information on GradCAM++.

- The Galaxy Zoo team and citizen scientists.

- PyTorch and open-source ML community.
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Limitations 
- Dataset imbalance for rare classes like “Merging” and “Cigar Shaped Smooth”.

- Low resolution may obscure fine morphological features.

- Model underperforms on ambiguous or noisy labels.
