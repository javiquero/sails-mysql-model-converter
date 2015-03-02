
# sails-mysql-model-converter

Convert mysql schema to sails.js models structure


## Installation
  Copy importdb.js to your sails.js application.


## Usage

For import all tables from database.
```
node importdb.js USER:PASSWORD@HOST:PORT/DATABASENAME
```

For import selected tables from database.
```
node importdb.js USER:PASSWORD@HOST:PORT/DATABASENAME tableName1, tableName2, ...
```


## Credits
[Javier Quero](https://github.com/javiquero/)