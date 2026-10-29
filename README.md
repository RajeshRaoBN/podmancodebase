# podmancodebase

podman search httpd     # Search
podman search httpd --filter=is-official

podman images       # lists all the images that were previously used

podman run -dt -p 8080:80/tcp docker.io/library/httpd         # To deploy an appache server

podman ps       # To list all the containers

# Find
podman search
podman pull

# Run
podman run

# Build
podman build

# Share
podman push

# Documentation and examples
podman pull docker.io/library/httpd

podman inspect -l | grep IPAddress "IPAddress": ""

podman logs -l
podman top -l
podman stop -l      # To stop a container
podman ps -a
podman rm -l        # To remove a container

# Instalation

podman machine init
podman machine start
podman info
