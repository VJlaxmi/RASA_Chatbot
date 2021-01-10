# RASA_Chatbot

#### Install Rasa

Install Rasa on your machine. Here is a great [installation guide](https://rasa.com/docs/rasa/user-guide/installation/).

#### Train NLU model

Then go to the directory of your application (cloned on the previous step) and make some changes in the model.
Please refer to the [Rasa documentaion](https://rasa.com/docs/rasa/user-guide/rasa-tutorial/) to learn how to build and evaluate NLU model.

Also note that NLU server doesn't run any actions - it only runs your NLU model. Thus you can use only rasa train nlu command.

Evaluate changes
To evaluate your changes on your local machine just run NLU server locally and make some HTTP requests.
