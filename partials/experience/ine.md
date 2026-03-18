### [INE](https://ine.com/) <small>Jun 2024 - Jan 2025</small>

+ Developed a real-time solution to capture video playback activity at 5-second granularity with 99.99% reliability. It ended up handling 3,000 concurrent users (~600 events/second) at peak with capacity to spare.
+ Built redundant dual-path capture via Django Channels and Amazon Kinesis + Elasticsearch in parallel. Tracked completion using PostgreSQL array fields for segment data, periodically consolidating from Elasticsearch, enabling automated user course completion reporting.
+ Expanded the existing infrastructure as code using Helm charts for Kubernetes to deploy the new playback tracking system.
+ Built observability and alerting for the playback tracking system using New Relic custom events and dashboards, aggregating cluster data to monitor event throughput and system health.

<small>
[Python :fontawesome-brands-python:](https://www.python.org/ "Python")
[Django :borrowed-django:](https://www.djangoproject.com/ "Django")
[Celery :borrowed-celery:](https://docs.celeryproject.org/ "Celery")
[Redis :borrowed-redis:](https://redis.io/ "Redis")
[PostgreSQL :borrowed-postgresql:](https://www.postgresql.org/ "Postgresql")
[ElasticSearch :borrowed-elastic:](https://www.elastic.co/ "ElasticSearch")
[Docker :borrowed-docker:](https://www.docker.com/ "Docker")
[Kubernetes :borrowed-kubernetes:](https://kubernetes.io/ "Kubernetes")
[Helm :borrowed-helm:](https://helm.sh/ "Helm")
[Amazon SQS :fontawesome-brands-amazon:](https://aws.amazon.com/sqs/ "Amazon SQS")
[Amazon SNS :fontawesome-brands-amazon:](https://aws.amazon.com/sns/ "Amazon SNS")
[Amazon Kinesis :fontawesome-brands-amazon:](https://aws.amazon.com/kinesis/ "Amazon Kinesis")
[New Relic :borrowed-newrelic:](https://newrelic.com/ "New Relic")
</small>