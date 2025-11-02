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

![clone the repo](https://github.com/user-attachments/assets/d39bd701-b96b-4b2d-9c78-956f42e6ec2c)

**Create Dockerfile in each folder and add the script in all the package.json**

![docs](https://github.com/user-attachments/assets/5dd64314-c8c3-4495-9112-e29161b5b939)

![npm edit](https://github.com/user-attachments/assets/81ccc4b8-4006-4ca3-a58b-48a6cf60323a)

**Create the docker-compose.yml and write the build for all three services**

![ymlfile](https://github.com/user-attachments/assets/1fac7543-4d98-4e4e-91b9-f4d516684730)

**We see that currently no Container is running in the Docker**

![docksno](https://github.com/user-attachments/assets/b0051bb8-8981-4aec-a617-2a3bd7f9b0f4)

![nodockcmd](https://github.com/user-attachments/assets/8ffff8f0-5910-4799-8704-2e7a8ae084ac)

**Let's run docker-compose up --build and create the container and check from Docker app and terminal that its created or not**

![ymlbuild](https://github.com/user-attachments/assets/8ea82a2f-0244-47d7-a0cc-d518d32d974c)

![successyml](https://github.com/user-attachments/assets/57082b3d-5e5d-41e0-88cc-3613f09c0d67)

![docksrunning](https://github.com/user-attachments/assets/f49b0e8d-2a6c-4e35-a353-08680d99a3f9)

![cmdter&#39;](https://github.com/user-attachments/assets/b73cef86-e64d-4856-a3b3-9c1b22fefde5)

## Step 4
**Open the respected ports in the browser to see the data**

![user3000](https://github.com/user-attachments/assets/78c37e33-41ed-4de6-93f6-dd3168341d64)

![prod3001](https://github.com/user-attachments/assets/abc9ac85-35f6-4341-8c2c-55da27366381)

![gatapi](https://github.com/user-attachments/assets/a223def3-d573-4267-b6f7-550b6a2caf00)

## Step 5
**Push the code to Github**

![gitpush](https://github.com/user-attachments/assets/74db6819-470f-4229-8959-087b89485eef)



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
