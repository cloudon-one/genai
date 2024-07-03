# OpenAI applications samples
## OpenAI API: Building custom agents with the Assistant API 

  ## Instructions

This repository provides basic examples of how to use the OpenAI Assistant API in both Python and Node.js. The Python examples are found in the `/python` folder, the Node.js examples in the `/node` folder. The examples perform identical tasks using the same API across the two different languages.

  

To use these exercise files you need an OpenAI API key. You get that key at [platform.openai.com](https://platform.openai.com)

  

## Running the examples in GitHub Codespaces

1. Click the "Code" button and select "Codespaces."

2. Create a new Codespace or open one you've already created.

3. Create a new file named `.env` in the root folder.

4. Add `OPENAI_API_KEY=` followed by your OpenAI API key to `.env`

5. Note `.env` is not tracked by GitHub so the file will only exist in this Codespace.

6. To run the Python examples in terminal, navigate to the `/python` folder and use the `python [filename.py]` command.

7. To run the Node.js examples in terminal, navigate to the `/node` folder and use the `node [filename.js]` command.

## OpenAI API: Multimodal development with GPT-4o
OpenAI API to leverage the multimodal capabilities of GPT-4o and function calling to extract text from images, conform the data to JSON, and call functions to save the extracted data to a spreadsheet.

## Instructions

This repository holds example data and two Jupyter Notebooks:
-  `data/` holds a collection of images of random receipts and one wild-card.
-  `expenses.csv` is the target CSV. At init, the CSV only holds column headings.
-  `gp4o-setup.py` demonstrates how to how to access gpt-4o for multimodal prompting.
-  `modular-process.py` and the module files in `utils/` demonstrate a comprehensive process of ingesting and interpreting multiple receipts and sending the data to a CSV file.
The first time you run a block in a Jupyter Notebook, the environment will ask you to pick an environment. Follow the instructions and pick the first available Python environment.

NOTE: The first code block may take a while to load because the environment has to load first.
## Installing

It is recommended you run these exercise files in GitHub Codespaces. This gives you a pre-configured Python environment for the Jupyter Notebooks to run.

To use the exercise files, follow these steps:
1. In the root folder, rename the file `env-template` to `.env`.
2. Go to [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys).
3. Generate a new key and copy the key to your clipboard.
4. In `.env` add the key without quotes or parentheses.

# OpenAI API: Vision

OpenAI’s vision API opens the door to a new generation of Apps. These APIs are also accessible, reducing the barrier to entry for building such apps. How to use the vision API to build an application that sees.