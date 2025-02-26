from node:18.9.1
workdir /app
copy package.json .
run npm install
copy . .
expose 5050
cmd ["npm","start"]