Step 1 - Update the system
$ sudo apt update && sudo apt upgrade -y
Why: refreshes the list of available software and installs updates.

Step 2 - Install tools
$ sudo apt install -y python3 python3-pip python3-venv git mysql-server
why:
python3-venv - lets us make an isolated Python environment per project
git - version control
mysql-server - the MySQL database