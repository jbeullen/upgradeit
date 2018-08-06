# Serverless setup for upgrade-it.be
[![Build Status](https://travis-ci.org/jbeullen/upgradeit.svg?branch=master)](https://travis-ci.org/jbeullen/upgradeit)

## Sync Site Folder with S3
````
sls s3sync
````

**Currently the Stack Resources are disabled, because they were created manually**
## Create Stack
````
sls deploy
````
## Destroy Stack
````
sls remove
````