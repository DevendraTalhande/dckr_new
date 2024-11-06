clear  # Clears the terminal screen for a cleaner view

sudo apt-get update  # Updates the package list to fetch the latest versions of packages

clear  # Clears the terminal screen

sudo apt-get install docker.io  # Installs Docker on Ubuntu

clear  # Clears the terminal screen

docker pull mysql  # Pulls the latest MySQL Docker image from Docker Hub

whoami  # Displays the current username

clear  # Clears the terminal screen

cat /etc/group  # Displays the contents of the /etc/group file, listing groups on the system

clear  # Clears the terminal screen

docker --version  # Shows the installed Docker version

systemctl status docker  # Checks the Docker service status to see if it's active

clear  # Clears the terminal screen

docker ps  # Lists all running Docker containers

sudo usermod -aG docker $USER  # Adds the current user to the Docker group to avoid using 'sudo' with Docker commands

clear  # Clears the terminal screen

cat /etc/group  # Verifies that the user was added to the Docker group

clear  # Clears the terminal screen

sudo usermod -aG docker ubuntu  # Adds the 'ubuntu' user to the Docker group

cat /etc/group  # Verifies the 'ubuntu' user addition to the Docker group

clear  # Clears the terminal screen

docker ps  # Lists running Docker containers to check if Docker is set up correctly

sudo reboot  # Reboots the system, necessary to apply group changes for Docker permissions

clear  # Clears the terminal screen

docker stop mysql  # Stops a running Docker container named 'mysql' if it exists

docker images  # Lists all downloaded Docker images on the system

docker stop be960704dfac  # Stops a running container identified by its unique ID

docker ps  # Verifies which containers are currently running

docker stop 17b0a43043b4  # Stops another container using its ID

docker rm 17b0a43043b4  # Removes the stopped container by its ID

clear  # Clears the terminal screen

docker pull mysql  # Ensures the latest MySQL Docker image is downloaded

clear  # Clears the terminal screen

docker ps  # Lists running containers to verify setup

docker exec -it 381575ec9979 bash  # Opens an interactive terminal session inside a running container by ID

clear  # Clears the terminal screen

history  # Displays the command history for tracking or review
