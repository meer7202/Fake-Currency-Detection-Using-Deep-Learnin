# Indian Fake Currency Detection Using Deep Learning

This project implements an automated, AI-driven solution to combat financial fraud by identifying counterfeit Indian banknotes. By leveraging Convolutional Neural Networks (CNNs), the system reduces human error and provides a high-accuracy alternative to traditional manual inspection.


## Project Overview
Counterfeit currency is a global issue that destabilizes economies. This research evaluates four state-of-the-art deep learning architectures to classify currency notes across multiple denominations (₹10, ₹20, ₹50, ₹100, ₹200, ₹500, and ₹2000) as either "Real" or "Fake"


### Key Features

- Multi-Model Evaluation: Compares VGG16, VGG19, MobileNet, and ResNet.

- High Precision: Achieved up to 99.83% training accuracy using MobileNet.

- Diverse Dataset: Includes 377 images captured under various lighting conditions and angles to ensure robustness.

- User-Friendly Interface: Includes a GUI for image input and real-time classification results.


## System Architecture

- The system follows a structured pipeline from raw image input to final classification:

- Dataset Collection: 377 images of Indian Rupee denominations captured via mobile camera.

- Preprocessing: Includes RGB to grayscale conversion, Gaussian blur for noise reduction, and image resizing/normalization.

- Feature Extraction: CNN models analyze textures, security patterns, and bleed lines.

- Classification: A SoftMax layer determines the final label: Real or Fake.


## Performance Comparison (Experimental Analysis)

MobileNet emerged as the top-performing model with a 99.83% training accuracy. Its use of depthwise separable convolutions allows for efficient extraction of security features like watermarks and microprinting, making it ideal for real-time mobile use. ResNet followed closely with 99.22% testing accuracy, demonstrating high stability. While VGG-16 and VGG-19 showed strong results, they were less efficient than these modern, lightweight architectures.

Note: MobileNet is identified as the most suitable model for real-time deployment due to its lightweight architecture and highest accuracy.


## Future Scope

- Expanding Dataset: Including international currencies and more diverse imaging conditions.

- Mobile Integration: Optimizing models for deployment on mobile devices and ATMs.

- Real-time Optimization: Enhancing processing speeds for instant verification.


## Contributors

* Ashmeer Raza 
* Hire Rushikesh 
* Sujaat Ali 
* Man Suryawanshi 
* Prof. Misbah Kauser & Dr. Md Salman Baig (Advisors)

Final Year Engineering Student

Project Domain: Deep Learning & Computer Vision

Tags: #DeepLearning #CNN #CurrencyDetection #Python #MobileNet #ArtificialIntelligence

## Note (Dataset)

The dataset used in this project is approximately 600 MB in size and cannot be hosted directly on GitHub due to file size limitations.

🔗 Dataset Download: https://drive.google.com/drive/folders/16O1ejMrTpbiPPqquqKg6fUjtSHivzar7?usp=drive_link
