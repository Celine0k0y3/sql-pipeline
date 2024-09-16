sql-pipeline.yml:

This pipeline s for SQL script dewployment. 
It outlines a CI/CD pipeine that automates the build, test and deployment of SQL scripts.
The breakdown of the pipeline stages:

Build: Compiled he SQL script into a deployable package.
Lint: Checks the SQL script for syntax errors and formatting issues.
Test Unit: Runs unit tests on the SQL script to verify its functionality.
Test Integration:  Runsintegration tests to ensure the SQL script works with other database components.
Deploy Dev: Deploys the SQL script to the Dev environment. 
Deploy Prod: Deploys the SQL script to the Prod environment. 
