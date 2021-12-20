# Minting_Contract
#This is a contract written in solidity based on the ERC-721 standard.

#It can be deployed on several blockchains such as ethereum, polygon or avalanche.


#It is a minting dapp that will fetch the NFTs from ipfs and do a few functionalities being whether getters (without fees) or setters.

#Functionalities you may want to know about, that exist in this contract  :
-reveal collection ( a collection must not be revealed at first, but since it is stored on IPFS and everything is open-source, there must be a function revealed that should be activated once the collection is sold-out.)

-Function transferOwnership transfers the ownership and so to say sends the nft to a new address

-function withdraw will show the amount earned of the sales on your wallet once you want to withdraw them from the contract.