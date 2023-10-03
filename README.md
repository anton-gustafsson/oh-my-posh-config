# oh-my-posh-config



# Prerequisites

* Install oh-my-posh
* Install font


## Open $Profile (Windows)
```cmd
notepad $PROFILE
```

## Add this to config
```cmd
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/main/themes/amro.omp.json' | Invoke-Expression
```


## Add this to settings.json in VSCode
```json
  "terminal.integrated.gpuAcceleration": "auto",
  "terminal.integrated.fontFamily": "'RobotoMono Nerd Font Mono'"
```
