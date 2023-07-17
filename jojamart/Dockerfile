FROM node:20.4.0

ENV NUXT_HOST='0.0.0.0' 
ENV NUXT_PORT='3000'

WORKDIR /jojamart

COPY ./ /jojamart

RUN npm install
RUN npm run build

EXPOSE 3000

CMD ["npm", "run", "dev"]