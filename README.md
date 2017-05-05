**DataVision-Exchange**
=======================

![ruby](https://img.shields.io/badge/Ruby-2.4.1-red.svg)
![rails](https://img.shields.io/badge/Rails-5.0.1-red.svg)
![rails](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)

## Acerca de este proyecto

Aplicativo que simula la conversió de monedas. Sirve para que el usuário pueda reallizar una consulta rápida de cual es el valor de su dinero comparando la cantidad digitada en otra moneda. Puede escoger una moneda local o consultar entre las principales monedas del mundo...

## [Clique e veja online](https://datavision-exchange.herokuapp.com/)

![DataVisionExchange](https://raw.githubusercontent.com/enchenu/datavision_exchange/blob/master/public/screenshot.png)

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
