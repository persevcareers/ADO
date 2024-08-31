# RG Creation:


``` bash
az group create --name dev-cluster --location centralindia 
```
``` bash
az aks create --resource-group prod --name prod-env --node-count 1 --enable-addons monitoring --generate-ssh-keys

```
