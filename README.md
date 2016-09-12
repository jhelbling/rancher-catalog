# Rancher Catalog

* In this repo you can adjust the deployment of our services with rancher.
* In /templates, the different stacks are specified. (e.g. cfs-config-tool).
* the file config.yml specifies the description in the Rancher-Catalog-UI
* the file <stack>Icon-<stack>.svg is the logo shown in the Rancher-Catalog-UI
* Each stack has different deployment-versions (int-valued folders)
* each folder contains a docker-compose.yml and a rancher-compose.yml

# docker-compose.yml
* specifies the build

# rancher-compose.yml
* specifies which variables can be specified in the rancher-UI and then can be used in the docker-compose.yml
