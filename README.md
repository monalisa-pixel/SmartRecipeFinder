# SmartRecipeFinder

Suggest recipes that minimize food waste by using ingredients that are about to expire or are leftovers from other meals. SmartRecipeFinder is a chatbot specifically designed to assist users with recipe suggestion-related inquiries. By feeding data about various recipe suggestions into a large language model (LLM), this chatbot provides insightful information and advice for recipe suggestion care, identification, and maintenance.

## Features
- User-friendly interface for answering recipe suggestion-related questions.
- Comprehensive repository of recipe suggestion-related information.
- Personalized guidance and recommendations based on user inputs.

## Installation
To get started with SmartRecipeFinder, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/code001001/SmartRecipeFinder.git
    cd SmartRecipeFinder
    ```

2. Install the Gaia Node:
    Run the command below:
    ```bash
    curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
    ```

3. Update the `config.json` file to run with a small language model:
    ```bash
    gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json
    ```

4. Start the node:
    ```bash
    gaianet start
    ```

## How to Use
1. Open your web browser and navigate to the generated link.
2. Start interacting with the chatbot by typing your recipe suggestion-related questions.
