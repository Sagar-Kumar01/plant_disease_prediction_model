
# Plant Disease Prediction

A machine learning project to detect plant diseases using image classification.

---

## Key Features

- **Disease Detection**: Identifies plant diseases from images of leaves.
- **Frontend**: A user-friendly interface for easy interaction.

---

## Dataset

The project uses the [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset). It contains images of healthy and diseased leaves for multiple plant species.

---

## Installation

### Clone the Repository
```bash
git clone https://github.com/Sagar-Kumar01/plant_disease_prediction_model.git
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

### Launch the Streamlit App
Start the Streamlit app with:
```bash
streamlit run streamlit_app/app.py
```

Once started, open your browser and navigate to the provided URL (e.g., `http://localhost:8501`).


## Demo

### Streamlit App
![Streamlit Demo](docs/demo.gif)

---

## Performance Metrics

- **Accuracy**: 92%
- **Confusion Matrix**:

  ![Confusion Matrix](docs/confusion_matrix.png)

## Future Enhancements

- Add support for more plant species.
- Implement explainable AI techniques to highlight regions causing predictions.
- Improve model performance with advanced architectures.

---

## Acknowledgments

Thanks to [PlantVillage](https://www.plantvillage.psu.edu/) for the dataset and the open-source community for tools and libraries.

---

Feel free to fork the repository, contribute, or report issues!
