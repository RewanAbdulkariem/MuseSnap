# 🖼️ Artifact Recognition App

A Streamlit web application that uses a YOLOv8 classification model to recognize and describe artifacts from images. Users can scan artifacts using images or a camera, test their recognition skills through a game, or take a fun quiz!

### About the Project
This project was developed as part of AIO competition and is a unique, one-of-a-kind idea.
The main idea and artifact descriptions were created by Farida, a creative and talented team member.

I was the mentor and developer, responsible for turning the concept into a working application. I handled:

- Training and integrating the YOLOv8 classification model.
- Designing the game modes and user experience.
- Implementing the entire Streamlit web app.
- Structuring the data and building the interactive features like scanning, gaming, and quiz modes.


### Features

- 🔍 Artifact Scanner: Upload an image or use your camera to identify the artifact and view its description.
- 🎮 Artifact Hunting Game: Get a random artifact target and try to capture an image of it with your camera.
- 🧠 Quiz Mode: Test your knowledge by matching artifact descriptions with the correct classes.
- 📸 Camera Integration: Use your device’s camera to scan real-time images.
- 📤 Download & Share: Save your prediction results or share them on social media.
- 💡 YOLOv8 Model: Uses Ultralytics YOLOv8 classification for accurate artifact predictions.

### How to Run
1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. Run the app
```bash
streamlit run App.py
```

### Model & Data
Model: yolov8n-cls.pt — A YOLOv8 classification model trained to recognize various artifacts.

Descriptions: Data.json contains human-readable descriptions for each class label predicted by the model.

### Developed by
Rawan Abdul Kareem – Technical Mentor & Sole Developer
Led the full technical implementation: designed game modes, trained and integrated the YOLOv8 model, built the Streamlit app, and developed all features.

Farida Eladham – Idea Creator & Content Writer
Came up with the unique project idea and crafted the artifact descriptions and quiz content.
