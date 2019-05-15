## Want to use this project?

1. Fork/Clone
1. Install dependencies - `npm install`
1. Sanity check - `npm start`
1. Test - `npm test`

//add password to postgres database
CREATE DATABASE koa_api;
CREATE DATABASE koa_api_test;

sudo su -
sudo -u postgres psql koa_api_test
ALTER USER postgres WITH PASSWORD '123456';


sudo su -
sudo -u postgres psql koa_api
ALTER USER postgres WITH PASSWORD '123456';
