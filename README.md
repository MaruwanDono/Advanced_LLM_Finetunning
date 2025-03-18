# Advanced_LLM_Finetunning
Finetuning llama-7b-hf model for specific tasks (generating python code for example) with a focus on efficiency using techniques like LoRA adapters (applied on top of Q/K/V linear layers in Llama attention, MLP components and lm_head), attention masks, autocasting and gradient accumulation. The finetuning is only on the LoRA adapter parameters.
