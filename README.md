# Building a CI/CD Pipeline.

### Introduction
In this project, We will build a Github repository from scratch and create a scaffolding that will assist you in performing both Continuous Integration and Continuous Delivery. You'll use Github Actions along with a Makefile, requirements.txt and application code to perform an initial lint, test, and install cycle. Next, you'll integrate this project with Azure Pipelines to enable Continuous Delivery to Azure App Service.

We will perform continuous delivery for a Python-based machine learning application using the Flask web framework.

- Agile Project Management build CI CD Pipeline
![screenshot - Agile Project Management build CI CD Pipeline](./output_images/building-a-ci-cd-pipeline?raw=true)

### Dependencies
1. Create an [Azure Account](https://portal.azure.com) 
2. Install the [Azure command line interface](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
3. Create a [Github Account](https://www.github.com)

### Pre-requisites
1. Clone this repository
    - Launch Azure shell environment and create ssh-keys
        https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
    - Add ssh-keys to your github account
        https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account

### Getting Started
1. Continuous Integration: Set Up Azure Cloud Shell  
    - Refer to: : https://github.com/hikingbloke/azure-devops-ci-cd/tree/master/project-scaffolding
        Copy the files and push them to your git repo
    - Create Github actions for your git repository
        https://docs.github.com/en/actions/learn-github-actions
    - Youtube video for my demo:


2. Continuous Delivery on Azure
    - This will involve setting up Azure Pipelines to deploy the `Flask starter code` to Azure App Services.
        - Flask starter code 
            https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/tree/master/C2-AgileDevelopmentwithAzure/project/starter_files
        - Azure Pipeline - Setting up
            https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/pipelines-sign-up?view=azure-devops
    - Youtube video for my demo:

### Output

- Azure Cloud Shell git setup
![screenshot - Azure policy Tag creation](./output_images/1.azure-cloud-shell-git-setup-and-modify-files.png?raw=true)

- Python tests passing and using MAKE file
![screenshot - Python tests passing and using MAKE file](./output_images/2.passing-test-after-using-make-all.png?raw=true)

- Github Actions
![screenshot - Github Actions](./output_images/3.github-actions-continuous-integration.png?raw=true)

- Flask Web App deployed
![screenshot - Flask Web App deployed](./output_images/4.web-app-deployed.png?raw=true)

- Authorize permission for Azure pipeline
![screenshot - Authorize permission for Azure pipeline](./output_images/5.authorize-permissions.png?raw=true)

- Azure Pipeline deployment and status
![screenshot - Azure Pipeline deployment and status](./output_images/6.azure-pipeline-deployment-and-status.png?raw=true)

- Predcitions using script file
![screenshot - Predcitions using script file](./output_images/7.prediction-using-script-file.png?raw=true)

- Logs for Flask App
![screenshot - Logs for Flask App](./output_images/8.logs-for-running-application.png?raw=true)

- Detailed Logs for Flask App
![screenshot - Detailed Logs for Flask App](./output_images/9.logs-for-running-application.png?raw=true)