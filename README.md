# docker-compose-mongo-seeder
For quick development when working with mongo, with mongo express

Seeds a db called ukplatform-local-readstore with a single DealershipReadModel

- `cd <this directory>`
- `docker compose build`
- `docker compose up`

To get further json samples using existing dbs and Studio3T
Open up studio3t connect to dev mongo
Select the collection you want
Query the collection to filter out unwanted items
Select JSON view
Click the settings symbol and select JSON: mongoexport