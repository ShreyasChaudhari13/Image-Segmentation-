# Image-Segmentation-
Image processing on a image of a 'Room' including filtering, enhancement, segmentation and finding the dimensions of that room.

In this project, I have implemented an instance segmentation model using the MaskFormer architecture for image analysis. Here is a summary of the key steps and achievements in your project:

**Techniques:**
- **Instance Segmentation:** Utilized the MaskFormer model for precise segmentation of objects within an image.
- **Contour Analysis:** Employed OpenCV to find contours of segmented regions (floor, wall, window) for further analysis.

**Skills:**
- **Computer Vision:** Applied computer vision techniques to analyze and extract information from images.
- **Model Implementation:** Implemented pre-trained models for instance segmentation using the Transformers library.
- **Image Processing:** Utilized PIL and OpenCV for loading images, preprocessing, and contour analysis.

**Tools:**
- **Transformers Library:** Installed and used for accessing pre-trained models, specifically the MaskFormer architecture.
- **OpenCV:** Applied for image processing, contour analysis, and visualization of segmentation results.
- **PIL (Python Imaging Library):** Used for loading and manipulating images.

**Language:**
- **Python:** The entire project is implemented in Python, leveraging its extensive libraries for image processing, machine learning, and data analysis.

**Libraries:**
- **Transformers:** Used for accessing pre-trained models and processing images.
- **torch (PyTorch):** Utilized for deep learning operations and working with the MaskFormer model.
- **numpy:** Used for array manipulation and numerical operations.
- **cv2 (OpenCV):** Applied for image processing, contour analysis, and visualization.

**Additional Libraries:**
- **PIL (Python Imaging Library):** Used for image loading and basic manipulation.
- **requests:** Utilized for loading images from a URL.


1. **Setup and Installation:**
   - Installed the Transformers library, which provides pre-trained models for natural language processing and computer vision tasks.
   - Utilized the MaskFormer model, specifically the "facebook/maskformer-swin-small-coco" checkpoint, designed for instance segmentation.

2. **Image Processing:**
   - Loaded an image from a specified URL using the PIL library.
   - Used the MaskFormerImageProcessor to preprocess the image for input to the MaskFormerForInstanceSegmentation model.

3. **Instance Segmentation:**
   - Created an instance of the MaskFormerForInstanceSegmentation model and passed the preprocessed image through it.
   - Extracted the panoptic segmentation results and obtained information about different segments in the image.

4. **Segmentation Masks:**
   - Identified specific segments related to different objects in the image, such as floor, roof, window, and wall, based on label IDs.

5. **Image Manipulation:**
   - Generated binary masks for each segment based on the panoptic segmentation results.
   - Applied these masks to the original image to segment and highlight specific regions of interest, such as the wall.

6. **Contour Analysis:**
   - Utilized OpenCV to find contours of specific segments (floor, wall) and extract information about the contours, such as bounding rectangles.

7. **Measurements and Scaling:**
   - Calculated the width and height of the room based on the contours of the floor and wall.
   - Determined the width of a window in the image.
   - Established a scaling factor to convert pixel measurements to centimeters.

8. **Room Dimensions:**
   - Calculated the approximate width and height of the room in both pixels and meters using the scaling factor.

9. **Visualization:**
   - Displayed the contours of the floor, wall, and window separately using OpenCV.

1. **Instance Segmentation with MaskFormer:**
   - Implemented MaskFormer model for instance segmentation, extracting key segments (floor, wall, window) in an image.
   - Used the Facebook "maskformer-swin-small-coco" checkpoint for efficient processing.

2. **Room Analysis and Dimension Estimation:**
   - Leveraged OpenCV for contour analysis, determining the width and height of a room from segmented floor and wall.
   - Calculated scaling factor to convert pixel measurements to centimeters, providing approximate room dimensions.

3. **Technical Proficiency:**
   - Applied computer vision techniques to real-world scenarios, showcasing expertise in model implementation and image analysis.
   - Demonstrated skills in using popular libraries such as Transformers and OpenCV for efficient processing and measurement calculations.


**Overall, the project demonstrates proficiency in Python programming, deep learning with PyTorch, computer vision using OpenCV, and leveraging state-of-the-art models with the Transformers library for image segmentation tasks.**


