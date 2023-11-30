FROM node:20.10-alpine3.17

# Set environment variables

# Install dependencies.
RUN npm install -g @angular/cli

USER node

# Set work directory.
WORKDIR /app

# Copy project code.
COPY / /app/

# Start server.
EXPOSE 4200
CMD npm start