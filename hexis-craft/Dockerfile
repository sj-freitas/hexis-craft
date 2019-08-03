FROM itzg/minecraft-server
WORKDIR /home
EXPOSE 25565
COPY . .

ENV WORLD="/home/world"

WORKDIR /data
ENTRYPOINT [ "/start" ]
