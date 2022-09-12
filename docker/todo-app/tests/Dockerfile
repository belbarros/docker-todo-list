FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
# RUN npm install
CMD ["npm", "test"]
