# Backup & Restore MySQL Database Using VB.Net

## Description
Simple Backup and Restore Application Using VB.Net for XAMPP or WAMP MySQL Database.

## What You Need to Know
**Backup Code default format:**
```
Process.Start("[MySQL Dump File Location]", "-u [USERNAME] -p [YOUR PASSWORD] [DATABASE THAT YOU WANT TO BACKUP] -r ""[OUTPUT LOCATION INCLUDE .SQL EXTENSION]""")
```

**Restore Code default format:**
```
myStreamerWriter.WriteLine("mysql -u [USERNAME] -p [PASSWORD] [YOUR DATABASE NAME] < [DATABASE THAT YOU ALREADY BACKUP FILE PATH]")
```

## How to Use
Change this File Location based on what application you used, WAMP or XAMPP to find MySQLDump.exe and MySQL Bin Folder
### On Backup Section (Sub Backup)
* **WAMP User:** C:\wamp64\bin\mysql\mysql5.7.14\bin\mysqldump.exe
* **XAMPP USer:** C:\xampp\mysql\bin\mysqldump.exe

### On Restore Section (Sub Restore)
* **WAMP User:** C:\wamp64\bin\mysql\mysql5.7.14\bin"
* **XAMPP User:** C:\xampp\mysql\bin\"

## Update
* 4 june 2021: Add --column-statistics=0 to the script for MySQL 8.0 above. Because Column Statistic is enabled by default since MySQL 8.0.

## Last But Not Least
For more info you can contact me on my social media. Visit [My Website](https://ericliputra.com/) for more information about this project. Thank You!
