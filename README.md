# **Ethereum - Getting Started for Newbies \(by**[**Thetta.io**](https://web.thetta.io) **microcompany tokenization platform\)**

**Ethereum - smart contracts run on top of Ethereum Virtual Machine. Each state change is “saved” to the blockchain, but not to the memory of the single computer.**

**Very good list of Blockchain resources is available here \(but don’t stop to read this document!\) -**[**https://a16z.com/2018/02/10/crypto-readings-resources/**](https://a16z.com/2018/02/10/crypto-readings-resources/)

# Book\#1 - **Mastering Bitcoin: Programming the Open Blockchainbook**

\*\*Very good book that is must read for any blockchain developer. Currently Ethereum uses same crypto-consensus algorithm, just like Bitcoin does. There is no necessity to read the whole book, you can skip chapters and sections.

**\[**[https://www.amazon.com/Mastering-Bitcoin-Programming-Open-Blockchain/dp/1491954388\*\*\]\(https://www.amazon.com/Mastering-Bitcoin-Programming-Open-Blockchain/dp/1491954388](https://www.amazon.com/Mastering-Bitcoin-Programming-Open-Blockchain/dp/1491954388**]%28https://www.amazon.com/Mastering-Bitcoin-Programming-Open-Blockchain/dp/1491954388)\)

![](https://lh4.googleusercontent.com/CFaSa_Es7AJ8v3JAqlCIDKQyBxMCRgYe2WU9SVoHmNu0dqSy89XfUIdGzw5a3rSOCuQlJggL7pp88ShV13l4Dcx0IuK0ny0L7MW77J0k3HCfVCElbpikqrYKdUDy7YHffNr-FYo7)

## Book\#2 - Introducing Ethereum and Solidity

[**https://www.amazon.com/Introducing-Ethereum-Solidity-Foundations-Cryptocurrency/dp/1484225341/**](https://www.amazon.com/Introducing-Ethereum-Solidity-Foundations-Cryptocurrency/dp/1484225341/)

**    
**![](https://lh6.googleusercontent.com/vbWZDECiNF-Y_l7C6pk3ekBeX793L0Gf2wBeEH0OALPH0jJPdLp9qjEJcvgfbmMbSYYIuozDWRJHZHZC33NijzhxNgrfR6jgQlRGn7junwGl5cY6Wzv5ykbsiGbtLB-BbSWSExPo)

[**https://www.dropbox.com/s/c0pzi0fv51ow66w/Ethereum.pdf?dl=0**](https://www.dropbox.com/s/c0pzi0fv51ow66w/Ethereum.pdf?dl=0)

## Articles to read

### In English

[https://medium.com/blockchannel/tools-and-technologies-in-the-ethereum-ecosystem-e5b7e5060eb9](https://medium.com/blockchannel/tools-and-technologies-in-the-ethereum-ecosystem-e5b7e5060eb9)

[http://candidtim.github.io/ethereum/2016/03/24/ethereum-quick-start.html](http://candidtim.github.io/ethereum/2016/03/24/ethereum-quick-start.html)

[http://blockgeeks.com/guides/what-is-ethereum/](http://blockgeeks.com/guides/what-is-ethereum/)

Ethereum smart contracts guide is available here - [https://github.com/ethereum/guide](https://github.com/ethereum/guide)

[https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-2-30b3d335aa1f](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-2-30b3d335aa1f)

PoS - [https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ)

### In Russian

[https://habrahabr.ru/company/alfa/blog/323070/](https://habrahabr.ru/company/alfa/blog/323070/)

[https://habrahabr.ru/company/microsoft/blog/323548/](https://habrahabr.ru/company/microsoft/blog/323548/)

[https://habrahabr.ru/company/neobit/blog/324456/](https://habrahabr.ru/company/neobit/blog/324456/)

## Workshops

1. https://github.com/androlo/solidity-workshop

## What to do next?

1. Research the [https://www.myetherwallet.com    
   ](https://www.myetherwallet.com)- generate new wallet

   * export the wallet to JSON  
   * load the JSON  
   * send or receive test transaction \(say, 0.00000001 ETH\)

2. Create **coinbase** account -very easy way to keep you crypto \(but please don’t keep a lot! you can loose your money, because the service is centralized; also it can be hacked\).

3. Check how block Explorer works -[http://etherscan.io/    
   ](http://etherscan.io/)- see you transaction

   * check your transactions  
   * switch between mainnet and testnet

4. install **geth** and start it from your console

5. install **parity** and start it from your console \(kovan or rinkeby testnet\) + connect from the browser

6. Install Mist \(Ethereum Wallet\) and start syncing it with the mainnet \(can take more than 100+ GB on your hdd\)

   * create new account  
   * check how smart contract deployment works

7. MetaMask chrome add-on

8. Brave web-browser

9. DApp vs ordinary web app

10. Infura.io

## Terms

* Miner

* Node

* Lightnode, different modes

* Lightwallet

* Blockcain sync

* Consensus

* PoW, PoS, \(D\)PoS, Raft/Paxos

* Differences between decentralization and distributed systems

* DHT \(torrents\)

* Block, basic structures

* MIner’s fee, rewards

* Coinbase-tx

* Public/private keys

* Lightning network/Raiden

* Segwit

* 51% attack

* Transaction Maleability attack

* Sybil attack

* Eclipse attack

* Blockchain bloat attack

* Sharding

* Plasma

* Zero-Knowledge Proofs

## **Questions**

1. **Will for cycle \(read-only iteration\) eat gas?**

2. **What if the method throws - will gas be eaten?**

3. **What if you specified low gaslimit value?**

4. **call vs send? What can be called in thefallback functionof the contract?    
   **[**http://ethereum.stackexchange.com/questions/765/what-is-the-difference-between-a-transaction-and-a-call    
   **](http://ethereum.stackexchange.com/questions/765/what-is-the-difference-between-a-transaction-and-a-call)[**http://ethereum.stackexchange.com/questions/6470/send-vs-call-differences-and-when-to-use-and-when-not-to-use**](http://ethereum.stackexchange.com/questions/6470/send-vs-call-differences-and-when-to-use-and-when-not-to-use)

5. **How to send tx in the Parity, if it stuck?    
   **[**https://kovan.etherscan.io/address/0xdf8845a26e1db43236e591a863289ad5c1fcda5a**](https://kovan.etherscan.io/address/0xdf8845a26e1db43236e591a863289ad5c1fcda5a)

6. **tx.originvsmsg.sender?    
   **[**http://ethereum.stackexchange.com/questions/1891/whats-the-difference-between-msg-sender-and-tx-origin**](http://ethereum.stackexchange.com/questions/1891/whats-the-difference-between-msg-sender-and-tx-origin)

7. **mappingsandarrays of mappings?    
   **[**http://ethereum.stackexchange.com/questions/2718/is-it-possible-to-have-mappings-inside-mappings**](http://ethereum.stackexchange.com/questions/2718/is-it-possible-to-have-mappings-inside-mappings)\[![](https://lh5.googleusercontent.com/HLfs7Ny36jERhK5c766wWpL-l6alCfrm0sJHspBKKHnGXzutmoX8q0XxOyliUB3pJGw2f28x4508cEsrAV5alEDs1q4AdRPB8mLJ229owl-dkHKxACmX4x2pudBn0eU8uSv1hkaL)\*\*

   \*\*\]\([http://ethereum.stackexchange.com/questions/1891/whats-the-difference-between-msg-sender-and-tx-origin](http://ethereum.stackexchange.com/questions/1891/whats-the-difference-between-msg-sender-and-tx-origin)\)

8. **Why new solc version requires ‘payable’ modifier to be specified? Even if no money-consuming operations occur inside the fallback.**

9. **Contract address and account address have different formats?**

10. **How to startprivatenode?    
    **[**https://blockgeeks.com/how-to-setup-an-ethereum-private-node/**](https://blockgeeks.com/how-to-setup-an-ethereum-private-node/)

11. **PoS vs PoW    
    **[**https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/    
    **](https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/)[**https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ**](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ)

12. **What is PoA \(Kovan\)?**

13. **Is Byzantine generals problem solved?**

14. **What happens if you send ETH from the wallet that is not synced?**

15. **How to execute arbitrary binary code? Is it even possible?    
    **[**https://github.com/ChainCloud/jibrel-contracts/blob/master/contracts/feature/bytecode/BytecodeExecutor.sol**](https://github.com/ChainCloud/jibrel-contracts/blob/master/contracts/feature/bytecode/BytecodeExecutor.sol)

16. **How to get string hash?    
    **[**https://github.com/ChainCloud/jibrel-contracts/blob/master/contracts/feature/assetid/AssetID.sol**](https://github.com/ChainCloud/jibrel-contracts/blob/master/contracts/feature/assetid/AssetID.sol)

17. **How to pass arrays/strings between contracts?    
    **[**https://gist.github.com/AnthonyAkentiev/68c90721d062b7b21879af7b74b1e95e**](https://gist.github.com/AnthonyAkentiev/68c90721d062b7b21879af7b74b1e95e)

18. **pure? view? staticcall?    
    **[**https://medium.com/blockchannel/state-specifiers-and-staticcall-d50d5b2e4920**](https://medium.com/blockchannel/state-specifiers-and-staticcall-d50d5b2e4920)

19. **delegatecall    
    **[**https://ethereum.stackexchange.com/questions/3667/difference-between-call-callcode-and-delegatecall**](https://ethereum.stackexchange.com/questions/3667/difference-between-call-callcode-and-delegatecall)

20. **memory vs storage?    
    **[**https://ethereum.stackexchange.com/questions/1701/what-does-the-keyword-memory-do-exactly**](https://ethereum.stackexchange.com/questions/1701/what-does-the-keyword-memory-do-exactly)

21. **Libraries -**[**https://vomtom.at/upgrade-smart-contracts-on-chain/**](https://vomtom.at/upgrade-smart-contracts-on-chain/)

22. **NatSpec -**[**https://ethereum.gitbooks.io/frontier-guide/content/natspec.html**](https://ethereum.gitbooks.io/frontier-guide/content/natspec.html)

23. **How to check if address is contract?    
    **[**https://github.com/ethereum/yellowpaper/issues/320**](https://github.com/ethereum/yellowpaper/issues/320)

## **Smart contract examples**

1. [**http://www.giveth.io**](http://www.giveth.io)

2. **Cloneable -**[**https://github.com/Giveth/minime**](https://github.com/Giveth/minime)

3. **Vault -**[**https://github.com/Giveth/vaultcontract**](https://github.com/Giveth/vaultcontract)

4. **Token-curated registry -**[**https://medium.com/@simondlr/city-walls-bo-taoshi-exploring-the-power-of-token-curated-registries-588f208c17d5**](https://medium.com/@simondlr/city-walls-bo-taoshi-exploring-the-power-of-token-curated-registries-588f208c17d5)

5. **LN Payment Channels    
   **[**https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc**](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc)

## **Awesome smart contract style**

1. [**https://github.com/ChainCloud/angel-contracts**](https://github.com/ChainCloud/angel-contracts)

2. [**https://github.com/aragon/**](https://github.com/aragon/)

3. [**https://github.com/ChainCloud/jibrel-contracts/tree/master/contracts**](https://github.com/ChainCloud/jibrel-contracts/tree/master/contracts)**    
   **

## **Lightning Network**

1. [**https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc**](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc)

2. [**https://funfair.io/approach-turing-complete-state-channels-part-1/**](https://funfair.io/approach-turing-complete-state-channels-part-1/)

3. [**https://medium.com/@raiden\_network/the-raiden-network-token-rdn-launch-is-set-to-october-18th-5e9a2ffd7960**](https://medium.com/@raiden_network/the-raiden-network-token-rdn-launch-is-set-to-october-18th-5e9a2ffd7960)

4. [**https://github.com/raiden-network/microraiden**](https://github.com/raiden-network/microraiden)

## **Links**

1. **Trusted Relay Networks \(By Consensys\) -**[**https://blog.gridplus.io/introducing-trusted-relay-networks-6c168f72a6f6**](https://blog.gridplus.io/introducing-trusted-relay-networks-6c168f72a6f6)

## **Notable ERCs**

1. **ERC721 \(non-fungible token, CryptoKitties\) -**[**https://github.com/ethereum/EIPs/issues/721**](https://github.com/ethereum/EIPs/issues/721)

2. **ERC223 \(tokenFallback - receiving tokens callback\) -**[**https://github.com/ethereum/EIPs/issues/223**](https://github.com/ethereum/EIPs/issues/223)

## **Vulnerabilities**

1. **Reentrancy attack    
   **[**https://medium.com/@gus\_tavo\_guim/reentrancy-attack-on-smart-contracts-how-to-identify-the-exploitable-and-an-example-of-an-attack-4470a2d8dfe4**](https://medium.com/@gus_tavo_guim/reentrancy-attack-on-smart-contracts-how-to-identify-the-exploitable-and-an-example-of-an-attack-4470a2d8dfe4)

2. [**https://github.com/ChainCloud/diligence-takehome/tree/attack**](https://github.com/ChainCloud/diligence-takehome/tree/attack)

## **Upgradeability**

1. https://blog.zeppelin.solutions/proxy-libraries-in-solidity-79fbe4b970fd
1. http://swende.se/blog/EVM-Assembly-trick.html
1. https://gist.github.com/Arachnid/4ca9da48d51e23e5cfe0f0e14dd6318f
1. https://www.reddit.com/r/ethereum/comments/4kt1zp/mad_blockchain_science_a_100_upgradeable_contract/

