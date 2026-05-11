# Christmas Sales Data Science Project
## Background

In the run up to Christmas, retail stores hold sales events, such as Black Friday, in order to increase footfall into brick and mortar stores and online traffic to their web based sales. The sales events are used to increase sales and brand awareness, upping profit to stores. 
As sales events can increase the likelihood for individuals to purchase items on a whim, this analytical project has been introduced to see if items are more likely to be returned if they were purchased during a sales event. 


### Data and Analysis
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
Next, I took the return flag field to see how balanced the results are in the data set. The chart easily shows how balanced the results are. 
<img width="746" height="680" alt="image" src="https://github.com/user-attachments/assets/e3ce03c7-c712-47c7-abb3-afb9259a60a0" />
Balance of Outcomes
<img width="505" height="222" alt="image" src="https://github.com/user-attachments/assets/e56d13ac-39dd-4d58-8011-05b38e84c8bb" />
The dataset is split into a training and test set, with 80% used to train the model. The dataset split is checked. 
<img width="1141" height="125" alt="image" src="https://github.com/user-attachments/assets/dea9ddc6-1a2c-47db-a578-47cbe90f1fbf" />
<img width="1132" height="541" alt="image" src="https://github.com/user-attachments/assets/21c6b3af-5e25-4eee-98b5-5bf6a52881de" />
The split and balance displayed as charts. 
<img width="427" height="232" alt="image" src="https://github.com/user-attachments/assets/ec049376-37a9-48a5-80a1-c2a0f792b8d3" />
The correlation is checked as a table and displayed. 
<img width="797" height="665" alt="image" src="https://github.com/user-attachments/assets/165021fd-db1f-42d9-817a-fe893b4f227c" />
Heatmap of correlation
<img width="612" height="350" alt="image" src="https://github.com/user-attachments/assets/3f071554-9b24-4126-9660-0d057524c2b0" />
The model is initalised
<img width="890" height="662" alt="image" src="https://github.com/user-attachments/assets/684b4483-278a-422c-9d5e-57ca05dd730a" />
Scaling the data
<img width="1122" height="617" alt="image" src="https://github.com/user-attachments/assets/a01babaa-6271-48da-a495-d46726a9bd1d" />
Accuracy is checked - in this instance, it is not a very accurate result
<img width="545" height="215" alt="image" src="https://github.com/user-attachments/assets/531df997-c9c8-47d5-8288-02a2735b5296" />
Secondary accuracy test.
## Results
The results from the logistical regression show that there is a low accuracy rate, 50%, and therefore showing a link between a promotion or sales event and an item being returned is slim. This is encouraging as it shows that items are not regularly returned because of promotions or sales events encouraging customers to purchase items. 
Further analysis should be carried out to see if there is a pattern within the data to show why items are returned but providing more sales events during the year or christmas period would not encourage a high percentage of returns to occur. If the analysis was broken down to category of goods, there could be a pattern showing, for example, a higher rate of clothing returns (for example, the recipient of the gift requiring a differing size). 








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
