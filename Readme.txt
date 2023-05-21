# Holy Grail Layout Server

This repository contains a Node.js Express server that implements the Holy Grail Layout and utilizes Redis as a database.

## Description

The Holy Grail Layout is a classic web layout consisting of a header, left sidebar, right sidebar, main content area, and footer. This server allows you to dynamically update the components of the layout using Redis.

## Prerequisites

Before running this server, ensure that you have the following prerequisites installed:

- Node.js
- Docker

## Installation

Clone the repository:

git clone https://github.com/AravAravind/Holy-Grail-Layout.git

Install the dependencies:

npm install

Start the Redis server using Docker:

docker run -d -p 6379:6379 redis

Run the code:

npm start
