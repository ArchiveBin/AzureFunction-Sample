# AzureFunction-Sample

## What is repo is for?

- Azure function creation was failing using the VSCode extension and couldnt find any Microsoft repository with actual sample function for the host.json, function.json, etc files.

## Steps to run and deploy Azure function
- [Follow these steps](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local)
- [Install the Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Cnode%2Cportal%2Cbash#install-the-azure-functions-core-tools)
- [Create a function](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Cnode%2Cportal%2Cbash#create-func)
- Test locally with npm run start and deploy using CLI or VSCode extension
- If using extension then select 'sample' folder in this repo as the folder to deploy to function.
- Remove the '.vscode' settings folder if you want to deploy some other folder then while deploy the extension will again ask for the function location.

- This repo contains the sample code just for the Javascript version. 