# cedar-templates

Loading templates into CEDAR MongoDB database:

`mongorestore -d cedar <dump_directory>`

If you want to drop the contents from the database before restoring it:

`mongorestore --drop -d cedar <dump_directory>`

Creating a MongoDB dump:

`mongodump -d cedar`

This will create a ./data directory with subdirectories for the dumped database(s). 
