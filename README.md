# LlamaGuard-AlignScore-NeMoGuardrails-NIM



## How to run the app

### Start with setting up the llamaguard model

Make sure you have access allowed for the `meta-llama/LlamaGuard-7b` model from here - https://huggingface.co/meta-llama/LlamaGuard-7b

Once you have the access token generated, follow the steps here to setup the vllm for llamaGuard - https://github.com/NVIDIA/NeMo-Guardrails/blob/develop/docs/user_guides/advanced/llama-guard-deployment.md

### Running the app

Add the environment variables as follows:

Here NVIDIA NIMs are used for both the embedding model and LLM. You can easily swap the models with your choice

```
export NVIDIA_API_KEY=....
export OPEANI_API_KEY-"dummy"
```
run the `ingest.py` file with whatever pdf as your data. Here the data is based on NVIDIA AI Enterprise user guide.

run the `main.py` 

## For the notebook

Make sure the notebook is in this same directory as the app, for easy walk through

