# ECHO's target-uri-schema

## https:// 
http url, for all web2 content.

## dweb

### ipfs/ipfs

dweb/ipfs/{{CID}}

### ipfs/ipns

dweb/ipns/{{path}} 

### ar

dweb/ar/{{tx id}}

## NFT

> [slip-0044](https://github.com/satoshilabs/slips/blob/master/slip-0044.md)

nft/{{slip-0044 coin type}}/{{contract_address}}/{{token_id}}

## Contract

contract/{{slip-0044 coin type}}/{{contract_address}}

## Address

address/{{slip-0044 coin type}}/{{address}}

## Apps

### Mirror

dapp/mirror/{{ori_content_digest}}

### Voice

dapp/voice/{{id}}
