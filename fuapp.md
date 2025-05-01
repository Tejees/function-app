# Create an function which triggers name and size of the image 


## Overview

Azure Functions is a serverless solution that allows you to write less code, maintain less infrastructure, and save on costs. Instead of worrying about deploying and maintaining servers, the cloud infrastructure provides all the up-to-date resources needed to keep your applications running.

## Task to be Done

1. Create a Function App 
1. Create a Blob triggered function 


## Task 1 : Create a Function App

1.From your local machine, search for Visual Studio code and open it.

  ![](https://github.com/Tejees/function-app/blob/main/0.png)

2. Once the Visual studio code is open, follow the below mentioned steps:

   -  Press `cntrl + shift + P` **(1)**
   -  On search bar, enter **Azure sign in (2)**
   -  Click on **Azure Sign In (3)**
   ![](https://github.com/Tejees/function-app/blob/main/1.png)

3. Once sign into the azure, Follow the below Steps

   - Search for **Azure Functions: Create a project (1)**
     ![](https://github.com/Tejees/function-app/blob/main/3.png)

4.In Creation of Project
   - **Browse a folder to insert the code(1)**
     ![](https://github.com/Tejees/function-app/blob/main/4.png)
   - Select a Language **Python (2)**
     ![](https://github.com/Tejees/function-app/blob/main/5.png)
   - Choose the Version of that Language **Python Version 3.11.9 (3)**
     ![](https://github.com/Tejees/function-app/blob/main/6.png)
   - Select the Template **Blob Trigger (4)**
     ![](https://github.com/Tejees/function-app/blob/main/7.png)
   - Name the Function You want to create **Blob Trigger (5)**
     ![](https://github.com/Tejees/function-app/blob/main/8.png)
   - The path within the storage account that the trigger will moniter **Select the container in the Storage (6)**
     ![](https://github.com/Tejees/function-app/blob/main/9.png)
   - **Create a local app String (7)**
     ![](https://github.com/Tejees/function-app/blob/main/10.png)
   - **Select the Subscription (8)**
     ![](https://github.com/Tejees/function-app/blob/main/11.png)
   - Select a storage account type for development **Use Azure Storage for remote storage (9)**
     ![](https://github.com/Tejees/function-app/blob/main/12.png)
   - **Select the Storage Account (10)**
     ![](https://github.com/Tejees/function-app/blob/main/13.png)
   - Select How you would like to open your project **open in current window (11)**
     ![](https://github.com/Tejees/function-app/blob/main/14.png)
   
  
 5. **Now Environment is ready**
     ![](https://github.com/Tejees/function-app/blob/main/15.png)
   
   - **Navigate to local.settings.json (1)**
     ![](https://github.com/Tejees/function-app/blob/main/16.png)

6. Navigate to Azure Portal
   - **Click Azure Storage Accounts (1) (2)**
   - **In Storage Accounts click on Access keys (3)**
   - **Then copy the connection string value (4)**
     ![](https://github.com/Tejees/function-app/blob/main/17.png)

7. Again Navigate to local.settings.json in vs code
   -**Copy the connection string in AzureWebjobstorages (1)**
    ![](https://github.com/Tejees/function-app/blob/main/18.png)

8. Open Terminal in Vs code
   -**Navigate to Terminal in vscode and give command --Func start-- (1) (2)**
    ![](https://github.com/Tejees/function-app/blob/main/19.png)

9. Output
   - **Function Triggers (1)**
     ![](https://github.com/Tejees/function-app/blob/main/20.png)

10. Python blob Trigger function processed blob name
    -**Blob name and size exists (1)**
     ![](https://github.com/Tejees/function-app/blob/main/21.png)

11. Coming to Azure portal
    -**Sign into the Azure portal**
     ![](https://github.com/Tejees/function-app/blob/main/22.png)

12. Navigate to Search bar in azure portal
    -**In Search bar search Azure Functions and click it (1) (2)**
     ![](https://github.com/Tejees/function-app/blob/main/23.png)

13. In the Funtion App
    - **click on +Create (1)**
      ![](https://github.com/Tejees/function-app/blob/main/24.png)

14. Hosting plans will be displayed
    - **In the hosting plans choose consumption and select it (1) (2)**
      ![](https://github.com/Tejees/function-app/blob/main/25.png)
 
