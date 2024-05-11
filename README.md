# Prompt-Expansion


- **Base Model**: [Gemma-2B](https://huggingface.co/google/gemma-2b)
- **Instruction-tune model**: [Gemma-2B instruction tuned](https://huggingface.co/rootacess/gemma-instruction-tuned)
- **Dataset**: [Dolly 15K](https://huggingface.co/datasets/databricks/databricks-dolly-15k)
- **Finetuning method**: Supervised Finetuning with QLoRA

## Future steps
- Develop a synthetic specialized prompt expansion dataset using LLMs (GPT-4, etc)
- Perform finetuning over the dataset, expecting to get better performance
