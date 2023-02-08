# OpenAI ChatGPT API



Build your own OpenAI application


Now that you’ve found a good prompt and settings, you’re ready to build your pet name generator! We’ve written some code to get you started — follow the instructions below to download the code and run the app.


Setup

If you don’t have Python installed, install it from here. Then download the code by cloning this repository.

    $ git clone https://github.com/openai/openai-quickstart-python.git
    
    
If you prefer not to use git, you can alternatively download the code using this zip file.


Add your API key

Navigate into the project directory and make a copy of the example environment variables file.

    $ cd openai-quickstart-python
    $ cp .env.example .env
    
    
Copy your secret API key and set it as the OPENAI_API_KEY in your newly created .env file. If you haven't created a secret key yet, you can do so below.

Run the app

Run the following commands in the project directory to install the dependencies and run the app. When running the commands, you may need to type python3/pip3 instead of python/pip depending on your setup.

    $ python -m venv venv
    $. venv/bin/activate
    $ pip install -r requirements.txt
    $ flask run
    
   
Open http://localhost:5000 in your browser and you should see the pet name generator!
