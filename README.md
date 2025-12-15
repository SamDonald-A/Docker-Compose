# Microservices Kubernetes Deployment Assessment
---

# Objective: 
Deploy a microservices application on Kubernetes using Minikube, ensuring proper service communication and configuration.

GitHub Links: https://github.com/SamDonald-A/Docker-Compose/tree/skill-test-2 

# Step 1: Clone the repo

<img width="976" height="501" alt="image" src="https://github.com/user-attachments/assets/0ee369d1-fcc5-457c-b46f-316597f6170a" />

Create Dockerfile in every service folder
---
<img width="976" height="580" alt="image" src="https://github.com/user-attachments/assets/1636ff46-a709-40af-8541-1092104f34ea" />

After creating Dockerfiles build them using docker build -t name/serviceName .
---
<img width="974" height="429" alt="image" src="https://github.com/user-attachments/assets/3366283c-402e-4909-b7f5-e9d25134ac81" />

Create repo for each service in DockerHub
---
<img width="976" height="412" alt="image" src="https://github.com/user-attachments/assets/27787505-e005-4988-b857-cc6cb7f5b37e" />

Push the images to its respected repositories
---
<img width="974" height="215" alt="image" src="https://github.com/user-attachments/assets/412012d0-03ee-4020-bac0-6b2dec074eaa" />

Do the same with other services as well
---
<img width="974" height="330" alt="image" src="https://github.com/user-attachments/assets/beaab8df-d28b-4b16-af93-ac0da0d945f8" />

After that create deployment folder and write kuberneties menifest code
---
<img width="974" height="610" alt="image" src="https://github.com/user-attachments/assets/aa4cc3ba-976c-4c6a-9e4b-89fd3760e6d3" />

Make sure you are entering correct repo names in each yml files
---
<img width="974" height="603" alt="image" src="https://github.com/user-attachments/assets/523453cb-4411-4fe3-bd12-f03947d28152" />

We can see each service repositories in DockerHub
---
<img width="974" height="344" alt="image" src="https://github.com/user-attachments/assets/6d51050b-dbaf-46a4-8037-2267afb731fd" />

# Step 2: Minikube Setup

Go to minikube installer in the browser and download the compatable version and install in your local system
---
<img width="976" height="449" alt="image" src="https://github.com/user-attachments/assets/497f68b5-4a72-4d4c-bb4c-9373f070b159" />

After installing check in the terminal 
---
<img width="974" height="395" alt="image" src="https://github.com/user-attachments/assets/b14a7537-a146-43b6-8991-512c54fa5759" />

Now change the context in the terminal to use it
---
<img width="974" height="112" alt="image" src="https://github.com/user-attachments/assets/a536b82e-12f2-40bb-855b-7ed7e9a1e699" />

after starting the minikube apply all the deployment yml files
---
<img width="973" height="326" alt="image" src="https://github.com/user-attachments/assets/d98d73f8-8bf7-449b-9dc9-4e98b7e16d6c" />

Create service folder and create services for each service
---
<img width="976" height="359" alt="image" src="https://github.com/user-attachments/assets/638d479f-a93f-4f59-97f9-f9d1429b413f" />

Apply all services as well
---
<img width="974" height="121" alt="image" src="https://github.com/user-attachments/assets/58fee46f-d728-4795-8445-6b03b7c21452" />

Verify the pods and services are created
---
<img width="976" height="455" alt="image" src="https://github.com/user-attachments/assets/9dfa6816-b734-4470-9ee9-1c894d2d19e0" />

Port forwarding to check the services
<img width="974" height="326" alt="image" src="https://github.com/user-attachments/assets/a8603406-d9d2-4ab4-b8d7-d4481f7b1f4b" />

Check them on browser
---
<img width="916" height="601" alt="image" src="https://github.com/user-attachments/assets/92c27570-a5fb-4854-8019-c13def14fb80" />
---
<img width="832" height="502" alt="image" src="https://github.com/user-attachments/assets/d4f84c94-7753-459c-8b7a-4058f8fe40b7" />
---
<img width="940" height="607" alt="image" src="https://github.com/user-attachments/assets/eb4b4c19-6adc-406a-9e55-1f3ea09dbd10" />

# Step 3: Setup Ingress

Create ingress folder and file and write ingress setup
---
<img width="974" height="438" alt="image" src="https://github.com/user-attachments/assets/034151e3-ddde-459d-ad30-6dc5538aac40" />

Create Ingress controller
Install Nginx controller and check the service is created or not
---
<img width="976" height="400" alt="image" src="https://github.com/user-attachments/assets/c099de6f-f8a4-43ed-ac99-5f7b605cc42b" />

Apply the ingress for gateway
---
<img width="976" height="113" alt="image" src="https://github.com/user-attachments/assets/27b197ee-3f75-4f96-9369-13e7cd9aa6cd" />


Since we are running our pods on minkube the localhost/services will not work, but we need to use minikube IP to see on the browser. Get the ingress address and use it on the browser
---
<img width="976" height="338" alt="image" src="https://github.com/user-attachments/assets/540c9735-0427-42ad-801d-9308063c0ca6" />


Now it’s able to access via IP
---
<img width="921" height="609" alt="image" src="https://github.com/user-attachments/assets/f64c90b6-7eff-4d06-aa15-a3ce2dd8b2c3" />
---
<img width="800" height="483" alt="image" src="https://github.com/user-attachments/assets/2f274453-75bd-46a5-b143-b168bb5df4f2" />
---
<img width="938" height="548" alt="image" src="https://github.com/user-attachments/assets/8206018d-3057-454f-9314-44fb0cd55ec4" />


---
---

Documentation by: Sam Donald A

Email: samdonaldand@gmail.com

GitHub: https://github.com/SamDonald-A

Website: www.samdonald.in


