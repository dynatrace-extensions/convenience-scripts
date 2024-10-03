# [Oracle Database extension][hub tile]

In this folder:
* User setup scripts
    * [user_setup_multitenant.sql][user_setup_multitenant_link]
    * [user_setup_nonmultitenant.sql](https://github.com/dynatrace-extensions/convenience-scripts/blob/main/oracle-db/user_setup_nonmultitenant.sql)

## Extension user setup

The scripts [user_setup_multitenant.sql][user_setup_multitenant_link] and [user_setup_nonmultitenant.sql][user_setup_nonmultitenant_link] provided in this folder will create a user with the required permissions for the Oracle Database monitoring extension to work fully. Run only the script for your database setup, either multitenant or non-multitenant. For multitenant setups, the user should be created at the CDB level. Refer to the [official documentation][hub tile] for more details.

Before running the scripts, ensure that you replace `<DYNATRACE_USER>` and `<PASSWORD>` with the appropriate values. 

[hub tile]: https://www.dynatrace.com/hub/detail/oracle-database/
[user_setup_multitenant_link]: user_setup_multitenant.sql
[user_setup_nonmultitenant_link]: user_setup_nonmultitenant.sql