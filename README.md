# Autonomous Researcher - Twitter Threads Generator

This script uses the OpenAI GPT-3 model and the SERPAPI service to autonomously generate Twitter threads on a specified topic. The script finds relevant articles based on the topic, summarizes the content, and then generates a Twitter thread.

## Requirements

This script requires Python 3 and the following Python packages:

- `streamlit`
- `openai`
- `dotenv`
- `requests`
- `json`
- `langchain`

You can install these packages using pip:

`pip install streamlit openai python-dotenv requests`


Please note that the `langchain` package is not publicly available and you will need to have access to this package for the script to run.

## Setup

To run this script, you need to set up an environment file (`.env`) in the same directory as your script. The environment file should contain your OpenAI API key and your SERPAPI API key. Here's an example of what this file might look like:

`OPENAI_API_KEY=your_openai_api_key_here`
`SERPAPI_API_KEY=your_serpapi_key_here`


Replace `your_openai_api_key_here` and `your_serpapi_key_here` with your actual keys.

## Running the Script

You can run the script with Streamlit. Open a terminal or command prompt, navigate to the directory containing the script, and run the following command:

`streamlit run your_script_name.py`


Replace `your_script_name.py` with the actual name of your script.

Once the script is running, you should see a URL in your terminal or command prompt that points to your local machine (something like `http://localhost:8501`). Open this URL in a web browser to interact with the Streamlit application.

## Costs and Usage Limits

Please note that this script interacts with the OpenAI API and the SERPAPI service, which may have costs associated with their use, depending on your usage level. Make sure you understand any potential costs before running the script.
