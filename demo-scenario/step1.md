Premier step.

## Task

Exemple d'execution d'une commande **command**

` docker run --name keycloak -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin -p 8080:8080 -it jboss/keycloak -b 0.0.0.0 -Djboss.socket.binding.port-offset=100&`{{execute}}

Pour accéder à la démo : https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/


