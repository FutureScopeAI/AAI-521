
# AAI-521 Final Project Proposal

## Team Information
- **Team Number:** 2
- **Team Members:**
  - Manikanta Katuri
  - Troy Crawford
- **Team Leader/Representative:** Manikanta Katuri
- **Team GitHub Link:** [AAI-521 GitHub Repository](https://github.com/FutureScopeAI/AAI-521)
- **Cloud Services:** (If applicable, provide the link)

## Project Description
- **Project Title:** Car Object Detection
- **Short Description/Project Objectives:** 
  - Implement a real-time car object detection system using the YOLO (You Only Look Once) algorithm. Fast YOLO processes 155 frames per second, achieving higher mean Average Precision (mAP) compared to other real-time detectors.

## Project Dataset
- **Selected Dataset:** [Car Object Detection Dataset](https://www.kaggle.com/datasets/sshikamaru/car-object-detection)
- **Description of Selected Dataset:**
  - **Data Source:** Kaggle
  - **Number of Images:** (Specify the number)
  - **Dimension of Images:** (Specify the dimensions)
  - **Size of Dataset:** (Specify the size)

## Description and Requirements
- **Task Importance:** Achieve real-time car detection for applications like traffic monitoring and autonomous vehicles.
- **Data Characteristics:**
  - Not specified: type of camera, cropping, or editing status of photos.
  - No detailed information provided about raw or pre-processed state.
- **Usage History:** Likely used for papers, competitions, and applications but needs further research for specifics.
- **Feature Extraction Plan:** Leverage YOLO to identify cars and bounding boxes in images.
- **Data Quality Issues:** Possible presence of bad or cropped images. Solutions may involve augmentation or filtering.

## Team Responsibilities
- **Member 1 (Troy Crawford):**
  - Data processing and cleaning.
  - Conclusion.
- **Member 2 (Manikanta Katuri):**
  - Technical paper and coding.

## About Dataset
- **Context:**
  - YOLO ("You Only Look Once") is a popular algorithm because it achieves high accuracy while also being able to run in real-time, almost clocking 45 frames per second. A smaller version of the network, Fast YOLO, processes an astounding 155 frames per second while still achieving double the mAP of other real-time detectors. This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions. After non-max suppression, it then outputs recognized objects together with the bounding boxes.
- **Content:**
  - The dataset contains media of cars in all views, and your job is to create an algorithm to detect them!