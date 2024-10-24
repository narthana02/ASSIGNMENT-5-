# ASSIGNMENT-5

Task 1: Motion Estimation and Event Detection in a Video
Objective:
Detect motion and specific events in a video using frame differencing or optical flow to estimate motion and identify events without machine learning.

Task Description:

Load Video:

Load the provided video using OpenCV.
Motion Estimation:

Use frame differencing (Histogram comparision) to detect changes between consecutive frames.
Subtract consecutive frames and threshold the difference to identify regions of motion.
Event Detection:

Detect significant motion events, such as sudden movements or object appearances, based on the intensity of motion detected in specific regions.
Identify and mark frames where events occur based on changes in motion intensity or region activity.
Result:

Visualize motion by highlighting moving regions in each frame.
Display and annotate the frames where events were detected, along with timestamps.
Task 2: Estimating Sentiments of People in a Crowd – Gesture Analysis and Image Categorization
Objective:
Estimate the sentiments of individuals in a crowd using basic gesture analysis techniques, such as detecting facial expressions or hand gestures, without using machine learning models.

Task Description:

Load Image Set:

Load the provided images of people in a crowd.
Preprocessing:

Use traditional face detection techniques (skin-color-based detection) to detect faces in the images.
Detect hand gestures based on skin color thresholding or simple shape analysis (contours).
Gesture Analysis:

Perform facial feature extraction using geometric methods (e.g., detecting the positions of the eyes, mouth, and eyebrows).
Classify basic emotions (happy, sad, neutral) based on facial geometry:
Smiling (upward curvature of the mouth) could indicate happiness.
A frowning face (downward curvature of the mouth, raised eyebrows) could indicate sadness.
Image Categorization:

Categorize the images based on the overall sentiment detected by averaging the identified sentiments of individuals in the crowd (e.g., majority happy, majority sad).
Result:

Output the sentiment of each individual and the overall sentiment of the crowd.
Display the key facial features used for gesture analysis.
Task 3: Gender Identification from Facial Features
Objective:
Identify the gender of individuals based on facial features using traditional image processing and feature extraction techniques without using machine learning models.

Task Description:

Load Dataset:

Load the facial image dataset labeled with gender.
Preprocessing:

Detect faces in the images using a technique like Haar Cascades.
Normalize and crop the facial regions for feature extraction.
Feature Extraction:

Extract facial features using methods like:
Geometric-based feature extraction: Calculate distances between key facial landmarks like the eyes, nose, mouth, and jawline.
Texture-based feature extraction: Use Local Binary Patterns (LBP) or Edge Detection (Sobel/Canny) to extract important texture patterns from the face.
Rule-Based Gender Identification:

Use predefined rules based on facial geometry or texture:
For example, classify gender based on the width of the jawline, distance between eyes, and texture features.
Male faces generally have a broader jawline, while female faces may have a softer texture.
Result:

Output the identified gender for each image.
Display the extracted facial features and explain how these features led to the decision.
