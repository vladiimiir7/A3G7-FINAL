| Problem                                | Cause                                            | Solution                                                              |
|----------------------------------------|--------------------------------------------------|---------------------------------------------------------------------- |
| ping: the command was not in container | The Python installed was not the correct version.| We installed  ping using apt-get install -y iputils-ping.             |
| The Flask app not connecting to MySQL  | The credentials in .env file were incorrect.     | We checked MYSQL_USER, MYSQL_PASSWORD, and MYSQL_DATABASE values.     |
| The .env was not ignored by the Git    | The .env was not added to .gitignore correctly.  | We had to add .env to .gitignore                                      |
| The Flask app not running custom port  | The Port in .env was not like docker-compose.yml.| The same PORT value had to be in both .env and docker-compose.yml.    |
