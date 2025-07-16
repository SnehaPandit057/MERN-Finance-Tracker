# 💰 MERN Finance Tracker

A full-stack **Finance Tracker** application built using the **MERN** stack (MongoDB, Express, React, Node.js). This app helps users track their income and expenses with ease, providing a clean interface and persistent data storage.


---

## 📌 Features

- ➕ Add income and expense entries
- 🧾 Track transaction history
- 📉 Calculate and display balance
- 🧠 Categorize transactions
- 🧼 Clean and user-friendly UI
- 🌐 Persistent data with MongoDB
- 🧪 RESTful API with Express and Node.js

---

## 🛠️ Tech Stack

- **Frontend:** React, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (via Mongoose)
- **Other Tools:** Postman, Git, VS Code

---

## 📂 Project Structure

MERN-Finance-Tracker/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── App.js
│ │ └── ...
│ └── package.json
├── server/ # Express backend
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── server.js
│ └── ...
├── .gitignore
├── README.md
└── package.json

yaml
Copy
Edit

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/SnehaPandit057/MERN-Finance-Tracker.git
cd MERN-Finance-Tracker
2. Setup Backend
bash
Copy
Edit
cd server
npm install
Create a .env file in the server directory:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000
Start backend:

bash
Copy
Edit
npm run dev
3. Setup Frontend
Open a new terminal:

bash
Copy
Edit
cd client
npm install
npm start
Frontend will run at: http://localhost:3000
Backend runs at: http://localhost:5000

📦 API Endpoints
Method	Endpoint	Description
GET	/api/transactions	Get all transactions
POST	/api/transactions	Add new transaction
DELETE	/api/transactions/:id	Delete a transaction

💡 Future Enhancements
✍️ Authentication (login/signup)

📆 Date-wise filtering

📊 Data visualization (charts & graphs)

☁️ Cloud deployment (Render, Vercel, etc.)

🤝 Contributing
Contributions are welcome!
Feel free to open an issue or submit a pull request.

📄 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Made with ❤️ by Sneha Pandit

yaml
Copy
Edit

---

Would you like help deploying it on Render or integrating chart libraries for data visualization?
