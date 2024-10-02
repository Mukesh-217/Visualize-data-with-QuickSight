# Visualize-data-with-QuickSight

DESCRIPTION:

Amazon QuickSight helps you analyse data and create visualisations easily. Today we're going to analyse a huge dataset of Netflix shows and movies to create a dashboard that extracts all the juicy insights. 

OBJECTIVE:

The objective of this project is to utilize Amazon QuickSight to analyze a large dataset of Netflix shows and movies, and create an interactive dashboard that provides valuable insights. The dashboard will enable users to explore data through visualizations, identify trends, and make informed decisions based on key metrics such as genre popularity, content ratings, production years, and regional distributions. This project aims to showcase how Amazon QuickSight simplifies data analysis and visualization processes for large datasets.

SERVICES UTILIZED:

1. Amazon S3: Amazon S3 (Simple Storage Service) is a scalable, secure, and durable cloud-based object storage service that allows users to store and retrieve any amount of data from anywhere on the web. It is commonly used for data backup, archiving, hosting static websites, and serving files, while integrating seamlessly with other AWS services, making it ideal for data lakes, big data analytics, and machine learning.
2. Amazon QuickSight: Amazon QuickSight is a cloud-based business intelligence and data visualization tool that enables users to create interactive dashboards and reports. It allows organizations to analyze data from various sources, generate insights, and share visualizations with teams, all without needing extensive infrastructure or technical expertise. QuickSight is designed for scalability, offering self-service analytics and machine learning-powered insights.

IMPLEMENTATION STEPS:

1. Log into your AWS Management Console.
2. Create a S3 Bucket. Upload the csv and json file into the S3 bucket.
3. Copy the url of csv file and place it in json file and reupload the json file.
   
   ![image](https://github.com/user-attachments/assets/c10fe5ab-4c98-4e55-ab33-5bef5e21d18d)
   
4. Search for Amazon Quicksight and select Signup with QuickSight.
5. Sign up for a free trial of the Enterprise edition if you don't have an account. Select Amazon S3 and then Select the S3 bucket. Click on Create.
6. From the left hand navigation bar, select Datasets then New Dataset, Select S3.
7. Open a new tab to open your AWS Management Console again. Head back to your S3 bucket. Select the checkbox next to json file then select Copy S3 url.

 ![image](https://github.com/user-attachments/assets/2a5c0824-7553-44eb-8457-98ff67d9b51b)

8. Select Connect --> Select Visualize.
9. Select Interactive sheet to start creating visualisations. Drag fields into the graph to create visualisations.
   
   ![image](https://github.com/user-attachments/assets/8c72996e-2b94-4a4f-b0da-861e5ed38f53)


FINALIZED OUTPUT:

![image](https://github.com/user-attachments/assets/eeca49e1-629f-4054-a396-f50e833c11ed)
