# json_schema2adoc

⛔️ This project is now archived - No Maintenance Intended

## Requirements
- Python3
- pip

## Running

- Create virtual environment and source it (if required):
```
json-schema2adoc$ mkdir .env
json-schema2adoc$ python3 -m venv .env
json-schema2adoc$ source .env/bin/activate
```
- Install api_from_schema
```
$ pip install git+https://github.com/AAFC-BICoE/json-schema2adoc.git[@branch|@tag]
```


## Usage
The ```generate_api_doc``` entry point can be called directly once the package is installed:
```$ generate_api_doc path/to/schema.json destination/directory/```

To use schemaAdocGeneratorV2.py as a module, import the api_from_schema package from a python interpreter or another module:
```
import json_schema2adoc.jsonSchemaAdocGenerator
```

## Developing

### To contribute to the json-schema2adoc codebase, do the following:
- Clone the repo
```
$ git clone https://github/AAFC-BICoE/json-schema2adoc.git
```
- Switch to the json-schema2adoc directory
```
$ cd json-schema2adoc
```
- Create virtual environment and source it:
```
json-schema2adoc$ mkdir .env
json-schema2adoc$ python3 -m venv .env
json-schema2adoc$ source .env/bin/activate
```

