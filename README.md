# RDS_Vault_Connection
approach for the connecting RDS by using Vault generated credentials 
**Commands to Check Vault roles and Creds**

First command to enable the secrets engine 
$ vault secrets enable  -path=my-first-database database

 $vault read my-first-database/creds/readonly

for checking the connection

$vault read my-first-database/config
