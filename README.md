# Containerized-react-app-test-deployment-on-google-cloud
fwfwefe

## test
- dadsa

- *Containerize frontend*
```
sudo docker build -t frontend:v3 .
sudo docker images frontend (check image)
sudo docker run -p 8091:80 frontend:v3 (run test - localhost:8091)
sudo docker ps (if there is something, remove it by its ID with sudo docker rm *id*)
sudo docker tag frontend:v3 localhost:32000/frontend:v3 (tag the image)
sudo docker push localhost:32000/frontend:v3 (push it)

```
