How to Start docker in local machine
	1) Start podman socket with command {systemctl --user start podman.socket}
	2) Start and create the containers: Run the following command to build, create, and start all services defined in your docker-compose.yml file in the background:
		{docker compose up -d}
	3) Verify you are in the right folder: Make sure your terminal is currently inside the exact folder that contains your docker-compose.yml file. Run ls to confirm the file is there.
	4) Check for containers outside Compose: Run podman ps -a (or docker ps -a) to see if a mysql container already exists elsewhere on your system under a different project name.
	
