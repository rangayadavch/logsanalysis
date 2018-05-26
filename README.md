# Logsanalysis project
## Description
  This project is about to find top three article,top three authors and days with more than 1% of errors.
## Procedure 

## To Run

 ### You will need:
 - Python3
 - Vagrant
 - VirtualBox

 ### Setup
 1. Install Vagrant And VirtualBox
 2. Clone this repository

 ### To Run

 Launch Vagrant VM by running `vagrant up`, you can the log in with `vagrant ssh`

 To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

 The database includes three tables:
 - Authors table
 - Articles table
 - Log table

To execute the program, run `python3 newsdata.py` from the command line.
