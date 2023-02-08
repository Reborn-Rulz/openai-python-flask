# openai
OpenAI ChatGPT API

# OpenAI ChatGPT API 

Build your application

Now that you’ve found a good prompt and settings, you’re ready to build your pet name generator! We’ve written some code to get you started — follow the instructions below to download the code and run the app.

# Copy
     $ git clone https://github.com/openai/openai-quickstart-python.git
    
    
Add your API key

Navigate into the project directory and make a copy of the example environment variables file.

      $ cd openai-quickstart-python
      $ cp .env.example .env
      
Opeb the link url https://openai.com/api/ and sign up to create your API key.

Important note: When using Javascript, all API calls should be made on the server-side only, since making calls in client-side browser code will expose your API key.

Run the app

Run the following commands in the project directory to install the dependencies and run the app. When running the commands, you may need to type python3/pip3 instead of python/pip depending on your setup.

      $ python -m venv venv
      $ . venv/bin/activate
      $ pip install -r requirements.txt
      $ flask run
      
 Open http://localhost:5000 in your browser and you should see the pet name generator!
 
