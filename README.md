# metabase
setup for metabase in aws elastic beanstalk

## Platform
Choose Docker as the beanstalk platform.

## Once you setup the metabase environment, add the following environment variables.
MB_DB_DBNAME: "metabase"
MB_DB_HOST: "abc.database.com"
MB_DB_PASS: "mypassword"
MB_DB_PORT: 5432
MB_DB_TYPE: "postgres"
MB_DB_USER: "rdsuser"
