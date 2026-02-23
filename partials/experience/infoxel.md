### [Infoxel (Now Seenka)](https://seenka.com) <small>Feb 2018 - Oct 2018</small> 

+ Scaled welo.tv, a Django-based video clipping platform (predating YouTube clips), to handle 50x traffic increase for the 2018 FIFA World Cup, delivering clips embedded across Argentina's largest news sites (La Nación, Clarín, Infobae).
+ Implemented Nginx load balancing, horizontal scaling, static content delivery, and Brightcove streaming integration to ensure reliable video workflows during peak demand.
+ Extracted a broker-agnostic Python microservice from the Django monolith to ingest 10-second video chunks from DVRs capturing 10 Argentine TV channels 24/7, maintaining sub-1-minute latency and eliminating processing gaps via Google Cloud Pub/Sub and message late acks.

<small>
[Python :fontawesome-brands-python:](https://www.python.org/ "Python")
[Django :borrowed-django:](https://www.djangoproject.com/ "Django")
[Celery :borrowed-celery:](https://docs.celeryproject.org/ "Celery")
[Redis :borrowed-redis:](https://redis.io/ "Redis")
[ElasticSearch :borrowed-elastic:](https://www.elastic.co/ "ElasticSearch")
[PostgreSQL :borrowed-postgresql:](https://www.postgresql.org/ "Postgresql")
[Google Cloud :borrowed-googlecloud:](https://cloud.google.com/ "Google Cloud")
[Nginx :borrowed-nginx:](https://nginx.org/ "Nginx")
</small>
