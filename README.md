# Ruby JSON Schema Validator + cli

This is a fork of [hoxworth/json-schema](https://github.com/hoxworth/json-schema), to which I've added a minimalistic command line interface.

## Installation

To install this gem straight from GitHub, use the [`specific_install`](https://github.com/rdp/specific_install) rubygems plugin:

* First install `specific_install`: `gem install specific_install`
* Then install this fork of `json-schema`: `gem specific_install -l https://github.com/ottopoellath/json-schema.git`

## Usage

### Validate a JSON file against a JSON schema file

`$ json-schema myschema.json.schema myfile.json`