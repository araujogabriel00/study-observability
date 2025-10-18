FROM docker.elastic.co/beats/heartbeat:7.13.0
COPY heartbeat.yml /usr/share/heartbeat/heartbeat.yml

# GitHub Copilot: Esse arquivo é um **Dockerfile** usado para criar uma imagem Docker personalizada do **Heartbeat**, outro Beat do Elastic Stack.

# Veja o que cada linha faz:

# - `FROM docker.elastic.co/beats/heartbeat:7.13.0`  
#   Define a imagem base, que é o Heartbeat na versão 7.13.0, fornecida oficialmente pela Elastic.

# - `COPY heartbeat.yml /usr/share/heartbeat/heartbeat.yml`  
#   Copia o arquivo de configuração `heartbeat.yml` do seu diretório local para dentro da imagem, substituindo o arquivo de configuração padrão do Heartbeat.

# **Resumo:**  
# Esse Dockerfile cria uma imagem Docker do Heartbeat já configurada com o seu próprio arquivo `heartbeat.yml`, pronta para ser executada em containers.