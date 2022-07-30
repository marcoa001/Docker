FROM node:12.22.1-alpine3.11

 # /app es un dir que no existe en node pero lo va a crear
WORKDIR /app   
# el primer . significa q va a copiar todo lo q esta en este dir y el 2° que va a pegar todo en el /app
COPY . .   
RUN yarn install --production 
# especificar el comando q va a correr
CMD ["node", "/app/src/index.js"] , 
