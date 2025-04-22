# HH-Clean
This is a cleaned version of Anthropic-HH dataset introduced in the paper ***[How Reliable Is Human Feedback For Aligning Large Language Models?
](https://arxiv.org/abs/2410.01957)*** by Min-Hsuan Yeh, Leitian Tao, Jeffrey Wang, Xuefeng Du, and Yixuan Li.

Please download the data from [this link](https://drive.google.com/file/d/1J50h_v8S0WKsOu3tFjlme8DGECjyPyTq/view?usp=sharing)

## File Description

- `harmless`: cleaned version of the harmless split of Anthropic-HH
- `helpful`: cleaned version of the helpful split of Anthropic-HH
- `train.jsonl`: file merged from `harmless/train.jsonl` and `helpful/train.jsonl`
- `test.jsonl`: file merged from `harmless/test.jsonl` and `helpful/test.jsonl`

## Citation

Please cite this work if you use HH-Clean.

```
@article{yeh2024how,
      title={How Reliable Is Human Feedback For Aligning Large Language Models?}, 
      author={Min-Hsuan Yeh and Leitian Tao and Jeffrey Wang and Xuefeng Du and Yixuan Li},
      year={2024},
      journal={arXiv preprint arXiv:2410.01957},}
```