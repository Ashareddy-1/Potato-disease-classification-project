📱🧠 Cross-Platform Potato disease Classification Project

A full-stack project that includes API services, web frontend, mobile app integration, model training, deployment on Google Cloud Platform (GCP), and evaluation using test images from the internet.

📁 Folder Structure

├── api/                         # Backend APIs to serve predictions or other services

├── frontend/                    # Web frontend interface (React, Vue, etc.)

├── gcp/                         # Deployment scripts/configs for Google Cloud Platform

├── mobile-app/                  # Mobile app code (likely Flutter, React Native, or Android)

├── saved_models/               # Trained and serialized machine learning models

├── test_images_from_internet/  # Real-world test images for validation

├── training/                    # Model training scripts and data handling

🚀 Project Components

🧠 api/

RESTful API for serving predictions, health checks, or integrations with the trained model.

🌐 frontend/

Web-based UI to interact with the classification model, visualize results, or upload test images.

☁️ gcp/

Cloud deployment code (e.g., Dockerfiles, Terraform, App Engine configs, or CI/CD pipelines for GCP).

📱 mobile-app/

Mobile app that allows users to interact with the model on the go — either through local inference or via API.

🧳 saved_models/

Serialized versions of trained models (e.g., .pkl, .h5, or TensorFlow SavedModel format).

🧪 test_images_from_internet/

Images collected externally to evaluate model generalization performance.

🏋️ training/

Code and datasets used to train and validate your ML/DL model.

⚙️ Setup Instructions

1. Clone the repository

2. Set up a virtual environment

   python -m venv venv
   
   source venv/bin/activate   # Windows: venv\Scripts\activate
       
4. Install backend dependencies

cd api

5. Run the API
   
python app.py

Frontend or Mobile App

Check frontend/README.md or mobile-app/README.md for platform-specific instructions.

✅ Features

🧠 Custom-trained deep learning models

🌐 Web and mobile app interfaces

☁️ GCP integration for cloud deployment

🧪 Internet-based test images for robustness testing

🔁 Modular code: training, serving, and UI are all separated
