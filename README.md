```
apt-get install python3 python3-dev python3-pip mysql-server mysql-client libmysqlclient-dev libxml2-dev
pip3 install -r requirements.txt
mysql -u root -p
CREATE DATABASE sta;
GRANT ALL ON sta.* to 'sta'@'localhost' identified by 'sta';
cp config/example.py config/default.py
./run.py
```
