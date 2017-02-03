# elastic-docker-cluster
Elastic docker (compose) cluster for development

1) Create your local docker registry
2) set EDC_DOCKER_REPO to point to the registry
3) edit your hosts file so that edc_ingest and edc_kibana are available from localhost

127.0.0.1 edc_kibana.localdomain edc_kibana
127.0.0.1 edc_ingest.localdomain edc_ingest

4) docker-compose up

5) Point your browser to http://edc_ingest:9200/ or http://edc_kibana:5601/