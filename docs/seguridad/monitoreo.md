# Monitoreo
1. Listar Procesos en Ejecución
Revisa los procesos en ejecución para identificar alguno que no reconozcas.

```
Get-Process | Sort-Object CPU -Descending | Select-Object -First 10
```

2. Verificar Conexiones de Red
Lista las conexiones de red activas y escucha puertos para identificar conexiones sospechosas.
```
Get-NetTCPConnection -State Listen, Established | Sort-Object -Property State
```
3. Revisar Tareas Programadas
Las puertas traseras a menudo crean tareas programadas para mantenerse persistentes.
```
Get-ScheduledTask | Where-Object {.State -eq 'Ready'}
```
4. Buscar Programas que se Ejecutan al Iniciar el Sistema
Revisa los programas que se inician al arrancar el sistema.
```
Get-ItemProperty -Path "HKLM:\Software\Microsoft\Windows\CurrentVersion\Run"
Get-ItemProperty -Path "HKCU:\Software\Microsoft\Windows\CurrentVersion\Run"
```