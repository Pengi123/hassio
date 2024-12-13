ARG BUILD_FROM=node:18-alpine
FROM ${BUILD_FROM}

# Install necessary dependencies
RUN apk add --no-cache git

# Clone the Maintainerr repository
RUN git clone https://github.com/jorenn92/Maintainerr.git /app

WORKDIR /app

# Install npm dependencies
RUN npm install

# Expose the correct port per the Maintainerr docs
EXPOSE 6246

# Start the application
CMD ["npm", "start"]
