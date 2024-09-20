# es2024-studentcode-lab2

![image](https://github.com/user-attachments/assets/5dab0728-4d62-4917-92b6-72b97246c86a)

## 1.docker start beautiful_wilson 
## 2.docker run --name mongodb-container -d -p 27017:27017 mongo  
## 3.docker build -t express-app .
## 4.docker run --name express-container --link mongodb-container -d -p 3000:3000 express-app(express-container ถ้ามีอันเก่าอยู่ก็ลบอันเก่าก่อนถึงจะรันได้่)
