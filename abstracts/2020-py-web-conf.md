Testing Best Practices
======================

**Format:** 3 hour tutorial

We'll use a non-trivial Flask application to review general best practices when testing.  In
addition, we'll examine methods for testing an application when it must interact with services
outside itself.  In particular, we will review how to test:

* Database
* Celery tasks
* 3rd party external APIs (REST/JSON)
* CLI commands
* Emails
* Using Continuous Integration (CI) services

We will discuss both principles and implementation so that even if you don't use Flask, the
principles learned can be applied to other frameworks (Django, etc.).

Preparation
-----------

This is an intermediate to advanced talk so attendees should feel comfortable:


* working in Python
* cloning repos from GitHub
* using pip and friends to create virtualenvs and install dependencies
* running applications from the command line
* using Docker and docker-compose to spin up external services (database, email, RabbitMQ) or
  having those services installed & available at the OS level
* familiarity with using pytest will be helpful

I will post a repo a few days prior to the event that attendees can use to get their environment
setup to be prepared for the tutorial.


Flask: Beyond Hello World!
==========================

**Format:** 45 min presentation

Getting started in Flask is super easy.  But what happens when your application needs more than
just the basics?  Flask's simplicity makes it easy to get started but also means you have to do
more legwork as your application's needs grow.

We will start from a typical "Hello World" Flask app and then discuss integration of features needed
for many modern web applications, including:

* Utilizing application factory pattern & blue prints
* Automated testing with pytest
* CLI integration with external packages and global options
* Logging
* Database integration with Flask-SQLAlchemy
* Distributed task queues for background tasks


Preparation
-----------

A familiarity with Flask will be helpful, but not required.  The presentation will mostly be
focused on concepts, not on the fine details of implementation.  A companion GitHub repository
will be available after the talk so attendees can dig deeper into implementation if desired.
