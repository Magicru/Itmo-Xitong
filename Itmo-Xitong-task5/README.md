// Build docker image

``docker build . -t magicli/docker222``

// Run(Optionally pull) 

``docker pull magicli/docker222``  
``docker run -d -p 8000:8000 magicli/docker222``

//log example

running on http://localhost:8080

//enter container interactively

docker exec -it /bin/bash

//stop running container

docker stop <container_id>
