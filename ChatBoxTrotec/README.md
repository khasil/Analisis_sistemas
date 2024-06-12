# System Analysis - Final Project

The system analysis chatbox project focused on improving the sales experience of laser cutting and engraving machines from the Trotec Laser brand is stored in this repository. The project only includes a series of PDFs of the models most requested by customers (determined through systemic analysis),the explanatory documents are located in the "slides" folder

## How to Use

Next steps should help you to make the better use possible of this skeleton:
1. Create a _python virtual environtment_ for this project.
2. This project is created using _poetry_, so you could add _python dependencies_ just moving in a terminal ath the root of the project (where this _README_ file is allocated), and execute next command:

```[bash]
poetry install
```
3. download the model from the link: https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.2-GGUF/blob/main/mistral-7b-instruct-v0.2.Q2_K.gguf and add it to the folder: llm_model

4. To run the project, againa in a temrinal in the root of the project, you could use next command:

```[bash]
poetry run run-agent
```
