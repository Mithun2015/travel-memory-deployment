# Travel Memory
## 📌 Project Overview

Travel Memory is a MERN stack application deployed on AWS EC2.
It includes a React frontend, Node.js backend, MongoDB Atlas database,
Nginx reverse proxy, and Application Load Balancer for scalability.

## 🚀 Live Application
http://travelmemoryapp.duckdns.org
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/61beec1d-90c5-4c1b-b5f3-0401b51fda8b" />


## Tech Stack
React
Node.js
Express
MongoDB Atlas
AWS EC2
Nginx
PM2
ALB
DuckDNS

## Deployment Architecture
Internet → ALB → EC2 → Nginx → Node → MongoDB Atlas

## Backend Setup Steps
Clone repo

<img width="789" height="153" alt="image" src="https://github.com/user-attachments/assets/eac7e879-e6d0-4d9d-a15e-70b1abf275fe" />

Install dependencies
<img width="968" height="572" alt="image" src="https://github.com/user-attachments/assets/c18364d9-1f77-47ad-a8be-6e93e4cc53c6" />
Create .env
<img width="968" height="124" alt="image" src="https://github.com/user-attachments/assets/9d1b0edb-fccd-4a1b-879d-716ad30bd431" />

Start using PM2
<img width="968" height="1636" alt="image" src="https://github.com/user-attachments/assets/4265e37b-f8ac-4836-88e2-3ec4b0bea16f" />


## Frontend Build Steps
Update src/url.js

Run npm run build
Nginx config

## MongoDB Atlas Setup
Include:
Free cluster creation
<img width="475" height="26" alt="image" src="https://github.com/user-attachments/assets/cb7e0043-d931-4a1d-8b8d-68e4e5262791" />

<img width="794" height="259" alt="image" src="https://github.com/user-attachments/assets/9dec475d-dd99-447f-86d7-de83a3f70951" />

<img width="968" height="3052" alt="image" src="https://github.com/user-attachments/assets/a3ca3fef-08df-461d-a8c6-45884b7ea9cb" />

DB user creation
Network access setup

## Nginx Reverse Proxy Config
<img width="908" height="165" alt="image" src="https://github.com/user-attachments/assets/02eb790f-9f63-455d-ac6c-9daf9d6bbe1c" />
<img width="908" height="165" alt="image" src="https://github.com/user-attachments/assets/4aa404b1-76bc-43e7-a15a-a0065c49bb48" />
<img width="968" height="764" alt="image" src="https://github.com/user-attachments/assets/fe3df551-cf5b-474e-a072-3a6b10e4d718" />
<img width="968" height="1016" alt="image" src="https://github.com/user-attachments/assets/bcf257fb-c446-4010-a65b-9d2b9b910691" />



## Load Balancer & Scaling
Document:
AMI creation
Launching multiple instances
<img width="1280" height="724" alt="image" src="https://github.com/user-attachments/assets/8ea56293-7308-4491-869c-c69d815f1dcd" />

Target group setup
<img width="1278" height="723" alt="image" src="https://github.com/user-attachments/assets/875dd6ef-b3f8-4263-a061-485c2d2700ae" />

Listener rules
<img width="1095" height="286" alt="image" src="https://github.com/user-attachments/assets/31dac9f4-7f24-4f77-bd72-8b998de3cddb" />



## Challenges & Fixes
## ⚠ Challenges Faced
- Production build still pointing to localhost
- Nginx proxy path rewrite issue
- MongoDB authentication error
## ✅ Solutions
- Updated src/url.js
- Removed trailing slash in proxy_pass
- Configured environment variables properly







