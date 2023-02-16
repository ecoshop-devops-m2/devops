# devops
This repo contains the docker compose for the monitoring stack and the docker compose for the Jenkins agent aswell as configuration for these tools.

</br>

## Monitoring 
Run `docker compose up -d` to build and start the monitoring stack. Each service that you should access via GUI has its port listed on Docker Desktop or in the config file. 

For alertmanager to work, please create you own config.yml in the alertmanager folder and follow the config.example.yml.
</br>

## CICD
As previously, run `docker compose up -d` to build and start the Jenkins Agent. You may need to install plugins for the pipeline to work such as Git and Github Integration. I recommend installing recommended plugins and see if it works out of the box.
