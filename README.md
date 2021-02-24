# Azure DevOps authentication with device credential flow

1. Create an app registration in your Azure Active Directory. Enable you app to be public/native to not require a callback URL. Add API permissions for Azure DevOps.
2. Make sure to connect Azure DevOps with your active directory
3. Call you API by starting this console app with "dotnet run --tenant-id {your tenantId} --client-id {clientId from your app registration from step 1} --org-name {name of your devops organization}"
