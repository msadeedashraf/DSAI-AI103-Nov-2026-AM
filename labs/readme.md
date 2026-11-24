
## Create a generative AI app that uses tools

[Lab - 04a-use-own-data](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/Exercises/04a-use-own-data.html)

- Custom Instructions

- after downloading the code from the git setup the local environment

```

cd cd c:\CBC\DSAI\11-AI-103\my-work\code\mslearn-ai-studio

```

```
python -m venv .venv
```

```
.\.venv\Scripts\Activate.ps1
```
- if the script does not get execute

```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

- Activate the environment 

```
.\.venv\Scripts\Activate.ps1

```

- Change the directory to the /labfiles/tools/python/tools-app

```
cd [drag the folder]
```

```
python -m pip install -r requirements.txt
```

- Check you have Azure CLI installed

```
az --version
```

- If not version not found 
- Check whether Azure CLI is installed

```
winget list --id Microsoft.AzureCLI

```
- Install Azure CLI

```
winget install --exact --id Microsoft.AzureCLI

```

```
az login 
```





