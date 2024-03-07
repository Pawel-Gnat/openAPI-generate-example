
# OpenAPI Generator

[Link to the documentation of OpenAPI](https://openapi-generator.tech/)
Generate clients, servers, and documentation

## How to run my example

spec.json (generate handle .yaml files also) contains data from rickandmortyapi. 

Firstly validate your spec with command

    ./validate-spec.sh
if successful then

    ./generate-client.sh
It will produce files inside `api-client` folder to use in your project.