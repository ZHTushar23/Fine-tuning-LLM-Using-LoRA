# Fine-tuning-LLM-Using-LoRA
Adopted from huggingface demo on fine-tuning quantized LLMs using Low Rank Adapters (LoRA).


## Install Required Packages

Install the necessary Python packages using pip:

```bash
pip install transformers accelerate peft bitsandbytes
```
## Run Inference using colab
To run inference using colab, refer to _inference_quantized_LLM.ipynb_ file.

To run inference on conda/virtual env, use the following command:

```bash
bash run_test.sh --model_name [model_name]
```
E.g. 
```bash
bash run_test.sh --model_name 'local-phi3-mini-yoda-adapter-zahid'
