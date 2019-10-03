# actions-demo

1. Create azure resources either through azure portal or az cli. In this case app service with node runtime stack and postgres SQL. 
   The workflow yaml contains az cli scripts for the same.
   
2. Set app settings for postgres connection string in app service as defined in application readme.

3. In postgres SQL enable connection to Azure services.

4. Copy application code in a github repo and add your workflow under .github/

5. Use webapps-deploy to deploy. Workflow contains other details.
