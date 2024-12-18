# Identifying the Parameters of Video of Traffic Surveillance -

This project focuses on optimizing object detection for traffic surveillance videos using the YOLOv8 model, with post-processing via TensorRT for real-time deployment on edge devices. It incorporates detailed analysis of detection results through Intersection over Union (IoU)-based metrics to identify differences between ground truth (GT) and TensorRT (TRT) model predictions.

## Features
	1. YOLOv8 Quantization: The YOLOv8 model has been quantized to enhance performance while retaining detection accuracy.
	2. TensorRT Optimization: TensorRT boosts inference by compiling the model for edge deployment.
	3. Detection Analysis: IoU-based comparison of GT with TRT and PT outputs for detection validation.
	4. Results Analysis: CSV generation to track:
      • Detection mismatches
      • Overlapping and non-overlapping bounding boxes
      • Additional information on class labels and bounding box coordinates
	5. CSV Output: Comprehensive data saved for further insights using IoU metrics.

 ## File Descriptions
  ### 1. model_comparison.py
    Compares the GT detections with TRT and PT model outputs and exports the comparison results into a CSV file.
  ### 2. result_analysis.py
  ### 3. result_analysis_pt.py
  ### 4. detection_analysis.ipynb
  ### 5. result_analysis.py
  ### 6. result_analysis_pt.py
  ### 7. requirements.txt
    Refer to requirements.txt for all dependencies.
