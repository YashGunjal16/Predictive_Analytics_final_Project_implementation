🧠 Predictive Analytics Final Project – MoViNet-Based Video Classification
This project is a part of our Predictive Analytics coursework, focused on implementing MoViNets (Mobile Video Networks) for efficient video-based activity recognition. We leverage deep learning for understanding human actions from videos, applying pretrained MoViNet models to classify video samples and derive insights for physical activity analysis.

📁 Repository Contents
Trained_movinets_notebook_PA_Project.ipynb – Main notebook containing the complete pipeline:

Video data preprocessing

MoViNet model loading (pretrained)

Fine-tuning for classification

Evaluation and visualization

📽️ Project Objective
To build an efficient and lightweight video classification model using MoViNets to recognize human actions from video clips. MoViNets are optimized for mobile and edge deployment, making them suitable for real-time activity recognition tasks.

🔧 Tech Stack
Python

TensorFlow (with TF Hub MoViNet models)

OpenCV (for video frame extraction)

NumPy, Matplotlib, Seaborn

Jupyter Notebook

🚀 Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/YashGunjal16/Predictive_Analytics_final_Project_implementation.git
cd Predictive_Analytics_final_Project_implementation
Install the required libraries
(You can create a virtual environment if needed)

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook

bash
Copy
Edit
jupyter notebook Trained_movinets_notebook_PA_Project.ipynb
Dataset

Make sure your video dataset is available and paths are correctly set in the notebook.

Format expected: short video clips categorized into labeled folders.

📊 Results Summary
Model Used: MoViNet-A0 (Pretrained on Kinetics-600)

Achieved high accuracy on a small set of human action videos.

Lightweight inference suitable for edge/real-time use.

📌 Future Scope
Real-time prediction from webcam streams

Fine-tune on larger datasets (e.g., UCF101, HMDB51)

Streamlit dashboard for live inference

Integration with pose estimation frameworks

👨‍💻 Contributors
Yash Gunjal

📄 License
This repository is shared under the MIT License. Feel free to use, modify, and distribute with attribution.
