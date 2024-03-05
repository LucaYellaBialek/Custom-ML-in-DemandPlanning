# Custom-ML-in-DemandPlanning
## Introduction 
This project aimed to serve as a bridge between Costom ML models developed in Azure ML and the Dynamics 365 Demand Planning. It is supposed to guide you thought the process of creating your own Custom forecasting model in Azure ML and how to use it in demand planning. The Documentation consists of this ReadMe file, a scoring script, a Docker file and demonstrative videos. Use the files to easily set up your own Custom ML.
## End-to-end
### Set up
1. Go to https://ms.portal.azure.com/#home > Azure Machine Learning > Launch studio
2. Create  Workspace
3. In that Workspace set up  Compute Clustor
   > Compute > Compute Cluster > +New

For more information go to https://learn.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources?view=azureml-api-2
### Gettign started 
1. Create an envrionmemnt
   > Environment > Custom Envionments > +Create
2. Create the Scoring Script using the file attached
3. Register a model
   > Models > +Register
4. Create an Endpoint
   > Endpoints > Batch Endpoints > +Create
5. Add Deployment
   > your endpoint > +Add deployment
### use your Custom ML in Demand Planning
Go to  https://learn.microsoft.com/en-gb/dynamics365/supply-chain/demand-planning/custom-azure-machine-learning-algorithms

1. Set up a third party App
2. Assign access to workspace and storage account
3. Connect to Azure ML Service frm Demand Planning
4. Set up a forecast using your Custom ML
   
