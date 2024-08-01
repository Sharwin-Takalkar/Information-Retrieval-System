# Information Retrieval from Multiple PDF with PaLM2


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n gpalm2 python=3.12 -y
```

```bash
conda activate gpalm2
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY as follows:

```ini
GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up : http://localhost:8501
```


### Techstack Used:

- Python
- LangChain
- Streamlit 
- PaLM2
- FAISS