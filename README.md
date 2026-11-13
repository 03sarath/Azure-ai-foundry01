## Run this:

```
sudo rm /etc/apt/sources.list.d/yarn.list 2>/dev/null
sudo apt update

Then install Azure CLI again:

curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

az version
az login 

```

If using Azure VS Code container
```
az login --use-device-code
```
