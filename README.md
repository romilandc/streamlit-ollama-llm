# streamlit-ollama-llm
A Streamlit user interface for local LLM implementation on Ollama.  With just two python apps you can have a localized LLM to chat with.  I'm running Ollama Windows (just updated) and DuckDuckGo browser and it's working great as a coding assistant.

## How to use
- create local path and data subfolder 
- create virtual env using conda `conda create -n ollama` or venv
- install requirements.txt `pip install -r /path/to/requirements.txt`
- check Ollama is activated:
    - for Ollama Windows bottom right there should be 🦙
    - for Linux check Ollama documentation https://github.com/ollama/ollama
- download models (https://ollama.com/library) from Ollama if you haven't yet `ollama pull model_name_here` in cmd terminal
- change directory to local path where llm_app.py is saved
- in terminal enter `streamlit run llm_app.py`
- you should see this

- copy/paste the link in your browser and see this

- select the model of choice:

- enter your question in the prompt and hit enter

- enjoy and let me know if you've come up with any other additions to the Streamlit app

![Image1](https://github.com/romilan24/llama-index-RAG/blob/main/RAG_inference_pdfs.JPG)
