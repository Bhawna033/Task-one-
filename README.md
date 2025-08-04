# Task-one-
I have downloaded two Datasets from Kaggle to Data cleaning Process. The tools which i have used are power query editor and Gen AI Tools for some advanced methods. Firstly i used the power query editor to clean the Netflix Movies and TV shows dataset in which i have to deal with missing values and duplicate values. I will  mentions the steps below and also upload some screenshots.

Steps:

1) Upload the dataset into power bi and trasform it into power query editor. Power query automatically checks the quality of your Dataset, after reviewing the dataset we can see that there are several missing values as:
   
 director: 2634 missing

cast: 825 missing

country: 831 missing

2) I have analyzed the dataset very carefully and used various methods to deal with these missing values. As we all know we cannot just remove the null values as it will give us incomplete data. So for Director and cast column i just use the Categorial method and fill it with "Missing Director and Missing Cast". For Country i used the column statistics and used the most frequntly used country "United States". This Dataset is all clean and ready for the next process.

<img width="1920" height="1080" alt="Screenshot (191)" src="https://github.com/user-attachments/assets/fc88d9ac-85ff-4ea5-89d2-8926e258146f" />
<img width="1920" height="1080" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/fe04f47b-8227-4656-ac82-bfe7d8b0da48" />
<img width="1920" height="1080" alt="Screenshot (193)" src="https://github.com/user-attachments/assets/5c2c2ab3-24a4-4103-9014-c165d015df72" />

As you can see now our Dataset is Clean.

3) After that i have uploaded the second dataset which is sales datasete which have missing values, errors and incomplete data. I have used some advanced power query methods to clean this dataset which involves column merging, changing the types of columns, Tronsposing the table and filtering the rows and lastly unpivot the columns.

4) Firstly i merged the two columns by delimiter and then transpose the table. Then i fill down some values in Shipmode column to deal with null values.

5) After that i promoted the Headers of the column and changed the type of the column.

6) Then i select the first two column and unpivot the other columns.

7) Then i split the column that i have merged before by delimiter, changed the type of columns and rename it by giving a proper heading to the column.
   
<img width="1920" height="1080" alt="Screenshot (194)" src="https://github.com/user-attachments/assets/74d42c70-b47a-4ee1-b06c-18c284e6c8e6" />
 <img width="1920" height="1080" alt="Screenshot (195)" src="https://github.com/user-attachments/assets/5ff2068a-388d-49a6-b170-3e095b87f6d7" />

 In these screenshot you can see all the steps that i have applied.

 For the Second opinion i used Chat GPT to clean the Netflix Movies and TV shows Dataset, and it deliver the various methods that i have attached below:

 director, cast: Categorical, often unique → Fill with 'Unknown'

country: Categorical → Fill with mode (most frequent value)

date_added: Date → Fill with mode or a placeholder date like 'Unknown'

rating: Categorical → Fill with mode

duration: Categorical → Fill with mode 

All missing values in the dataset have been successfully handled using appropriate imputation techniques. The dataset is now clean and ready for further analysis or modeling.

<img width="1920" height="1080" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/5fdb9201-5cdd-4db4-8825-080e15c87c7e" />

I used two Datasets just for the practice purpose, i will be using only one dataset for the futher process.

Thankyou.
