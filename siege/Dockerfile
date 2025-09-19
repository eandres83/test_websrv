# Usamos una imagen base de Debian delgada
FROM debian:bullseye-slim

# Instalamos siege
RUN apt-get update && apt-get install -y siege --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*
