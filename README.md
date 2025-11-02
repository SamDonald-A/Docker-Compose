# Microservices-Task

## Step 1
**Fork the given repo**

![git - image](https://github.com/user-attachments/assets/03396628-da54-4fff-9fa3-98f9e3ce250d)

![git - image](https://github.com/user-attachments/assets/58b566df-a369-42a4-ad6a-9f7a4d942287)

![git - image](https://github.com/user-attachments/assets/870c8714-884d-42ac-b70f-1833fdfaacf1)

![git - image](https://github.com/user-attachments/assets/24976ae9-a20f-4c65-9bf5-c7df68d3b7e0)

## Step 2
**Start the docker engine by opening your Docker Desktop App**

![docker start](https://github.com/user-attachments/assets/17d14446-db0a-4a88-bab6-c9cd99259dae)

## Step 3
**Create submision folder and open it in the VS Code Editor**

![create folder](https://github.com/user-attachments/assets/e82c0d2d-880a-4767-9a57-99cccd64a5a9)

![openin vscode](https://github.com/user-attachments/assets/3702f0ee-330b-4dc2-8376-707abf72509a)

**Clone the forked repository**

![clone the repo](https://github.com/user-attachments/assets/2bcbb572-9fa9-4ba5-a8c0-de3a5637e8ba)









## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---


## Services and Endpoints

### **User Service**
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://localhost:3000/users
    ```
    Or open in your browser: [http://localhost:3000/users](http://localhost:3000/users)

---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)

---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)

---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://localhost:3003/api/users
    ```
  - **Products:**  
    ```
    curl http://localhost:3003/api/products
    ```
  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders
    ```

---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```
2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
