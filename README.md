# STA Client

This repository contains a couple of files containing environmental variables, collected in the context of the 
[eMOTIONAL Cities project](https://emotionalcities-h2020.eu/).

* [CO2V2.Humidity.csv](./CO2V2.Humidity.csv) - humidity data
* [CO2V2.Temperature.csv](./CO2V2.Temperature.csv) - temperature data

An example [jupyter notebook](./sta-data.ipynb) to publish these data in a [Sensor Things API server](https://github.com/opengeospatial/sensorthings) is provided.

If you don't have a server, you can use [this one](https://github.com/emotional-cities/openapi-sdi) as an example.

## Quick Setup

You will need python and [jupyter](https://jupyter.org/install) installed on your machine. To run the notebook, type:

```
jupyter notebook
```
Before running the notebook, export the password of the FROST server as an environmental variable. In Linux:
```
export FROST_PASSWORD=[some password]
```

## License

This project is released under an [MIT License](./LICENSE)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
