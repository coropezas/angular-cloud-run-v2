# Laboratorio Canary Deployment

## Prerequisitos:
1. cuenta de servicio en google
2. environment dev con aprobadores

## Pasos
1. Crear cuenta de servicio
2. configurar cuenta de servicio en github con el nombre de SA_GCP_DEV a nivel de repositorio
3. configurar variable de entorno ENVIRONMENT_NAME a nivel de environment dev
4. configurar variable de entorno ALUMNO_ID a nivel de environment dev
5. Ejecutar workflow .github/workflows/utec.yml
