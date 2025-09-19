# Usamos una imagen base de Debian delgada
FROM debian:bullseye-slim

# Instalamos git, los certificados y las herramientas de compilación
RUN apt-get update && apt-get install -y git ca-certificates build-essential --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*

# Establecemos el directorio de trabajo
WORKDIR /app
