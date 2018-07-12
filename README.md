# ansible-pan-geolocation
Updates a list of PAN devices with the geolocation (latitude and longitude coordidates). Partial changes for the specified username are commited after applying the configuration.

## Device settings
Firewall credentials and HTTP settings are defined in firewall-secrets.yml

## Inventory
Create the list of devices inventory.ini, including the latitude and longitude coordinates.

## Run
ansible-playbook firewalls.yml