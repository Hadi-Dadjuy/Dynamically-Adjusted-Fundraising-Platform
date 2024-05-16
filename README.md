# Dynamically Adjusted Fundraising Platform

In this project I implemented a customized funding platform using bonding curves. The formula related to curve mentioned below.  

In my opinion, one drawback of bonding curves is that they are prone to pump and dump schemes. In this project, selling option is disabled and in order to prevent unfair reward allocation to the investors, I used a concept of epochs. Using epochs, investors who lock their DAI token in the contract, get the same amount of reward related to their locked DAI.  Project includes frontend in React ([link to repo](https://github.com/hadi-dadjuy/fundraising-frontend)) and blockchain in Solidity ([link to repo](https://github.com/hadi-dadjuy/fundraising-contracts)).

User will deposit DAI and after the end of sale he or she will get HDT reward token  which stands for Hadi Dadjuy's Token :)

Head over to [this link](https://hdt-fundraise.netlify.app/) to see a live demo of dapp.

# Smart Contracts

All smart contracts are deployed to **zksync-v2** testnet. Smart contracts are implemented in Solidity. Be careful, contracts aren't tested so use them at your own risk.

### Deployed addresses on zksync v2:
**DAI Contract:**  [0x8426B56b9e41A0d4f960008797564d199b69888F](https://zksync2-testnet.zkscan.io/address/0x8426B56b9e41A0d4f960008797564d199b69888F/transactions)

**HDT Contract:**  [0xFF02423a967747B6ECc0f4C2Dc470a4bb2778ed2](https://zksync2-testnet.zkscan.io/address/0xFF02423a967747B6ECc0f4C2Dc470a4bb2778ed2/transactions)

**Vault Contract:**  [0x57d35Fc068C9AcBEFe58B7bC951aa3036C361241](https://zksync2-testnet.zkscan.io/address/0x57d35Fc068C9AcBEFe58B7bC951aa3036C361241/transactions)

## Bonding curve formula

The following  image shows the formula used for bonding curve in Solidity.
![](/Screenshots/1.png)

## A simple scenario

Image below, represents a simple scenario of how bonding curve works.
![](/Screenshots/2.png)

## Screen shots

![](/Screenshots/3.png)
![](/Screenshots/4.png)
![](/Screenshots/5.png)

