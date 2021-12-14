<h1 align="center">AdonisJS Api</h1>
<p align="center">Simple api written in <a href="https://adonisjs.com/">AdonisJS</a>.</p>

## Project
The project is very simple.

You can:
- Create users
- List all users

All the project uses are AdonisJS features, such as:
- AdonisJS routes
- ORM/Database
- Automatic controllers

## How to use

After download, run this command to install the dependencies:

```
yarn
# or
npm install
```

Then, you need to configure `.env` variables:

```
PORT=
HOST=
NODE_ENV=
APP_KEY=
DRIVE_DISK=
DB_CONNECTION=
```

Follow the file `~/.env.example`.

### Development

If you wanna run this app in development mode, just run this command:
```
yarn dev
# or
npm run dev
```

### Production

But if you wanna run this app in production mode, you have to build the TypeScript app:
```
yarn build
# or
npm run build
```

Enter the created directory:
```
cd build/
```

Run the app:
```
node server.js
```

## API/Routes

POST:
- `/users`: Create a new user

GET:
- `/users`: List all users
