# **DBank-Motoko**  

A simple decentralized banking app (**DBank**) built using **Motoko** and deployed on the **Internet Computer (ICP)**. It allows users to check their balance, top-up funds, withdraw funds, and earn **1% daily compound interest**. 🚀💰  

---

## 🚀 **Features**  

- 💰 **Check Current Balance** – Displays the user’s real-time balance.  
- 📥 **Top Up Funds** – Users can add money to their account.  
- 📤 **Withdraw Funds** – Users can withdraw money from their account.  
- 📈 **1% Daily Interest** – The balance compounds **automatically** every day.  
- 🌐 **Deployed on Internet Computer** – Powered by blockchain for secure, decentralized banking.  

---

## 🛠 **Tech Stack**  

- **Frontend**: HTML, CSS (Glassmorphism + Animations), JavaScript  
- **Backend**: Motoko (Smart Contracts on Internet Computer)  
- **Deployment**: Local Development with DFX, Internet Computer (ICP)  

---

## 🔧 Setup & Run Locally  
   - - 1️⃣ **Install DFINITY SDK (DFX)** - First, install DFINITY SDK (if not already installed).
      ```sh
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
      ```
   - - 2️⃣ **Clone the Repository** - git clone https://github.com/your-username/dbank.git - cd dbank
   - - 3️⃣ **Start Local ICP Blockchain** - dfx start --background
   - - 4️⃣ **Deploy the Backend** - dfx deploy
   - - 5️⃣ **Start the Frontend** - npm install - npm start - Now, visit http://localhost:8000/ to see your DBank in action! 🎉  #
     
** 🌍 Deploy on Internet Computer  To deploy your DBank on the Internet Computer blockchain:  **dfx deploy --network ic** This will create a live version of your DBank on the Internet Computer.
