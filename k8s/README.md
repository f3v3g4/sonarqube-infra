# Infraestructura de SonarQube y PostgreSQL

Este directorio contiene la configuración de Kubernetes para desplegar SonarQube con PostgreSQL.

## Archivos

- `postgres-pv-pvc.yaml`: Persistent Volume y Persistent Volume Claim para PostgreSQL.
- `postgres-deployment.yaml`: Despliegue de PostgreSQL.
- `sonarqube-deployment.yaml`: Despliegue de SonarQube.
- `sonarqube-service.yaml`: Servicio para SonarQube.

## Despliegue

1. Asegúrate de que tu clúster de Kubernetes esté funcionando.
2. Configura ArgoCD para apuntar a este repositorio.
3. Crea una nueva aplicación en ArgoCD que apunte a este directorio.
