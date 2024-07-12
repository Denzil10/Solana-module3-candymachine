## Project Title

Solana Candy Machine UI with SPL Token Payment

## Description

This project is an advanced Solana ecosystem application where users can mint NFTs using a custom SPL token instead of the native SOL token. The project involves creating an SPL token, configuring the Candy Machine to accept this token for minting, and setting up a user interface (UI) for the Candy Machine.

## Getting Started

### Prerequisites

-   Node.js
-   NPM (Node Package Manager)
-   Solana CLI
-   Phantom Wallet
-   Git

## Getting Started

### Installing

1.  **Clone the repository:**    

    `git clone <repository_url>`
    `cd <repository_name>`
 
    
2.  **Install dependencies:**
    `sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
export PATH="/home/gitpod/.local/share/solana/install/active_release/bin:$PATH"
eval $(gp env -e PATH=$HOME/.local/share/solana/install/active_release/bin:$PATH)
wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_amd64.deb
sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2_amd64.deb
bash <(curl -sSf https://sugar.metaplex.com/install.sh)` 

    `cd candy-machine-ui`
	`npm install` 
    
   ### Config Setup 
    
   1.  **Setup wallet and spl-token** Setup the solana configs and create your spl-token
   
   2. **Modify `config.json`:** Update your `config.json` to use the`splTokenAddress` of the token you created. (or solana addresss if you want use native currency)
 
   3. **Create candy machine** Create it using sugar cli 
   4. **Create env file in UI folder** Rename env.example to env and update it
env
    `REACT_APP_CANDY_MACHINE_ID=<your_candy_machine_id>`

### Executing Program

1.  **Start the application:** 
	`npm start` 
    
3.  **Minting NFTs:**
    
    -   Open the application in your browser.
    -   Connect your Phantom Wallet.
    -   Mint an NFT using the SPL token.


## Help

For common issues:

-   Ensure your sugar version is compatible with the UI used
-   Verify your wallet connection and ensure it has enough sol and SPL tokens.
-   Check that your `config.json` is correctly set up with the correct wallet addresses.

`npm run help` 

## Authors

-   Denzil Nelson (GitHub: @Denzil10)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.