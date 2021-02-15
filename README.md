# Building Continuous with Delivery Azure Pipeline.

### Introduction
In this project, We will build a Github repository from scratch and create a scaffolding that will assist you in performing Continuous Delivery. You'll integrate this project with Azure Pipelines to enable Continuous Delivery to Azure App Service.

We will perform continuous delivery for a Python-based machine learning application using the Flask web framework.

Your webapp has a pre-trained, sklearn model that has been trained to predict housing prices in Boston.

### Dependencies
1. Create an [Azure Account](https://portal.azure.com) 
2. Install the [Azure command line interface](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
3. Create a [Github Account](https://www.github.com)

### Pre-requisites
1. Set Azure Cloud Shell environment and integrate Github repository communication.
    - Launch Azure shell environment and create ssh-keys
        https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
    - Add ssh-keys to your github account
        https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account

### Getting Started
1. Continuous Delivery on Azure
    - This will involve setting up Azure Pipelines to deploy the `Flask starter code` to Azure App Services.
        - Flask starter code 
            https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/tree/master/C2-AgileDevelopmentwithAzure/project/starter_files
        - Azure Pipeline - Setting up
            https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/pipelines-sign-up?view=azure-devops

    - Youtube video for my demo:

### Output

- Azure Cloud Shell git setup
![screenshot - Azure policy Tag creation](./output_images/1.azure-cloud-shell-git-setup-and-modify-files.png?raw=true)

- Flask Web App deployed
![screenshot - Flask Web App deployed](./output_images/4.web-app-deployed.png?raw=true)

- Authorize permission for Azure pipeline
![screenshot - Authorize permission for Azure pipeline](./output_images/5.authorize-permissions.png?raw=true)

- Azure Pipeline deployment and status
![screenshot - Azure Pipeline deployment and status](./output_images/6.azure-pipeline-deployment-and-status.png?raw=true)

- Predcitions json output
![screenshot - Predcitions json output](./output_images/7.prediction-json-output.png?raw=true)

- Logs for Flask App
![screenshot - Logs for Flask App](./output_images/8.logs-for-running-application.png?raw=true)

- Detailed Logs for Flask App
![screenshot - Detailed Logs for Flask App](./output_images/9.logs-for-running-application.png?raw=true)