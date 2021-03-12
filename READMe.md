This is an overly simplistic application developped using the Flask micro web-framework. 
Of course you can do better in terms of code refactoring, but that's not the main focus here. 
It uses an already trained (linear regression) model to predict data that a user may send to the app.
It also caches in a Postgres database the last predicted value matching with the corresponding input sent by the user.

<u>What we ask you to do is:</u>
1. **containerize this app**, bundling it along with its dependencies using a **Dockerfile** 
2. **orchestrate it** using a **docker-compose.yml file**, with a **Postgres server** using the corresponding **Docker image** from the Docker Hub registry.