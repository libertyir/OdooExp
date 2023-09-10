# OdooExp

OdooExploit parameter :
 server: Ip Address or hostname
 port: port number 8069 or other
 db: database name
 username: username of database
 password: passwrod of database
 Command:  
     remember: remember connection parameters by name and load by config['name']
     dump: dump database
     sqli: execute sql script
     python: safe_eval python script
     sqli_databases: sqli get all databases 
     sqli_dir: sqli dir directory by pg_ls_dir(path |arg2,...) 
     sqli_readfile: sqli read file by pg_read_file(file |arg2,...)
     sqli_readfile2: sqli read file by copy TABLE From file |arg2,...)
     sqli_linuxread: sqli read file by linux shell
     sqli_winread: sqli read file by windows shell
     sqli_linuxdir: sqli directory list by linux shell
     sqli_windir: sqli directory list by windows shell
     sqli_linuxshell: sqli linux shell
     sqli_winshell: sqli windows shell
 Parameters: Command parameters
