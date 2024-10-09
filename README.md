# DigitalOceanConfig

Documentacao dos sites no Digital Ocean
torjc01/shortnsweet
| Site            | Github                    | DigitalOcean                | Micro | Porta | Linha de comando                                       |
|-----------------|---------------------------|-----------------------------|-------|-------|--------------------------------------------------------|
| Short'n'Sweet   | [torjc01/shortnsweet](https://github.com/torjc01/shortnsweet) | /app/nestjs/shortnsweet | n/a | 8024 | cd app/nestjs/shortnsweet; docker-compose up -d &      |
| Kryptogarten.ca | [torjc01/kryptogarten-site](https://github.com/torjc01/kryptogarten-site) | /app/node/kryptogarten-site | n/a | 4000 | docker run -d -p 4000:3000 juliozohar/kryptogarten:1.0 & |
| 4e Soldat       | [torjc01/4eSoldatSite](https://github.com/torjc01/4eSoldatSite) | /app/node/4eSoldatSite | n/a | 3000 | docker run -d -p 3000:3000 juliozohar/4esoldat:1.1 &    |


## Referências

Configuracao Digital Ocean para novo site

How To Configure Nginx as a Reverse Proxy on Ubuntu 22.04    
https://www.digitalocean.com/community/tutorials/how-to-configure-nginx-as-a-reverse-proxy-on-ubuntu-22-04

NGINX as Reverse Proxy for Node or Angular application    
https://www.digitalocean.com/community/tutorials/nginx-reverse-proxy-node-angular

How To Secure Nginx with Let's Encrypt on Ubuntu 20.04    
https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-20-04