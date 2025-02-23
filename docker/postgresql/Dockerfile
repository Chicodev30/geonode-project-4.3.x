ARG BASE_IMAGE_VERSION
FROM geonode/postgis:${BASE_IMAGE_VERSION}

# Copia o script SQL para dentro do container
COPY TMPOA-srid.sql /docker-entrypoint-initdb.d/