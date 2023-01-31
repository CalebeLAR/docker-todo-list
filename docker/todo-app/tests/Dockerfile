FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /todo-app/tests
COPY . .
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "test" ]