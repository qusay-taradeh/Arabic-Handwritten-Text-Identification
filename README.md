# Arabic Handwritten Text Identification  
Arabic Handwritten Text Identification Using Local Feature Extraction Techniques

## Summary  
Implementation of a system that identifies Arabic handwritten text by applying local feature extraction techniques. The project compares the SIFT algorithm with SURF, evaluating each method's performance on the AHAWP dataset. The evaluation focuses on accuracy, computational efficiency, robustness to variations (scale, rotation, illumination, and noise), and the number of detected key points.

## Specifications  
This application should be able to perform the following tasks:
1. **Data Preprocessing:**  
   - Load and preprocess handwritten word images from the AHAWP dataset.
2. **Feature Extraction:**  
   - Extract local features using the SIFT algorithm.
   - Extract local features using the SURF algorithm.
3. **Keypoint Matching:**  
   - Match keypoints between images for identification purposes.
4. **Performance Evaluation:**  
   - Compute evaluation metrics:
     - **Accuracy:** Percentage of correctly matched keypoints.
     - **Time Efficiency:** Execution time for feature extraction and matching.
     - **Robustness:** Performance under variations in scale, rotation, illumination, and noise.
     - **Number of Key Points:** Total key points detected by each algorithm.
5. **Result Analysis:**  
   - Compare and report the performance of SIFT and SURF based on the metrics above.
6. **Output:**  
   - Display and document the evaluation results, discussing the trade-offs between accuracy and computational cost.

## Authors
Qusay Taradeh, Karim Marayta
