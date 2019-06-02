# ElasticSearch Study Server

This repo has been created for programmers and or data scientists who wish to learn about ElasticSearch without the boilerplate to configure nothing;

## What do I need to get this running

You will need to have only two services running on your machine;
* Docker: Tested with latest version of the community edition;
* Docker Compose: It's a tool that handles docker-compose.yml file in order to kickoff a ElasticSearch environment;

The system used for the test was a GNU/Linux with a Fedora distribution; I strongly recommend that you use a Linux environment, but your commands should run on docker for Windows without issues.

## Running

For running the stack, please do:

* Clone this repo (or download the zip and unzip it);
* Enter inside the directory of this repo and run;

```
$ docker-compose up
```

It will create the needed containers, volumes and networks used by docker and it output would be echoed on terminal.
To finish the work, shutdowning the process, just hit a `Ctrl + C` and the containers would be stopped;

If you wish to not see the output messages, you can trigger the containers in background appending a `-d` param just after the `docker-compose up` command.

# Presentation
This repo has been created for the ElasticSearch Meetup (in portuguese): [Google Slides](https://docs.google.com/presentation/d/1mLYXg-8tOhDj6QjBMzygQo50n4KGUerJE7oy5e5X9gY/edit?usp=sharing)
