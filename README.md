**DataVision-Exchange**
=======================

![ruby](https://img.shields.io/badge/Ruby-2.4.1-red.svg)
![rails](https://img.shields.io/badge/Rails-5.1.0-red.svg)
![rails](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)

## Sobre o projeto

Sistema de conversión de monedas muy facil de utilizar.

## [Clique e veja online](https://datavision-exchange.herokuapp.com/)

![DataVisionExchange](https://raw.githubusercontent.com/cheesepaulo/OneExchange/master/app/assets/images/screenshot.png)

# Stack
```
  * Application
```

# Dependencies
```
  * Fixer.io to consult currency rates
```

# Getting Started
```
  * docker-compose build
  * docker-compose run --rm website rake db:create db:migrate
  * docker-compose up
```

# Test
```
  * docker-compose run --rm website rspec
```
