# Loadbalanced applications
> Java, NodeJS, Python web applications loadbalanced through NGINX. All aplications are running in containers in their own docker bridged network.
The stack is provisioned by Ansible from the [provisioning repo][1]

## Applications

### Java
- PORT: `50001`

### NodeJS
- PORT: `50002`

### Python
- PORT: `50003`

### Nginx Loadbalancer
- PORT: `8090`

## Monitoring Stack
> ELK stack on Docker containers

### Logstash
- PORT: `5000`

### Elasticsearch
- PORT: `9200`

### Kibana
- PORT: `5601`

### TODO
- [x] pornirea aplicatiilor ca servicii (pentru simplitate toate aplicatiile vor fi pornite pe aceeasi masina)
- [x] un load balancer care sa directioneze request-urile venite la una dintre aplicatii
- [x] o stiva ELK pentru colectarea logurilor si monitorizarea aplicatiilor

[1]: https://github.com/dminca/scaling-fiesta

