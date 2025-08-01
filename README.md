# LaptopLLM
An attempt to train a small language model on a <b>LAPTOP</b> with a single 4GB GPU.



![Alt text for your image](./Media/Unified_picture.png)

## Introduction
Can we train a language model(small one) on a <b>laptop</b> just enough to teach it something?
This repo demonstrates how to fine-tune a ~100M parameter base model—which, as a pretrained model, has no initial question-answering capability—to start answering questions, all on a laptop with only 4GB of GPU memory.

Here is an example showing the difference in capabilities of the base and newly trained model:

```
Question: What do you know about Toshiba?
Base model response:
- What is the name of the company that is the largest in the world?
- What is the name of the company that is the largest in the world?
- What is the name of the company that is the largest in the world?
```
```
Question: What do you know about Toshiba?
Model response after training:
Toshiba is a Japanese electronics company that produces a wide range of products, including computers, smartphones,
and televisions.<|im_end|>
```

## How can I train my own model?
1. ADD DETAILS ABOUT SETTING UP THE ENVIRONMENT
2. ADD DETAILS ABOUT RUNNING THE NOTEBOOK
3. ADD DETAILS ABOUT RUNNING THE EVALUATION NOTEBOOK 

## Hardware details

## Dataset details

## Training parameters details

## Add To-Try
1. Mixed precision training
2. Flash attention
3. Loss on response only
4. Torch tools - ??
