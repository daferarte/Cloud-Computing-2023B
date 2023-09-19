FROM node:14-alpine
# Add a work directory
WORKDIR /app
# Cache and Install dependencies
COPY ./front/package.json .
RUN npm install

COPY ./front/ .

# Expose port
EXPOSE 3000
# Start the app
CMD [ "npm", "start" ]