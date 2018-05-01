# Azure Checklist

The steps below help to ensure that your Azure access and subscription will be sufficient and qualified to run the initial ML/DL workloads required in your curriculum. Please ensure that you can perform the steps 1 through 10. 

Reach out to the facilitators if you face issues.

## The Steps

1. Have you been provided Azure credentials?
2. Can you log into Azure Portal at https://portal.azure.com with the credentails provided? Please set/reset the password as soon as you are able to.
3. Can you create and access a sample Linux virtual machine with the Azure portal using the instructions found [here](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal?toc=%2Fazure%2Fvirtual-machines%2Flinux%2Ftoc.json)? Note that you will not be able to create a new resource group due to limitations. But a resource group matching your account has already been provisioned to you. Please use the assigned resource group instead.
4. Can you delete all the resources (but *NOT THE ACTUAL RESOURCE GROUP*) from the resource group that you were assigned to?
5. Can you set up a Linux Ubuntu Azure Data Science Virtual Machine (DSVM) using the instructions found [here](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/)?
6. Can you access your DSVM via SSH?
7. Can you access your DSVM via JupyterHub and JupyterLab and run some notebooks?
8. Can you set up X2Go and access the DSVM graphical desktop? Instructions be found from the previous link given in step 5.
9. Can you stop/deallocate and then restart your DSVM using the instructions found [here](https://buildazure.com/2017/03/16/properly-shutdown-azure-vm-to-save-money/)? Can you still access your restarted DSVM?
10. Can you delete all the resources under the DSVM's resource group similar to step 4?
