FROM mjgargani/puppeteer:trybe1.0
WORKDIR ./todo-app/tests/
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3000
CMD ["npm", "test"] 
