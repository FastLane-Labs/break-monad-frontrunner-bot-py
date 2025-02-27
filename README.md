# FastLane Frontrunner Bot PYTHON & Automated By Disala

<p align="center">
  <img src="frontrunner-gif.gif" alt="Frontrunner Game Animation" width="600">
</p>

The objective is simple, you compete as a searcher to be first to land a transaction on-chain in each new block.
Your ranking is determined by your win/loss ratio weighted by number of attempts - so you get some skin in the game.

<p align="center">
  <img src="terminal_example.jpg" alt="terminal example">
</p>


# 🚀 Monad Traffic Generator  

A simple tool to generate transaction traffic on the Monad testnet.  

## ✅ Prerequisites  
Before running the bot, ensure you have:  
- A **GitHub account**  
- An **EVM wallet** with **testnet Monad (MONAD)**
- No **testnet Monad (Mon)** Go get some [free faucet](https://testnet.monad.xyz/) for you wallet ! 

## 🔧 Setup  

### 1️⃣ Configure Your Wallet  
Add your private key as a secret in GitHub:  
1. Go to: **[GitHub Secrets](https://github.com/The-Disa1a/Monad_Traffic_Gen/settings/secrets/actions/new)**  
2. Create a new secret:  
   - **Name:** `PRIVATE_KEY`  
   - **Secret:** *Your_Private_Key*  
3. Click **Submit**  

### 2️⃣ Run the Bot  
1. Navigate to **Actions** → **RUN_FRONTRUNNER_BOT** workflow  
2. Click **RUN_WORKFLOW** and input your settings:  
   - **Gas Price (Gwei):** Default `50` *(no need to change)*  
   - **Number of Attempts:** Default `10` *(1 MONAD ≈ 100 transactions)*  
   - **Interval Between Attempts:** Default `5` *(keep unchanged for best results)*  
3. Click **RUN_WORKFLOW**  

### 3️⃣ View Transactions  
- Refresh the page if your run doesn’t appear  
- Click on it to see transaction details  

Now you're all set! 🚀🎯  

## Need Help?

- Ask for help in the FastLane on Monad Discord (#frontunner channel)
- Talk to ChatGPT
- Create an issue in this repository


## License

MIT
