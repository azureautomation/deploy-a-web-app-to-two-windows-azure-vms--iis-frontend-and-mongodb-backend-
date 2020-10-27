Deploy a Web App to Two Windows Azure VMs (IIS Frontend and MongoDB Backend)
============================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Creates two virtual machines; a front-end Windows Server and a back-end MongoDB server.


The front-end server is configured with the Web Platform Installer, which is then used to install IIS.


The back-end MongoDB server is configured with two additional data disk; one for data and another for log files.


Both Virtual Machines are placed in a single subnet.

Example
 
Scenario
You need to create an environment with and IIS front-end server and a MongoDB back-end server.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  Get-AzureVMImage 
  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
