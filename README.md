# Remo, or Ruby Demo

## Purpose
This is a simple Ruby on Rails application.

This application uses:
* Ruby 3.2.3

See the Dockerfile and docker-compose.yml for more details.

## Getting Started
In order to get this running, there are a few steps you need to take.
* Clone this repository into a local directory.
* Ensure Docker desktop is installed on your host.
* From the `remo` directory, run `docker-compose build` - this will build the Docker image.
* Now run `docker-compose up -d` - this will run the Docker container (`-d` will allow you to perform CL actions within the container).
* Access the running application by navigating to `https://localhost:3000/` in a web browser.

## Example Actions
Running CL actions within the container is easy! Use `docker-compose exec web rails` as the prefix.

## Credits
I used the following tutorials to help me in setting this up:
* https://nicolasiensen.github.io/2022-02-01-creating-a-new-rails-application-with-docker/