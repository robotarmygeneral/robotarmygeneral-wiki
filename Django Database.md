Adding a column

First, take these steps in the development environment (i.e., not on the production server):

Add the field to your model.

Run manage.pysqlall[yourapp] to see the new CREATE TABLE statement for the model. Note the column definition for the new field

Start your database’s interactive shell (e.g., psql or mysql, or you can use manage.pydbshell). Execute an ALTER TABLE statement that adds your new column.

or run evolve in our case

(Optional.) Launch the Python interactive shell with manage.pyshell and verify that the new field was added properly by importing the model and selecting from the table (e.g., MyModel.objects.all()[:5]).

Then on the production server perform these steps:

Start your database’s interactive shell.

old one:

 psql gosuapm_learnstream gosuapm_learnstream  
 password: 0727786e

current:

 psql gosuapm_lsdev gosuapm_lsdev  
 password c3b059f6

Execute the ALTERTABLE statement you used in step 3 of the development environment steps.

Add the field to your model. If you’re using source-code revision control and you checked in your change in development environment step 1, now is the time to update the code (e.g., svn update, with Subversion) on the production server.

Restart the Web server for the code changes to take effect.

Adding NOT NULL columns

  BEGIN;  
  ALTER TABLE books_book ADD COLUMN num_pages integer;  
  UPDATE books_book SET num_pages=0;  
  ALTER TABLE books_book ALTER COLUMN num_pages SET NOT NULL;  
  COMMIT;
