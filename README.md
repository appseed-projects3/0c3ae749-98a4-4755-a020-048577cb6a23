# React Material Kit `full-stack`

Full-Stack Seed project generated by **[React App Generator](https://appseed.us/generator/react/)** top of *Material Kit* design. The backend logic is provided by a simple, `easy-to-extend` API Server that manages the Authentication flow (login, registration, logout) using `JSON Web Tokens` (JWT).

- 👉 [React Material Kit](https://react-material-kit.appseed-srv1.com/pages/authentication/sign-in) - LIVE Demo (from a similar product)

- 🚀 Built with [React App Generator](https://appseed.us/generator/react/), timestamp `2023-04-03 19:42`

<br />

![React Material Kit - Open-Source Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/205701017-aba36ff7-1db0-41d0-8691-9f989c047014.png)


<br >

## ✨ `React` Material Kit

- Design crafted by *[Creative-Tim](https://bit.ly/3fKQZaL)*
- Innovative **Material Kit Design**
- Full-stack ready
- `UI Kit`: 750+ components, `4 Sample Pages`  

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ✅ | ❌ |
| `v15.0.0` | ✅ | ❌ | 
| `v16.15.0` | ✅ | ✅ | 


<br />

## ✨ `NodeJS API` Features

- Stack: `NodeJS` / `Express` / **SQLite** 
- `TypeScript`, Joy for validation
- **DB Layer**: `TypeORM`, `SQLite` persistence
- **Auth**: Passport / `passport-jwt` strategy
- [API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- | 
| `v18.0.0`  | ❌ | ✅ |
| `v17.0.0`  | ❌ | ✅ |
| `v16.13.0` | ❌ | ✅ | 
| `v16.0.0`  | ❌ | ❌ | 


<br /> 

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).


<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `api-server-nodejs`

```bash
$ cd api-server-nodejs
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Run the SQLite migration via TypeORM

```bash
$ npm run typeorm migration:run
// OR 
$ yarn typeorm migration:run
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ npm run dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default 5000).

<br /> 

## 👉 Codebase Structure

```bash
< ROOT / src >
     | 
     |-- config/                              
     |    |-- config.ts             # Configuration       
     |    |-- passport.ts           # Define Passport Strategy             
     | 
     |-- migration/
     |    |-- some_migration.ts     # database migrations
     |
     |-- models/                              
     |    |-- activeSession.ts      # Sessions Model (Typeorm)              
     |    |-- user.ts               # User Model (Typeorm) 
     | 
     |-- routes/                              
     |    |-- users.ts              # Define Users API Routes
     | 
     | 
     |-- index.js                   # API Entry Point
     |-- .env                       # Specify the ENV variables
     |                        
     |-- ************************************************************************
```

<br />

## 👉 SQLite Path

The SQLite Path is set in `.env`, as `SQLITE_PATH`

<br />

## 👉 Database migration

> Generate migration:

```bash
$ yarn typeorm migration:generate -n your_migration_name
```

> run migration: 

```bash
$ yarn typeorm migration:run
```

<br />

<br />

## [React Material Kit PRO](https://appseed.us/product/material-kit-pro/full-stack/)

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

`Material Kit React PRO` is built with over 100 frontend individual elements, like buttons, inputs, navbars, alerts or cards, giving you the freedom of choosing and combining. The product comes with a simple JWT authentication flow: login/register/logout. 

- 👉 [React Material Kit PRO](https://appseed.us/product/material-kit-pro/full-stack/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![React Material Kit PRO - Premium Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/205701266-e721435d-22fc-48f2-9462-11f7fb050143.png)

<br />

---
**React Material Kit** - Full-Stack Seed project generated by **[App Generator](https://appseed.us/generator/)**.
