# EPPCV - Encryption protected passwords in cloud vault

[] AES-256
[] Nothing stored on the local pc
[] Web app - no cookies
[] First login done with master password and 2FA, then the session is stored on server
[] Every request needs master password
[] All contact with server via ssl connection

Datetime hashed by master password
password hashed by hashed datetime

## Web App
   - pyscript
## Extension
   - pyscript ?
   - HTML, CSS, JS
## Database
   - username, hashed datetime, hashed master password, hashed[[non hashed]URL, username, password]
   - technologie: MSSQL
## API
  - ASP .NET
  - Go?
