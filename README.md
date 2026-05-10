# IPCV-Experiments

EXP-01:-To study and implement basic image processing operations using OpenCV and NumPy, including image reading, color space conversion, channel splitting, image arithmetic operations, and geometric transformations.The experiment successfully demonstrates basic image manipulation techniques using OpenCV, helping to understand how digital images are processed and analyzed in computer vision systems.

EXP 02:-To study and implement basic image transformation techniques for image enhancement using Python and OpenCV.This experiment demonstrates how different image transformation techniques enhance image quality and reveal hidden details. These methods are fundamental in image processing applications such as medical imaging, computer vision, and pattern recognition.

EXP 03:-This project demonstrates Image Enhancement using Histogram Equalization, implemented as part of IPCV (Image Processing and Computer Vision) Experiment No. 03. The objective is to improve image contrast by redistributing pixel intensity values using both manual implementation and OpenCV’s built-in method.Histogram Equalization significantly improves image contrast by spreading pixel intensities across the available range. The manual implementation helps in understanding the internal working of the algorithm, while OpenCV provides a fast and optimized built-in solution. Both approaches yield comparable enhancement results.

EXP- 04:-IPCV Experiment 04 — Noise Models and Image Restoration using Filters
This project demonstrates the addition of three types of noise — Gaussian, Salt & Pepper, and Uniform — to a grayscale image, simulating real-world image degradation scenarios. It then applies restoration filters including the Arithmetic Mean Filter, Midpoint Filter, and Alpha-Trimmed Mean Filter to recover image quality from each noise type. Each filter is implemented from scratch using NumPy with sliding-window operations, without relying on built-in smoothing functions. Results are visualized side-by-side using Matplotlib to compare the effectiveness of each filter against its corresponding noise model.

IPCV Experiment 05 — Sobel, Canny & LoG Edge Detection
This experiment demonstrates classical edge detection techniques in image processing using OpenCV and Python. It applies the Sobel Filter to compute horizontal/vertical gradients and their magnitude, the Canny Edge Detector (with Gaussian pre-smoothing and dual thresholding) for clean, thin edges, and the Laplacian of Gaussian (LoG) filter for second-order edge detection. Gradient magnitude and direction maps are also visualized using HSV colormaps to analyze edge orientation across all three methods.

IPCV Experiment 06 — CNN-based Image Classification on MNIST
This experiment builds and compares three CNN architectures (Model 1: 3×Conv2D + MaxPooling, Model 2: 3×Conv2D + AvgPooling with wider dense layers, Model 3: LeNet-5 inspired) trained on the MNIST handwritten digit dataset using TensorFlow/Keras. All three models achieve over 98% test accuracy after 10 epochs, with training/validation accuracy curves plotted for comparison and per-image predictions visualized with color-coded correct/incorrect labels.

IPCV Experiment 08 — Indian License Plate Recognition using CNN
This experiment implements an end-to-end Indian License Plate Recognition (ANPR) system using OpenCV and a CNN trained on 36 alphanumeric character classes (0–9, A–Z). A Haar Cascade classifier first detects and extracts the license plate region from a car image, followed by contour-based character segmentation with binary thresholding; a 4-layer CNN (757K params, trained with a custom F1-score metric) then classifies each character, achieving a val F1-score > 0.99 in just 22 epochs before early stopping. The final output overlays the recognized plate text (e.g., DL8CAF5030) directly onto the original image.

IPCV Experiment 09 — Brain Tumor Detection using VGG-16 (Transfer Learning)
This experiment builds a binary brain tumor classifier (Tumor: YES/NO) on Brain MRI scans using Transfer Learning with VGG-16 pretrained weights, with only the top dense layer trained (25K trainable out of 14.7M total params). MRI images are preprocessed via contour-based brain cropping (Gaussian blur + thresholding + extreme-point detection) and resized to 224×224, followed by data augmentation (rotation, flips, brightness shifts) to handle the small dataset (193 train / 50 val / 10 test); the model is trained with early stopping and achieves ~76% val accuracy and ~70% test accuracy. Results are evaluated using confusion matrices and misclassified image visualization.


