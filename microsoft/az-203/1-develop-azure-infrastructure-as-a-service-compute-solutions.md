# AZ-203: Develop Azure Infrastructure as a Service Compute Solutions (10-15%)

## Implement solutions that use virtual machines (VM)
* Know the basic options for provisinging a VM
* For the disks, focus on [encryption basics and how keyvault is related](https://docs.microsoft.com/en-us/azure/security/azure-security-disk-encryption-windows)
* Creating ARM templates - review the ARM templates in the [quickstart templates](https://github.com/Azure/azure-quickstart-templates/tree/master/101-vm-simple-linux)
* Either in [PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-powershell))  or [CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-cli), Create a Windows VM
* For a LInux VM, go through how to [create one with the CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli)

## Implement batch jobs by using Azure Batch Services
* Read through the [overview of Batch APIs and tools](https://docs.microsoft.com/en-us/azure/batch/batch-apis-tools)
* For batch jobs, focus on knowing [how to use the .NET SDK for creating jobs](https://docs.microsoft.com/en-us/azure/batch/quick-run-dotnet), setting them up, and executing.
* Complete the [batch .NET quickstart](https://github.com/Azure-Samples/batch-dotnet-quickstart)
* Skim through [Azure CLI and how to manage batch resources](https://docs.microsoft.com/en-us/azure/batch/batch-cli-get-started)
* Know how to [persist task data to Azure Storage with the Batch service API](https://docs.microsoft.com/en-us/azure/batch/batch-task-output-files)
* Finally, know about how to [use Azure Batch CLI templates and file transfer](https://docs.microsoft.com/en-us/azure/batch/batch-cli-templates)

## Create containerized solutions
* Complete the [walkthrough of setting up an AKS cluster](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough) (including the service principal option)
* Know how to use the [CLI at least for basic management of ACR](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-azure-cli)
* [Create an Azure Container Registry, create, prep, and push images to it](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-acr)
