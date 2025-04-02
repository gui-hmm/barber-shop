# Imagem base
FROM gradle:8.11.1-jdk-21-and-23

# Atualizando pacotes e instalando dependências necessárias
RUN apt-get update && apt-get install -qq -y --no-install-recommends

# Diretório de instalação
ENV INSTALL_PATH /barber-shop-api
RUN mkdir $INSTALL_PATH

WORKDIR $INSTALL_PATH

# Copiar o conteúdo do projeto
COPY . .

# Instalar dependências e rodar o aplicativo
RUN gradle build --no-daemon

# Expor a porta 8080 para acesso externo
EXPOSE 8080

# Comando para rodar a aplicação Spring
CMD ["gradle", "bootRun"]
