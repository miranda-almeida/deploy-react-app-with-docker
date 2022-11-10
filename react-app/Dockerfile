# puxa imagem base
FROM node:16.14 as build

# define a pasta padrão
WORKDIR /app

# copia arquivos para instalação
# a esquerda são arquivos/portais locais e a direita são arquivos/portas do container
COPY package.json .

# o package-lock.json garante a integridade da aplicação
COPY package-lock.json .