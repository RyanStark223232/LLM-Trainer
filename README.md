<h1> LLM-Trainer </h1>

This GitHub project contains a set of Jupyter notebooks that can be used to finetune pre-trained large language models using LoRA.
It uses Rick and Morty dialog as training examples, and create a chatbot that sometimes insults the user and provide short and unhelpful answer...
Please switch to better data when used in actual production.
All the notebooks can be execute in google colab's free T4 GPU machine.

![Alt Text](/public/cover.png)

<h2> Setup </h2>

<ol>
<li>Step 1: Install the dependcies, preferably in a new virtual environment

   ```bat
   pip install -r requirements.txt
   ```
   
<li>Step 2: Run the notebook of your choice. "Preprocess.ipynb" is used for creating "RM.json"