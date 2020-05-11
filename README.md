# cloudguru-snapshot
CG Python course - snapshot analyser

## About
Demo project using boto3 to manage EC2 instance snapshots.

## Configuring
shotty uses the configuration file created by the AWS CLI. E.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes or snapshots 

*subcommand* depends on command. For instances: list, start or stop

*project* is optional