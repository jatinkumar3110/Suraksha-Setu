Suraksha Setu: AI-IoT Platform for Disaster Prediction & Response
This repository contains the source code, notebooks, and resources for the Suraksha Setu project, an AI-powered platform for disaster management.

📂 Repository Structure
The project is organized into a modular structure to separate concerns and improve maintainability.

/data: Contains raw and processed datasets.

/docs: Includes the original research paper and other documentation.

/models: Stores serialized, trained machine learning models.

/notebooks: Jupyter notebooks for experimentation and analysis.

1_Data_Exploration_and_Preprocessing.ipynb: Loading, cleaning, and visualizing data.

2_Model_Training_and_Evaluation.ipynb: Building and evaluating predictive models.

3_Advanced_Simulations_and_Deployment.ipynb: Simulating system features and prototyping an API.

/src: Reusable Python scripts with core project functions.

data_processing.py: Functions for data generation and preprocessing.

model_training.py: Functions for building and training all models.

evaluate.py: Functions for getting predictions and evaluating performance.

utils.py: Helper functions, such as saving and loading models.

requirements.txt: A list of all Python dependencies for the project.

🛠️ How to Run the Project
1. Prerequisites
Python 3.8+

pip and venv

2. Setup
Clone the repository and set up a virtual environment.

git clone [https://github.com/your-username/Suraksha-Setu-Project.git](https://github.com/your-username/Suraksha-Setu-Project.git)
cd Suraksha-Setu-Project
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install Dependencies
pip install -r requirements.txt

4. Run the Notebooks
Open the Jupyter Notebooks located in the /notebooks directory to step through the data processing, model training, and simulation pipeline.

jupyter notebook

⚖️ License
This project is licensed under the MIT License. See the LICENSE file for details.
