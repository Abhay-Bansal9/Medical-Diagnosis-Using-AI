# Disease Prediction Using AI

This project is a web-based application that uses machine learning models to predict various diseases, including diabetes, heart disease, Parkinson's disease, lung cancer, and hypo-thyroid. The application is built using **Streamlit** and provides an intuitive interface for users to input their health data and receive predictions.

## Features

- **Disease Prediction**: Supports predictions for:
  - Diabetes
  - Heart Disease
  - Parkinson's Disease
  - Lung Cancer
  - Hypo-Thyroid
- **Interactive UI**: Built with Streamlit for a user-friendly experience.
- **Background Customization**: Includes a custom background image for enhanced aesthetics.
- **Pre-trained Models**: Uses pre-trained machine learning models for predictions.

## Project Structure

```
Medical diagnosis using AI/
├── app.py                     # Main application file
├── Heart_Disease_Prediction.ipynb
├── Lung_Cancer.ipynb
├── Parkinson's_Disease_Detection.ipynb
├── Thyroid.ipynb
├── Datasets/                  # Contains datasets used for training
│   ├── diabetes_data.csv
│   ├── heart_disease_data.csv
│   ├── hypothyroid.csv
│   ├── parkinson_data.csv
│   ├── prepocessed_hypothyroid.csv
│   ├── prepocessed_lungs_data.csv
│   └── survey lung cancer.csv
├── Models/                    # Contains pre-trained models
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── lungs_disease_model.sav
│   ├── parkinsons_model.sav
│   └── thyroid_model.sav
└── .ipynb_checkpoints/        # Auto-generated Jupyter Notebook checkpoints
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   cd Medical diagnosis using AI
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open the application in your browser (usually at `http://localhost:8501`).
2. Select a disease from the dropdown menu.
3. Enter the required health parameters.
4. Click the prediction button to see the result.

## Dependencies

- Python 3.7+
- Streamlit
- scikit-learn
- pandas
- numpy
- streamlit-option-menu

## Datasets

The datasets used for training the models are located in the `Datasets/` directory. These include data for diabetes, heart disease, Parkinson's disease, lung cancer, and hypothyroid.

## Models

The pre-trained models are stored in the `Models/` directory. These models were trained using the respective datasets and saved in `.sav` format.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The datasets used in this project are sourced from publicly available repositories.
- Special thanks to the Streamlit community for their support and resources.
