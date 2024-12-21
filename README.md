
# Plant Disease Prediction

A machine learning project to detect plant diseases using image classification with a Streamlit frontend.

---

## Key Features

- **Disease Detection**: Identifies plant diseases from images of leaves.
- **Streamlit App**: A user-friendly interface for easy interaction.

---

## Dataset

The project uses the [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset). It contains images of healthy and diseased leaves for multiple plant species.

---

## Installation

### Clone the Repository
```bash
git clone https://github.com/username/plant-disease-prediction.git
```

### Navigate to the Directory
```bash
cd plant-disease-prediction
```

### Install Dependencies

Using pip:
```bash
pip install -r requirements.txt
```

Using Conda:
```bash
conda env create -f environment.yml
conda activate plant-disease
```

---

## Running the Project

### Train the Model
Run the following command to train the machine learning model:
```bash
python src/model_training.py
```

### Launch the Streamlit App
Start the Streamlit app with:
```bash
streamlit run streamlit_app/app.py
```

Once started, open your browser and navigate to the provided URL (e.g., `http://localhost:8501`).

---

## Project Structure
```
project_name/
├── README.md
├── requirements.txt
├── src/
│   ├── model_training.py
│   ├── preprocessing.py
│   └── inference.py
├── streamlit_app/
│   ├── app.py
│   └── assets/
│       └── example_image.jpg
├── data/
│   ├── raw/
│   ├── processed/
│   └── sample_data.csv
├── models/
│   └── trained_model.h5
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   └── model_training.ipynb
└── docs/
    └── architecture_diagram.png
```

---

## Demo

### Streamlit App
![Streamlit Demo](docs/demo.gif)

---

## Performance Metrics

- **Accuracy**: 92%
- **Confusion Matrix**:

  ![Confusion Matrix](docs/confusion_matrix.png)

---

## Deployment

### Streamlit Cloud
1. Create an account on [Streamlit Cloud](https://streamlit.io/cloud).
2. Upload your repository.
3. Add environment dependencies in the platform's settings.

### Heroku
1. Install Heroku CLI.
2. Create a `Procfile` with:
   ```plaintext
   web: streamlit run streamlit_app/app.py
   ```
3. Push to Heroku:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push heroku main
   ```

---

## Future Enhancements

- Add support for more plant species.
- Implement explainable AI techniques to highlight regions causing predictions.
- Improve model performance with advanced architectures.

---

## Acknowledgments

Thanks to [PlantVillage](https://www.plantvillage.psu.edu/) for the dataset and the open-source community for tools and libraries.

---

Feel free to fork the repository, contribute, or report issues!
