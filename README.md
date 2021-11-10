# How to deploy wordpress with docker compose
1. Install docker compose
2. Create folder for wordpress
3. Then create file docker-compose.yml to pulling image and wordpress from dockerhub or registry internal
4. Fill file docker-compose.yml like file docker-compose.yml repository above
5. Running compose with command to pulling images and run image
>docker-compose up -d
7. Check status wordpress service 
>docker-compose ps
9. If wordpress already running visit website with localhost:port or with nginx to share your website with dns
