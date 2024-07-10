# Recursos Humanos Application

Este repositorio contiene los archivos necesarios para desplegar la aplicación de Recursos Humanos usando Docker Compose. La aplicación está dividida en dos submódulos: `recursos-humanos-app` y `recursos-humanos-spring`, y una base de datos MySQL.

## Estructura del Proyecto

- **recursos-humanos-app**: Contiene la aplicación principal.
- **recursos-humanos-spring**: Contiene el backend de la aplicación.
- **mysqlserver_data**: Volumen de datos para la base de datos MySQL.
- **docker-compose.yml**: Archivo de configuración de Docker Compose.

## Requisitos Previos

Antes de empezar, asegúrate de tener instalados los siguientes programas en tu sistema:

- Docker
- Docker Compose
- Git

## Instrucciones de Configuración

### Clonar el Repositorio

Clona este repositorio y sus submódulos usando el siguiente comando:

```bash
git clone --recurse-submodules <URL_DEL_REPOSITORIO>

### Configuración de Docker Compose
El archivo docker-compose.yml contiene la configuración necesaria para desplegar la aplicación
