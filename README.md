# Project-Code

## Install the requirements
pip install -r requirements.txt

## Run the train_model.py first and save the trained model in a folder called saved_model
python train_model.py

## Run cs_gen_model_train.py second to fine-tune the model for cs generation
python cs_gen_model_train.py

## Then run this code
python stance_chatbot.py