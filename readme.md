# DevTraining API

> Backend API for DevTraining application, which is a bootcamp directory website

## Usage

Rename "config/config.env.env" to "config/config.env" and update the values/settings to your own

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "\_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```

## Demo

The API is live at [alfredofernandez.me](https://alfredofernandez.me)

Extensive documentation with examples [here](https://documenter.getpostman.com/view/9630047/SztK25HT?version=latest#5bb4d405-6d75-4e88-9a4c-0ca83b2c7fa3)

- Version: 1.0.0
- License: MIT
- Author: Alfredo Fernandez
