# Programas

## `chocolately:`

- abrir con permisos administrativos

- ejecutar el comando:

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## `pandoc:`

- convertidor de `markdown` a `pdf`:

```
choco install pandoc
```

## `visual studio`

[Descargar visual studio version 2022](https://visualstudio.microsoft.com/es/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&passive=false&cid=2030)