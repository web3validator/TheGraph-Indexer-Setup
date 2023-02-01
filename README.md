# TheGraph-Indexer-Setup
## A guide to installing from scratch, how to install an indexer on the main network

## Pre-requisites 
1) Dedicated server (16 Core, RAM 128Gb, 2Tb nvme)
2) Domain like https://web3validator.info/
3) 100,000 GRT for indexing

### Server

Server must be with minimum 12-core proccessor and 64gb RAM , good example is AX101 in hetzner you can check the [step-by-step guide here](https://www.indivar.com/blog/setup-new-dedicated-hetzner-server/)

### Domain
Domain you can buy on imena.ua and [step-by-step guide here](https://www.imena.ua/en/domains)

After you bought a domain, you need to make dns records indicating the ip address of your server , it looks like this:

<img width="1381" alt="image" src="https://user-images.githubusercontent.com/59205554/216107600-24e8fda6-bffc-4c9b-ba80-49d2edac393b.png">
<img width="1377" alt="image" src="https://user-images.githubusercontent.com/59205554/216142709-7c3141a5-9ab8-4731-af12-6f347ee96f26.png">



### Run the following commands to clone the GraphProtocol's repository

```bash
git clone https://github.com/web3validator/graphprotocol-mainnet-docker.git
cd graphprotocol-mainnet-docker

```
