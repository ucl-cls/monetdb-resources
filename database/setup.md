Using Monet DB daemon
---------------------

Create database ‘farm area’
> monetdbd create /path/to/dbfarmarea

Start server 
> monetdbd start /path/to/dbfarmarea

Using Monet DB command
---------------------

Create database
> monetdb create mcs

Release database for use by the client
> monetdb release mcs

> mclient -u monetdb -d mcs
password <monetdb>

Insert schemas into database
----------------------------

>\< schema_data.sql
>\< schema_metadata.sql

Add in metadata extracted from SIR
----------------------------------

>\< metadata.sql

Add in metadata extracted from SIR
----------------------------------

>\< add_data.sql




