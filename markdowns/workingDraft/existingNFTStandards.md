# Existing NFT Standards

## Existing NFT Standards on Ethereum 

| Type     |  Standard / Name   |   Compatibility   |   Example Usage    |   Purpose    |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|
| Non-Fugible Token Standard     |  [ERC721](https://github.com/ethereum/EIPs/issues/721){:target="_blank"}    |    |   Cryptokitties    |   Standard allowing for tokens to be distinguished from each other, granting the ability to attach tokens to different types of assets and verify their ownership on the blockchain. Put simply, ERC721 is the non-fungible token standard, allowing us to create and exchange NFTs.    |
| Multi Token Standard     |  [ERC-1155](https://github.com/ethereum/EIPs/issues/1155){:target="_blank"}    |   ERC-721   |   Weapons and Coins in a Game    |   Created by the team at Enjin, this standard allows for both fungible and non-fungible items in the same smart contract. In doing so, ERC-1155 reduces the amount of data required, creating smoother deployments and requiring a lot less network power.    |
| Delegated Non-Fungible Token Standard     |  [ERC-994](https://github.com/ethereum/EIPs/issues/994){:target="_blank"}   |       |   Land registery NFT updated/notified whenever any of its "delegated NFT" change owners    |   ERC-994 has created a system where DNFT’s can identify an area or zone (let’s say the suburb you live in), and can then delegate NFT’s to represent individual houses or parcels of land. In this way, ownership of property can be tokenised whilst also providing a way to update land registries, and legally verify their sale.    |
| Partially Fungible Token Standard     |  [ERC-1410](https://github.com/ethereum/eips/issues/1410){:target="_blank"}   |      |       |  Both differentiated ownership and transparent restrictions. This interface supports an owner’s tokens to be grouped into partitions, with each of them being represented by an identifying key and a balance. Some of these partitions can be fungible while others are non-fungible.    |
| The Dank Standard     |  [ERC-420](https://medium.com/pepedapp/erc-420%C2%B9-the-dank-standard-83d7bb5fe18e){:target="_blank"}   |      |       |   Legacy standard proposal. This standard was proposed by the PepeDapp team. Designed with digital trading cards in mind. It takes into account that in a deck of trading cards    |
| Renting Standard for Rival, Non-Fungible Tokens     |  [ERC-809](https://github.com/ethereum/EIPs/issues/809){:target="_blank"}    |      |       |   Standard for renting out your NFT’s, by creating an API to allow any “rival” NFT to be rented.    |
| Two Tiered Token Structure for Non-fungible Asset Ownership and Rental Rights     |  [ERC-1201](https://github.com/ethereum/EIPs/issues/1201){:target="_blank"}   |      |   Think of it as follows: (i) ERC-721 creates an NFT for your house. (ii) ERC-809 creates a standard set of commands allowing you to rent said house. (iii) ERC-1201 tokenises this right, and in a practical sense, means the leaseholder could sub-lease your house, simply by exchanging the token.    |   Tokenise rental rights, as opposed to just allowing for them. This creates a means for the rented NFT to be easily exchanged between parties.    |
| Composable Non-Fungible Token Standard     |  [ERC-998](https://github.com/ethereum/EIPs/issues/998){:target="_blank"}   |     |      |   A standard for any NFT to own another ERC-721 NFT or ERC-20 fungible tokens.    |
| Re-Fungible Token     |  [ERC-1633](https://github.com/ethereum/EIPs/pull/1633){:target="_blank"}   |      |      |   NFT Fractional Ownership via ERC-20 token    |


## Other Existing NFT Standards

| Network  |  Type     |  Standard / Name   |   Compatibility   |   Example Usage    |   Purpose    |   Comments / Links  |
| ------------- |:------------- |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| BinanceChain  |  NFT     |  [BEP-7](https://github.com/binance-chain/BEPs/pull/7){:target="_blank"}   |      |       |   Basic support for NFTs    |     |
| NULS  |  NFT     |  [NRC-721](https://docs.nuls.io/Docs/s_nrc721.html){:target="_blank"}   |      |        |   standard interface for NFTs    |     |
| EOS  |  NFT     |  No Official Standard for NFT    |      |       |       |     |
| EOS  |  NFT Standard Proposal   |  [Unico EOS](https://github.com/unicoeos/eosio.nft){:target="_blank"}   |      |       |  Basic support for NFTs    |    |
| EOS  |  Standard for Fungible and Non-Fungible Tokens    |  [dGood](https://github.com/MythicalGames/dgoods){:target="_blank"}    |      |       |   Basic support for NFTs and other token types    |   https://medium.com/dgoods/dgoods-v1-0-public-beta-release-72f896ad7aed  |
| Tezos  |  Standard for NFTs and other Token Types  |  [FA2 (TZIP-12) - Multi-Asset Interface](https://gitlab.com/tzip/tzip/-/blob/master/proposals/tzip-12/tzip-12.md){:target="_blank"}   |      |       |   https://medium.com/@TQTezos/introducing-fa2-a-multi-asset-interface-for-tezos-55173d505e5f    |     |
| Tezos  |  NFT Implementation following FA2 (TZIP-12)     |  [tzNFT - not a standard](https://medium.com/@TQTezos/tznft-non-fungible-tokens-on-tezos-using-fa2-b1ab11185ec1){:target="_blank"}   |      |       |       |   https://github.com/tqtezos/nft-tutorial  |
| CosmWasm  |  NFT     |  [CW721](https://github.com/CosmWasm/cosmwasm-plus/blob/master/packages/cw721/README.md){:target="_blank"}   |      |       |       |     |
| Secret Network - Cosmos |  Private NFT     |  [SNIP-721](https://github.com/SecretFoundation/SNIPs/blob/master/SNIP-721.md){:target="_blank"}   |      |       |   The only Private Non-Fungible Tokens    |     |
