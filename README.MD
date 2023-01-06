davisdre linkshortner

using WSL on windows 11.

1. created a azure function in VS code via Azure extension.
2. create a azure sql database
- https://learn.microsoft.com/en-us/azure/azure-sql/database/free-sql-db-free-account-how-to-deploy?view=azuresql
- installed azure data studio
- Created a read only DB user to be used for connection string
    - https://www.studyyourdata.com/2019/04/creating-logins-and-users-in-azure.html
3. created azure function, shortner, via azure function extension. using HTTP trigger
4. updated index.js template
5. deploy function. 
6. test/run function in azure portal
7. go back and install npm install mssql locally on your machine in your directory
8. re-deploy function.
9. add 'readme.md' to .funcignore to remove file from being uploaded to function.
10. re-deploy function with latest files.
11. add new application settings, 'SqlConnectionString', via azure functions extension tools
12. create a API management service instances
- https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance
13. Update function.json to only do 'get' http triggers
- re-deploy function with latest files.
14. https://davisdrelinkshortner.azurewebsites.net/api/shortner?path=


https://user-images.githubusercontent.com/18203393/211223242-32aad8bf-2412-4eca-9cec-2a0bb67fe195.mp4

Technologies used:
- Azure Functions
- Azure SQL Database

Notes:

Was going to use Azure API Management Service due to Azure Functions Legacy Proxy is legacy now and promote to use the new Azure API service, was having issues with getting that resolved, but still proud of what I setup and will go back adventually to get Azure API integrated. 