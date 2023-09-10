# Overview
Report Management System
- For given task I built this application, implemented user actions services, admin actions services and also genarated refresh token.

## Technology used
- Nodejs (version - v16.20.1)
- MongoDB (version - 6.0.9)

## Inatallation and Run

1.  Install npm packages:

```bash
npm i
```
2. Setup environment variables:

Copy `.env.example` to `.env` and you can also replace `.env` configurations with yours.

3. Start app

```bash
npm run start
```

Now API will available at 6006 port, or other you configured

4. Seed data.

* for creating admin run this script (you can also add your own credential)
```
node ./seed/createAdmin.js
```
after creating admin, must clean the credential from the script 😊.

* for seeding sample report data run this script

```
node seed/data/import-data.js  --import
```




