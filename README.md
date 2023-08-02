# Medical_Student_Task4

# Introduction
This task was preceded by the session on pivot tables, where we looked at what a pivot table is, its use and how to use it to summarize our data to gain insights. In this session on the use of Excel, a medical student dataset was provided by the instructor Promise Chinonso which contained 13 columns and 200001 rows of information

# Task
The head of the medical department needed information about the health and lifestyle of students in the department. He decided to carry out research with the use of an online survey to know how the heart rate, temperature, age etc of his students and to know how many are living a diabetic-free life and those who engage in smoking. With respect to this, the following insights should be generated and visualized;
1. What is the average Age, BMI, Blood pressure, Heart rate, Temperature and Cholesterol
2. What is the average height and weight for both genders
3. Number of students across each blood group
4. Number of students who smoke and those who don't
5. Number of students with and without diabetes

# Skills Demonstrated
1. Use of pivot tables
2. Use of column and doughnut chart for visualization
3. Data manipulation skills
4. Use of basic and advanced Excel functions

# Raw Data
![Screenshot (28)](https://github.com/Yomeh/Medical_Student_Task4/assets/140501792/c27312dc-8845-4edc-93e7-02f1c1fe1919)

# Data Cleaning
![Screenshot (26)](https://github.com/Yomeh/Medical_Student_Task4/assets/140501792/6d69baec-117f-4630-a8b2-31cfe7b847a8)
![Screenshot (23)](https://github.com/Yomeh/Medical_Student_Task4/assets/140501792/f6f3d3b7-4803-4bf9-96a0-238ccb319fc4)
The dataset provided displayed above was an incomplete dataset as it had empty cells and missing values across the columns. The dataset was made up of the following column; Student ID, Age, Gender, Height, Weight, Blood type, BMI, Temperature, Heart rate, Blood pressure, Cholesterol, Diabetes, and Smoking. The dataset was cleaned up through the following process:
1. The student id column was automatically filled by highlighting the column and filling it up with the appropriate number by double-clicking the small square displayed at the edge of the cell.
2. I used the AVERAGE function to calculate the average age in the dataset and filled up the blank cells on the age column with the value gotten.
3. The gender column was populated by calculating the mode, the number of females and males were both counted using the COUNTIF function and then the gender with the highest number of counts was taken as the mode value and used to fill up the empty cells in the gender column.
4. The height** and weight column contained blank cells which were filled up by getting the average of each column. The height column was further formatted by dividing by 100 and formatted to 2 decimal places.
5. The blanks in the blood type were filled by counting the number of occurrences of each blood type using the COUNTIF function and then selecting the blood type with the highest number of occurrences.
6. The BMI known as Body Mass Index was calculated by dividing the weight by the height squared, and it was formatted to 2 decimal places.
7. The temperature, blood pressure, cholesterol, and heart rate columns were formatted to 2 decimal places and the blanks within the columns were filled with the averages of each column.
8. The blanks within the diabetes and smoking column were filled with the value gotten from counting the values of each column and picking the value with the highest occurrences through each column.

# Pivot Table
![Screenshot (24)](https://github.com/Yomeh/Medical_Student_Task4/assets/140501792/460c1977-1d9f-470d-8d01-bb5b2ffae59f)
After cleaning the dataset, a pivot table was used to summarise the data and generate our required insights.

# Visualization
![Screenshot (27)](https://github.com/Yomeh/Medical_Student_Task4/assets/140501792/d9a872d1-1355-47d5-9283-fd43977527d4)
From the pivot table, the insights were represented using a **column chart** and a **doughnut chart**.
1. The visualisation shows that the male student is at an average height of 174.97 which makes them taller than the female gender meanwhile, the female gender weighs more than the male students
2. The blood type visualisation shows that the large population of students belong to the O blood type
3. Finally, we have fewer smokers and diabetic students among the student population.

# Conclusion
I was able to demonstrate some basic data-cleaning skills, my ability to use basic Excel functions, and my data visualisation skills and overall it was an engaging task.

