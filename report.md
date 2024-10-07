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
    

### 3. Explore Functions as a Service (FaaS)
- Reflect on the use cases for serverless functions in cloud environments. Consider the benefits and limitations of using Functions as a Service (FaaS) in both Azure and GCP.

### *Azure*
#### Benefits
* They are cost-effective as they have option of consumption plan which has defaulty pricing based on actual usuage as well as pay-per-execution meaning you only pay for the resources during the execution
* They are able to autoscale based on demand
* Contain quick develoment which allow users to quickly deploy functions and contain many programming language support such as python, java, and C#
* Contain Development tools such as visual studio, azure functions core tools and azure portal integration
* Have multiple plans such as consumption, premium, app service to fit each indivudal's needs
#### Limitations 
* Has an execution time limit of maximum 10 mins for consumption plan
* Have limited memory and execution time 
### *GCP*
#### Benefits 
* They are cost-effective as they have option of pay per pricing which allow you to only pay for the time your functions are executed and no infrastructure management which eliminates costs associated with managing servers or infrastructure
* Contains seamless scaling allowing automatic scaling based on demand
* Contain rapid development allowing developer to quickly deploy functions without the overhead of server management and have several programming languages such as Node.js, Python, Go, Java, and .NET
* Is integrated with GCP Services such as Pub/Sub, Cloud Storage, Firestore and supports HTTP triggers, background events from GCP services, and third-party webhooks
#### Limitations
* Has an execution time limit of maximum 9 mins
* Have limited memory and CPU as they are limited up to 2 GB of memory
