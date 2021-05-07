# AUTHOR

Raman Sailopal

# Background

Docker compose file for the provision of yottadb container with M Gateway Service gateway as well as a Python client container with libraries installed to allow connection

# Prerequisites

It is assumed that Docker is running and that Docker compose is installed.

# Usage

Set the repodata variable to point to a directory for code on the host machine:

    export repopath="/opt/code"

This will map /opt/code on the host machine to /tmp/mgdbx on the container

Then run the deployment through:

    git clone https://github.com/RamSailopal/yottadb-python-compose.git
    cd yottadb-python-compose
    docker compose up

