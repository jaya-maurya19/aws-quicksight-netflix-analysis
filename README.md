## Amazon QuickSight Netflix Analysis  

### Introduction  
This project explores how **Amazon QuickSight**, a data analytics service, can be used to visualize datasets using graphs and charts.  

### Project Overview  
I used **Amazon QuickSight** to analyze the **Netflix dataset**, applying filters and creating interactive visualizations.  

### Unexpected Discovery  
One interesting feature I found was the ability to **share and download dashboards** directly from QuickSight.  

### Time Taken  
The entire project, including documentation, took me **over 2 hours**.  

---

## Steps to Implement  

### 1️⃣ Uploading project files to S3 bucket 
- The dataset consists of two files: **netflix-dataset.csv** and **manifest.json**.  
- After uploading these files to **AWS S3 bucket**, I updated the **S3 URI** in `manifest.json` to ensure correct access.  

![image](https://github.com/user-attachments/assets/005fce49-9293-4534-b6c7-5bdb66dccfda)


### 2️⃣ Setting Up QuickSight Account
- Creating a **QuickSight account** is free with a **30-day trial**.  
- The setup took **2-3 minutes**, including **granting permissions** to access the S3 bucket.

  ![image](https://github.com/user-attachments/assets/e1336d38-2d05-4c59-810c-195551a97537)


### 3️⃣ Connecting the Dataset  
- I connected **S3 to QuickSight** by copying the **manifest.json file URL** into the **S3 data source field**.  
- The `manifest.json` file tells QuickSight how to process the dataset for visualization.

  ![image](https://github.com/user-attachments/assets/b1366598-cac6-48a7-b3a8-e1ba0e7e04ad)


### 4️⃣ My First Visualization
- I dragged relevant fields into the **AutoGraph area** in QuickSight.  
- Example: **Movies vs. TV Shows per release year**  
  - **X-axis:** Release Year  
  - **Grouping Variable:** Movie or TV Show  

![image](https://github.com/user-attachments/assets/30310010-a072-43e5-a611-92c41e27233a)


### 5️⃣ Using Filters  
- Filters help refine data, focusing on **specific subsets** while **excluding irrelevant information**.  
- Example: I filtered **movies & TV shows from 2015 onwards**, removing older data.

  ![image](https://github.com/user-attachments/assets/7ece17c0-699c-40f5-90b7-b5598f55d90a)


### 6️⃣ Setting up the Dashboard  
- I adjusted **titles and labels** to make the graphs clear.  
- **QuickSight allows exporting dashboards as PDFs**, making sharing easy.  

![image](https://github.com/user-attachments/assets/ffb43ba9-8cc0-4f4f-b23b-eeca836dcf8d)

