# Helmet_Safety_Finetuning

## Overview
This repository contains a project focused on fine-tuning a helmet safety detection model. The goal is to enhance the model's accuracy in identifying whether individuals are wearing helmets in various scenarios.

## Repository Structure
- **model/**: Contains the pre-trained and fine-tuned models.
- **source/**: Includes the source code for data preprocessing, model training, and evaluation.
- **.github/workflows/**: Configuration files for GitHub Actions workflows.
- **.sonarlint/**: Configuration for code quality checks.
- **Helmet_Safety_Finetuning.ipynb**: Jupyter notebook for exploring and running the fine-tuning process.
- **requirement.txt**: Lists the dependencies required for the project.
- **sonar-project.properties**: Configuration for SonarQube analysis.

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Michelia235/Helmet_Safety_Finetuning.git

2. Navigate to the project directory:
   ```sh
   cd Helmet_Safety_Finetuning
   ```
3. Install the dependencies:
   ```sh
   pip install -r requirement.txt
   ```

### Usage
#### Running the Jupyter Notebook
Open the `Helmet_Safety_Finetuning.ipynb` notebook in Jupyter and follow the instructions to fine-tune and evaluate the helmet safety detection model.

#### Running the Streamlit App
1. Install Streamlit if you haven't already:
   ```sh
   pip install streamlit
   ```
2. Run the Streamlit app:
   ```sh
   streamlit run source/streamlit_app.py
   ```
3. Open your web browser and navigate to `http://localhost:8501` to use the app.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
Special thanks to the contributors and the open-source community for their valuable resources and tools.
```
