# compass
A demo project that uses python to manage AWS EC2 instance

## Running

This project requires python 3 and the requests package.

First, install pipenv. Then:

...

pipenv install
pipenv run "navigator.py"

## About
This project is a demo, and uses boto3 to manage AWS EC2 instances. (ex snapshots etc)

## Configuring
compass uses the configuration file created by the AWS cli e.g.

`aws configure --profile compass`

## Running
`pipenv run "python .\navigator\navigator.py"`
