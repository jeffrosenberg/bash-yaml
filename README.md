# bash-yaml

[![Build Status](https://travis-ci.org/jasperes/bash-yaml.svg?branch=master)](https://travis-ci.org/jasperes/bash-yaml)

Bash script to read a Yaml file and create variables.


## Current problems found:

- Can't parse "some-property".
- Can't parse a object list with first attribute like "- name: MyName". Must be down.
- Object lists must be informed all attributes. Null must be "attr: ".