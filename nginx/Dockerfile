FROM nginx:latest

#Diretório que vou trabalhar dentro do container
#Entra por padrão quando roda o container
#WORKDIR /app 

#Roda os comandos no bash
#RUN apt-get update && \
#    apt-get install vim -y

#Copia conteúdo da pasta html para a /usr/share/nginx/html
COPY html /usr/share/nginx/html

#comando fixo
ENTRYPOINT ["/docker-entrypoint.sh"]

#comando variável
CMD ["nginx", "-g", "daemon off;"]
