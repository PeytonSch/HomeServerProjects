FROM openjdk:18.0.2

#Make a minecraft dir
RUN mkdir -p /opt/minecraft/

ADD TheBearDen /opt/minecraft/

RUN chmod -R 777 /opt/minecraft/

RUN chmod +x /opt/minecraft/run.sh

RUN ls -al /opt/minecraft/

# CMD [ "/opt/minecraft/run.sh" ]