# mssql-vagrant
Quickly spin up a SQL Server instance on Ubuntu 16.04 LTS using Vagrant.


# Info

I mildly modified the unattended install script Microsoft provided on technet to help and change the default sa password, but since this is on GitHub you should probably hop in there and change it. Also the Vagrantfile activates bridged networking so if you don't like that then take it out. The backups folder is mounted into the VM, so you can add mssql backup files to it and open them in your instance. AdventureWorks2014 is included if you just want to goof around. Have fun (or as much fun as you can with MS software :P).
