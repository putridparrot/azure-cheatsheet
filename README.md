# Azure cheat sheet

A list of useful commands, params etc. for the Azure CLI

**General** 

| Command | Description |
|---------|-------------|
|az --version| Get the version |
|az login| Log into your Azure account |

**Container Registry**

| Command | Description |
|---------|-------------|
| az acr build -r &lt;name&gt;:&lt;ver&gt; -r &lt;regname&gt;| Builds a local docker container to given _name_ and _version_ and deploys to your Azure registry, _regname_|