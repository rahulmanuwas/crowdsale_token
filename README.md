# smart_token_ICO

This is an Ethereum Smart Contract for a crowdsale with KYC verification  

The aim is to do a crowdsale on Ethereum to distribute our custom Ethereum token to the public. But for this specific crowdsale, we require a KYC verification to be implemented too. 

But there's a catch.  

1) Any investor can invest up to 2 ethers, and get an equal amount of tokens. 

2) If they invest more than 2 ethers, without being KYC verified, they will get 2 ethers worth of tokens, and the excess ether will be refunded to their account. (For example: If the investor sends 5 ether without being KYC approved, he gets 2 ethers worth of tokens, and the remaining 3 ethers will be refunded to his account) 

3) If they are KYC verified, they can send any amount of ether they want, and they will get an equal amount of tokens in return  Implementation - Create an ERC20 Smart Contract for the custom token. The initialization parameters (name of coin, symbol, decimals, etc.) can be filled as per your wish. Create a crowdsale smart contract which implements this KYC verification and refund feature. The price per token in ether can be kept to any amount.   

Expected Output - 
2 Smart Contracts: 1 ERC20 Smart Contract and 1 Crowdsale Smart Contract 

![Image 1](1_Creating_Token.png?raw=true "Token Creation")

![Image 2](2_CrowdSale_Initialization.png?raw=true "CrowdSale Initialization")

Some accounts that I created for testing the contract:
![Image 3](3_Accounts_Created.png?raw=true "Test Accounts")


