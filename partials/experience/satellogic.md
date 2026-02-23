### [Satellogic](https://satellogic.com/) <small>Feb 2019 - Apr 2023</small>

+ Contributed to the design, development, and long-term maintenance of a mission planning system processing 400+ imaging tasks daily across 26 satellites (up from 3 at project start), enabling non-technical users to simulate, schedule, and deploy tasks to Earth observation satellites.
+ Migrated legacy systems and consolidated 10 GB of historical data into the new platform, including data model transformations, enabling self-service planning for sales and operations teams.
+ Maintained async tasking state for satellites executing offline, reconciling ~5% of daily captures against in-orbit execution data to ensure accurate system state.
+ Built Prometheus metrics and Grafana dashboards to monitor system health. Designed OpsGenie alerting integration and escalation rules for incident response.
+ Led the 4-month phased migration from Azure to AWS to enable service for US-based clients, including storage (S3), message queues (SQS), task workers, and databases (DMS replication with 10-second cutover downtime). Adapted Helm charts and CI/CD pipelines to support dual-cloud operation during transition.

<small>
[Python :fontawesome-brands-python:](https://www.python.org/ "Python")
[Django :borrowed-django:](https://www.djangoproject.com/ "Django")
[Celery :borrowed-celery:](https://docs.celeryproject.org/ "Celery")
[Redis :borrowed-redis:](https://redis.io/ "Redis")
[PostgreSQL :borrowed-postgresql:](https://www.postgresql.org/ "Postgresql")
[RabbitMQ :borrowed-rabbitmq:](https://www.rabbitmq.com/ "Rabbitmq")
[ElasticSearch :borrowed-elastic:](https://www.elastic.co/ "ElasticSearch")
[Docker :borrowed-docker:](https://www.docker.com/ "Docker")
[Kubernetes :borrowed-kubernetes:](https://kubernetes.io/ "Kubernetes")
[Helm :borrowed-helm:](https://helm.sh/ "Helm")
[Azure :borrowed-microsoftazure:](https://azure.microsoft.com/en-us/ "Azure cloud")
[Amazon SQS :fontawesome-brands-amazon:](https://aws.amazon.com/sqs/ "Amazon SQS")
[Amazon DMS :fontawesome-brands-amazon:](https://aws.amazon.com/dms/ "Amazon DMS")
[Amazon S3 :fontawesome-brands-amazon:](https://aws.amazon.com/s3/ "Amazon S3")
[Prometheus :borrowed-prometheus:](https://prometheus.io/ "Prometheus")
[Grafana :borrowed-grafana:](https://grafana.com/ "Grafana")
[OpsGenie :borrowed-opsgenie:](https://www.atlassian.com/software/opsgenie "OpsGenie")
</small>