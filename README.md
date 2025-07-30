# DATA-PIPELINE-DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DNYAN VINOD LANJEKAR

*INTERN ID*: CT04DZ1304

*DOMAIN*: DATA SCIENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##I decided to do this assignment in Jupyter Notebook because it makes step-by-step testing easy and allows you to include explanations along with your code. I made a dummy dataset that had columns such as Name, Age, Gender, and Salary. Values in Age and Salary were missing in some cases, and Gender contained text values such as "Male" and "Female." These are extremely common problems in real datasets, so it was a good practice example.

I employed two primary Python libraries to create the pipeline, namely Pandas and Scikit-learn. Pandas assisted me in reading the CSV file and handling the dataset in tabular form. I loaded the file into a DataFrame by using read_csv(). I employed Scikit-learn tools for data cleaning. I first addressed the missing values in Salary and Age through SimpleImputer, which filled the missing values with the mean of the column. Secondly, I applied LabelEncoder to translate the text values in the Gender column into numbers since machine learning algorithms don't accept text. Then, I normalized the Age and Salary columns through StandardScaler such that all the figures fell within a similar range, making it easier to train models subsequently.

Once all the steps were complete, I saved the end cleaned dataset as a new file named clean_data.csv. This finished the ETL process — I had extracted the data, transformed it, and loaded the final output. The pipeline that I constructed is completely reusable and can easily be adjusted to be applied to other datasets.

This assignment made me realize how much a necessity it is to clean and prepare data prior to using it. I was taught how to correct missing values, transform words into numbers, and properly scale numeric data. I also learned how Python libraries such as Pandas and Scikit-learn simplify this job. In general, this exercise provided me with hands-on experience in the construction of a simple yet efficient data pipeline, and I am more assured about handling data in actual projects now. It was an excellent learning experience that enhanced my coding, as well as my knowledge of data science fundamentals.

#OUTPUT

<img width="922" height="551" alt="Image" src="https://github.com/user-attachments/assets/21f77e7d-38f8-4532-ac80-19a2687a959f" /> 
