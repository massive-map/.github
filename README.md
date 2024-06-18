# .github

# Motivation 
Create a working app to attract founders and collectors to the project. 
# What it needs to do
## Map
- Users can set their coordinates to be displayed on the map
- Users can set other information, such as profile name or image
- Users can set which users may see their coordinates (either by individual user or by members of NFT collections)
- (optional?) Founders can set coordinates for 'special' purposes (events, easter eggs, etc --- can be discussed later)
## Token
- Anyone can mint Massive Map tokens (ERC-1155) which will be used as a gating mechanism to allow access to the application
- Founders can be given discounts to batch-mint large numbers of tokens to distribute to their communities
- Founders can set limited-release artwork by submitting it to us. This will allow them to use their own artwork for batches
## Messaging
A fully-functional, feature-rich messaging protocol is outside the scope of this POC. However, after settling the core functionality, it would be good to explore some rudimentary messaging (either wallet-to-wallet or within the app itself)
# Data storage
We acknowledge that we are handling extremely sensitive data by storing the physical locations of our users. We will handle this with the utmost care. For the POC, we will store coordinates fully encrypted in a DB. We will explore more advanced data storage moving forward.
# Revenue
We will initially charge a very small minting fee for the token. This will be collected in the native currency of the chain and will be small enough that it will not be a barrier to entry for new users. This fee can be reduced (or waived) for founders who need to mint a large batch of tokens to distribute to their communities. The revenue can be withdrawn via multisig.

# Stack
- Blockchain: TBD. Must be EVM compatible
- Frontend: React (Next.Js) with tools to query NFT ownership TBD
- Backend: Node.js (Express)
- Smart Contracts: Solidity
- Database: MongoDB 
- Deployment/hosting: TBD (probably AWS or equivalent)



