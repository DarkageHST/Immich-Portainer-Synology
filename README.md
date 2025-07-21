# Immich-Portainer-Synology

docker-compose.yml

ein Ordner immich

im Ordner immich die beiden Ordner anlegen

postgres
library               - da werden die Bilder abgelegt , ich habe den in Upload umbenannt

mkdir immich

cd immich


example.env


UPLOAD_LOCATION=./library              - passt man auf an    /volume1/docker/immich/upload         ich habe das ja in Upload benannt  

DB_DATA_LOCATION=./postgres            -  passt man auf an /volume1/docker/immich//postgres  
