# Flask Translator App

This app allows you to enter a string and pick a language and it will translate to your chosen language. This works with Azure's cognitive language service.

## Set Up

First you need to create the Azure cognitive service on the Azure portal.


Next you need to export some environment variables.

- TRANSLATOR_TEXT_ENDPOINT
- TRANSLATOR_TEXT_SUBSCRIPTION_KEY
- SECRET_KEY


## Run the app

If you are working with a bash terminal.

```bash
cd flask-translator-app
sudo apt install python3-pip python3-venv
export TRANSLATOR_TEXT_ENDPOINT=[YOUR ENDPOINT]
export TRANSLATOR_TEXT_SUBSCRIPTION_KEY=[YOUR KEY]
export SECRET_KEY=any_secret_key
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
python3 app.py
```

