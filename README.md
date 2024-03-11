A Streamlit webapp UI for local LLM implementation on Ollama.  With just three python libraries (torch, streamlit, ollama) you can have a localized LLM to chat with.  I'm running Ollama Windows (new update as-of 03/24) and DuckDuckGo browser and it's working great as a coding assistant.  

For coding, try code llama, dolphin-mixtral, or deepseek-coder.  For everyday questions, try mixtral or mistral.  There's a good selection available:  https://ollama.com/library

## How to use
- choose if you want to use gpu or cpu; llm_app.py will work in both instances
- create folder in path with gpu/cpu for the project
- change directory to this path `cd /path/to/project/folder'
- use git to clone repository `git clone https://github.com/romilan24/streamlit-ollama-llm.git`
- create virtual env using conda `conda create -n ollama` or venv
- activate the environment `conda activate ollama` and you should see this:

 ![Image1](https://github.com/romilan24/streamlit-ollama-llm/blob/main/img/conda.JPG)

- install requirements.txt `pip install -r /path/to/requirements.txt`
- check Ollama is activated:
    - for Ollama Windows bottom right there should be 🦙
    - for Linux check Ollama documentation https://github.com/ollama/ollama
- download models (https://ollama.com/library) from Ollama if you haven't yet `ollama pull model_name_here` in cmd terminal

![Image2](https://github.com/romilan24/streamlit-ollama-llm/blob/main/img/ollama_pull.JPG)

- change directory to local path where llm_app.py is saved
- in terminal enter `streamlit run llm_app.py`, you should see this:

![Image3](https://github.com/romilan24/streamlit-ollama-llm/blob/main/img/run_streamlit.JPG)

- copy/paste the link in your browser and see this

- select the model of choice:
  
![Image4](https://github.com/romilan24/streamlit-ollama-llm/blob/main/img/streamlit_model.JPG)

- enter your question in the prompt and hit enter
  
![Image5](https://github.com/romilan24/streamlit-ollama-llm/blob/main/img/integer_sum.JPG)

- and the code works!

![Image6](https://github.com/romilan24/streamlit-ollama-llm/blob/main/img/it_works.JPG)

- enjoy your local LLM and let me know if you come up with any additions
