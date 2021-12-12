# Basic Azure Static Web App Tutorial

In this tutorial we are going to build an Azure Static Web App that is protected with SSO via Azure.

## Step 1
Create yourself an Azure Static Web App and register it with GitHub or Azure DevOps for publishing.
Do create an index.html as your blank landing page.

## Step 2
Register yourself an Azure AD Application registration as described [here](https://docs.microsoft.com/en-us/azure/app-service/configure-authentication-provider-aad#-option-2-use-an-existing-registration-created-separately).

## Step 3
Update the staticwebapp.config.json with your tenant ID and make your way into the Azure Static Web App configuration section. Enter here

- AAD_CLIENT_ID (client id)
- AAD_CLIENT_SECRET (client secret - not secret id)

with the information that you received from Step 2.

## Step 4
Update your routes in staticwebapp.config.json to adjust for /login and /logout.
