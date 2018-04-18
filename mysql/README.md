# MYSQL Database
This shows how to setup a MySQL database in Kubernetes

# Steps
## Create the Configuration file
```
kubectl create mysql-config.yml
```
## Create the Persistent Volume Claim, Deployment and Service
```
kubectl create mysql.yml
```
## Get the Expose IP and Port
```
minikube service mysql-db --url
```