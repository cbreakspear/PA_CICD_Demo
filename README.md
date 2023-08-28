# PA_CICD_Demo
Demo repo for customer EMCOR

STEP 1: Create a gitHub Key
STEP 2: Create an Azure Key from the Powerapps Admin section. Also get the Solution ID and the Client ID of the application
STEP 3: Fill in all the Action secrets with the values gathered in the workflow files
STEP 4: Export and Branch Solution runs first as a RUN.
STEP 5: Create a release which will run release to action call workflow which will package up the DevEnvironment and push to Production
