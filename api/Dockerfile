FROM node:18

WORKDIR /usr/src/app

COPY package*.json . 

RUN npm install 

COPY . . 

ENV 	PORT=3001 \
	DB=hello \
	DBUSER=admin \
	DBPASS=kaizen123! \
	DBHOST=database-2-instance-1.c4b82e0eyi7z.us-east-1.rds.amazonaws.com \
	DBPORT=3306

EXPOSE 3001

CMD ["npm","start"]
	
