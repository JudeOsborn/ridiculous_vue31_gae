# Ridiculously Simple Vue + App Engine

Absolutely the simplest Vue + App Engine web app I could imagine. 

No backend. Everything goes through the .yaml file. 

Static files go in the /static folder. Nothing but a favicon.

Vue loaded via CDN.

## Setup

Install:
 * [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

## Local server server

	dev_appserver.py .

## Deploying

Replace [app id] with your very own App Engine id.

	gcloud app deploy app.yaml --project [app id] --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and start making stuff.

## Credits

Jude Osborn

