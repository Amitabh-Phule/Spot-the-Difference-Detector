# 🕵️ Spot the Difference Detector using OpenCV

This project detects and highlights differences between two images automatically.

## Features
- Load images from Google Drive or upload manually in Colab
- Works locally with command-line arguments
- Auto-alignment using ORB keypoints
- Auto-sensitivity depending on image detail (photo vs art)
- Heatmap visualization and bounding boxes for differences

## Install
```bash
git clone https://github.com/<your-username>/Spot-the-Difference-Detector.git
cd Spot-the-Difference-Detector
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
