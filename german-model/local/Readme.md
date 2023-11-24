# Train LeoLM on a multi-GPU Instances

- Edit config parameters in `config/``

- Run:

```
#Multi-GPU training with LORA/QLORA
ACCELERATE_LOG_LEVEL=info accelerate launch --config_file config/config_accelerate.yaml run_sft.py config/config_lora.yaml
```

Learn more on [The Alignment Handbook repo](https://github.com/huggingface/alignment-handbook/tree/main/scripts). For help on the `accelerate` configuration consult the [accelerate-examples Spaces](https://huggingface.co/spaces/hf-accelerate/accelerate_examples).

