### Dom Heallis 040728287
### Lab 4

# Step 1: Upload Data to Azure Data Lake 

created container named raw
![alt text](image.png)

uploaded files into container
![alt text](image-1.png)

copied files into their appropriate directories
![alt text](image-2.png)

![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)

# Step 2: Explore Data using Serverless SQL

original script with files outside of directory
![alt text](image-7.png)

modified script because files are in folders
![alt text](image-6.png)

addingf a filer WHERE year > 2022
![alt text](image-8.png)

# Step 3: Explore Data using Spark Notebook

Fixed path by removing .parquet, and instead looked at specific files like customers
![alt text](image-9.png)

if i looked at all the .parquet files, it was giving me null answers. I think because each schema had different columns?
![alt text](image-10.png)

# step 4

Original row count
![alt text](image-11.png)

 removing duplicates
 ![alt text](image-12.png)

 function to make sure every customer id only appears once
 ![alt text](image-13.png)

 # step 5

 using signup date instead of event_time for customers file
 ![alt text](image-15.png)

 # step 6

 Fixing data type, by seperating year and months
 ![alt text](image-14.png)

 # step 7

 ![alt text](image-18.png)

# step 8

![alt text](image-16.png)

# Step 9: Analyze & Visualize Data 

![alt text](image-17.png)

# step 10 delete everything

![alt text](image-19.png)

