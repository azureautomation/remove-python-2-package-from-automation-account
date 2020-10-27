Remove python 2 package from Automation account
===============================================

            




This Azure Automation runbook runs in Azure to remove a package from Azure Automation.
It requires the subscription id, resource group of the Automation account, Automation name, and package name as arguments.
Passing in * for the package name will remove all packages from the account.

Args:
    subscription_id (-s) - Subscription id of the Automation account
    resource_group (-g) - Resource group name of the Automation account
    automation_account (-a) - Automation account name
    module_name (-m) - Name of module to delete. Use * to remove all packages

    Removes module pytz
    Example:
        remove_python2package.py -s xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxx -g contosogroup -a contosoaccount -m pytz

Changelog:
    2018-10-04 AutomationTeam:
    -initial script

**






 




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
