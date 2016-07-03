# sql-cli
A very basic docker container with sql-li (mssql command line tool) - MSSQL - CLI

`docker run --rm shellmaster/sql-cli`

which will print help menu, if you are forwarding mssql ports to your local or mssql is running on your local you need to share host's network eg.:

`docker run --rm --net=host shellmaster/sql-cli`

Good Luck!
