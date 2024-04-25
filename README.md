# job consistency checker endpoint

## steps of deployment

1. install the required packages

```bash
pip install -r requirements.txt
```

2. download the model of spacy

```bash
python -m spacy download en_core_web_sm
```

3. start the service

```bash
uvicorn main:app --host 0.0.0.0 --port 8086 --reload
```

the service will be available at http://0.0.0.0:8086/docs#/
