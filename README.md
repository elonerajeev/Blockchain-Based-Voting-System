# 🗳️ **Decentralized Voting System Using Ethereum Blockchain**  

### **Secure | Transparent | Blockchain-Powered**  

🚀 **Developed by:** Tech Titan
📌 **GitHub Repository:** [Blockchain-Based-Voting-System](https://github.com/elonerajeev/Blockchain-Based-Voting-System)  

---

## 🎯 **About the Project**  

The **Decentralized Voting System** leverages **Ethereum Blockchain** to create a **secure, tamper-proof, and transparent** voting mechanism. It eliminates election fraud, ensures voter anonymity, and allows users to **cast votes remotely** with cryptographic security.  


---

## 🔥 **Key Features**  

✅ **Blockchain Security:** Uses Ethereum smart contracts to ensure **immutable** voting records.  
✅ **Decentralized & Trustless:** No central authority, reducing fraud and manipulation.  
✅ **JWT Authentication:** Ensures **secure voter login** and access control.  
✅ **Admin Dashboard:** Manage candidates, voting dates, and monitor results.  
✅ **Intuitive UI:** Simple & clean design for seamless voting experience.  
✅ **Remote & Anonymous Voting:** Voters can securely cast their votes **from anywhere**.  

---

## ⚡ **Tech Stack Used**  

| **Technology**  | **Purpose** |
|----------------|-------------|
| **Ethereum & Solidity** | Smart Contracts for Voting |
| **Node.js & Express.js** | Backend API |
| **React.js** | Frontend UI |
| **Web3.js / ether.js** | Blockchain Interaction |
| **Truffle & Ganache** | Ethereum Development & Testing |
| **Metamask** | Secure Wallet Integration |
| **MySQL** | Voter Database |
| **FastAPI & Python** | Secure API Services |

---

## 🛠 **Prerequisites**  

🔹 **Node.js** (Version: 18.14.0)  
🔹 **Python** (Version: 3.9)  
🔹 **Ganache** (Ethereum Test Blockchain)  
🔹 **Metamask** (Ethereum Wallet)  
🔹 **MySQL** (Port: 3306)  
🔹 **Truffle** (Ethereum Development Framework)  

---

## 📸 **Screenshots**  

### 🔐 **Login Page**  
![Login Page]

### 🏛 **Admin Dashboard**  
![Admin Page]

### 🗳️ **Voting Interface**  
![Voter Page]

---

## 🚀 **Installation Guide**  

### 🔹 **Step 1: Clone the Repository**  
```sh
git clone https://github.com/elonerajeev/Blockchain-Based-Voting-System.git
cd Blockchain-Based-Voting-System
```

### 🔹 **Step 2: Install Dependencies**  
```sh
npm install  # Installs Node.js dependencies
pip install -r requirements.txt  # Installs Python dependencies
```

### 🔹 **Step 3: Setup Blockchain**  
1. Download & Install [Ganache](https://trufflesuite.com/ganache/).  
2. Create a workspace named **development**.  
3. Add `truffle-config.js` in the Truffle projects section.  

### 🔹 **Step 4: Setup Metamask**  
1. Install [Metamask](https://metamask.io/download/).  
2. Create a new wallet or import an existing one from **Ganache**.  
3. Add a new network:  
   - **Network Name:** Localhost 7575  
   - **RPC URL:** `http://localhost:7545`  
   - **Chain ID:** `1337`  
   - **Currency Symbol:** `ETH`  

### 🔹 **Step 5: Setup MySQL Database**  
1. Open **MySQL** and create a new database named `voter_db`.  
2. Run the following SQL query to create a `voters` table:  

```sql
CREATE TABLE voters (
   voter_id VARCHAR(36) PRIMARY KEY NOT NULL,
   role ENUM('admin', 'user') NOT NULL,
   password VARCHAR(255) NOT NULL
);
```

---

## 🔄 **Running the Application**  

### 🔹 **Step 1: Compile Smart Contracts**  
```sh
truffle compile
```

### 🔹 **Step 2: Deploy Smart Contracts**  
```sh
truffle migrate
```

### 🔹 **Step 3: Start the Backend Server**  
```sh
node index.js
```

### 🔹 **Step 4: Start the Database API Server**  
```sh
cd Database_API
uvicorn main:app --reload --host 127.0.0.1
```

### 🔹 **Step 5: Bundle Frontend with Browserify**  
```sh
browserify ./src/js/app.js -o ./src/dist/app.bundle.js
```

### 🔹 **Step 6: Open the Application**  
✅ Your voting system is now running at: **[http://localhost:8080/](http://localhost:8080/)** 🎉  

---

## 📂 **Project Directory Structure**  

```
📦 Blockchain-Based-Voting-System
 ┣ 📂 build                 # Compiled Ethereum smart contracts
 ┣ 📂 contracts             # Solidity Smart Contracts
 ┣ 📂 Database_API          # API for database operations
 ┣ 📂 migrations            # Truffle migration scripts
 ┣ 📂 public                # Static assets
 ┣ 📂 src                   # Frontend (HTML, CSS, JS)
 ┃ ┣ 📂 assets             # Images
 ┃ ┣ 📂 css                # Stylesheets
 ┃ ┣ 📂 js                 # JavaScript Logic
 ┣ 📜 index.js              # Node.js Backend
 ┣ 📜 truffle-config.js      # Truffle Configuration
 ┣ 📜 package.json          # Node.js Dependencies
 ┗ 📜 README.md             # Documentation
```

---

## 📜 **License**  

🔓 This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it! 🎉  
🔗 **Read the full license here:** [LICENSE](https://github.com/elonerajeev/Blockchain-Based-Voting-System/blob/main/LICENSE)  

---

## 🙌 **Support & Contributions**  

💡 **Want to improve this project?**  
- Fork the repo & create a PR!  
- Report issues & suggest new features!  

🌟 **If you like this project, don’t forget to give it a ⭐!**  

---

## 📞 **Contact Me**  

🔹 **GitHub:** [@elonerajeev](https://github.com/elonerajeev)  
🔹 **LinkedIn:** [Rajeev Kumar](https://www.linkedin.com/in/rajeev-kumar-2209b1243)  

🚀 **Happy Coding! Build the Future of Transparent Elections!** 🎉 🗳️
