# My-Azure-Templates-Specs
Template Specs for import to create Labs and Demos
This is a simple repository of Template Specs to share.

## Azure Netapp Files (network options) Template
This template allows you to create an ANF infrastructure complete with networking, ANF account, capacity pool, volume and snapshot.
Defaults are listed in the Parameters.
Caution: Be sure to caclulate the correct CIDR ranges for the network components. 
### Parameters that can be configured during deployment
* Region - Uses the region of the Resource Group
* ANF Account - ANFAccount
* Virtual Network Name - NetAppFilesVnet
* Virtual Network Adress Space - 10.249.64.0/18
* Delegated Subnet Name - ANFDelegatedSubnetName
* Delegated Subnet Address Space - 10.249.120.0/28
* VM_Subnet - VM-subnet
* VM_Subnet Address Space - 10.249.121.0/24
