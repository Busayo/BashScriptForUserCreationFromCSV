# BashScriptForUserCreationFromCSV
bash script that takes one argument - path to CSV file. The script parses it and creates accounts with login names taken from the 3rd column. All accounts are added to the engineering group (which is created first if it doesn't exist) 

CSV test file used:

firstname,lastname,username
John,Doe,jdoe
Jan,Kowalski,jkowalski
