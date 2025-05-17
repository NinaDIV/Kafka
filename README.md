 # 🚀 Kafka con Docker Compose - Demo "Hola Mundo"

![Kafka Logo](https://kafka.apache.org/images/logo.png)

Este proyecto demuestra cómo configurar un entorno básico de **Apache Kafka** usando Docker Compose, incluyendo una prueba práctica de envío/recepción de mensajes.

## 📋 Prerrequisitos
- Docker 20.10+
- Docker Compose 2.0+
- 2GB RAM disponibles

## 🐳 Configuración del Entorno

```bash
# Levantar los servicios (Zookeeper + Kafka)
docker-compose up -d

# Verificar estado
docker-compose ps
