# Chicken-Disease-Classification

This project aims to develop a deep learning system to differentiate between chicken fecal samples that show signs of Coccidiosis and those that appear healthy. The system will analyze and interpret images of fecal samples to accurately identify disease symptoms versus normal characteristics, enhancing early detection and management of poultry diseases.

## Technologies Used
</h3>
<br>
<p align="left">
        <img width="48" height="48" src="https://img.icons8.com/fluency/48/python.png" alt="python"/>
        <img width="48" height="48" src="https://img.icons8.com/fluency/48/jupyter.png" alt="jupyter"/>
        <img width="48" height="48" src="https://img.icons8.com/color/48/amazon-web-services.png" alt="amazon-web-services"/>
        <img width="48" height="48" src="https://img.icons8.com/color/48/artificial-intelligence.png" alt="artificial-intelligence"/>
        <img width="55" height="55" src="https://img.icons8.com/nolan/64/flask.png" alt="flask"/>
        <img width="48" height="48" src="https://img.icons8.com/color/48/git.png" alt="git"/>

</p>
</div>
<br>

`Python`  `Jupyter Notebook` `AWS Elastic Beanstalk`  `CI/CD Pipelines`  `Machine Learning Algorithms`  `Flask`  `Git`

## Demo
![Recorded_screen_1_V1](https://github.com/user-attachments/assets/700b4850-18d9-4841-9bfb-96c5e972a1f4)

## Project Structure
The project follows a modular structure, comprising several stages and pipelines, including:

`stage_01_data_ingestion.py`: This stage handles data ingestion, including functions for downloading, extracting, and preprocessing the dataset to ensure it is ready for the subsequent stages.

`stage_02_prepare_base_model.py`: In this stage, the base model for classification is prepared. It involves loading a pre-trained model, making necessary modifications, and setting it up for training.

`stage_03_training.py`: This stage is responsible for model training. It encompasses functions for data augmentation, model training, and saving the trained model for future use.

`stage_04_evaluation.py`: The evaluation stage focuses on assessing the performance of the trained model. It includes functions for loading the trained model, performing inference on test data, and calculating various evaluation metrics to gauge model effectiveness.

Additionally, the project was deployed using AWS services, leveraging CI/CD pipelines for automated deployments and EC2 instances for scalable model hosting and inference.

