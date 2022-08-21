****Running with docker*****

## Configure and run TER project by Daouda Fomba

This is a simple way for deploying on server using flask, gunicorn and docker

### Folder Structure 
```
+-- app
|   +-- index.py            // source code of dashboad application
+-- .env                  // configuration about where the app runs
+-- docker-compose.yaml   // build instructions
+-- Dockerfile            // docker image instructions
```

### Commands
```
0. Have a projet on local machine : git clone https://github.com/Fomba-Daouda/dashbord_pubmed.git
1. give permission like sudo chmod 777 /var/run/docker.sock to allow connection
2. cd directory where your project is
3. docker-compose build
4. docker-compose up
```
Then, If you built it localy visit: 127.0.0.1:5000 otherwise, use your server ip xxx.xxx.xxx.xxx:5000 to see the dashboard.



##After doing that, you can also navigate to folder named code (projetTer2022/code/), and run pyhton index.py



##Do not forget that, each research you dou within interface generate word into corpus.txt file who is in the current folder.
