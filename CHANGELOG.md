# v3.0.0 - 2020-07-30

Breaking
  * AZ-198: Upgrade to AzureRM >= v2.0
 
Added
  * AZ-242: Allow to manage MSI on the app function
  
# v2.2.0 - 2020-07-30

Added
  * AZ-201: Allow to use function app v3
  
Breaking
  * AZ-238: Remove `create_storage_account_resource` and `create_application_insights_resource` variables. Now resources are created if `storage_account_connection_string` is `null` and `application_insights_instrumentation_key` is `null`. 
   
# v2.1.0 - 2020-02-17

Added
  * AZ-169: Storage Account - allow to configure account\_kind (default to StorageV2), enable\_https\_traffic\_only (default to false) and enable\_advanced\_threat\_protection (default to false)

# v2.0.1 - 2019-11-15

Fixed
  * AZ-118: Documentation update for public release

# v2.0.0 - 2019-11-14

Breaking
  * AZ-94: Upgrade module to terraform 0.12 / HCL2

# v1.1.0 - 2019-05-15

Added
  * AZ-78: Windows support

# v1.0.0 - 2019-04-23

Added
  * AZ-47: First release
