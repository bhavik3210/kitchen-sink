# kitchen-sink

> E-commerce for kitchenware

# Backend Services

- `inventory-management` service for Inventory Management System
- `order-management` service for processing order (not payment)
- `payment-processor` service for processing payments 
  - connecting to third party service for cc validation, etc.
- `customer-management` service for managing customers data 
- `reporting` service for generating stastical reports for stakeholders
- `catalog-service` service for frontends 
- `notification-service` service for sending out notification (email, text, etc.)

# Frontend Portals

- `online store` customer facing ecommerce web app
- `inventory-portal` for inventory management
- `dashboard-portal` for viewing, analysis and 

# Tech stack

- Go for cloud services/dev ops
- Python for internal apps on reporting, any other data related work
- React/Typescript for frontend portal
- Docker and k8s for managing microservice architecture 
- Even driven architecture
- Rest api first then migrate to grpc when it seems beneficial
