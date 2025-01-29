# Ollama

### Run the requirements using the below command
```pip3 install requirements.txt```

### Docker Commands
```docker pull ollama/ollama```

```sudo docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama```

#### If the container is already there
```sudo docker start ollama```

### Run the streamlit application
```streamlit run streamlit-app.py```

**NOTE:**
You can check that ollama in docker is working fine by hitting this url in the browser
<a href="http://localhost:11434/"> http://localhost:11434/ </a>
