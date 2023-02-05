# blockchain-developer-bootcamp-final-project

## Project Description 
SolPets is a pet verification platform that turns your pet's information into a passport NFT to show proof-of-animal, and proof-of-ownership. SolPets aims to make record keeping easier for pet parents so that they can store important vaccination records and health information in one place and keep pet's history accessible at all times. Our goal for this project is to also help stop the illegal trafficking of endangered animals and help support animal shelters by making exclusive NFTs that can be auctioned to donate to various animal organizations. We will also generate and store NFTs for pets that are looking for homes so that families looking to adopt or support the pet in need can do so. 


## Features 
- Make pet records accessible only to people you trust
- Store your pets records in one place 
- Trade or sell NFTs to earn tokens


## How it Works

1. Connect to your wallet 
2. Fill out a form with your pets information
3. Review your pet's passport to make sure everything is accurate
4. Mint

## Getting Started

```bash
# Install pnpm
npm i -g pnpm

# Install dependencies
pnpm install

# Copy & fill environments
cp packages/frontend/.env.local.example packages/frontend/.env.local
cp packages/hardhat/.env.example packages/hardhat/.env
```


## Development

```bash
# Generate contract-types & start frontend with turborepo
pnpm dev
```
