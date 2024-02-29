# Operationalize-MSSQL-Backups-With-Rubrik-Security-Cloud
Operationalize MSSQL Backups With Rubrik Security Cloud

This set of notebooks is desgined to take you through the steps to automate and operationalize common tasks DBAs will do day-to-day. 

# Familarize yourself with GraphQL and our APIs
- [Rubrik Security Cloud](https://www.rubrik.com/blog/technology/23/1/rubrik-security-cloud-transition-from-rest-to-graphql-api): Transition from REST to GraphQL
- [GQL vs REST](https://www.rubrik.com/blog/technology/19/11/graphql-vs-rest-apis#:~:text=The%20Core%20Difference%20Between%20REST,a%20single%20endpoint%20using%20HTTP.): What You Need to Know - Overview of GQL vs Rest
- [Rubrik YouTube Channel - GQL APIs](https://www.youtube.com/watch?v=hxzA5-FrMzY&list=PLHHKVC-uQ3XjL_LnGEBtgdbaqzReUuIqt)
- [API and Integration](https://www.rubrik.com/resources/api-integration) - Primary API and Integration website
- [An Introduction to GQL](https://www.rubrik.com/content/dam/rubrik/en/resources/white-paper/an-introduction-to-graphql-and-rubrik.pdf) - Overview of Rubrik’s GQL
- [GitHub](https://github.com/rubrikinc) - Rubrik Github site for SDKs, Sample code for download
- [GQL API Documentation](https://rubrikinc.github.io/rubrik-api-documentation/) - Rubrik GQL documentation, Changelog, Usage information, Use Cases
- [GQL Schema](https://rubrikinc.github.io/rubrik-api-documentation/reference/) - The GQL Schema for Rubrik Security Cloud
- [Rubrik APIs and Service Account Workflows for RSC and CDM](https://support.rubrik.com/servlet/servlet.FileDownload?file=00P8Y00001idNWKUA2)


# Learn how to use the new SDK via these YouTube Videos
1. [Installing and Connecting to the Rubrik Security Cloud PowerShell SDK](https://youtu.be/NXmNDgaviSY?si=xr2ziKBzlxgyfS1W)

1. [Fetching data using the Rubrik Security Cloud PowerShell SDK](https://youtu.be/EDnpQpll4N8?si=kcSNt73xXB686gNs)

# Table of Contents
## Getting Started
- [Getting Started](./content/GettingStarted.ipynb)
## Common cmdlets
- [Connect-Rsc](./content/Connect-Rsc.ipynb)
- [Get-RscCluster](./content/Get-RscCluster.ipynb)
## SQL Server
- [Get-RscMssqlDatabase](./content/Get-RscMssqlDatabase.ipynb)
- [Get-RscMssqlDatabaseFiles](./content/Get-RscMssqlDatabaseFiles.ipynb)
- [Get-RscMssqlDatabaseRecoveryPoint](./content/Get-RscMssqlDatabaseRecoveryPoint.ipynb)
- [Get-RscMssqlInstance](./content/Get-RscMssqlInstance.ipynb)
- [Get-RscMssqlLiveMount](./content/Get-RscMssqlLiveMount.ipynb)
- [Get-RscMssqlLogShipping](./content/Get-RscMssqlLogShipping.ipynb)
- [New-RscMssqlExport](./content/New-RscMssqlExport.ipynb)
- [New-RscMssqlLiveMount](./content/New-RscMssqlLiveMount.ipynb)
- [New-RscMssqlLogBackup](./content/New-RscMssqlLogBackup.ipynb)
- [New-RscMssqlLogShippingSecondary](./content/New-RscMssqlLogShippingSecondary.ipynb)
- [New-RscMssqlRestore](./content/New-RscMssqlRestore.ipynb)
- [New-RscMssqlSnapshot](./content/New-RscMssqlSnapshot.ipynb)
- [Remove-RscMssqlLiveMount](./content/Remove-RscMssqlLiveMount.ipynb)
- [Set-RscMssqlDatabase](./content/Set-RscMssqlDatabase.ipynb)
- [Set-RscMssqlInstance](./content/Set-RscMssqlInstance.ipynb)
## Managed Volume
- [Get-RscManagedVolume](./content/Get-RscManagedVolume.ipynb)
- [Start-RscManagedVolumeSnapshot](./content/Start-RscManagedVolumeSnapshot.ipynb)
- [Stop-RscManagedVolumeSnapshot](./content/Stop-RscManagedVolumeSnapshot.ipynb)