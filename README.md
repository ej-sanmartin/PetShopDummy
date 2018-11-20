# Pet Shop Dummy


## Details

Posted so I can practice deployment and modifications of this repo.


## Requirements

1. Ganache, which you can download [here](https://truffleframework.com/ganache)

2. Ganache CLI `npm install -g ganache-cli`

3. Truffles `npm install -g truffle`

4. Metamask Chrome or Firefox Extension installed


## Setting Up

To start, open Ganache. Then, navigate within the terminal until you've reached where this project
is located and enter the commands: 


`truffle compile`

`truffle migrate`


You should see Ganache output randomly generated address and your Eth Balance should be at 100 Eths.


Now, connect Ganache's development environment to your metamask extension by copying the MNEMONIC keywords found in Ganache and entering them into the login screen under the options "Enter Secret Keywords".

Upon login, click on the "Main Network" tab of metamask and click on "Custom RPC", where you'll be taken to a page. 
Where it prompts you "New RPC URL", paste "http://127.0.0.1:7545" and click save.

You'll now notice that network has been named "Private Network" and that your metamask account has a little less than 100Eths
(note, this money is fake :P).


## Run Environment

Once all the requirements are met and you finished successfully setting up, run:

`npm run dev`

