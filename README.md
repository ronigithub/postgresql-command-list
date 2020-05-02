| Description | Windows Command |
| --- | --- |
|Connect with Postgresql Database|psql -U username[postgres] -h localhost dbname |
| Create Database| create database mydb; |
| List of Database|\l|
| Delete Database|drop database mydb;|
|Connect with Selective Database|psql -U postgres dbname|
|Connect with Selective Database|psql -h localhost -p 5432 -U postgres dbname|
|Change Databases|\c|
|Show All table|\dt|
|Show table structure|\d tablename|
|See Command List|\h|
|Truncate Table with ID|truncate table restart identity or TRUNCATE "products" RESTART IDENTITY CASCADE;|
|Initially Locate Directory(DB Export)|C:\Program files\Postgresql\10\bin|
| Import Database|psql -U postgres dbname < Location[D:\backup.sql]|
| Export Database| pg_dump -U postgres dbname > Location[D:\backup.sql] | 

| Description | Linux Command |
| --- | --- |
|Linux Postgresql Install|sudo apt-get install build-dep python-psycopg2 and pip install psycopg2|
|Password less login |sudo -u user_name psql db_name|
|Linux Import database|psql -h hostname -d databasename -U username -f file.sql|
|Linux Export database|pg_dump -h localhost -U postgres dbname > filename.sql|
|Modify Users Password in Postgresql|ALTER USER user_name WITH PASSWORD 'new_password'

| Common | Linux Command |
| --- | --- |
| Start Postgresql Service when computer boot | update-rc.d postgresql enable |
| Restart Service | service postgresql start |



