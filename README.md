# CODIGO-nombre-apellido-iac-aws

Proyecto del taller de Cloud Computing (Ingeniería de Sistemas – UFPSO).

Despliega automáticamente en AWS una instancia EC2 con Apache y una página web
personalizada. La infraestructura está definida en `templates/template.yaml`
(CloudFormation) y el despliegue lo ejecuta GitHub Actions
(`.github/workflows/deploy.yml`) cada vez que se hace push a la rama `main`.

## Estructura

- `.github/workflows/deploy.yml`: flujo de GitHub Actions
- `templates/template.yaml`: plantilla de CloudFormation (EC2 + Security Group + User Data)
- `README.md`

## Estudiante

- Nombre: Juan Diego Moreno
- Código: 0192230
- Docente: Wilder Andrés Duarte Neira

## Sitio web desplegado

http://32.200.99.48/

(La IP cambia si la instancia se vuelve a crear.)
