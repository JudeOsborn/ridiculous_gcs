# Ridiculously Simple Google Cloud Storage on App Engine + Flask

A ridiculously simple example of how to use Google Cloud Storage with App Engine and Flask.

## Setup

Install:
 * [Python 3.9](https://www.python.org/downloads)
 * [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
 * [pip](https://pip.pypa.io/en/stable/installing)

Install python libraries:
 	pip install

Edit main.py to include your Cloud Storage bucket name. Note that App Engine instances include a default bucket with the name <app id>.appspot.com.

## Local server server

	python main.py

However, Cloud Storage is not simulated on a local dev server so there's no much point running this code locally.

## Deploying

Replace [app id] with your very own App Engine id.

	gcloud app deploy app.yaml --project [app id] --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and start making stuff.

## Credits

Jude Osborn
