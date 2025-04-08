# Grafana-NetH

The steps describe below are use to setup your own Grafana dashboard to monitor the traffic on your network.

 #Step 1 : Create storage volune for the container (Recommended)
 podman volume create grafana-storage
 #Step 2 : Validate the creation of your storage
 podman volume inspect grafana-storage
 #Step 3: Run  the doker-compose file to launch your container
