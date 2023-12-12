Similar to https://github.com/BigBangInfinity/ballot_NFT_shared-main

git clone these three repos into one common folder and continue like in the example above

```
C:\> git clone https://github.com/BigBangInfinity/ballot_animal_NFT_shared-backend-my-api
C:\> git clone https://github.com/BigBangInfinity/ballot_animal_NFT_shared-ballotcontract
C:\> git clone https://github.com/BigBangInfinity/ballot_animal_NFT_shared-scaffold-eth-2
```


## Short guide

Short guide is only for trying out frontend and Swagger API, minting NFTs and voting

Clone two repos to these folders:

```
C:\> git clone https://github.com/BigBangInfinity/ballot_animal_NFT_shared-backend-my-api
C:\> git clone https://github.com/BigBangInfinity/ballot_animal_NFT_shared-scaffold-eth-2
```

yarn install both repos

```
C:\ballot_animal_NFT_shared-backend-my-api> yarn install
C:\ballot_animal_NFT_shared-scaffold-eth-2> yarn install
```


```
C:\ballot_animal_NFT_shared-backend-my-api>yarn run start:dev
```      

Launches Swagger API on 
http://localhost:3001/route

```
C:\ballot_animal_NFT_shared-scaffold-eth-2>yarn start
```

Launches Scaffold ETH on 
http://localhost:3000
