# Oracle Database extension user setup scripts
The two scripts provided in this folder will create a user with the required permissions for the Oracle Database monitoring extension to work fully. Run only the script for your database setup, either multitenant or non-multitenant. For multitenant setups, the user should be created at the CDB level.

Before running the script, ensure that you replace \<DYNATRACE_USER\> and \<PASSWORD\> with the appropriate values. 