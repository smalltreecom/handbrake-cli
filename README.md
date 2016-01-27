# handbrake-cli
docker run -t -i -v /directory_on_host:/mountpoint_on_guest smalltree/handbrake-cli:latest /bin/bash

docker run -t -i -v /directory_on_host:/mountpoint_on_guest -v /etc/localtime:/etc/localtime:ro  smalltree/handbrake-cli:latest /bin/bash

HandBrakeCLI
