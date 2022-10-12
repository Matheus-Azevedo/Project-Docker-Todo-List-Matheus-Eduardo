FROM mjgargani/puppeteer:trybe1.0
RUN mkdir -p /app 
WORKDIR /app
ADD node_modules.tar.gz ./
COPY . .
ENTRYPOINT ["npm", "start"]
