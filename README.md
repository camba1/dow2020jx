## Fast track cloud development with JenkinsX

This repo is a clone of the repo used during the DevOps World 2020 session called Fast track cloud development with JenkinsX
The session depicts using Jenkins X to push an application to Kubernetes running in Google Cloud

While the application will run locally, a Jenkins X cluster is required to run throught the session demo.

#### Running locally

You can run locally using docker-compose with `docker-compose up`.
To view the application open your browser and point it to  localhost:8080
To stop the project, run `docker-compose down`.

### Quick notes

- The node_modules and mysqlDB directories are checked in to this repository to speed up some of the builds during the demo. That way we avoid having to re-dowload them when doing the initial docker builds. Normally these directories should not be checked in.


- The docker-compose file is not required for the demo, but it is so useful during development!


- We have the DB password checked into the repo. It is my throw away password for all my public repos so that is not an issue. However, in a normal project, passwords should never be checked in to source control.




