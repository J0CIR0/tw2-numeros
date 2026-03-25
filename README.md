# Generador de Números Aleatorios

Aplicación PHP orientada a objetos que solicita al usuario N elementos y muestra N números aleatorios en una tabla.

## Requisitos

- Docker
- docker-compose
- Puerto 8082 disponible

## Instrucciones

1. Colocar esta carpeta en `./html/noo/` del proyecto que contiene `docker-compose.yml`
2. Ejecutar `docker-compose up -d`
3. Abrir http://172.25.0.217:8082/noo/
4. PHP 7.4 es el target; la app evita sintaxis de PHP 8+

## Uso

- Ingrese la cantidad de números a generar (1-1000)
- Opcionalmente defina el rango mínimo y máximo
- Click en "Generar" para ver los resultados

## Nota

No se requiere Composer; todas las clases se incluyen con `require_once`.
