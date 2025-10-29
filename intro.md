# Intro to LangChain

## Environment prerequisites


1. [Python installers](https://www.python.org/downloads/)
2. [VScode](https://code.visualstudio.com/download) or any other python IDE
3. [Git](https://git-scm.com/install/windows) for version control 
4. [GitHub Desktop](https://desktop.github.com/download/) for a git GUI
5. uv as a python package/project manager using the [installers](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer) or ```python3 -m pip install --user pipx```
`python3 -m pipx ensurepath`
`pipx install uv` - much faster than pip for dependencies install


## Setting up the project

- `uv init` - bootstrap python project
- `uv add langchain`
- `uv add python-dotenv`
- `uv add langchain-openai`
- `uv add langchain-google-genai`

3. Create `.env` file. You Can start with free Gemini API key from [Google](https://aistudio.google.com/api-keys)
```
OPENAI_API_KEY = 
GOOGLE_API_KEY = 
```


## Running

If default python interpreter in VScode is the global one, switch to one in venv using 
`ctrl + shift + P` -> Python: Select Interpreter 

To run the, either 
- `python.exe .\main.py` in terminal
- setup hotkey for Run command using `ctrl + shift + P` -> Preferences: Open Keyboard Shortcuts -> set your preferred shortcut


# Adding UiPath LangChain SDK