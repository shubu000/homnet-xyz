# homnet-xyz
Repo for apps used in my own personal network

The core docker-compose has Traefik + Portainer as the core of the network

Pihole
Personal DNS + Ad blocker, deployed with a cloudflared for DNS over https
The cloudflared container is within its own external network
Future work, hide port 53 behind the traefik reverse proxy

Unifi
Unifi Network Controller 

Paperless
Personal Document management system

Heimdall 
Personal dashboard for apps

Watchtower
Automatic docker update
