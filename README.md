# Instructions to run:

The functions in tournament.py are reliant on a specifically structured database. To be able to use those functions you must first 
establish the database schema found in tournament.sql. The easiest way to do this is to open the PostgreSQL terminal (psql) and type the 
command \i tournament.sql. This will automatically establish the database (beware that the file is setup to drop any database already 
present named tournament). Alternatively you could copy all the commands and paste them into your terminal and run them from there. Once 
the database is set up, you can use the functions found in tournament.py. To test everything is working properly, you can run 
tournament_test.py by using the command python tournament_test.py in the shell. If the message returned ends with "Success! All tests 
pass!" then everything is working properly. To use the functions in your program, copy tournament.py into the same directory as your 
development directory and ensure you include the statment 'import tournament' at the top of your file. For explanations on what the 
various functions do, see the commented porition above each function definition in tournament.py.
