# NFT-Marketplace
NFT Marketplace with ReactJS

Tecnologias Usadas:

-Solidity (Writing Smart Contract)
-Javascript (React & Testing)
-Ethers (Blockchain Interaction)
-Hardhat (Development Framework)
-Ipfs (Metadata storage)
-React routers (Navigational components)

Inicie la blockchain de desarrollo local

 - cd nft_marketplace
 - npx hardhat node
 
Conectar la blockchain con Metamask

-Copiar la clave privadad e importarla a Metamask
-Conecta Metamask al Hardhat Blockchain, network 127.0.0.1:8545.
-Para "Network Name" introduce "Hardhat".
-Para "New RPC URL" coloca "http://127.0.0.1:8545".
-Para chain ID "31337". 
-Por ultimo Guardar.

Migrar los smart contracts

npx hardhat run src/backend/scripts/deploy.js --network localhost

Correr los test
npx hardhat test

Correr el front
npm start
