Use:
1. Run ```k create secret generic keycloak --from-literal=KC_DB_PASSWORD=<DB_PASSWORD> --from-literal=KEYCLOAK_ADMIN_PASSWORD=<KEYCLOAK_ADMIN_PASSWORD>```
2. Run kubectl apply -f kubernetes-config/
