

# QLoRA: Efficient Finetuning of Quantized LLMs [FORK](https://github.com/artidoro/qlora)

| [Paper](https://arxiv.org/abs/2305.14314) | [Adapter Weights](https://huggingface.co/timdettmers) | [Demo](https://huggingface.co/spaces/uwnlp/guanaco-playground-tgi) | 

This repo supports the paper "QLoRA: Efficient Finetuning of Quantized LLMs", an effort to democratize access to LLM research. 

QLoRA uses [bitsandbytes](https://github.com/TimDettmers/bitsandbytes) for quantization and is integrated with Hugging Face's [PEFT](https://github.com/huggingface/peft) and [transformers](https://github.com/huggingface/transformers/) libraries. QLoRA was developed by members of the [University of Washington's UW NLP group](https://twitter.com/uwnlp?s=20).

## New Features

- Text Learning rather than Input-Output (dataset_format=rawtext)
- Stop Learning on specific loss (stop_at_loss=1.4)

## Why forked

- I am new to python
- experimenting


## Acknowledgements

This is a fork. So shoutouts to the originator [artidoro/qlora](https://github.com/artidoro/qlora)