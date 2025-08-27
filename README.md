# Career‑Prediction‑System

## Project Title  
**Career-Prediction-System** – A machine learning–powered tool designed to suggest suitable career paths for students and professionals by analyzing their skills, interests, and academic performance. It delivers personalized career recommendations and actionable insights.  

---

## Table of Contents
- [About](#about)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
- [Repository Structure](#repository-structure)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)

---

## About
This project uses machine learning techniques to analyze user data—such as skills, interests, and academic records—and predicts career paths that align with them. The system supports interactive visual analytics and real-time data fetching to enhance guidance.

---

## Features
- **Career Recommendation**: Utilizes a trained ML model to suggest best-fit career options.  
- **Data Analytics & Visualizations**: Generates graphs, heatmaps, and trends for better insights.  
- **Real‑time Data Integration**: Fetches live data like job trends, workshops, certifications, and more.  
- **Modular Design**: Python scripts and Jupyter notebook for model training, analysis, and app logic.  
- **Web App Interface**: Interactive UI through `app.py` facilitating user inputs and output visualization.

---

## Tech Stack
- **Language**: Python  
- **ML Notebook**: `careerPredictionModel.ipynb` for training and experimentation  
- **Web Framework**: Flask (via `app.py`)  
- **Analytics**: Matplotlib/Seaborn or similar (via graph scripts like `generate_graphs.py`, `heatmap_analytics.py`)  
- **Data Fetching Modules**:  
  - `fetch_certifications.py`  
  - `fetch_job_trends.py`  
  - `fetch_suggested_roles.py`  
  - `fetch_workshop.py`  
- **Database Interaction**: `db.py`, utilizing `CBRSdata.db`  
- **Utilities & Updaters**: `update_mldata.py`, `update_graph.py`, `update_table.py`  
- **Model Artifact**: `weights.pkl`  

All required Python packages are listed in `requirements.txt`.

---

## Getting Started

```bash
git clone https://github.com/AdvayKankaria/Career-Prediction-System.git
cd Career-Prediction-System
pip install -r requirements.txt
```

**Run the Web App:**

```bash
python app.py
```

Then open your browser and navigate to `http://localhost:5000`.

For model retraining or analysis, open the Jupyter Notebook:

```bash
jupyter notebook careerPredictionModel.ipynb
```

---

## Repository Structure

```
Career‑Prediction‑System/
├── app.py                      # Flask web app entry point
├── careerPredictionModel.ipynb # Training & evaluation notebook
├── data/                       # Dataset files
├── models/                     # Stored ML models/weights
├── realtime_data/              # Cached real‑time data
├── assets/                     # Static assets (images, CSS, etc.)
├── pythonFunctions/            # Modular helper scripts
├── db.py                       # Database interaction
├── fetch_*.py                  # Live data retrieval scripts
├── generate_graphs.py          # Graph generation logic
├── heatmap_analytics.py        # Heatmap visual analysis
├── update_*.py                 # Scripts for data/model updating
├── checkcolumnvalues.py        # Data validation
├── removetable.py              # Script to drop tables
├── weights.pkl                 # Serialized model weights
├── requirements.txt            # Dependencies
└── How to run the app.docx     # Setup and usage instructions
```

---

## Usage
1. **Launch the app**: Run `app.py`.  
2. **Input data**: Enter or upload user profiles (skills, interests, academic details).  
3. **Get predictions**: The system calculates career suggestions using pre-trained ML.  
4. **View analytics**: Visual outputs like graphs or heatmaps display insights.  
5. **Live data**: The app integrates fresh data (job trends, workshops, certifications).  
6. **Update the model**: Run notebook or update scripts when new data is available.

---

## Contributing
Contributions are welcome!  
1. Fork the repository  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m "Add feature"`)  
4. Push to your branch (`git push origin feature-name`)  
5. Open a Pull Request

---

## License
Add your license info here (e.g., MIT License).


