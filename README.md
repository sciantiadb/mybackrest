
mybackrest 
==========

mysql / mariadb Backup & Restore tool



FEATURES
--------


mybackrest is set of tools to manage LOGICAL , PITR backups and
restores :

- Automation of the logical backup

- Automation of the lowlevel backup

- Management of BINLOGS based on a catalog with compression on localhost

- Restore to a particular date and/or to a particular directory

- Management of backup retention for both logical and lowlevel


QUICK SETUP
-----------

1. Get the source

2. Run `mybackrest --cluster cluster_name --generate`

3. Adapt the cluster_name.cfg in /etc/mybackrest.d

4. Run `mybackrest --cluster cluster_name --backup options ` to perform your backups



DEVELOPMENT
-----------

The source code is available on Github: https://github.com/sciantiadb/mybackrest

mybackrest is developed by sciantiadb under a classic 2 clauses BSD license. See
license block in the scripts or the COPYRIGHT file.

HOW TO CONTRIBUTE
-----------------

Any contribution is welcome. If you have any idea, feature request,
question or patch, please contact us on Github:

https://github.com/sciantiadb/mybackrest/issues
