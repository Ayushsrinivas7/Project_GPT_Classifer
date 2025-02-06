# 🚀 PROJECT: **Redesigning GPT-2 for Spam Classification**  
_(Custom LoRA Fine-Tuning & Normal Fine-Tuning)_

I redesigned the **entire GPT-2 model** for **spam classification** by modifying the last **output layer** to have **2 nodes** (Spam & Not Spam).  

For **fine-tuning**, I made only the **last transformer block** and **final LayerNorm trainable** to optimize performance.  

🔗 **[See my GitHub for Normal & LoRA Fine-Tuning](https://github.com/Ayushsrinivas7/Project_GPT_Classifer)**  

**Note:**  
- To **load the model**, use the `gpt2_model.py` file.  
- Refer to my **previous Colab** to see how to **load pre-trained weights** into the custom model.  



## 🔹 Steps I Followed:
![Steps I Followed](https://drive.google.com/uc?export=view&id=1fJ-_7pNN9ngsp5AKcD5tCMhJ6qXuXS4z)



## 🔹 LoRA Fine-Tuning Implementation:
I also fine-tuned the model using **fully custom-built LoRA (Low-Rank Adaptation) code**:  
✅ **Built a custom LoRA class** and replaced every **Linear Layer** with a **LoRA Linear Layer**.  
✅ This helped retain **pre-trained knowledge** while significantly **reducing the number of trainable parameters**.  
✅ **Trainable parameters reduced from 124M → 2M**, making the model much more efficient!  

![LoRA Implementation](https://drive.google.com/uc?export=view&id=1wf-JfaUKMDZIU3CWFZmgvTVPvqovfuIv)


This project was built **entirely from scratch**! 🚀 
