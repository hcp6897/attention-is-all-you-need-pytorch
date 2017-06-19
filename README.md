# [WIP] Attention is all you need: A Pytorch Implementation

This is a PyTorch implementation of the Transformer model in "[Attention is All You Need](https://arxiv.org/abs/1706.03762)". 

<img src="http://imgur.com/1krF2R6.png" width="250">

The project is still work in progress, now only support training.
Translating will be available soon.

# Usage

## 0) Prepare the data
```bash
python preprocess.py -train_src <train.src.txt> -train_tgt <train.tgt.txt> -valid_src <valid.src.txt> -valid_tgt <valid.tgt.txt> -output <output.pt>
```

## 1) Training
```bash
python train.py -data <output.pt>
```
## 2) Testing
### TODO
  - **Beam search** 

---
If there is any suggestion or error, feel free to fire an issue. :)
