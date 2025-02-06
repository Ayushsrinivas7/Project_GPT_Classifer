# This is AyushSrinivas7 (prathipati yadu vamsi ) From IIT patna  here is my project
# PROJECT :Redesiging _GPT2_for_SPAM_classification_&_finetuning_it.
I redesigned the entire GPT2 and finetuned the model (redesigned : the last output layer with 2 nodes for spam and no spam classification) . (for finetunning i just made the last transformer block and final layernorm  trainable ).   [SEE my git hub of normal and lora fine tunning ](https://github.com/Ayushsrinivas7/Project_GPT_Classifer). Every thing is from scratch 
note : for loading the model use the gpt2_model.py file so that you can load the model directly also see the prev colab of how to load the pretrains to our model 

![steps i followed](https://drive.google.com/uc?export=view&id=1fJ-_7pNN9ngsp5AKcD5tCMhJ6qXuXS4z) 
![Architecture ](https://drive.google.com/uc?export=view&id=1AKkTg2XnGdKqGzqgW0SLTzc3s3J3zTrr)

![loss](https://drive.google.com/uc?export=view&id=1LDxwVXJPv4X2Uxx2rWPCra8NxI69NkUq)

Also attached the finetuned the model with **fully custom built lora code ie built the lora class and replaced every linear layer with the lora linear layer so that pretrain information is retained and also the number of trainable weights is decreased ie 124 million to 2 million **
![LORA image](https://drive.google.com/uc?export=view&id=1wf-JfaUKMDZIU3CWFZmgvTVPvqovfuIv)

![Lorra loss curve](https://drive.google.com/uc?export=view&id=1sEz04dz3n9st6FvbJgQpDYTIfotBQnnw)
___
