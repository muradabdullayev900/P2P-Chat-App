# P2P Chat App
This is a peer-to-peer chat application written in python using flask RESTful api and socket programming

# How to Use
### Note
Please take into consideration that 
1) You should already have installed mysql and dedicated database for new users.
2) You should create your dotenv file yourself.

Your dotenv file credentials:
```
SECRET_KEY = "your secret key"
SQLALCHEMY_DATABASE_URI = "mysql+pymysql://[user]:[password]@[ip_address]/[database_name]"

```

You can use ```/help``` command once you logged in to get further assitance
## Configuration

### Install requirements
```pip install -r requirements.txt```

### Run the application

#### Execute 'run.py'

```
python run.py
```

#### Execute 'server.py'
```
cd app/sockets
python server.py
```


#### Execute 'app.py' with 'register' or 'login' parameter
For register
```
cd app
python app.py register
```

For login
```
cd app
python app.py login
```

Please contact [murad.abdullayev.std@bhos.edu.az](mailto:murad.abdullayev.std@bhos.edu.az) in case of any unexpected problems