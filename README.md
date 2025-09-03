# Detection Summary Engine - Object Detection on Video

This project performs object detection on a video using a YOLOv8 model and summarizes the results in a structured format including per-frame detection, total object counts, and class diversity.

## Objective

- Run object detection on every 5th frame of a video.
- Generate a JSON file with:
   - Detected class labels
   - Bounding box coordinates
   - Confidence scores
- Count total number of objects per class.
- Identify the frame with **maximum class diversity**.
- Generate a **bar chart** visualizing object frequency.
- Save **annotated frames** to output directory. 
