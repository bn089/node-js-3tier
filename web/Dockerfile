FROM node:18

WORKDIR /usr/src/app

COPY package*.json . 

RUN npm install 

COPY . . 

ENV 	PORT=3000 \
        API_HOST=http://13.219.98.76:30001

EXPOSE 3000

CMD ["npm","start"]
	
