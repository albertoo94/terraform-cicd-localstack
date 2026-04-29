# terraform-cicd-localstack
# CI/CD básico con Terraform y LocalStack

## Descripción
Este repositorio despliega automáticamente una infraestructura Terraform en LocalStack mediante GitHub Actions.

## Workflow
El flujo de trabajo se ejecuta en cada push a la rama `main` y realiza:
- terraform init
- terraform plan
- terraform apply
- verificación final del recurso en LocalStack
