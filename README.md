
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## Name
fbanalyze

## General info
This project is a web app that will allow you to analyse and fetch data from Facebook groups.
	
## Technologies
Project is created with:
* Docker: ">= 27.0.3", build: 7d4bcd8
* Docker Compose: ">= 2.28.1-desktop.1"
* MongoDB: ">= 8.0", file: "compose.yaml"
* Traefik: ">= 3.1.2", file: "compose.yaml"
* Flask: ">= 3.0.3", file: "requirements.txt"
	
## Setup
To run this project use Bash:
* Clone the repo: https://github.com/JuliaGlocka/sdk-fbanalyze.git
* Go to the project directory.
* Use docker command "docker-compose up" to build the image



```
$ cd ../sdk-fbanalyze
$ docker-compose up
```
