# Electra Vote Management System

A **Blockchain-based Voting Management System** designed to ensure secure, transparent, and tamper-proof voting. Electra simplifies the voting process while maintaining the highest security standards.

## 🔒 Key Features

- **Blockchain Security:** Immutable and transparent voting records.
- **Admin Dashboard:** Real-time user data monitoring and vote counters.
- **Voter Authentication:** Secure user verification to prevent fraud.
- **Decentralized Voting:** Distributed ledger technology for data integrity.
- **Responsive UI:** Modern and user-friendly interface.

## 🛠️ Tech Stack

- **Frontend:** React.js, SCSS, Chart.js
- **Backend:** Node.js, Express.js, TypeScript
- **Database:** MySQL
- **Blockchain:** Ethereum (Smart Contracts)
- **Smart Contracts:** Solidity

## 📂 Folder Structure

```
electra-vote-management/
├── client/          # Frontend (React)
├── server/          # Backend (Node.js, Express)
├── contracts/       # Smart Contracts (Solidity)
├── migrations/      # Deployment scripts
├── .gitignore       # Git ignored files
├── package.json     # Project dependencies
└── README.md        # Project documentation
```

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PranavPawar0/Electra-Vote-Management.git
   cd Electra-Vote-Management
   ```

2. **Install dependencies:**
   - **Frontend:**
     ```bash
     cd client
     npm install
     ```
   - **Backend:**
     ```bash
     cd ../server
     npm install
     ```
   - **Smart Contracts:**
     ```bash
     npm install -g truffle
     truffle compile
     ```

3. **Configure Database:**
   Update `DB_HOST`, `DB_USER`, `DB_PASSWORD`, and `DB_NAME` in the backend configuration.

4. **Deploy Smart Contracts:**
   ```bash
   truffle migrate --reset
   ```

5. **Run the project:**
   - **Backend:**
     ```bash
     npm run dev
     ```
   - **Frontend:**
     ```bash
     cd ../client
     npm run dev
     ```

6. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000`

## 🖥️ Admin Dashboard

- **Real-time Analytics:** Track voter participation and live vote counts.
- **User Management:** View and manage registered users.
- **Secure Access:** Admin-only access with authentication.

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🏆 Achievements

- **1st Place** in College Fintech Hackathon for innovative blockchain-based voting.

## 🙌 Acknowledgements

- Inspired by the need for secure and transparent voting systems.
- Developed with dedication by Pranav Pawar.

---

> For feedback or suggestions, feel free to reach out!

**Pranav Pawar**  
[LinkedIn](https://linkedin.com/in/pranavpawar0) | [GitHub](https://github.com/PranavPawar0)
