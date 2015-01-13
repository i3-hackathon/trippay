# Trip Pay

## Setup

Install node.js and gulp

    brew install node

    npm install gulp -g

## Install Dependencies

    npm install


Copy `config-sample.json` to `config.json` and add your config settings.

## running

Make sure mongo is running

    mongod

Run the server

    gulp develop

Open `http://localhost:3000` in your browser

## debugging

    DEBUG=trippay gulp develop
