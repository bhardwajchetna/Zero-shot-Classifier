# Zero-shot-Text-Classifier

Zero-Shot Learning is the ability to detect classes that the model has never seen during training. It refers to a specific use case of machine learning where you want the model to classify data based on very few or even no labeled example, which means classifying on the fly. 
Check this post — [Zero-Shot Learning in Modern NLP](https://joeddav.github.io/blog/2020/05/29/ZSL.html). There is a live [demo](https://huggingface.co/zero-shot/) from Hugging Face team, along with a sample [Colab notebook](https://colab.research.google.com/drive/1jocViLorbwWIkTXKwxCOV9HLTaDDgCaw).

This tutorial is a guide to building two basic types of zero-shot classifier. 

1. Single-Class Classifier (Only themes)
2. Multi-Class (Themes & Subthemes)

All you need is two csv files, one containing the reviews you want to classify and the [other](layers.csv) conatining the themes for your classification.  
