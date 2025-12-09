FROM quay.io/keycloak/keycloak:26.3.4
COPY realm-export.json /opt/keycloak/data/import/
CMD ["start-dev", "--import-realm"]

