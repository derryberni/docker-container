# docker-container


#up sonar
sudo sysctl -w vm.max_map_count=262144
sudo docker-compose -f sonarqube-docker-compose.yml up
