# Travel Memory

`.env` file to work with the backend after creating a database in mongodb: 

```
MONGO_URI='ENTER_YOUR_URL'
PORT=3001
```

Data format to be added: 

```json
{
    "tripName": "Incredible India",
    "startDateOfJourney": "19-03-2022",
    "endDateOfJourney": "27-03-2022",
    "nameOfHotels":"Hotel Namaste, Backpackers Club",
    "placesVisited":"Delhi, Kolkata, Chennai, Mumbai",
    "totalCost": 800000,
    "tripType": "leisure",
    "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ",
    "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg",
    "shortDescription":"India is a wonderful country with rich culture and good people.",
    "featured": true
}
```


For frontend, you need to create `.env` file and put the following content (remember to change it based on your requirements):
```bash
REACT_APP_BACKEND_URL=http://localhost:3001




## 📸 Screenshots

### 🖥️ Application Home Page
<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/fd574945-20e2-4d68-a3ec-cdfbdbeb06f8" />


### ☁️ EC2 Instances
<img width="1280" height="728" alt="image" src="https://github.com/user-attachments/assets/1259aa8b-9b83-430c-99fd-905dec25bb40" />


### ⚖️ Load Balancer
<img width="1280" height="724" alt="image" src="https://github.com/user-attachments/assets/644a5f05-93f2-44f0-a718-6edccb9372a8" />


### 🗄️ MongoDB Atlas
<img width="1280" height="725" alt="image" src="https://github.com/user-attachments/assets/f81e4319-a442-4436-b7b1-d3c9703db3de" />


```

