# Docker Compose for Java Servlet with Tomcat

This is a minimal example project of using Tomcat docker image to run war files. I've added a mysql database and adminer as demonstration also.

**How to run**:

`docker compose up`

**How to run rebuilding image (if you change war file):**

`docker compose up --build`

**How to access the application:**

Java application: [http:localhost:8080](http:localhost:8080)

Adminer for database inspection (credentials can be found in the `docker-compose.yml` file): [http:localhost:8081](http://localhost:8081)

Note: The war file used for testing deploy was downloaded from here: https://github.com/efsavage/hello-world-war
