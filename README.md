# Diabetes-Data-Analysis-Project

An overview of diabetes data analysis focused on leveraging big data for improved understanding, management, and treatment of diabetes. The project aims to harness the power of large-scale data sets to extract meaningful insights, identify patterns, and develop personalized strategies to enhance disease management and optimize patient outcomes. Due to high junk food consumption, the diabetes rate is highly increasing nowadays.

1.	Data collection and Integration- This involves the collection of Diabetes data and what are the attributes that have been identified in order to achieve this analysis and with the integration of these data, how it is useful to create a comprehensive and multifaceted view of data.

2.	Data Warehousing and Modeling- In order to do data warehousing, MongoDB compass is used and stored the collections under the Diabetes database.

3.	Database Implementation- Database implementation refers to the process of creating and setting up a database system to store, manage, and retrieve data efficiently. To gather requirements by understanding the data needs of the organization or application. This involves identifying the types of data to be stored, and the relationships between different entities.

4.	MongoDB queries- From inserting a document into the collection to doing a query for it by using find() method and providing a powerful aggregation framework for data processing. 

5.	Data Visualization and Insights- Then Data visualization is done using Python and gained insights by analyzing significant factors that affect diabetes.

#####Data warehousing and modeling in MongoDB###################3
Database and Collections
There are four collections made in the database Diabetes_data in MongoDB Compass:
1.	Diabetes Patient Data
2.	Patient Data (30)
3.	Blood group
4.	Patient Personal Data

   ![image](https://github.com/user-attachments/assets/e2ca849e-aeff-41a6-8b85-edb9873cb682)

   Diabetes_Patient_Data collection includes 16000 documents and each document has data such as Patient gender, age, hyper_tension, heart_disease, smoking_history, bmi, hba1c level, blood glucose level, and Diabetes as the Boolean variable contains values as 0 and 1, 0 indicates negative diabetes and 1 indicates positive diabetes. Details are given in the below figure:

   ![image](https://github.com/user-attachments/assets/5a8cecc3-bc26-48a6-9bec-bb3fc8325125)
![image](https://github.com/user-attachments/assets/91f1f4bf-543c-4d22-837f-c921110acf1f)

![image](https://github.com/user-attachments/assets/04956a19-0f0a-4cae-9792-4c30f7bf6949)

1.	Find all the patients where age is less or equal to 35.
{age:{$lte:35}}
![image](https://github.com/user-attachments/assets/f204fd08-f124-4ace-8ca9-127a0013768c)
2.	Find the total number of diabetic patients and non-diabetic patients from the collection.
   ![image](https://github.com/user-attachments/assets/a16c5f5d-c08b-4d63-838e-79e494dd6f59)

   Research Questions
There are 4 research questions identified based on the dataset.
1.	Does gender have an impact on diabetes?
2.	Is Age an affecting factor for diabetes?
3.	Is heart disease associated with an increased risk of developing diabetes?
4.	Is smoking also a risk factor for diabetes?
![image](https://github.com/user-attachments/assets/d4e683a6-c3c9-4f85-b3a3-4061ba6c9e9f)
![image](https://github.com/user-attachments/assets/1f041e8e-4ed3-4df9-a81c-ca90733761f0)
![image](https://github.com/user-attachments/assets/a1000cd0-034c-4b57-a0f0-abc723faa033)
![image](https://github.com/user-attachments/assets/e3bb0b57-4362-42e4-89d2-0166132bc193)
![image](https://github.com/user-attachments/assets/6ec0eea0-f6cf-4728-a941-0f114c19bdd6)
![image](https://github.com/user-attachments/assets/1eab66cc-3be3-40e8-9594-38351a7b2976)
![image](https://github.com/user-attachments/assets/f4e74601-9f27-48d6-9038-e18bf1c49eac)







