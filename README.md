# komorebi configration
you can set the KOMOREBI_CONFIG_HOME environment variable system-wide for all users using setx with the /M flag. Here's how to do it:<br>
Open CMD as admin
```
setx KOMOREBI_CONFIG_HOME "C:\Users\mail\.config\komorebi" /M
```
Open PowerShell as admin
```
[Environment]::SetEnvironmentVariable('KOMOREBI_CONFIG_HOME', 'C:\Users\mail\.config\komorebi', 'Machine')
```
