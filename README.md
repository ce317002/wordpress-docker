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
10. config nginx and ssl to create dns


# How to scale your website
1. If your website growth then we scaling the website if the service running in docker compose 
> docker-compose scale wordpress=2
2. If your service deploy in k8s scale service
> kubectl scale deployment/[name-deployment] --replicas=3
3. We can create load balancer in service to increas the performance our service or platform 
4. Create Automation to autoscale our service using other tools 
