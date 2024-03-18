# kidney_disease_classification

## Workflows 
1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. app.py



'''
# steps to follow to create  an enviornment 
'''
### STEPS:
Clone the repository
'''bash
https://github.com/Bhalchandra-patil03/kidney_disease_classification.git
'''


'''
### STEP 01- Create a conda environment after opening the repository
'''
conda create -n cnncls python=3.8 -y
'''


'''
conda activate cnncls
'''



'''
### STEP 02- install the requirements
'''
pip install -r requirements.txt
'''

#### cmd 
- mlflow ui

### dagshub 
[dagshub](https://dagshub.com/)


MLFLOW_TRACKING_URI=https://dagshub.com/bp154126/kidney_disease_classification.mlflow \
MLFLOW_TRACKING_USERNAME=bp154126 \
MLFLOW_TRACKING_PASSWORD=bf3efb4494a03cdcd792b4ad9b641278b70423b7 \
python script.py

Run this to export as env variables :

'''bash

export MLFLOW_TRACKING_URI=https://dagshub.com/bp154126/kidney_disease_classification.mlflow \

export MLFLOW_TRACKING_USERNAME=bp154126 \

export MLFLOW_TRACKING_PASSWORD=bf3efb4494a03cdcd792b4ad9b641278b70423b7 \
'''


