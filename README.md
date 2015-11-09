# node-demon
Nodejs-demon-template

Use below commands in linux/ mac os to bring this project using shell scripts

1. git clone https://github.com/ctschak/node-demon.git
2. cd node-demon
3. sudo npm install
4. sudo npm install -g forever
5. chmod 777 startup.sh 
6. chmod 777 shutdown.sh

To run the nodejs server as a background service / demon process. use below commands.
7. > ./startup.sh & 
To shutdown the nodejs server 
8. > ./shutdown.sh

To know forever instances
9. forever list

To know nodejs instances
10. ps axl | grep node

To kill specifc node instance
11. kill XXXXX (eg. 1234 id of sepcfic instance)
