# CRUD Products - DevOps Pipeline

## Descripción
Este proyecto implementa un CRUD de productos en Python usando archivos JSON.

## Funcionalidades
- Crear productos
- Leer productos
- Actualizar productos
- Eliminar productos

## Pruebas
Las pruebas se ejecutan con pytest.

## Pipeline CI/CD
El pipeline en GitHub Actions realiza:

1. Instalación de dependencias
2. Verificación de código con flake8
3. Ejecución de pruebas unitarias

## Ejecución local

Instalar dependencias:

pip install -r requirements.txt

Ejecutar pruebas:

pytest
