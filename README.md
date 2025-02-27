# FastLane Frontrunner Bot PYTHON & Automated By Disala

<p align="center">
  <img src="frontrunner-gif.gif" alt="Frontrunner Game Animation" width="600">
</p>

The objective is simple, you compete as a searcher to be first to land a transaction on-chain in each new block.
Your ranking is determined by your win/loss ratio weighted by number of attempts - so you get some skin in the game.

<p align="center">
  <img src="terminal_example.jpg" alt="terminal example">
</p>


## How to run

I hope u already have github account & evm wallet with testnet monad in it ? 

1. Jump to Settings and Do that

2. Now jump to actions > click RUN_FRONTRUNNER_BOT workflow
   now click RUN_WORKFLOW and give your desired numbers.

Gas Price in Gwei : Default (50) its okey not to change it
Number of attempts (how much traffic/transactions u want) : Default (10) u can set any number but (100 transactions = 1monad)
Interval between attemps : Default (5) prefer not to change it

   then click RUN_WORKFLOW 

3. Refresh webpage if ur run didn't showup , click it , click again. now u can see your transactions

### Settings
1. Add your configuration:

Go to here : https://github.com/The-Disa1a/Monad_Traffic_Gen/settings/secrets/actions/new
Now setup your evm wallet private key 
Name : PRIVATE_KEY
Secret : Your_PVT_KEY
Click Submit Button After That.

⚠️ IMPORTANT SECURITY NOTES:
- Never share your private key or commit it to version control!
- Store your private key securely and keep a backup

## Need Help?

- Ask for help in the FastLane on Monad Discord (#frontunner channel)
- Talk to ChatGPT
- Create an issue in this repository


## License

MIT
