# massive_rasa
Here we wish to use some of the [MASSIVE dataset](https://github.com/alexa/massive) from Amazon used to train and 
evaluate virtual assistants. We use only the data in English, found under `data/en-US.jsonl` and filter it to just a 
small number of intents in the notebook `generate_chatbot_data.ipynb`. The result is essentially the training data
found in `data/nlu.yml`. To run:

## To run

1. clone the repo with `git clone git@github.com:clharris/massive_rasa.git`
2. run `conda env create -p ./env`
3. run `rasa train` to train a model
4. run `rasa interactive` for an interactive session with the chatbot

See more details in the [rasa docs](https://rasa.com/docs/).
