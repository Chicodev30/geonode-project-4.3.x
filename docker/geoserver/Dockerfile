ARG BASE_IMAGE_VERSION
FROM geonode/geoserver:${BASE_IMAGE_VERSION}

# Garantir que o arquivo antigo seja deletado antes de copiar o novo (caso necessário)
RUN rm -f /usr/local/tomcat/webapps/geoserver/WEB-INF/lib/gt-epsg-hsql-30.3.jar
COPY ./gt-epsg-hsql-30.3.jar /usr/local/tomcat/webapps/geoserver/WEB-INF/lib/
