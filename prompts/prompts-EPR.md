# Prompts

## Prompt 1
Necesito  un workflow de GitHub Actions que ejecute tests de backend para una aplicación Node.js. El workflow debe:
- Ejecutarse solo en las pull requests
- Configurar Node.js en la versión adecuada
- Instalar dependencias con npm o yarn
- Ejecutar los tests unitarios e integración con comandos específicos
- Fallar el pipeline si algún test no pasa
- Mostrar informes de cobertura si es posible

## Prompt 2
Añade la generación de un build de la aplicación de backend en Node.js al workflow cumpliendo lo siguiente:
- Crear un build optimizado para producción
- Verificar que el build se generó correctamente
- Almacenar el build como un artefacto de GitHub Actions

## Prompt 3
Añade la generación de un build de la aplicación de backend en Node.js al workflow cumpliendo lo siguiente:
- Crear un build optimizado para producción
- Verificar que el build se generó correctamente
- Almacenar el build como un artefacto de GitHub Actions

## Prompt 4
Añade el despliegue a una instancia EC2 de AWS. Sigue los siguientes requisitos:
- Configurar las credenciales de AWS usando secretos de GitHub
- Transferir el nuevo build a la instancia
- Verificar que el despliegue fue exitoso mediante un health check
