# -DATA-CLEANING-WITH-PYSPARK

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MANASVI KISAN PAWAR

*INTERN ID*: CT08DN290

*DOMAIN*: BIG DATA

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

The first task focuses on cleaning and preprocessing a large dataset using PySpark, which is Apache Spark’s Python API. This task is essential because real-world datasets are often incomplete, inconsistent, or
filled with duplicates and null values, making them unsuitable for immediate analysis.
In this task, the Titanic dataset was used as a sample dataset for illustration. It included typical data issues like missing values in columns such as "Age" and "Embarked", and potential duplicate entries. The
dataset was loaded using a SparkSession and was initially examined to understand its structure and inconsistencies.
The first step was removing duplicates using the dropDuplicates() method to ensure no repeated records skewed the analysis. Following this, missing values were handled in two primary ways. For critical columns like
"Age", "Fare", and "Embarked", records containing nulls were dropped using the na.drop() method to ensure the dataset remained clean and reliable. Alternatively, in practical scenarios, these values can also be
filled using mean imputation or forward filling, but for the sake of clarity and simplicity in this internship, null-dropping was used.
The cleaned dataset was then previewed and saved using Spark’s built-in write functionality. This cleaned data serves as a strong foundation for further analysis, such as filtering, aggregations, or machine
learning model building. This task illustrated how PySpark provides scalable and distributed methods for handling large-scale data cleaning jobs that go beyond what traditional pandas or Excel-based solutions can
manage.
Overall, the output of this task was a cleaned, duplicate-free, and null-free dataset that could be reliably used in downstream analytical pipelines. This task demonstrates not only the technical skills of handling
PySpark but also the analytical thought process required to prepare real-world data for analysis.

#OUTPUT

<img width="785" height="847" alt="Image" src="https://github.com/user-attachments/assets/287ab9e7-b8c0-4433-89e9-09eda7804ce6" />
