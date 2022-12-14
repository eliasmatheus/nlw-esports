<p align="center">
  <img src="./public/logo.svg" alt="My Project GIF">
</p>

<h1 align="center">NLW eSports</h1>
<h3 align="center">An application to find partners or, as we prefer, a <i>duo</i>, to play your favorite games</h3>

<br />

<p align="center">
  <img src="./public/screen.jpeg" alt="My Project GIF" style="border-radius: 12px;">
</p>

## Technologies

- Typescript

- React
- Tailwind CSS
- React Native
- Expo

- Node.js
- Express
- Prisma
- SQLite

# How to run the application

Clone the application and access the `nlw-esports` folder

```bash
$ git clone https://github.com/eliasmatheus/nlw-esports.git && cd nlw-esports
```

## Server

### Requirements

- Node.js

### 1. Install server dependencies:

```sh
npm install     # npm
yarn            # yarn
```

### 2. Create and seed the database

Run the following command to create your SQLite database file. This also creates the `Ads` and `Games` tables:

```
npx prisma migrate dev --name init
```

### 3. Start the server:

```bash
$ npm run dev
```

## Web

Access the `web` folder with `cd web` and install dependencies with `npm i` then:

```bash
$ npm run dev
```

## Mobile

Access the `mobile` folder with `cd mobile` and install dependencies with `npm i` then:

```bash
$ expo start
```
