# Relational Database Bootstrap
0. MySQL 5.7
0. PostgreSQL 9.6.6
0. Oracle 11g
0. SQL Server Linux 2017 CU2

# Startup
Run ``docker-compose up -f FILE.yml``


# TODO
0. Oracle 12c
0. DB2 LUW
0. MariaDB

## Defaults
### Volumes, Host Mounted vs Docker File System
The ./data directory contains several host mounted volumes, and the YML file may have a commented out docker volume mount described.

### Common Environmental Variables
Default credentails are stored in the .env file