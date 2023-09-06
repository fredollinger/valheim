# Valheim

Scripts to spin up a Valheim Server.

Assumes a Debian/Ubuntu Linux Distribution.

## Set up Docker

One time set up

```
./pre-docker-install.sh
./get-docker.sh
./post-docker-install.sh
```

# Create the Valheim Server Script

Copy the script template and fill in the variables:

```
cp run-valheim-docker-container.sh.in run-valheim-docker-container.sh
```

# Start the Valheim Server

Run each time you need to start the server.

```
./run-valheim-docker-container.sh
```

# Stop the Valheim Server
