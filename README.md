# Hostel Management System

***A system to manage the infrastructure and students of a hostel***


* git clone https://github.com/Nayhay99/Hostel-Management.git
* cd Hostel-Management-DBMS-Project
* npm install

> Setting up the database

#### Make sure to have postgres installed(postgresql 96 preferable) and the server is started

```
psql
create database hosteldb;
create user hosteluser with encrypted password 'hostelpass';
grant all privileges on database hosteldb to hosteluser;

```

#### To login as the hosteluser
```
psql -d  hosteldb -U hosteluser
```
Then,

```
Run the app
npm start
```
Server will start running on http://localhost:8888

