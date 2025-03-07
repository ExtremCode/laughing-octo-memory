# Simple counter

## Description

This project is a simple web application that return "Hello World! I have been seen *count* times." on GET request. *count* is a number of GET requests that have been get server.

## How to run

It's correctly for Windows OS.

0. You should clone repository `git clone https://github.com/ExtremCode/laughing-octo-memory.git`
1. run `docker compose up -d`
2. run `curl http://localhost:8000` to send GET request. You get response automatically in your command line.

Notice that number of GET requests counts is not removed when you remove *database* container due to the fact that data from Redis database saved in *redis_data* folder. If it's necessary, you can change location of *redis_data* folder: in docker-compose.yaml write absolute path in 25th line.
