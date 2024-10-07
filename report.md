## Objective
The objective of this assignment is to introduce you to serverless computing and the use of cron jobs in cloud environments. You will deploy serverless functions on both Azure and Google Cloud Platform (GCP), and create a scheduled task using GitHub Actions.

## Instructions

### 1. Deploy a Serverless Function
- **Azure:**
  - Navigate to the Azure portal and create an Azure Function.
  - Choose a simple trigger (e.g., HTTP trigger) and deploy a basic function (e.g., "Hello, World").

![azure 1](https://github.com/user-attachments/assets/28a6c44e-111f-4e71-b2a8-5325fbe92875)
![azure 2](https://github.com/user-attachments/assets/1b050962-6cee-4071-afcc-bbbbca0e5eae)
![azure 3](https://github.com/user-attachments/assets/d3a2c851-bbe8-4b02-abe3-21ba96889125)

- **GCP:**
  - Access the Google Cloud Console and create a Google Cloud Function.
  - Deploy a similar function with an HTTP trigger in GCP.
    
![gcp 1](https://github.com/user-attachments/assets/ca912c4c-0866-4bee-b8eb-9eace8998113)
![gcp 2](https://github.com/user-attachments/assets/6b038c93-3f65-49c5-bef3-ee24a0bede2c)
![gcp 3](https://github.com/user-attachments/assets/50c7869e-3e56-44c1-93f5-5ee9f42dda27)


### 2. Create a Cron Job
- **GitHub Actions:**
  - Create a new GitHub repository (or use an existing one).
  - Set up a GitHub Action workflow that runs a script on a schedule (e.g., daily at midnight). You can use a simple script that logs "Scheduled task executed" to the console.
![cron job](https://github.com/user-attachments/assets/06e473a7-1aa1-49a3-9dec-09b7fa1f6d44)
![cron job1](https://github.com/user-attachments/assets/74c73619-c990-4242-bfd2-885455505ca6)


### 3. Explore Functions as a Service (FaaS)
- Reflect on the use cases for serverless functions in cloud environments. Consider the benefits and limitations of using Functions as a Service (FaaS) in both Azure and GCP.

### *Azure*
#### Benefits
* Automatic scaling based on demand in both Azure and GCP, FaaS eliminates the need for server management and other infrastructure.
* Pay per pricing or only for the execution time compared to the traditional VM-based environments.
#### Limitations 
* Have limited memory and execution time 
### *GCP*
#### Benefits 
** Automatic scaling based on demand in both Azure and GCP, FaaS eliminates the need for server management and other infrastructure.
* Pay per pricing or only for the execution time compared to the traditional VM-based environments.
* I prefer the GCP environment, more straightforword and easier to navigate.
#### Limitations
* Have limited memory and CPU, execution time
