<h1> LLM-Trainer </h1>

<h2> Objective </h2>

This GitHub project contains a set of Jupyter notebooks that can be used to finetune pre-trained large language models using LoRA.
It uses Rick and Morty dialog as training examples, and create a chatbot that sometimes insults the user and provide short and unhelpful answer...
Overall, it makes it worse. However, this dummy task is mean to guide user through the process of (1) Preparing Finetuning Data & (2) What to lookout for in LoRA training.
And it is much easier to observe the effect if your deliberately try to ingest negative effect.
All the notebooks can be execute in google colab's free T4 GPU machine.

![Alt Text](/public/cover.png)

<h2> Setup </h2>

<ol>
<li>Step 1: Go to https://colab.research.google.com/

<li>Step 2: File > Upload Notebook > Notebooks/Preprocess.ipynb, Or you can skip this step because the output is alrady in "RM.json"
   
<li>Step 3: File > Upload Notebook > Notebooks/*_lora_training.ipynb, Pick whichever one you like, all of them are 3B LLM that works on Colab
</ol>