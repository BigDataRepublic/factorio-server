# factorio-server
Private Factorio server running on our company server

## How to
Run `kubectl apply -f factorio.yaml` to start a Deployment.

## Settings
You can change the configuration in the files in `/var/data/factorio` on the host or `/factorio` from the container itself.
This is also the folder where all the map files are located.
