# Christmas Sales Data Science Project
## Background

In the run up to Christmas, retail stores hold sales events, such as Black Friday, in order to increase footfall into brick and mortar stores and online traffic to their web based sales. The sales events are used to increase sales and brand awareness, upping profit to stores. 
As sales events can increase the likelihood for individuals to purchase items on a whim, this analytical project has been introduced to see if items are more likely to be returned if they were purchased during a sales event. 


### Data Source
The data has been sourced from Kaggle.com and provides information on sales, both in store and online, for items on various categories, including if it was sold during a Black Friday or Christmas Market event. The dataset contains information on the customer as well, which for this instance, was not needed for analysis. 
The data was clean and contained no duplicated entries as found within the results. As such, no cleaning or deduplication was required. Multiple columns were dropped from the source table as they provided no assistance to the results. 
<img width="287" height="91" alt="image" src="https://github.com/user-attachments/assets/19440773-77d2-4f68-95ab-83e7e59b93cf" />
Checking Duplicated Rows
<img width="1367" height="106" alt="image" src="https://github.com/user-attachments/assets/0da259ef-72ae-47d6-a246-bb374c0a3389" />
Dropping Extra Columns
<img width="552" height="282" alt="image" src="https://github.com/user-attachments/assets/4f05c938-eef2-4b50-88a7-57f3ce1758d0" />
Table After Dropping Extra Columns

The remaining columns; promotions applied, event and return flag, are then transformed into binary fields - true converting to 1, false 0 and a sales event converting to 1. The text fields were then dropped, leaving the binary fields only. 
<img width="897" height="147" alt="image" src="https://github.com/user-attachments/assets/e352bd09-20f6-434b-8be6-6d6603586791" />
Coverting to Binary Fields
<img width="817" height="537" alt="image" src="https://github.com/user-attachments/assets/77d29edf-da63-4091-b46a-faacc46ad7b6" />
Results
<img width="626" height="332" alt="image" src="https://github.com/user-attachments/assets/e76cf2b8-24f2-4db4-9f15-f5d118630362" />
Binary Fields Remaining








https://www.kaggle.com/datasets/ibikunlegabriel/christmas-sales-and-trends 


<!--
**BP0324006/BP0324006** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
