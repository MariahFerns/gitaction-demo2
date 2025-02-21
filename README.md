## This project shouw how to work with github action 
On any change (push/pull)
Create a docker image and connect to docker hub and push the image to hub
pytest
Before it sends on docker hub, it performs the test and then pushes it to docker hub

From docker hub, the image can then be pulled and deployed wherever you want