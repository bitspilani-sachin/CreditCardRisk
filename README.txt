Steps to be followed to access the document

1. Upload the .ipynb file into colab

2. Add the following keys in the secrets section in colab
LLM_CERT_PATH: /content/vm06-ca.crt 
LLM_BASE_URL: https://103.42.50.41:1032/v1 
LLM_API_KEY: sk--lir-paKzfdCFyPGcpS-b9btjQMYB-r0UM18fpsu9co 
LLM_MODEL: Qwen/Qwen3-8B 

EMBEDDING_CERT_PATH: /content/vm02-ca.crt 
EMBEDDING_BASE_URL: https://103.42.50.41:1035/v1 
EMBEDDING_API_KEY: sk-ucwh-7vEEfPHRit6WNtNjPhtq4IPmWM7zTmyk1Wfx6iQt8Ka 
EMBEDDING_MODEL: bge-small-en-v1.5

3. As mentioned in step #2, copy the vm06-ca.crt and vm02-ca.crt files in /content/ folder 
4. Select Run All
