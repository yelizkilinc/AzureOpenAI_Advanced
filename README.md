# AzureOpenAI_Advanced
Azure OpenAI Advanced Materials
Pre-requisites: 

Azure ML Workspace 

Compute Instance per attendee 

AOAI Resource and AOAI models deployed 

Bing Resource  

Azure OpenAI POC VBD Set Up 

 

 

Check which AOAI models are deployed on your resource. If there is no deployment, Azure Open AI Studio->Deployments-> Create new Deployment:  gpt-4 (0125 Preview) and gpt-35-turbo (0301) and gpt-4o(global deployment) in the UK South Region.  

Note your deployment names 

Open Azure Machine Learning Studio and navigate to Notebooks and Start your Compute Instance and Open the terminal 

Git clone the given repo on terminal 

Run "git clone https://github.com/yelizkilinc/AzureOpenAI_Advanced.git" command 

Make sure you run the notebooks on a Python 3.10 conda enviroment 

Install the dependencies on your machine (make sure you do the below pip command on the same conda environment that you are going to run the notebooks. For example, in AZML compute instance run: 

Open Terminal and run first 

cd AzureOpenAI_Advanced 

Then 

conda activate azureml_py310_sdkv2 

pip install -r ./common/requirements.txt 

Edit the file credentials.env with your own values: Azure Portal->Azure OpenAI Resource->Keys and Endpoint 

AZURE_OPENAI_ENDPOINT 

AZURE_OPENAI_API_KEY 

A screenshot of a computer

Description automatically generated 

 

Create Bing resource: Azure Portal-> Bing Resources->Add “Bing Search”->Review and Create 

 BING_SUBSCRIPTION_KEY 

A screenshot of a login form

Description aut