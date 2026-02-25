# pg_export
postgresql linux bash export and import utility database to file with tables greater than 1 gb

If even one of your database table became greater than 1gb pg_dump and pg_dump utility is broken and save only a part of database into file. 
This utitlity is made to save separatly every table to distent file in bynary format and compress all files to one.
After exporting all tables this utility adds pg_import file to make import of copy more comfortable.
