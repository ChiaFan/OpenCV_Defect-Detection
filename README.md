# OpenCV_Defect-Detection

Plastic Pellet Contamination Detection

Overview

This project provides a Python-based solution for detecting contamination in plastic pellet test samples. It uses OpenCV for image processing to identify contaminants in test samples created from plastic pellets, based on contour detection, color analysis, and circularity metrics. The program supports multiple platforms (PC, PAC, Colab) and includes features for configuration management, automated contamination marking, and image processing workflows.

Features

* Contamination Detection: Identifies circular contaminants in test sample images using Canny edge detection and contour analysis.
* Platform Support: Configurable for PC, PAC, and Google Colab environments.
* Configuration Management: Reads settings from JSON (cdec_var.json) and INI (config.ini) files for detection thresholds and user-defined exclusions.
* Automated Processing: Supports single-file and multi-file processing modes with real-time monitoring.
* Output Generation: Saves processed images with marked contaminants and logs results.

Prerequisites
* Python: Version 3.6 or higher
* Dependencies:
  opencv-python (cv2)
  numpy
  matplotlib
  pillow (PIL)
* Optional:
  Google Colab setup for cloud-based execution
  PAC platform-specific hardware for embedded systems
