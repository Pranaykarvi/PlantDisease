# PlantDisease
Overview
This project is a machine learning web application utilizing a Convolutional Neural Network (CNN) to make predictions based on user input data. The project includes a Jupyter notebook for training and evaluating the CNN model and a Streamlit-based web application (App.py) for interaction with the model.

Project Structure
Train_Dataset.ipynb: A Jupyter notebook focused on:

Data preprocessing and exploration
Model training using a CNN for effective feature extraction and classification
Evaluation of the model's performance
Saving the trained CNN model for use in the web app
App.py: A Streamlit web application that enables:

User input of data for predictions
Integration with the CNN model for generating and displaying results

Setup Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/your-repo.git
cd your-repo
Install Requirements Make sure Python 3.x is installed, then install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Application Start the Streamlit app:

bash
Copy code
streamlit run App.py
Access the Web App Open the provided local URL (e.g., http://localhost:8501/) to interact with the web application.

Model Training
The CNN model is trained on a prepared dataset in Train_Dataset.ipynb, which includes:

Data preprocessing and augmentation (if applicable)
Training and validation phases to assess accuracy and loss
Saving the trained CNN model for predictions in the web application
Screenshots
Home Page

Prediction Result

Contributing
We welcome contributions! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.
