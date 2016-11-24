# Backup ARM and Classic IaaSVMs to Recovery Services Vault

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgitrakesh%2FRecoveryServicesTemplate%2Fmaster%2FRecoveryServicesTemplate%2FTemplates%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template will use existing recovery services vault and policy, and enables protection of classic and ARM based IaaSVMs. VM and vault - both must be in same GEO.

To create new Recovery Services Vault, please use this existing template: [Create Recovery Services Vault] (https://github.com/Azure/azure-quickstart-templates/tree/master/101-recovery-services-vault-create)

To create Recovery Services Vault and Backup Policy, please use this existing template: [Create Recovery Services Vault and Weekly Backup Policy] (https://github.com/Azure/azure-quickstart-templates/tree/master/101-recovery-services-weekly-backup-policy-create)

For more information, Visit [Back up ARM VMs to a Recovery Services vault] (https://azure.microsoft.com/en-us/documentation/articles/backup-azure-vms-first-look-arm/)
