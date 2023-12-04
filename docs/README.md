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





```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```





```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```









# Frontend Portals

- `online store` customer facing ecommerce web app
- `inventory-portal` for inventory management
- `dashboard-portal` for viewing, analysis and 

