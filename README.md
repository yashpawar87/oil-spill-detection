# Oil Spill Detection using YOLOv8 🌊

This repository contains a deep learning computer vision model trained to identify and localize oil spills imagery using the ultralytics YOLOv8 architecture.

## Dataset 📊
The model is trained on the **Oil Spill Detection - v2** dataset hosted on Roboflow. 
* **Dataset Link:** [Oil Spill Dataset (Version 3)](https://universe.roboflow.com/work-cni0k/oil-ujwyl-fwgbd/dataset/3)
* **Classes:** 1 (`oil spill detection - v2 resize-640`)
* **Format:** YOLOv8

## Getting Started 🚀
The training pipeline is fully configured and designed to be run in a Kaggle Notebook or Google Colab environment.

1. Clone this repository and open the `Oil-Spill-Detection.ipynb` notebook in your preferred Jupyter environment (Kaggle is highly recommended).
2. **Enable GPU:** Ensure you have a GPU accelerator enabled (e.g., T4 x2 or P100).
3. **API Key Setup:** Add your personal Roboflow API key in the dataset download cell. *(Never commit your real API key to GitHub!)*
4. Run the notebook cells sequentially to automatically install YOLOv8, download the dataset, train the model, and evaluate its performance.
5. Use the provided interactive upload widget at the bottom of the notebook to test the model on your own custom images!

## Requirements ⚙️
* `ultralytics`
* `roboflow`
* `ipywidgets` (for interactive image testing)
