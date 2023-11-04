# RASA Commands
conda create --name rasa-chatbot python=3.9
conda activate rasa-chatbot
pip install rasa
pip install spacy
python -m spacy download en_core_web_md
Goto the required folder
rasa init


rasa train

rasa shell  # start chatting with chatbot