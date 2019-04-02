# helm eShop


# ubuntu powershell howto

# Deployment settings

    [parameter(Mandatory=$false)][string]$registry,
        [parameter(Mandatory=$false)][string]$dockerUser,
	    [parameter(Mandatory=$false)][string]$dockerPassword,
	        [parameter(Mandatory=$false)][string]$externalDns,
		    [parameter(Mandatory=$false)][string]$appName="eshop",
		        [parameter(Mandatory=$false)][bool]$deployInfrastructure=$true,
			    [parameter(Mandatory=$false)][bool]$clean=$true,
			        [parameter(Mandatory=$false)][string]$aksName="",
				    [parameter(Mandatory=$false)][string]$aksRg="",
				        [parameter(Mandatory=$false)][string]$imageTag="latest",
					    [parameter(Mandatory=$false)][bool]$useLocalk8s=$false
