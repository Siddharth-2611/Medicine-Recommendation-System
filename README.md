# Medicine Recommendation System

A web-based application that recommends medicines, diets, and workouts based on user symptoms. The system leverages machine learning to predict diseases and suggest appropriate treatments, precautions, and lifestyle modifications.

## Features
- Disease prediction based on user-input symptoms
- Medicine, diet, and workout recommendations
- Precautionary advice for predicted diseases
- User-friendly web interface
- Blog, About, Contact, and Developer information pages

## Project Structure
```
main.py                        # Main application file (Flask app)
Medicine Recommendation System.ipynb  # Jupyter notebook for data analysis/modeling
requirements.txt               # Python dependencies
svc.pkl                        # Trained ML model (pickle file)
vercel.json                    # Deployment configuration

datasets/                      # Data files for symptoms, medications, etc.
models/                        # (Optional) Model-related files
static/                        # Static assets (images, CSS, JS)
templates/                     # HTML templates for web pages
```

## Setup Instructions
1. **Clone the repository**
2. **Install dependencies**
   ```
   pip install -r requirements.txt
   ```
3. **Run the application**
   ```
   python main.py
   ```
4. **Access the app**
   Open your browser and go to `http://localhost:5000`

## Data Sources
- `datasets/` contains CSV files for symptoms, medications, diets, precautions, and more.

## Model
- The ML model (`svc.pkl`) is trained to predict diseases based on symptoms using the data in `datasets/Training.csv`.


## Screenshots
### Home Page
![Home Page](static/Homepage.png)

### Additional Screenshots
<!-- Add more screenshots as needed -->

## Video Demo
Watch the video demonstration of the working application:

![Video Demo](static/video_demo.gif)
<!-- Or embed a YouTube link if available -->
<!-- [Watch on YouTube](https://youtu.be/your-demo-link) -->

## License
This project is for educational purposes.

---
**Developed by:** [Your Name]
