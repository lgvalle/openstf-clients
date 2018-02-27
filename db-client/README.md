# Database

You only need **one** database client in your setup. All the dashboard clients will need to point to it

* web access through port: 8080
* dashboard clients connect to port 28015

1. Deploy this container using `docker-compose up -d`
2. Write down the IP of the machine where it runs. You'll need to pass it to the dashboard clients
