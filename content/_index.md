## About

10+ years of backend engineering: distributed systems, Django & PostgreSQL at scale, geospatial tech, media pipelines, and infrastructure migrations.

## Experience

### [INE](https://ine.com/) <small>Jun 2025 - Oct 2025</small>

+ Refactored the video learning platform transcription and translation pipeline to support video version updates (a gap in the original architecture) automating reprocessing for ~100 monthly updates and saving ~17 hours/month of developer time
+ Integrated user progress tracking to handle video updates accurately, ensuring reliable course completion reporting for clients with purchased seats.

<div class="skills">

[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")
[Celery](https://docs.celeryproject.org/ "Celery")
[Redis](https://redis.io/ "Redis")
[PostgreSQL](https://www.postgresql.org/ "Postgresql")
[Amazon SQS](https://aws.amazon.com/sqs/ "Amazon SQS")
[Amazon SNS](https://aws.amazon.com/sns/ "Amazon SNS")

</div>

### [INE](https://ine.com/) <small>Jun 2024 - Jan 2025</small>

+ Developed a real-time solution to capture video playback activity at 5-second granularity with 99.99% reliability. It ended up handling 3,000 concurrent users (~600 events/second) at peak with capacity to spare.
+ Built redundant dual-path capture via Django Channels and Amazon Kinesis + Elasticsearch in parallel. Tracked completion using PostgreSQL array fields for segment data, periodically consolidating from Elasticsearch, enabling automated user course completion reporting.
+ Expanded the existing infrastructure as code using Helm charts for Kubernetes to deploy the new playback tracking system.
+ Built observability and alerting for the playback tracking system using New Relic custom events and dashboards, aggregating cluster data to monitor event throughput and system health.

<div class="skills">

[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")
[Celery](https://docs.celeryproject.org/ "Celery")
[Redis](https://redis.io/ "Redis")
[PostgreSQL](https://www.postgresql.org/ "Postgresql")
[ElasticSearch](https://www.elastic.co/ "ElasticSearch")
[Docker](https://www.docker.com/ "Docker")
[Kubernetes](https://kubernetes.io/ "Kubernetes")
[Helm](https://helm.sh/ "Helm")
[Amazon SQS](https://aws.amazon.com/sqs/ "Amazon SQS")
[Amazon SNS](https://aws.amazon.com/sns/ "Amazon SNS")
[Amazon Kinesis](https://aws.amazon.com/kinesis/ "Amazon Kinesis")
[New Relic](https://newrelic.com/ "New Relic")

</div>

### [Sonder](https://sonder.com/) <small>Aug 2023 - Feb 2024</small>

+ Migrated availability windows from static to dynamic calculation, enabling the pricing engine to automatically target single-day availability gaps, the hardest inventory to book, increasing bookings on these gaps by 4x across 17,000+ units.
+ Consolidated state handling for unit collections, improving shuffling accuracy to optimize floor occupancy and minimize unbookable inventory.
+ Built Datadog dashboards and monitoring for dynamic availability window updates, tracking window state changes and pricing triggers.

<div class="skills">

[Python](https://www.python.org/ "Python")
[Flask](https://flask.palletsprojects.com/ "Flask")
[PostgreSQL](https://www.postgresql.org/ "Postgresql")
[MySQL](https://www.mysql.com/ "MySQL")
[Docker](https://www.docker.com/ "Docker")
[Kubernetes](https://kubernetes.io/ "Kubernetes")
[Helm](https://helm.sh/ "Helm")
[Datadog](https://www.datadoghq.com/ "Datadog")

</div>

### [Satellogic](https://satellogic.com/) <small>Feb 2019 - Apr 2023</small>

+ Contributed to the design, development, and long-term maintenance of a mission planning system processing 400+ imaging tasks daily across 26 satellites (up from 3 at project start), enabling non-technical users to simulate, schedule, and deploy tasks to Earth observation satellites.
+ Migrated legacy systems and consolidated 10 GB of historical data into the new platform, including data model transformations, enabling self-service planning for sales and operations teams.
+ Maintained async tasking state for satellites executing offline, reconciling ~5% of daily captures against in-orbit execution data to ensure accurate system state.
+ Built Prometheus metrics and Grafana dashboards to monitor system health. Designed OpsGenie alerting integration and escalation rules for incident response.
+ Led the 4-month phased migration from Azure to AWS to enable service for US-based clients, including storage (S3), message queues (SQS), task workers, and databases (DMS replication with 10-second cutover downtime). Adapted Helm charts and CI/CD pipelines to support dual-cloud operation during transition.

<div class="skills">

[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")
[Celery](https://docs.celeryproject.org/ "Celery")
[Redis](https://redis.io/ "Redis")
[PostgreSQL](https://www.postgresql.org/ "Postgresql")
[PostGIS](https://postgis.net/ "PostGIS")
[RabbitMQ](https://www.rabbitmq.com/ "Rabbitmq")
[ElasticSearch](https://www.elastic.co/ "ElasticSearch")
[Docker](https://www.docker.com/ "Docker")
[Kubernetes](https://kubernetes.io/ "Kubernetes")
[Helm](https://helm.sh/ "Helm")
[Azure](https://azure.microsoft.com/en-us/ "Azure cloud")
[Amazon SQS](https://aws.amazon.com/sqs/ "Amazon SQS")
[Amazon DMS](https://aws.amazon.com/dms/ "Amazon DMS")
[Amazon S3](https://aws.amazon.com/s3/ "Amazon S3")
[Prometheus](https://prometheus.io/ "Prometheus")
[Grafana](https://grafana.com/ "Grafana")
[OpsGenie](https://www.atlassian.com/software/opsgenie "OpsGenie")

</div>

### [Infoxel (Now Seenka)](https://seenka.com) <small>Feb 2018 - Oct 2018</small>

+ Scaled welo.tv, a Django-based video clipping platform (predating YouTube clips), to handle 50x traffic increase for the 2018 FIFA World Cup, delivering clips embedded across Argentina's largest news sites (La Nación, Clarín, Infobae).
+ Implemented Nginx load balancing, horizontal scaling, static content delivery, and Brightcove streaming integration to ensure reliable video workflows during peak demand.
+ Extracted a broker-agnostic Python microservice from the Django monolith to ingest 10-second video chunks from DVRs capturing 10 Argentine TV channels 24/7, maintaining sub-1-minute latency and eliminating processing gaps via Google Cloud Pub/Sub and message late acks.

<div class="skills">

[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")
[Celery](https://docs.celeryproject.org/ "Celery")
[Redis](https://redis.io/ "Redis")
[ElasticSearch](https://www.elastic.co/ "ElasticSearch")
[PostgreSQL](https://www.postgresql.org/ "Postgresql")
[Google Cloud](https://cloud.google.com/ "Google Cloud")
[Nginx](https://nginx.org/ "Nginx")

</div>

### [DKS-ARG](https://dks-arg.com/) <small>Feb 2017 - Dec 2017</small>

+ Built a click tracking and fraud detection service handling ~10 million clicks/day using Nginx/OpenResty/Django, blacklisting ~10% of traffic as fraudulent and redirecting ~25% of non-mobile traffic from mobile-only campaigns based on content.
+ Implemented Celery-based traffic analysis bots to detect suspicious behavior patterns and verify destination availability.
+ Developed Grafana/InfluxDB dashboards providing real-time traffic performance and campaign insights for internal and external use.

<div class="skills">

[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")
[Celery](https://docs.celeryproject.org/ "Celery")
[Redis](https://redis.io/ "Redis")
[PostgreSQL](https://www.postgresql.org/ "Postgresql")
[Heroku](https://www.heroku.com/ "Heroku")
[Nginx](https://nginx.org/ "Nginx")
[InfluxDB](https://www.influxdata.com/ "InfluxDB")
[Grafana](https://grafana.com/ "Grafana")

</div>

### [NuCivic](https://github.com/GetDKAN/dkan) <small>Nov 2013 - May 2017</small>

+ Full-stack development on DKAN, an open-source open data platform built on Drupal, customizing functionality for dozens of federal government clients.
+ Built custom visualizations (maps, charts, dashboards) and extended data type support, with focus on geospatial file handling, to help agencies publish accessible public datasets.

<div class="skills">

[Drupal](https://www.drupal.org/ "Drupal")
[MySQL](https://www.mysql.com/ "MySQL")
[Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript "JavaScript")
[Acquia](https://www.acquia.com/ "Acquia")
[Python](https://www.python.org/ "Python")

</div>

### [Buenos Aires City Government](https://buenosaires.gob.ar) <small>Feb 2011 - Nov 2013</small>

+ Introduced Drupal as the CMS for buenosaires.gob.ar, migrating 100+ city sites serving millions of monthly visitors. Trained 4 non-PHP developers to build internal Drupal expertise.
+ Built a custom Drupal module for unified search via Apache Solr, aggregating content from the city site, government gazette, and city legislation.
+ Built a centralized citizen procedures system providing step-by-step guides for government services (e.g., driver's license renewal).
+ Developed a city-wide OpenID-based SSO prototype integrating dozens of internal SOAP services, serving as the foundation for miArgentina and providing unified access for ~3 million residents.
+ Introduced Ansible provisioning, enabling multiple daily deployments versus manual configuration.

<div class="skills">

[Drupal](https://www.drupal.org/ "Drupal")
[MySQL](https://www.mysql.com/ "MySQL")
[Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript "JavaScript")
[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")
[Celery](https://docs.celeryproject.org/ "Celery")
[Redis](https://redis.io/ "Redis")
[MongoDB](https://www.mongodb.com/ "MongoDB")
[Apache Solr](https://solr.apache.org/ "Apache Solr")
[Ansible](https://www.ansible.com/ "Ansible")
[PostGIS](https://postgis.net/ "PostGIS")

</div>

### [SibileauLang]() <small>2003 - Feb 2011</small>

During the golden era of Flash apps, I founded, managed, and eventually closed a two-person web design studio focused on building interactive web experiences. Most of the work involved crafting portfolio sites for artists and fulfilling contract work for media agencies looking for visually rich, custom-built solutions.

Development centered on building Flash applications and websites using ActionScript, with backend integration powered by Django starting from its early days (v0.9, late 2005). This approach allowed for seamless content management behind highly dynamic interfaces.

Thank you Steve for ['Thoughts on Flash'](https://news.ycombinator.com/item?id=37229212). No pun intended at all.

<div class="skills">

[ActionScript](https://apache.github.io/royale-docs/features/as3 "ActionScript")
[MySQL](https://www.mysql.com/ "MySQL")
[Python](https://www.python.org/ "Python")
[Django](https://www.djangoproject.com/ "Django")

</div>

