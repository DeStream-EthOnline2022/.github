# Destream - Eth Online 2022

Bridge of web2 API data like Square, Shopify, etc. to on-chain.


[destream.store](https://www.destream.store/)

## Project Description

DAOs are commonly involved with the off-chain world especially IRL, for example, Krause House and LinksDAO, etc.

A particular problem when DAOs operate this way can be the visualization of in real life activities, which does not yet exist on-chain. It is crucial for transparent communication among its community members. To reinforce this, we used Livepeer to broadcast a continuous livestream of our DAO's interior facility in hopes to enhance the community's native experience and organic engagement. For this demo, we used a physical store under the assumption that the DAO runs this retail store but the concept certainly isn't limited to physical stores and could essentially be in any environment such as a conference hall or even a golf club etc.

We believe that on-chain data should be visible in a NFT / token-gated way for exclusive members to access, so we write the off-chain data (web2 - IRL data) aggregated with Chainlink, that includes APIs for smart cameras, credit cares, etc.

Soon after, we have a huge motivation to make this mobile native application so that any community members can interact with its community with a rich experience of their IRL place at the same time of seeing its off-chain activities of DAO.

## Service Architecture Diagram

![Service Architecture Diagram](https://github.com/DeStream-EthOnline2022/.github/blob/main/architecture/v1.png)


Quick link node: http://quick-loadb-bmwt0sjkitaq-1478310917.us-east-1.elb.amazonaws.com:6688

Livepeer StreamID: be836105-a3b8-4a15-9dc3-606d76f0c4f2

# How it’s made
Polygon - Our product lives on Polygon

IPFS - Several cases.NFT(ERC721),Live NFT,web2 integration public data

LivePeer - Used with LiveScreen at the NFT gateway.

QuickNode -  Our product connect eth by node on QuickNode.

