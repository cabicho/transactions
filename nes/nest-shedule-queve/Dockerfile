From node:14.15.4-alpine3.12 
#//# 283.6MB
RUN npm install -g @nestjs/cli@8.2.0
USER		node 				
#// usuario da imagem e do container
WORKDIR 	/home/node/app 		
#// local de trabalho
COPY . /home/node/app
# RUN npm install 
# \ && npm run start:dev 

EXPOSE 3900

# ENTRYPOINT
#Learn more about the "ENTRYPOINT" Dockerfile command.
# ["top", "-b"]
# CMD []

#ENTRYPOINT 3300

RUN pwd && ls

RUN npm run start:dev

#CMD ["node", "dist/main"]