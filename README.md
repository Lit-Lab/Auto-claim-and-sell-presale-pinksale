# auto claim and sell presale
- this bot is serverless and only working locally at your device, so this bot cannot collect any data from your device.
- its make that way to make sure user data is safe and only the user who can access their data.
- this bot using 1% tax per success transaction (you can join our group for more information).
![screenshoot1](https://github.com/Lit-Lab/Auto-claim-and-sell-presale-pinksale/assets/139533775/13307d85-8b2e-487c-92bd-b6c29f494ae4)

## notes :
- for now this bot only supported :
  - chain :
    - BSC chain :ballot_box_with_check:
    - more will be updated at future.
  - launchpad :
    - pinksale :ballot_box_with_check:
    - more will be updated at future.
  - contract address with enabletrade is supported :ballot_box_with_check:

## feature : 
- auto claiming your contribution at presale launchpad
- auto selling your token with option :
  - instant sell after launching
  - sell with limit profit (set limit % profit to trigger auto sell)

## installation
there are two option :
- run bot.exe
- run bot.pyc (if you already installed python at your device)

## usage
- run bot file
- enter your public or private RPC
  for public RPC its recommended using official BSC RPC at [here](https://docs.bscscan.com/misc-tools-and-utilities/public-rpc-nodes).
- add your wallet :
  1. generate new wallet
     bot will generating your new wallet (please save generated wallet address and privatekey to somewhere else)
  2. import wallet
     input your privatekey and bot will save it temporary (bot will clean temporary data after you close it)
- enter target token address
  enter your taget token you want to auto claim
- enter target presale address
  usually you can find presale address at presale page
- choose your method :
  1. instant sell
     bot will auto claim and wait until token launched to sell intsantly after launch
  2. sell with target price
     enter how much % profit you want to trugger auto sell after token launched. example : you contribute 1bnb at presale and want to sell at price 1.2bnb so you enter "20" for 20% profit limit.
- after that this bot will start to fetching your contribution at presale > waiting presale to finalized > claiming your presale contribution > selling presale token
  - bot will beeping if its job are done, and write log activity and txn hash used at bot terminal panel for temporary (you can copy it and paste to somewhere to save it).

## extra
- telegram : https://t.me/LitLab_bot
