# VM with explicit Managed Disk (OS)

Provisions a Linux VM (Ubuntu) with an explicitly defined managed OS-Disk.

´´´
$ az group create -n myrg -l northeurope

$ az group deployment create -g myrg --mode Complete --template-file azuredeploy.json --parameters @azuredeploy.parameters.json
´´´