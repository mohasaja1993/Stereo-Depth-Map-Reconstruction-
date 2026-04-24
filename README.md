# Stereo-Depth-Map-Reconstruction-
Stereo Depth Map Reconstruction

This project implements Stereo Vision to reconstruct a 3D depth map from a pair of rectified 2D images (Left and Right). It utilizes the Disparity-to-Depth relationship to estimate the distance of objects from the camera.
Overview
Stereo Depth Reconstruction is the process of extracting 3D information from digital images. By comparing two images of the same scene taken from slightly different viewpoints, we can compute the Disparity Map, which is then converted into a Depth Map.
Key Features:
• Block Matching (BM): Fast computation for real-time applications.
• Semi-Global Block Matching (SGBM): High-quality depth maps with smoother surfaces.
• Depth Calculation: Real-world distance estimation using focal length and baseline.
Prerequisites
Before running the code, ensure you have the following installed:
• Python 3.x
• OpenCV (opencv-python)
• NumPy
• Matplotlib (for visualization)
