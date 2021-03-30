# Ridiculously Simple Google Cloud Storage on App Engine + Flask

A ridiculously simple example of how to use Google Cloud storage on App Engine and Flask.

No backend. A simple entry point and an HTML template for when you just want to start making stuff.

## Setup

Install:
 * [Python 3.9](https://www.python.org/downloads)
 * [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
 * [pip](https://pip.pypa.io/en/stable/installing)

Install python libraries:
 	pip install

Edit main.py to include your Cloud Storage bucket name. App Engine instances include a default bucket with the name <app id>.appspot.com.

## Local server server

	python main.py

Note that Cloud Storage is not simulated locally so there's no much point running this code locally.

## Deploying

Replace [app id] with your very own App Engine id.

	gcloud app deploy app.yaml --project [app id] --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and start making stuff.

## Credits

Jude Osborn
