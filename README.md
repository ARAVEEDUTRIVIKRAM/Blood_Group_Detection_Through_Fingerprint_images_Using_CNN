🩸 Blood Group Detection Using Fingerprint Images with CNN

   This project explores a non-invasive approach to detect human blood groups from fingerprint images using Convolutional Neural Networks (CNNs). By leveraging deep learning, the model identifies the correlation 
   between fingerprint ridge patterns and blood group types, offering a faster, safer, and cost-effective alternative to traditional testing.


📌 Overview

  🔹Non-Invasive: No pricking or blood samples needed – predictions are based solely on fingerprint patterns.
  🔹Deep Learning Approach: CNN architecture extracts key features and patterns in fingerprints.
  🔹Efficient Preprocessing: Uses Gabor filtering and image enhancement to highlight ridge structures for optimal model input.
  🔹Real-World Applications: Potential applications in emergency medical diagnostics, rural healthcare, and mobile app-based blood group detection.


🏗️ Project Structure

Blood_Group_Detection_Through_Fingerprint_images_using_CNN
│
├── Project_Code
│   └── Code_For_Blood_Group_Detection_Using_CNN.ipynb     # Jupyter Notebook
│
├── Training_DataSet
│   ├── A-
│   ├── A+
│   ├── AB-
│   ├── AB+
│   ├── B-
│   ├── B+
│   ├── O-
│   └── O+
│
├── Testing_DataSet
│   ├── A-
│   ├── A+
│   ├── AB-
│   ├── AB+
│   ├── B-
│   ├── B+
│   ├── O-
│   └── O+
│
├── Results
│   ├── accuracy_plot.png
│   ├── classification_report.png
│   └── confusion_matrix.png
│
└── README.md


📂 Dataset

   🔹Description: High-resolution fingerprint images, labeled with respective blood groups (A+, A-, B+, B-, AB+, AB-, O+, O-).
   🔹Preprocessing Steps:
       1.Resize images to 128×128 pixels.
       2.Apply Gabor filtering to highlight ridge patterns.
       3.Convert to grayscale for improved CNN input.


⚙️ How It Works

   ✅ Image Acquisition: Fingerprint images captured via scanner or smartphone.
   ✅ Preprocessing: Resize images and apply Gabor filters for texture enhancement.
   ✅ Feature Extraction & Classification: CNN layers extract and classify patterns linked to blood group types.
   ✅ Model Architecture:
                         Conv2D → ReLU → MaxPooling2D
                         Fully Connected Layers → Dropout → Softmax
                         Loss Function: Categorical Cross-Entropy
                         Optimizer: Adam
                         Epochs: 100


💻 Installation and Usage

   🔹Prerequisites:
                    1.Python 3.7 or higher
                    2.Google Colab / Jupyter Notebook
                    3.Libraries: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Seaborn
  🔹Install Required Libraries: pip install tensorflow keras opencv-python numpy matplotlib seaborn
  🔹Running the Project
       1️⃣ Clone the Repository:
                        git clone https://github.com/ARAVEEDUTRIVIKRAM/Blood_Group_Detection_Through_Fingerprint_images_Using_CNN.git
                        cd BloodGroupDetectionCNN
       2️⃣ Open the Jupyter Notebook:
                         jupyter notebook Project_Code/Code_For_Blood_Group_Detection_Using_CNN.ipynb
       3️⃣ Run All Cells:
                         This includes data preprocessing, model training, and evaluation.

📈 Results

  🔹Accuracy: Achieved ~85% classification accuracy on the test data.
  🔹Evaluation Metrics:
                        Precision: 87%
                        Recall: 82%
                        F1-Score: 85%

📊 Visualization

  🔹Loss and Accuracy Graphs – Show convergence and model training stability.
  🔹Confusion Matrix – Visualizes classification performance across blood groups.

🌟 Applications

  🔹Emergency Medical Diagnostics
  🔹Blood Banks & Rural Healthcare
  🔹Mobile App Integration

🚀 Future Scope

  🔹 Expand dataset with more diverse samples for better generalization.
  🔹 Mobile application deployment for real-time predictions.
  🔹 Enhance model architecture with advanced techniques like EfficientNet or transfer learning.
  🔹 Real-time hospital/forensic use to support decision-making in emergencies.

📚 References

  🔹"EfficientNet-Based Blood Group Prediction Using Fingerprint Images"
  🔹"The Association Between Fingerprint Patterns and Blood Groups in the Omani Population"
  🔹"Blood Group Detection Using Deep Convolutional Neural Networks"

👥 Contributors

   1.ARAVEEDU TRIVIKRAM
   2.IRAGAMAREDDY ANITHA
   3.DASARI SNEHITHA
   4.KALLURU NAGA MANJULA

   Project - Guide: Sri Y. Venkateswara Raju, M.Tech (Ph.D)

📧 Contact

For queries, collaborations, or suggestions: 📧araveedutrivikram@gmail.com


