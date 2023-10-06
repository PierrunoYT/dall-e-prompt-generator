# dall-e-prompt-generator
GitHub Copilot: Here is the formatted description for GitHub:

## `promptgenerator.py` Script for DALL-E Prompt Generation

This is a Python script that generates prompts for DALL-E, an image generator, using the OpenAI API and the ChatGPT API. The script allows the user to generate a random prompt or a prompt based on specific keywords. The generated prompt is then displayed to the user, along with a count of the total number of image generations.

### Usage

To use the `promptgenerator.py` script on your computer, you will need to follow these steps:

1. Install Python: If you don't already have Python installed on your computer, you can download it from the official website: https://www.python.org/downloads/

2. Install the required packages: The `promptgenerator.py` script requires several Python packages to run, including `nltk` and `openai`. You can install these packages using the following commands in your terminal:

```
pip install nltk
pip install openai
```

3. Download the `punkt` resource: The `promptgenerator.py` script also requires the `punkt` resource from the Natural Language Toolkit (NLTK). You can download and install this resource by running the following command in your terminal:

```
python -m nltk.downloader punkt
```

4. Set up your OpenAI API key: To use the OpenAI API, you will need to set up an account and obtain an API key. You can follow the instructions on the OpenAI website to do this: https://beta.openai.com/docs/api-reference/authentication

5. Create a configuration file: The `promptgenerator.py` script reads your OpenAI API key from a configuration file called `config.ini`. You can create this file in the same directory as the `promptgenerator.py` script, and add the following contents:

```
[openai]
api_key = YOUR_API_KEY_HERE
```

Replace `YOUR_API_KEY_HERE` with your actual OpenAI API key.

6. Run the script: Once you have completed the above steps, you can run the `promptgenerator.py` script by opening a terminal, navigating to the directory where the script is located, and running the following command:

```
python promptgenerator.py
```

This will start the script and display a menu with two options. Follow the prompts to generate a DALL-E prompt or a prompt for specific keywords.

Note: The `promptgenerator.py` script requires an internet connection to access the OpenAI API. Make sure you are connected to the internet before running the script.
