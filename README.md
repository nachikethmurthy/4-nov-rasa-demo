```# RASA Commands
conda create --name rasa-v2 python=3.9
conda activate rasa-v2
pip install rasa
pip install spacy
python -m spacy download en_core_web_md
Goto the required folder
rasa init

rasa train

rasa shell  # start chatting with chatbot```

# Next Time Run

```
conda activate rasa-v2

goto the folder where you have files of (config.yml) present..

rasa shell 
```


# NYTimes URL
- https://developer.nytimes.com/
- Create app, enable APIs and generate API Key, and use it actions.py 


# Slack Integration

- https://rasa.com/docs/rasa/connectors/slack


# Install NGROK
-  https://ngrok.com/download

# After install of ngrok

- `rasa run` ( needs to be executed from RASA project folder with virtual environment)
- On other terminal --> `ngrok http 5005`