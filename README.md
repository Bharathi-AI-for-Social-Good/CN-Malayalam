## Install the requirements
pip install -r requirements.txt

# Project-Code
The full code can be accessed in the ReZG_Train+Gen_Full_Code.ipynb or rezg_train+gen_full_code.py (.py version of the .ipynb). The below codes were used during research purpose only.
Colab Pro version was used for training (A100 GPU)

## Run the train_model.py first and save the trained model in a folder called saved_model
python train_model.py

## Run cs_gen_model_train.py second to fine-tune the model for cs generation
python cs_gen_model_train.py

## Then run this code
python stance_chatbot.py
