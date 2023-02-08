# OpenAI API - Python

Build your OpenAI application

To build your own OpenAI pet name generator! — follow the instructions below to download the code and run the app.


Setup


1. If you don’t have Python installed from this link (https://www.python.org/downloads/).

2. Open the Prompt and run the command below to install Flask.

   $ pip3 install flask
 
 
Add your API key

3. Navigate into the project directory and make a copy of the example environment variables file.

   $ cd openai-quickstart-python
   $ cp .env.example .env


5. Copy your secret API key and set it as the OPENAI_API_KEY in your newly created .env file. If you haven't created a secret key yet, you can do so below.

3. Navigate into the project directory

   ```bash
   $ cd openai-quickstart-python
   ```

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

8. Run the app

   ```bash
   $ flask run
   ```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! For the full context behind this example app, check out the [tutorial](https://beta.openai.com/docs/quickstart).
