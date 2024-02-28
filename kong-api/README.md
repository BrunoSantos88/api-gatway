# Introduction to Kong Gateway

- Understand basic concepts of API Kong 
- Services
- Routes
- Consumers
- Kong Plugins to extend Kong API Gateway
- Key Auth
- Rate Limiting
- Use Kong Manager and the Kong Admin API for management
- Use Insomnia to design an API using the OpenAPI Specification 
- Basic Kong Konnect Gateway Troubleshooting 
- Convert an OpenAPI Specification into API Kong
- Import/Export API Kong Config with decK

# LAB de Instalação:

- curl -Ls https://get.konghq.com/quickstart | bash
- docker-compose up -d



# Setup a Local Containerized Kong Gateway

- Task 1: Install Kong Gateway
- Task 2: Verify Kong Gateway
- Task 3: Evaluate Kong Gateway configuration

# Working with Kong Manager

- Task 1: Login to the Kong Manager UI and select the 'default' Workspace
- Task 2: Create a Kong API Service for an upstream application
- Task 3: Create our new Route for our API Service
- Task 4: Verify Forwarding a request through Kong Gateway

# Plugin Configuration Using Kong Manager

- Task 1: Enable a Plugin for Authentication
- Task 2: Verify that the plugin is correctly configured
- Task 3: Enable a Consumer
- Task 4: Provision key credentials for the Consumer 'Joe'
- Task 5: Verify the Consumer credentials and that the Key Auth plugin is correctly configured

 # Create Resource Objects Using Kong Admin API

 - Task 1: Verify Kong Admin API is Running
 - Task 2: Create a Service
 - Task 3: Create a Route
 - Task 4: Verify Forwarding a request through Kong
 - Task 5: Create a Consumer 'Jane'
 - Task 6: Provision key credentials for Consumer 'Jane'
 - Task 7: Verify Forwarding a request through Kong
 - Task 8: Verify all Items with the Admin API
 - Task 9: Verify all Items with in Kong Manager