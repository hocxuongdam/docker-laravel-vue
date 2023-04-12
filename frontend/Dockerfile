# BASE IMAGE
FROM node:19-alpine

# SET WORKING DIRECTORY
WORKDIR /app

# COPY package.json and yarn.lock first because of the reuse of layering cache
COPY package.json package-lock.json ./

# INSTALL DEPENDENCIES
RUN npm install

# COPY OTHER FILES (DO THEY OVERWRITE?)
COPY . .

# EXPOSE THE PORT
EXPOSE 5173

# START THE SERVER
CMD ["npm", "run", "dev"]
