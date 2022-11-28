# docker-k8s
POC for docker k8s

````
docker build -t web:v6 .

docker image tag web:v6 manoj7shekhawat/web:v6

docker image push manoj7shekhawat/web:v6
````

After deploying k8s objects:
http://<EXTERNAL_IP of web service>:5000/
