# Knownodes Public API app

Provides direct interface with neo4j database for Knownodes project. Proof of concept based on http://www.coolgarif.com/brain-food/flask-api-over-neo4j-in-python and https://gist.github.com/coolgarifTech/5671071

## Dependencies

Python + Flask + Neo4jRestClient

## Instructions

Install and configure Neo4J to run a default database on localhost:7474, which should make localhost:7474/db/data accessible.

Then, install this app:

    $ virtualenv env
    $ source env/bin/activate
    $ git clone the.url.com/to/your/fork/`
    $ cd /the-repo-dir/
    $ pip install -r requirements.txt
    $ python public_api.py

Browse to http://localhost:5000/api/v1/?callback= to see the generic response

## Usage

There are two additional routes currently:

http://localhost:5000/api/vi/nodes/?callback=
http://localhost:5000/api/vi/rels/?callback=

Play with it and submit issues and ideas to the ticket tracker here.
