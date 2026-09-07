# Exp-10--Record-IMPLEMENTATION-OF-OPENING-AND-CLOSING

## Name :Sameer Shariff M
## Reg No : 212224220085
## Date : 07-09-2026

# Opening and Closing Operations Using OpenCV

## Aim

To write a Python program using OpenCV to perform morphological Opening and Closing operations on an image.

The program performs the following operations:

- Morphological Opening
- Morphological Closing

## Software Used

- Anaconda – Python 3.7
- Jupyter Notebook / VS Code
- OpenCV (cv2)
- NumPy
- Matplotlib

## Algorithm

### Step 1:

Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:

Create or load an input image containing foreground objects.

### Step 3:

Display the original image.

### Step 4:

Create a structuring element (kernel) of suitable size.

### Step 5: Opening Operation

- Apply the Opening operation using the structuring element.
- Opening consists of Erosion followed by Dilation.
- Remove small foreground noises while preserving the shape of larger objects.
- Display the opened image.

### Step 6: Closing Operation

- Apply the Closing operation using the structuring element.
- Closing consists of Dilation followed by Erosion.
- Fill small holes and gaps within foreground objects.
- Display the closed image.

### Step 7:

Compare the original, opened, and closed images.

## Program

## Developed By

**Name: Sameer Shariff M** 

**Register No: 212224220085** 

## Output

### Original Image

- The input image is displayed.
- The image serves as the source for morphological processing.

<img width="637" height="396" alt="image" src="https://github.com/user-attachments/assets/9a1602e1-766f-4afd-8169-68f98c02ef7f" />


### Opening Operation

- Original image is displayed.
- Opened image is displayed.
- Small foreground noise is removed.
- Thin protrusions and isolated pixels are eliminated.
- Object boundaries become smoother.

<img width="631" height="392" alt="image" src="https://github.com/user-attachments/assets/4eca8bf1-ef80-4456-92b8-1f331ac852f3" />


### Closing Operation

- Original image is displayed.
- Closed image is displayed.
- Small holes and gaps inside objects are filled.
- Broken regions are connected.
- Object boundaries become more continuous.

<img width="651" height="381" alt="image" src="https://github.com/user-attachments/assets/09f48e2d-f5ba-4c3c-88a1-72d762c14dee" />


## Applications

### Opening

- Noise removal in binary images.
- Separation of connected objects.
- Preprocessing for object detection.

### Closing

- Filling small holes in objects.
- Connecting nearby components.
- Enhancing segmented regions.
- 

## Advantages

### Opening

- Removes unwanted foreground noise.
- Preserves major object structures.
- Improves segmentation quality.

  

### Closing

- Restores object continuity.
- Eliminates small background gaps.
- Improves object representation.

## Result

Thus, the morphological operations **Opening** and **Closing** are successfully implemented using OpenCV. 
