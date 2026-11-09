PRCP-1001 Rice Leaf Disease Detection

Files:
- PRCP_1001_RiceLeaf_Disease_Detection.ipynb: complete single-notebook project.
- PRCP-1001-RiceLeaf.zip: original dataset archive.

How to run:
1. Install Python 3.10+ and Jupyter Notebook/JupyterLab.
2. Install dependencies in a notebook cell:
   %pip install numpy pandas matplotlib seaborn pillow scikit-learn scikit-image tensorflow joblib
3. Keep the dataset ZIP beside the notebook, or edit DATASET_ZIP in section 2.
4. Run all notebook cells from top to bottom.

The dataset archive contains nested ZIP files. The notebook extracts them into riceleaf_data automatically.
The supplied data has 39 Leaf smut, 40 Brown spot, and 40 Bacterial leaf blight images (119 total).
Training MobileNetV2 with ImageNet weights may need internet access the first time. Set USE_PRETRAINED=False if offline.
