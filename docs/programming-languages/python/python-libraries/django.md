---
title: Django
---

# [Django](https://www.djangoproject.com/)

## OSS Django Apps

- [Django Rest Framework + Next.js + Tailwind](https://github.com/Emceelamb/django-next)

## Notes

- Make migration (where `./manage` is a script that wraps over `python manage.py`):
  1. Change model. Add/remove fields etc.
  2. Run `./manage makemigrations` to create migration from changed models. (can run `./manage makemigrations -n <migration-name>` to give it custom name).
  3. Migration file is created. Run `./manage migrate` to apply
- Run tests:
  - `./manage test` = run all tests
  - `./manage test -k path.to.test` = run specific test. can also run some function from the test inside the file with another `.`.
- Migrate down/up: `./manage migrate <app> <migration-number>`
- Make empty migration: `./manage makemigrations --empty <name-of-migration> <app>`
- [Rewrote the Pegasus teams UI in HTMX and I gotta say I'm sold. You build an app in standard Django, add a few annotations, and then boom: SPA. The number of situations in which I'll reach for React by default just got chopped in half at least.](https://twitter.com/czue/status/1442446129065517056)

## Links

- [Profiling Django with DTrace and cProfile (2019)](https://wiedi.frubar.net/blog/2019/11/18/django-performance/)
- [Django’s CBVs were a mistake (2012)](https://lukeplant.me.uk/blog/posts/djangos-cbvs-were-a-mistake/)
- [Testing Django Migrations (2019)](https://sobolevn.me/2019/10/testing-django-migrations)
- [HN: Django 3](https://news.ycombinator.com/item?id=21681732)
- [Viewflow](https://github.com/viewflow/viewflow) - Reusable workflow library for Django.
- [cookiecutter-django-rest](https://github.com/agconti/cookiecutter-django-rest) - Build best practiced apis fast with Python3.
- [rules](https://github.com/dfunckt/django-rules) - Awesome Django authorization, without the database.
- [Django REST framework](https://github.com/encode/django-rest-framework) - Awesome web-browsable Web APIs.
- [Awesome Django](https://github.com/wsvincent/awesome-django)
- [Introducing Django (2005)](https://simonwillison.net/2005/Jul/17/django/)
- [Django 3.1 (2020)](https://www.djangoproject.com/weblog/2020/aug/04/django-31-released/) ([HN](https://news.ycombinator.com/item?id=24048046))
- [Surviving Django (if you care about databases) (2020)](https://www.varrazzo.com/blog/2020/07/25/surviving-django/) ([HN](https://news.ycombinator.com/item?id=24074520)) ([Lobsters](https://lobste.rs/s/l7dqrf/surviving_django_if_you_care_about))
- [Django Views — The Right Way](https://spookylukey.github.io/django-views-the-right-way/) - Opinionated guide on how to write views in Django. ([Lobsters](https://lobste.rs/s/4n63nn/django_views_right_way))
- [Django Middleware](https://www.reddit.com/r/django/comments/hms3n6/django_middleware/)
- [Django Async: What's new and what's next? (2020)](https://deepsource.io/blog/django-async-support/) ([HN](https://news.ycombinator.com/item?id=24160608))
- [Django Redis](https://github.com/jazzband/django-redis) - Redis cache backend for Django.
- [Django styleguide](https://github.com/HackSoftware/Django-Styleguide)
- [Deploy Machine Learning Models with Django](https://www.deploymachinelearning.com/) ([Code](https://github.com/pplonski/my_ml_service))
- [Async Views in Django 3.1 (2020)](https://testdriven.io/blog/django-async-views/) ([HN](https://news.ycombinator.com/item?id=24423637))
- [Build a simple Hacker News clone using Django 3 (2020)](https://www.youtube.com/watch?v=292GB6snFYo)
- [Building a Django app with data access control in 30 minutes (2020)](https://www.osohq.com/post/django-access-control) ([Lobsters](https://lobste.rs/s/tpoc8j/building_django_app_with_data_access))
- [Django Waffle](https://github.com/django-waffle/django-waffle) - Feature flipper for Django.
- [Cookiecutter Django](https://github.com/pydanny/cookiecutter-django) - Framework for jump starting production-ready Django projects quickly.
- [SaaS Pegasus](https://www.saaspegasus.com/) - Django-Powered SaaS Template. ([Docs](https://docs.saaspegasus.com/))
- [Django Filter](https://github.com/carltongibson/django-filter) - Reusable Django application allowing users to declaratively add dynamic QuerySet filtering from URL parameters. ([Docs](https://django-filter.readthedocs.io/en/master/))
- [Django Best Practices: Security (2020)](https://learndjango.com/tutorials/django-best-practices-security)
- [LearnDjango](https://learndjango.com/) - Django Tutorials.
- [Django Dynamic Fixture](https://github.com/paulocheque/django-dynamic-fixture) - Complete library to create dynamic model instances for testing purposes.
- [Two Scoops of Django 3.x: Best Practices for the Django Web Framework](https://www.feldroy.com/products/two-scoops-of-django-3-x)
- [Speed Up Your Django Tests book](https://gumroad.com/l/suydt)
- [django-read-only](https://github.com/adamchainz/django-read-only) - Disable Django database writes.
- [Simple JWT](https://github.com/SimpleJWT/django-rest-framework-simplejwt) - JSON Web Token authentication plugin for the Django REST Framework.
- [drf-yasg](https://github.com/axnsan12/drf-yasg) - Generate real Swagger/OpenAPI 2.0 specifications from a Django Rest Framework API.
- [Graphene-Django](https://github.com/graphql-python/graphene-django) - Integrate GraphQL into your Django project.
- [Graphene-Django-Plus](https://github.com/0soft/graphene-django-plus) - Tools to easily create permissioned CRUD endpoints in graphene.
- [Optimizing Postgres full text search in Django (2019)](https://hodovi.ch/blog/optimizing-postgres-full-text-search-django/)
- [Understand Group by in Django with SQL (2020)](https://hakibenita.com/django-group-by-sql)
- [Running Django + React service by Cloud Run (2020)](http://djkooks.github.io/gcp-django-deploy-cloudrun)
- [Django Doctor](https://django.doctor/) - Django GitHub PR bot that suggest the fix.
- [Django’s Structure – A Heretic’s Eye View](https://djangobook.com/mdj2-django-structure/)
- [Django Book](https://djangobook.com/) - Python Django Tutorials.
- [Blazing fast tests in Django (2018)](https://dizballanze.com/django-blazing-fast-tests/)
- [Django project optimization guide (2017)](https://dizballanze.com/django-project-optimization-part-1/)
- [Django Ninja](https://github.com/vitalik/django-ninja) - Fast Django REST Framework. ([HN](https://news.ycombinator.com/item?id=30221016))
- [django-guardian](https://github.com/django-guardian/django-guardian) - Per object permissions for Django.
- [Docker-Compose for Django and React with Nginx Reverse-Proxy and Let's Encrypt (2020)](https://saasitive.com/tutorial/docker-compose-django-react-nginx-let-s-encrypt/) ([HN](https://news.ycombinator.com/item?id=25169155))
- [Django Smartmin](https://github.com/nyaruka/smartmin) - Admin-like utility for users.
- [Deploying Django to AWS ECS with Terraform](https://github.com/testdrivenio/django-ecs-terraform)
- [Django Slick Reporting](https://github.com/ra-systems/django-slick-reporting) - Powerful and Efficient reporting engine with Charting capabilities.
- [Dataclasses serializer](https://github.com/oxan/djangorestframework-dataclasses) - Dataclasses serializer for Django REST framework.
- [django-floppyforms](https://github.com/jazzband/django-floppyforms) - Full control of form rendering in the templates.
- [DIY Django and React Boilerplate for SaaS](https://github.com/saasitive/django-react-boilerplate) ([Web](https://saasitive.com/)) ([HN](https://news.ycombinator.com/item?id=25517226))
- [django-unicorn](https://github.com/adamghill/django-unicorn) - Provides a way to use backend Django code and regular Django templates to create interactive experiences without investing in a separate frontend framework. ([Web](https://www.django-unicorn.com/))
- [Hotwire + Django](https://github.com/hotwire-django/hotwire-django) - Meta package to combine turbo-django and stimulus-django.
- [Django migrations without downtimes (2015)](http://pankrat.github.io/2015/django-migrations-without-downtimes/)
- [wemake-django-template](https://github.com/wemake-services/wemake-django-template) - Bleeding edge django template focused on code quality and security.
- [Django Activity Stream](https://github.com/justquick/django-activity-stream) - Way of creating activities generated by the actions on your site.
- [Django antipatterns](https://www.django-antipatterns.com/) ([Code](https://github.com/hapytex/django-antipatterns))
- [Turbo for Django](https://github.com/hotwire-django/turbo-django) - Integration of Hotwire Turbo with Django.
- [Modern Django: A Guide on How to Deploy Django-based Web Applications](https://github.com/djstein/modern-django)
- [Django Algolia Integration](https://github.com/algolia/algoliasearch-django)
- [Docker, Django, Traefik, and IntercoolerJS: My go-to stack for building a SaaS (2021)](https://www.simplecto.com/docker-django-traefik-intercoolerjs-is-my-stack-for-2021/) ([HN](https://news.ycombinator.com/item?id=25973242))
- [Django 3.2 (2021)](https://www.djangoproject.com/weblog/2021/apr/06/django-32-released/) ([HN](https://news.ycombinator.com/item?id=26710013))
- [Constance](https://github.com/jazzband/django-constance) - Dynamic Django settings.
- [Rapid Prototyping with Django, htmx, and Tailwind CSS (2021)](https://testdriven.io/blog/django-htmx-tailwind/)
- [Django SQL Dashboard](https://django-sql-dashboard.datasette.io/en/latest/) ([HN](https://news.ycombinator.com/item?id=27107428)) ([Code](https://github.com/simonw/django-sql-dashboard)) ([Article](https://simonwillison.net/2021/May/10/django-sql-dashboard/))
- [Get to know Django models better (2021)](https://girlthatlovestocode.com/django-model)
- [Django Chat](https://djangochat.com/) - Podcast on the Django Web Framework by William Vincent and Carlton Gibson.
- [Django Channels](https://github.com/django/channels) - Developer-friendly asynchrony for Django.
- [Kolo](https://kolo.app/) - Django VSCode Extension. See everything happening in your running Django app. ([Code](https://github.com/kolofordjango/kolo))
- [concrete-datastore](https://github.com/Netsach/concrete-datastore) - Highly versatile HTTP REST Datastore based on the web framework Django.
- [Django for Startup Founders: A better software architecture for SaaS startups (2021)](https://alexkrupp.typepad.com/sensemaking/2021/06/django-for-startup-founders-a-better-software-architecture-for-saas-startups-and-consumer-apps.html) ([HN](https://news.ycombinator.com/item?id=27605052))
- [One Database Transaction Too Many (2021)](https://hakibenita.com/django-nested-transaction)
- [Modeltranslation](https://github.com/deschler/django-modeltranslation) - Translates Django models using a registration approach.
- [Django Packages](https://djangopackages.org/) - Reusable apps, sites and tools directory.
- [Building MVPs fast on Django (2021)](https://davidkell.substack.com/p/davids-opinionated-guide-for-building)
- [Building a Django driver for Psycopg 3 (2021)](https://www.psycopg.org/articles/2021/08/02/psycopg3-django-driver/) ([HN](https://news.ycombinator.com/item?id=28034581))
- [Python Django Web Framework - Full Course for Beginners (2019)](https://www.youtube.com/watch?v=F5mRW0jo-U4)
- [Django Hijack](https://github.com/django-hijack/django-hijack) - With Django Hijack, admins can log in and work on behalf of other users without having to know their credentials.
- [django-htmx](https://github.com/adamchainz/django-htmx) - Extensions for using Django with htmx.
- [Appliku Deploy](https://appliku.com/) - Server Management, designed specially for Django. ([HN](https://news.ycombinator.com/item?id=28468660))
- [Type Check Your Django Application](https://kracekumar.com/post/type_check_your_django_app/)
- [Hotwired/Turbo Django response helpers](https://github.com/hotwire-django/django-turbo-response)
- [New Testing Features in Django 4.0 (2021)](https://adamj.eu/tech/2021/09/28/new-testing-features-in-django-4.0/)
- [High Performance Django (2014)](https://lincolnloop.com/high-performance-django/)
- [New Testing Features in Django 4.0 (2021)](https://adamj.eu/tech/2021/09/28/new-testing-features-in-django-4.0/)
- [Model Bakery](https://github.com/model-bakers/model_bakery) - Object factory for Django.
- [The Decline of Django (2021)](https://www.david-dahan.com/blog/the-decline-of-django) ([HN](https://news.ycombinator.com/item?id=28863465))
- [Profiling Django App](https://kracekumar.com/post/profiling_django/) ([Lobsters](https://lobste.rs/s/04c6zh/three_tools_profile_django_app))
- [Reactor](https://github.com/edelvalle/reactor) - Phoenix LiveView but for Django.
- [Observing a Django backend with Honeycomb.io (2020)](https://www.yanglinzhao.com/posts/using-honeycomb/)
- [django-pgtrigger](https://github.com/Opus10/django-pgtrigger) - Postgres trigger support integrated with Django models.
- [django-pghistory](https://github.com/Opus10/django-pghistory) - Provides automated and customizable history tracking for Django models using Postgres triggers.
- [A complete guide to organizing settings in Django (2021)](https://apibakery.com/blog/django-settings-howto/) ([HN](https://news.ycombinator.com/item?id=29198346))
- [Why I Run Django on Kubernetes as a One-Man SaaS (2021)](https://anthonynsimon.com/blog/tools-of-the-trade/)
- [Django, HTMX and Alpine.js: Modern websites, JavaScript optional (2021)](https://www.saaspegasus.com/guides/modern-javascript-for-django-developers/htmx-alpine/) ([HN](https://news.ycombinator.com/item?id=29319034))
- [django-fsm](https://github.com/viewflow/django-fsm) - Adds simple declarative state management for django models.
- [Django APScheduler](https://github.com/jcass77/django-apscheduler) - Adds a lightweight wrapper around APScheduler. It enables storing persistent jobs in the database using Django's ORM.
- [Swapper](https://github.com/openwisp/django-swappable-models) - Django Swappable Models.
- [dj-stripe](https://github.com/dj-stripe/dj-stripe) - Django + Stripe Made Easy.
- [The Definitive Guide to Celery and Django](https://testdriven.io/courses/django-celery/) ([Code](https://github.com/testdrivenio/django-celery-project))
- [django-upgrade](https://github.com/adamchainz/django-upgrade) - Automatically upgrade your Django projects.
- [Integrate Pydantic with Django and Django REST Framework (2021)](https://blog.yezz.me/blog/Integrate-Pydantic-with-Django-and-Django-REST-Framework)
- [Database-backed Periodic Tasks](https://github.com/celery/django-celery-beat) - Celery Periodic Tasks backed by the Django ORM.
- [Create Django App](https://github.com/imagineai/create-django-app)
- [Django JWT Auth](https://github.com/webstack/django-jwt-auth) - JSON Web Token Authentication support for Django.
- [Django Async Orm](https://github.com/rednaks/django-async-orm) - Django module that brings async to django ORM.
- [drf-spectacular](https://github.com/tfranzel/drf-spectacular) - Sane and flexible OpenAPI 3 schema generation for Django REST framework.
- [Paperclip](https://github.com/makinacorpus/django-paperclip) - Add attachments to Django models.
- [Django-RQ](https://github.com/rq/django-rq) - Simple app that provides Django integration for RQ (Redis Queue).
- [django-clone](https://github.com/tj-django/django-clone) - Controlled Django model instance replication.
- [Jolie](https://www.jolie.dev/) - Gorgeous drop-in replacement of Django Admin. ([HN](https://news.ycombinator.com/item?id=30224838))
- [Django-invitations](https://github.com/bee-keeper/django-invitations) - Generic invitations app for Django.
- [Django IDOM](https://github.com/idom-team/django-idom) - Allows Django to integrate with IDOM, a reactive Python web framework for building interactive websites without needing a single line of JavaScript.
- [Django Easy Audit](https://github.com/soynatan/django-easy-audit) - Allows you to keep track of every action taken by your users.
- [Django Garnett](https://github.com/Aristotle-Metadata-Enterprises/django-garnett) - Field level translation library that allows you to store strings in multiple languages.
- [Django CORS Headers](https://github.com/adamchainz/django-cors-headers) - Django app for handling the server headers required for Cross-Origin Resource Sharing (CORS).
- [Security And Django](https://www.mattlayman.com/understand-django/secure-apps/)
- [Awesome Django Blogs](https://github.com/theArjun/awesome-django-blogs)
- [Django Sockpuppet](https://github.com/jonathan-s/django-sockpuppet) - Build reactive applications with the Django tooling you already know and love.
- [Django Celery Results](https://github.com/celery/django-celery-results) - Celery result back end with Django.
- [Polymorphic Models for Django](https://github.com/django-polymorphic/django-polymorphic) - Improved Django model inheritance with automatic downcasting.
- [Django Postgres Metrics](https://github.com/django-postgres-metrics/django-postgres-metrics) - Django application that exposes a bunch of PostgreSQL database metrics.
- [django-stubs](https://github.com/typeddjango/django-stubs) - Type stubs and a custom mypy plugin to provide more precise static types and type inference for Django framework.
- [Django Channels Rest Framework](https://github.com/LostMoa/djangochannelsrestframework) - Provides a DRF like interface for building channels-v3 websocket consumers.
- [django-structlog](https://github.com/jrobichaud/django-structlog) - Structured Logging for Django.
- [Django FastAPI ORM](https://github.com/kigawas/fastapi-django)
- [Djantic](https://github.com/jordaneremieff/djantic) - Pydantic models for Django.
- [nango](https://github.com/nicois/nango) - Streamlining Django forms to provide all the wins of single-page-applications without the pain.
- [Django PostgreSQL Materialized View Example](https://github.com/s-kust/django-postgresql-view) - Example of how to use a PostgreSQL materialized view in Django to speed up a complex query.
- [Django Debug Toolbar](https://github.com/jazzband/django-debug-toolbar) - Configurable set of panels that display various debug information about the current request/response.
- [Django Ratelimit](https://github.com/jsocol/django-ratelimit) - Cache-based rate-limiting for Django.
- [Django Admin Interface](https://github.com/fabiocaccamo/django-admin-interface) - Modern responsive flat admin interface customizable by the admin itself.
- [Django Step by Step](https://github.com/briancaffey/django-step-by-step) - Django + Vue reference project that focuses on developer tooling and CI/CD + IaC.
- [summarize-template](https://github.com/simonw/summarize-template) - Show a summary of a Django or Jinja template.
- [Rasters for Django](https://github.com/geodesign/django-raster) - Raster data integration for Django projects with a PostGIS database backend.
- [Anatomy of a Django/HTMX Project (2022)](https://danjacob.net/posts/anatomyofdjangohtmxproject/) ([HN](https://news.ycombinator.com/item?id=31104095))
- [snapshot-queries](https://github.com/cedar-team/snapshot-queries) - Capture all SQL statements executed via Django and SqlAlchemy ORM queries.
- [Pyngo](https://github.com/yezz123/pyngo) - Pydantic model support for Django & Django-Rest-Framework.
- [Enforcing Zero Downtime Django Migrations (2022)](https://cheigh.me/blog/posts/2022-05-10-enforcing-zero-downtime-django-migrations.html)
- [Djangox](https://github.com/wsvincent/djangox) - Django starter project with batteries.
- [The Django speaking tour 2022](https://www.paulox.net/2022/05/26/the-django-speaking-tour-2022/)
- [Tetra](https://www.tetraframework.com/) - Full stack reactive component framework for Django using Alpine.js ([Code](https://github.com/samwillis/tetra))
