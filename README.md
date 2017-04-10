# Hidden Docker Limesurvey
example docker compose file for running Limesurvey as a hidden service (aka on the darknet)

## How?
- install [docker](https://store.docker.com/search?type=edition&offering=community) and[docker-compose](https://docs.docker.com/compose/install/)
- run ```docker-compose up -d``` to start this all up
- ```docker-compose logs | grep .onion``` to find the address of your new hidden service
- visit  [http://localhost:8000](http://localhost:8000) to finish the server setup + create a survey
- then share the .onion url  (or use a hidden services gateway like https://onion.to/ )

## Why?
- grants even more anonymity+deniability to survey participants
- allows you to self host the Limesurvey internally behind a NAT
- easy setup + teardown