# Description

This is a Tour Booking API that provide functionalities for users to book tours, submit reviews, and manage their bookings seamlessly.

## Built with

- Node.js
- Expressjs
- MongoDB
- Mongoose

## Features

### User Features

- User signup, login, and logout
- Password reset and update
- Profile update and deletion
- Admin-only user management

### Tour Features

- Create, read, update, and delete tours
- Get top 5 cheap tours
- Get tour statistics
- Get monthly plan for tours
- Get tours within a certain distance
- Get distances to tours from a point

### Review Features

- Create, read, update, and delete reviews
- Nested routes for reviews on tours
- Booking Features
- Create, read, update, and delete bookings
- Get checkout session for booking tours

## Built with

- Node.js
- Expressjs
- MongoDB

## Getting Started

### Prerequisites

The tools listed below are needed to run this application:

- Node
- Npm

You can check the Node.js and npm versions by running the following commands.

### Check node.js version

`node -v`

### Check npm version

`npm -v`

## Installation

To run this API on your local machine:

- Install project dependencies by running `npm install`.

- Create a `config.env` file containing the environment variables listed in `sample.env`

- Start the server with `npm start:dev` to run in developement environment and `npm start:prod` for production environment

## Base URL

Localhost: http://127.0.0.1:{PORT}/api/v1 (`PORT` specified in `config.env`)

## Documentation

View documentation on: https://documenter.getpostman.com/view/24160587/2s8YzXvzvi
