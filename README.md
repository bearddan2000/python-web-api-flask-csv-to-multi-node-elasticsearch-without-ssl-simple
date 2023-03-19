# python-web-api-flask-csv-to-multi-node-elasticsearch-without-ssl-simple

## Description
Creates an api of `dog` for a flask project by loading csv into elasticsearch. 

Elasticsearch DSL is used to build a proxy connection to all the `elasticsearch` services.

Has the ability to query by parameters.
If path is not found, will default to 404 error.

## Tech stack
- python
  - flask
  - elasticsearch
  - elasticsearch_dsl

## Docker stack
- python:latest
- elasticsearch
- kibana

## To run
`sudo ./install.sh -u`
- Get all dogs: http://localhost/dog
  - Schema id, breed, and color
- Query with params: http://localhost/dog/id/<id>

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
