# Medical Signal Analysis
## But what does this even mean?

This repository contains notebooks I made to analyse signals registered during various electro- medical examinations (eg. EKG, EMG, EOG, EEG). Each notebook is a solution to specific examination method related task on 2nd year Bioelectrical Signals class (Biomedical Physics, Neuroinformatics, Physics Department, University of Warsaw).



## Electromyography (EMG)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xg7bjmLnSa_x7dp0svAgRSzEjvvR2kME?usp=sharing)

### Face emotions
EMG face recording for different emotions. The subject had to replicate emotions shown on screen (active procedure) or just look at them (passive procedure). Whats important is: both procedures should have the same results, according to literature, the subject shouldn't have to conciously replicate the emotions in order for the muscles to activate.
Only the final results are presented. Take a look into the .ipynb file for middle steps and code.   


**Muscles of facial expression** 
So we are on the same page with what we're looking at.  
![image](https://user-images.githubusercontent.com/62252332/121500668-cf228200-c9de-11eb-9f4f-ae52127e913b.png)  

**Emotion:** Anger       
**Procedure:** Active   
**Expected most active muscles:** Orbicularis  
**Result:**  Orbicularis  
![image](https://user-images.githubusercontent.com/62252332/121499657-e14ff080-c9dd-11eb-94ee-5c8f7e38aac9.png) 

**Emotion:** Anger       
**Procedure:** Passive   
**Expected most active muscles:** Orbicularis  
**Result:**  Orbicularis   
![image](https://user-images.githubusercontent.com/62252332/121500011-312eb780-c9de-11eb-9d72-213db6d4efb9.png)
  
 ----

### Hands load spectrum  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-wyZkxxYcRvcu30Eg99aXhdsoqfiMnmg?usp=sharing)
EMG hands recording for the book holding experiment. The subject had to hold up to 5 books.  
Only the final results are presented. Take a look into the .ipynb file for middle steps and code.  

**Number of books vs voltage average**
![image](https://user-images.githubusercontent.com/62252332/121497665-f7f54800-c9db-11eb-9902-4483ba72ae41.png) 

**Power spectrum for rising amount of books (1, 2,..., 5)**
![image](https://user-images.githubusercontent.com/62252332/121497242-861cfe80-c9db-11eb-8f9e-408772ccee8e.png)
  
 ----

### Hands movement detector  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1d_uQuA9lwHjszQ5OBshBH1osUt34usH6?usp=sharing)
EMG hands recording for the vertical movement experiment. The subject had to rise his hand for the duration of the alert on screen (alert = tag).  
Only the final results are presented. Take a look into the .ipynb file for middle steps and code.  


**Comparison of the original alerts (red zones) vs the detector indications (orange line)**  
The detection algorithm looks at the signal movement between standard deviation levels (dashed line). 
![image](https://user-images.githubusercontent.com/62252332/121518188-7bb92f80-c9f0-11eb-825c-57ac9d7a19f8.png)


