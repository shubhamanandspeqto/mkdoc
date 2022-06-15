#

## BSC Mainnet

### **What is Mainnet?​**

Mainnet is the term used to describe when a blockchain protocol is fully developed and deployed, meaning that cryptocurrency transactions are being broadcasted, verified, and recorded on a distributed ledger technology (blockchain).

BNB Smart Chain's mainnet can be used for deploying actual dApps on the BSC blockchain ad perform real transactions. Since this is the actual network, you will require to purchase real BNB tokens to perform different operations on the network.

### **How to Get BNB​**

There are multiple ways to purchase BNB Tokens for use on the mainnet. Other than the official [BNB Extension Wallet](), BNB Smart Chain supports several popular wallets like [MetaMask]() and [TrustWallet](), to learn more about the supported wallets [refer]() here. For a list of tutorials on how to use different supported wallets with BNB Smart Chain, refer [here]().


### **How to Access BSC​**

There are multiple ways to access the BSC mainnet. One possible method is to join the mainnet as a [full node](). You can also use the RPC endpoints specified [here]() to connect to the mainnet. RPC endpoints may be used to interact with a node directly over HTTP or websockets. Using RPC, you may perform low-level operations like executing ABCI queries, viewing network/consensus state or broadcasting a transaction. RPC endpoints are also used with web wallets like [MetaMask]() to connect to the BSC mainnet.


### **How to Know BSC Ecosystem​**

To get an overview of the BNB Smart Chain, refer [here](). To learn more about the ecosystem and the different development tools like APIs, IDEs, wallets, etc., that are available on the BSC network, you can refer [here](). You can visit [BNBProject]() or [DappRadar]() to view real-time ranking and tracking of BSC projects.

### **How to Build on BSC​**

You can build deploy [smart contracts](), [NFTs](), [BEP20 Tokens](), and [BEP20 Upgradable Contracts]() on the BNB Smart Chain.

### **BSC today​**

To get an overview of what is the current state and the future developements that BSC's team is working refer [here]().


## BSC Testnet

### **What is a Testnet?​**

The testnet is a test environment for BNB Smart Chain network, run by the BNB Chain development community, which is open to developers.

The validators on the testnet are from the development team.

You can connect a node to the testnet by downloading the [node binary]() to use this [configuration]().

There is also a [web wallet]() that can directly interact with the DEX testnet.

### **What is the Testnet good for?​**

  - Create your test address and get your testnet funds.
  - Develop applications and try tutorials on BNB Smart Chain without the potential to lose your own assets.
  - Test your applications against new versions of BNB Smart Chain.
  - Analyze blockchain data on a smaller, non-trivial data set compared to the public network.

### **How to get Testnet Fund?​**

The testnet faucet for BNB Chain can be accessed [here]().

**Steps to claim testnet BNB:**

  1. Create a new Wallet of BNB Smart Chain testnet with MetaMask or MathWallet
  2. Get Testnet Fund: https://testnet.binance.org/faucet-smart

To request funds, please make a tweet with your BNB Smart Chain address pasted into the contents. Then, copy-paste the tweets URL! **BNB** will be sent to your BSC wallet right away.

  3. Transfer From BNB Smart Chain to Beacon Chain

You can use [BNB Chain Extension Wallet]() for cross-chain transfer.

If you wish to test Beacon Chain features, you could transfer BNB cross-chain with MathWallet dApp: [https://docs.bnbchain.org/docs/wallet/math#transfer-bnb-from-bsc-to-bc-in-testnet]()

### **Explorers for Testnet​**

    * BscSCAN - https://testnet.bscscan.com/
    * Bitquery - https://explorer.bitquery.io/bsc_testnet


## BSC Explorers


BNB Smart Chain (BSC) explorers is a graphic user interface designed to allow users to interact with the blockchain. Through this interface, a user can browse information about blocks that have been added to the blockchain, transactions that have occurred on the blockchain, wallet balances, and information about BNB.

BNB Smart Chain (BSC) provides explorers for both its mainnet and testnet.

### **Explorers for Mainnet​**

  - BscSCAN - [https://bscscan.com/]()
  - Bitquery - [https://explorer.bitquery.io/bsc]()

### **Explorers for Testnet**
​
  - BscSCAN - [https://testnet.bscscan.com/]()
  - Bitquery - [https://explorer.bitquery.io/bsc_testnet]()


## Running Fullnode 

### BNB Smart Chain Full Node

#### How to Run A Fullnode on BNB Smart Chain

##### **Fullnodes Functions​**

 - Stores the full blockchain history on disk and can answer the data request from the network.
 - Receives and validates the new blocks and transactions.
 - Verifies the states of every accounts.


##### **Supported Platforms​**

We support running a full node on ``Mac OS X``and ``Linux``.*


##### **Suggested Requirements**
​
**Fullnode**
​
 - VPS running recent versions of Mac OS X or Linux.
 - **IMPORTANT** 2T GB of free disk space, solid-state drive(SSD), gp3, 8k IOPS, 250MB/S throughput, read latency <1ms. (if start with snap/fast sync, it will need NVMe SSD)
 - 16 cores of CPU and 64 gigabytes of memory (RAM).
 - Suggest m5zn.3xlarge instance type on AWS, c2-standard-16 on Google cloud.
 - A broadband Internet connection with upload/download speeds of 5 megabyte per second


**Validator​**

 - VPS running recent versions of Mac OS X or Linux.
 - **IMPORTANT** 2T GB of free disk space, solid-state drive(SSD), gp3, 8k IOPS, 250MB/S throughput, read latency <1ms
 - 16 cores of CPU and 64 gigabytes of memory (RAM)
 - Suggest m5zn.3xlarge instance type on AWS, or c2-standard-16 on Google cloud.
 - A broadband Internet connection with upload/download speeds of 10 megabyte per second


##### **Settings**
​
**Common Problems With Connectivity​**

Sometimes you just can’t get synced. The most common reasons are as follows:

 - You have started geth without the discovery protocol, you can set the --nodiscover parameter to False. You only want this if you are running full node with fixed nodes.
 - Update ``BootstrapNodes``
     BootstrapNodes = ["enode://1cc4534b14cfe351ab740a1418ab944a234ca2f702915eadb7e558a02010cb7c5a8c295a3b56bcefa7701c07752acd5539cb13df2aab8ae2d98934d712611443@52.71.43.172:30311","enode://28b1d16562dac280dacaaf45d54516b85bc6c994252a9825c5cc4e080d3e53446d05f63ba495ea7d44d6c316b54cd92b245c5c328c37da24605c4a93a0d099c4@34.246.65.14:30311","enode://5a7b996048d1b0a07683a949662c87c09b55247ce774aeee10bb886892e586e3c604564393292e38ef43c023ee9981e1f8b335766ec4f0f256e57f8640b079d5@35.73.137.11:30311"]
 - Add Static nodes

Geth also supports a feature called static nodes if you have certain peers you always want to connect to. Static nodes are re-connected on disconnects. You can configure permanent static nodes by putting something like the following into ``<datadir>/geth/static-nodes.json:``

     [
       "enode://pubkey@ip:port",
       "enode://     cfc556867894dc84707c2ce6290740d6ba112b279217e6db420f215397492a91ef76bbfe18ebd349a09b37fc8bfef5740d2d2335838e063094d5     b63c3fd20d8f@34.197.85.99:30311",
       "enode://     7cf68af17a83f925f34eeced2a139b1d11bac03fd2635707e459a821965b5e6016021a43379f24dc428ebcb84b8fb377517dee6ae484cd276a2f     9360dac9c183@52.86.7.102:30311",
       "enode://     b2ed83944f4c0e18d6b2f5f6c2e86b0320c10b8a96f897a535b43f25dc625ae739f449765ad86f38a393472638fcef69f30d7af53b02c3545722     b1dd6f18f606@34.194.252.9:30311",
       "enode://     42deadff5ff5d97ea4245128952335969fafea6c4ddd05146b3cac125099e1b2d1ea42c8d02c11ee8b5272a75d4f4b9f51a99244fd6daf1c6a1d     5017242a3d43@101.36.120.67:30311",
       "enode://     905f585c09b8eed66afdf8a99acdab7487185357f33d5c9fe40332e4aa4a661382b159ffb300b20fbc12e81505505944ac3bfc7e6673b352d01e     09f2df8af5bc@152.32.131.34:30311",
       "enode://     e585bafb7ab5a187534d69e84531165e5d4b0ee4f76b21641fe778c53770cd72e1850d44b48ad00c08ca4dc860cd5c5afa04b23a5061303f61d2     658b1c48b9b2@152.32.132.171:30311",
       "enode://     8fb5dd1259e0672efb8c141434bf0c24c73b338f7c2da15efc2def7403b952d453814230eeb97f555aaed46ee0b0b6e2a8568b518f88bd328729     031746114dd2@3.0.236.154:30311",
       "enode://     8fb5dd1259e0672efb8c141434bf0c24c73b338f7c2da15efc2def7403b952d453814230eeb97f555aaed46ee0b0b6e2a8568b518f88bd328729     031746114dd2@3.0.236.154:30311"
     ]

You can also add static nodes at runtime via the js console using admin.addPeer():

     admin.addPeer( "enode://8fb5dd1259e0672efb8c141434bf0c24c73b338f7c2da15efc2def7403b952d453814230eeb97f555aaed46ee0b0b6e2a8568b518f88bd328729031746114dd2@3.0.236.154:30311"
     )
 - Add ``Trusted nodes``

Geth supports trusted nodes that are always allowed to reconnect, even if the peer limit is reached. They can be added permanently via a config file ``<datadir>/geth/trusted-nodes.json ``or temporary via RPC call.


##### **Chaindata Snapshot​**

Please download the chain data [snapshot]() and extract to your home folder to speed up

     ## Extract the data
     unzip geth.zip -d /NAME_OF_YOUR_HOME/node &


**Sync Mode​**

 - Fast Sync

The **default**  sync mode. Synchronizes a full node doing a fast synchronization by downloading the entire state database, requesting the headers first, and filling in block bodies and receipts afterward. Once the fast sync reaches the best block of the BNB Smart Chain network, it switches to full sync mode.

 - Full Sync

Synchronizes a full node starting at genesis, verifying all blocks and executing all transactions. This mode is a bit slower than the fast sync mode but comes with increased security.


##### **Steps to Run a Fullnode​**

**Sync From Snapshot (Recommended)**
​
1. Download the pre-build binaries from release page or follow the instructions below:
     # Linux
     wget   $(curl -s https://api.github.com/repos/bnb-chain/bsc/releases/latest |grep browser_ |grep geth_linux |cut -d\" -f4)
     # MacOS
     wget   $(curl -s https://api.github.com/repos/bnb-chain/bsc/releases/latest |grep browser_ |grep geth_mac |cut -d\" -f4)

2. Download the config files

Download ``genesis.json`` and ``config.toml`` by:

     wget   $(curl -s https://api.github.com/repos/bnb-chain/bsc/releases/latest |grep browser_ |grep mainnet |cut -d\" -f4)
     unzip mainnet.zip

3. Download snapshot


Download latest snapshot from [Download site]() Follow the guide to structure the files.

4. Start a full node

     geth --config ./config.toml --datadir ./node --diffsync --cache 8000 --rpc.allow-unprotected-txs --txlookuplimit 0

**Sync From Genesis Block (Not Recommended)​**

1. Build from source code

Make sure that you have installed [Go 1.13+]() and have added ``GOPATH`` to ``PATH`` environment variable

     git clone https://github.com/bnb-chain/bsc
     # Enter the folder bsc was cloned into
     cd bsc
     # Compile and install bsc
     make geth

or you can download the pre-build binaries from [release page]() or follow the instructions below:

     # Linux
     wget   $(curl -s https://api.github.com/repos/binance-chain/bsc/releases/latest |grep browser_ |grep geth_linux |cut -d\" -f4)
     # MacOS
     wget   $(curl -s https://api.github.com/repos/binance-chain/bsc/releases/latest |grep browser_ |grep geth_mac |cut -d\" -f4)

2. Download the config files

Download ``genesis.json`` and ``config.toml`` by:

     ## mainet
     wget   $(curl -s https://api.github.com/repos/binance-chain/bsc/releases/latest |grep browser_ |grep mainnet |cut -d\" -f4)
     unzip mainnet.zip

     ## testnet
     wget   $(curl -s https://api.github.com/repos/binance-chain/bsc/releases/latest |grep browser_ |grep testnet |cut -d\" -f4)
     unzip testnet.zip

3. Write genesis state locally

     geth --datadir node init genesis.json

You could see the following output:

     INFO [05-19|14:53:17.468] Allocated cache and file handles         database=/Users/huangsuyu/Downloads/bsc/node/geth/chaindata cache=16.00MiB handles=16
     INFO [05-19|14:53:17.498] Writing custom genesis block
     INFO [05-19|14:53:17.501] Persisted trie from memory database      nodes=21 size=56.84KiB time=357.915µs gcnodes=0 gcsize=0.00B gctime=0s livenodes=1 livesize=-574.00B
     INFO [05-19|14:53:17.502] Successfully wrote genesis state         database=chaindata hash=7d79cc…fb0d1e
     INFO [05-19|14:53:17.503] Allocated cache and file handles         database=/Users/huangsuyu/Downloads/bsc/node/geth/lightchaindata cache=16.00MiB handles=16
     INFO [05-19|14:53:17.524] Writing custom genesis block
     INFO [05-19|14:53:17.525] Persisted trie from memory database      nodes=21 size=56.84KiB time=638.396µs gcnodes=0 gcsize=0.00B gctime=0s livenodes=1 livesize=-574.00B
     INFO [05-19|14:53:17.528] Successfully wrote genesis state         database=lightchaindata hash=7d79cc…fb0d1e


4. Start your fullnode

!!! Note BREAKING CHANGE: Non-EIP155 transactions (i.e. transactions which are not replay-protected) are now rejected by the RPC API. You can disable this restriction using the --rpc.allow-unprotected-txs command-line flag.

     ## start a full node
     geth --config ./config.toml --datadir ./node  --cache 8000 --rpc.allow-unprotected-txs --txlookuplimit 0

Start a validator node

     ## generate the consensus key and input the password
     geth account new --datadir ./node
     echo {your-password} > password.txt
     geth --config ./config.toml --datadir ./node --syncmode snap -unlock {your-validator-address} --password password.txt  --mine  --allow-insecure-unlock  --cache 8000


!!! Note Because the default value of TrieTimeout in config.toml is large, it means geth will not persist state into database until reach this time threshold, if the node has been force shutdown, it will start syncing from last state which may take long time. The recommended setting for valiidators is ``TrieTimeout = 100000000000``

5. Monitor node status

you can monitor the log from ``/node/bsc.log`` by default.


##### **Node Maintainence**

**Peer Discovery​**

The bootstrap nodes will be enhanced in the short future. So far, a discovery http service will provide some stable public p2p peers for syncing. Please visit [https://api.binance.org/v1/discovery/peers]() to get dynamic peer info. You can append the peer info to the ``StaticNodes`` in the config.toml to enhance the networking of the full nodes. To avoid crowded networking, the discovery service will change the peer info from time to time, try fetch new ones if the connected peers of full node are too few.


**Binary​**

All the clients are suggested to upgrade to the [latest release](). The latest version is supposed to be more stable and get better performance.


**Storage​**

According to the test, the performance of a fullnode will degrade when the storage size exceeds 1.5T. We suggest the fullnode always keep light storage by pruning the storage.

How to prune:

 1. Stop the BSC node.
 2. Run ``nohup geth snapshot prune-state --datadir {the data dir of your bsc node} &``. It will take 3-5 hours to finish.
 3. Start the node once it is done.

The maintainers should always have a few backup nodes.

The hardware is also important, **make sure the SSD meets: 2T GB of free disk space, solid-state drive(SSD), gp3, 8k IOPS, 250MB/S throughput, read latency <1ms.**


**Diff Sync**
​
The diffsync protocol rolled out as a stable feature in release v1.1.5. Diff sync improves the syncing speed by 60%～70% approximately according to the test. All full nodes are suggested to enable it by adding ``--diffsync`` in the starting command.


**Light Storage​**

When the node crashes or been force killed, the node will sync from a block that was a few minutes or a few hours ago. This is because the state in memory is not persisted into the database in real time, and the node needs to replay blocks from the last checkpoint once it start. The replaying time dependents on the configuration  ``TrieTimeout`` in the config.toml. We suggest you raise it if you can tolerate with long replaying time, so the node can keep light storage.


##### **Upgrade Geth​**

Please read [this guide]()



### Download Blockchain Snapshot

#### **Chaindata Snapshot**

For latest chaindata snapshots visit [here]()

**For v1.1.0:​**

 - [Latest Snapshot]()

 - [2021-05-15 snapshot]() (size 220GB)


checksum: 39e311c37a9844b4dd7fb218553cc99f


 - [2021-05-13 snapshot]()(Size: 203G)

 - [2021-05-02 snapshot]() (Size: 175G)


**For v1.0.7:​**

 - [2021-04-15 snapshot]() (271 GB, md5sum 3ace16d3e2a52100025da387c73861a3f00de833)

 - [2021-04-17 snapshot]() (260 GB, md5sum dd68c7fddaba42997eda013535a572cb)

March snapshot: [download]() (146 GB, md5sum 74ada3bcd6a9d0f101501919f6cc8a534e9d796e)

February snapshot: [download]() (87.4 GB, md5sum 6611dedde095ba9b72b50ebf6c35a8d7)

The following commands are step by step instructions for BSC node operators that can be used for two major use-cases:

 1. Fixing nodes that are stuck or crashed;
 2. Jumpstarting a newly setup validator node; avoid waiting some hours for synchronization

Basically, a compressed version of the last-known "good" chaindata is downloaded. Remove the node's old data and update it with the newly downloaded data. Finally, restart the sync-process from this known-good checkpoint.

Note: Ensure there is enough disk space for both the zip file AND its uncompressed contents. Double the space or more.

Download March Snapshot from CLI using wget

      wget --no-check-certificate --no-proxy 'https://s3.ap-northeast-1.amazonaws.com/dex-bin.bnbstatic.com/s3-witness-data-download/chaindata_202103.zip?AWSAccessKeyId=AKIAYINE6SBQPUZDDRRO&Expires=1641450253&Signature=hOC8I8HSpCOytlYMVQwKRc5oUaI%3D'


Tip: extract the data in the background

In case you can not wait for the extraction to finish, you can run it in the background

      # Extract the data
      nohup unzip  /NAME_OF_YOUR_HOME/node/geth/ -f chaindata_202102.zip &
      # Start your node back
      geth --config ./config.toml --datadir ./node --syncmode snap


### Local BNB Smart Chain Network

See also : [https://github.com/ethereum/go-ethereum/wiki/Private-network]()

#### **Setting up your BSC Node(s)**
​
##### **Pre-Requisites​**

**Install Geth​**

Review the guide [here]()

[Create /projects​]()

Create a ``/projects`` symbolic link (Note: This step is simply so "/projects" can be used in all other commands, instead you could use full paths, or set an env var)

      $ mkdir <my projects folder>
      $ sudo ln -s <my projects folder> /projects


 **Create local_ethereum_blockchain folder**

      $ mkdir /projects/local_ethereum_blockchain

##### **Create the genesis block config​**

Create this file : ``/projects/local_ethereum_blockchain/genesis.json``

With the following contents :

      {
           "config": {
             "chainId": 1000,
             "homesteadBlock": 0,
             "eip155Block": 0,
             "eip158Block": 0
                      },
           "nonce": "0x0000000000000061",
           "timestamp": "0x0",
           "parentHash": "0x0000000000000000000000000000000000000000000000000000000000000000",
           "gasLimit": "0x8000000",
           "difficulty": "0x100",
           "mixhash": "0x0000000000000000000000000000000000000000000000000000000000000000",
           "coinbase": "0x3333333333333333333333333333333333333333",
           "alloc": {}
      }

([info about the genesis file]())


##### **Initialize an Ethereum node​**

      $ geth --datadir /projects/local_ethereum_blockchain/node1 init /projects/local_ethereum_blockchain/genesis.json

##### **Start the Ethereum node​**

      $ geth --datadir /projects/local_ethereum_blockchain/node1 --networkid 1000 console

##### **Initialize another Ethereum node​**

      $ geth --datadir /projects/local_ethereum_blockchain/node-2 init /projects/local_ethereum_blockchain/genesis.json

##### **Start the 2nd Ethereum node​**

      $ geth --datadir /projects/local_ethereum_blockchain/node-2 --port 30304 --nodiscover --networkid 1000 console

##### **Connect one node to the other​**

In one geth console :

      > admin.nodeInfo.enode

In the other console :

      > admin.addPeer( <the enode value from the first console> )


#### **Useful geth commands​**

##### **Node info​**

      > admin.nodeInfo

##### **Peers​**

Show peers

      > admin.peers

How many peers ?

      > admin.peers.length

##### **Create an account​**

You need an account to do be able to do things like mining

      > personal.newAccount()

And make sure you remember/save the password!

##### **Unlock account​**

Neccessary before some actions

      > personal.unlockAccount( eth.accounts[0] )

##### **Start mining​**

      > miner.start(1)

The first block may take a while to mine, allow a few minutes

##### **Stop mining​**

      > miner.stop()

##### **Current block number​**

      > eth.blockNumber
##### **Details of current block​**

      > eth.getBlock( eth.blockNumber )
##### **Which node minded the last block​**

      > eth.getBlock(eth.blockNumber).miner
##### **Account balance, in ether​**

      > web3.fromWei(eth.getBalance(eth.accounts[0]))
##### **Transfer ether between accounts​**

First get the account numbers by doing

      > eth.accounts

Then unlock the account you are sending from

      > personal.unlockAccount( <from account> )

eg.

      > personal.unlockAccount(eth.accounts[0])

Finally transfer 1 ether

      > eth.sendTransaction({from: "<from account>", to: "<to account>", value: web3.toWei(1, "ether")})

##### **Exit​**

      > exit

(This will also stop the node from running if it was started using ``$ geth console`` (as opposed to ``$ geth attach``))

#### **Connect to other nodes on your network​**

 1. Get the IP of the node : ``$ ifconfig|grep netmask|awk '{print $2}'``

 2. Get the enode of the node : ``> admin.nodeInfo.enode``

 3. REPLACE ``[::]`` in the enode string with the ``[<ip address>]``

 4. On your console ``> admin.addPeer(< the enode string with the ip address in it>)``


### Upgrading Geth

 #### **How to Upgrade Geth**

Updating geth is as easy as it gets. You just need to download and install the newer version of geth, shutdown your node and restart with the new software. Geth will automatically use the data of your old node and sync the latest blocks that were mined since you shut down the old software.

**Step 1: Compile the new version**
​
      git clone https://github.com/bnb-chain/bsc
      # Enter the folder bsc was cloned into
      cd bsc
      # Comile and install bsc
      make geth

**Step 2: Stop Geth​**

      $ pid=`ps -ef | grep geth | grep -v grep | awk '{print $2}'`

      $ kill  $pid

**Step 3: Restart​**

      ## start a full node
      geth --config ./config.toml --datadir ./node --syncmode snap


## RPC

### **JSON-RPC Endpoint**

#### **Available Resources​**

**Mainnet(ChainID 0x38, 56 in decimal)​**

BSC RPC Endpoints:

!!! NOTE You can make eth_getLogs requests with up to a 5K block range. If you need to pull logs frequently, we recommend using WebSockets to push new logs to you when they are available.

Recommend

 - [https://bsc-dataseed.binance.org/]()
 - [https://bsc-dataseed1.defibit.io/]()
 - [https://bsc-dataseed1.ninicoin.io/]()
 - [https://bsc.nodereal.io]()

BC RPC Endpoints:

 - [https://dataseed1.binance.org/]()
 - [https://dataseed2.binance.org/]()
 - [https://dataseed3.binance.org/]()
 - [https://dataseed4.binance.org/]()
 - [https://dataseed1.defibit.io/]()
 - [https://dataseed2.defibit.io/]()
 - [https://dataseed3.defibit.io/]()
 - [https://dataseed4.defibit.io/]()
 - [https://dataseed1.ninicoin.io/]()
 - [https://dataseed2.ninicoin.io/]()
 - [https://dataseed3.ninicoin.io/]()
 - [https://dataseed4.ninicoin.io/]()

**Testnet(ChainID 0x61, 97 in decimal)**
​
BSC RPC Endpoints:

 - [https://data-seed-prebsc-1-s1.binance.org:8545/]()
 - [https://data-seed-prebsc-2-s1.binance.org:8545/]()
 - [https://data-seed-prebsc-1-s2.binance.org:8545/]()
 - [https://data-seed-prebsc-2-s2.binance.org:8545/]()
 - [https://data-seed-prebsc-1-s3.binance.org:8545/]()
 - [https://data-seed-prebsc-2-s3.binance.org:8545/]()


BC RPC Endpoints:

 - [http://data-seed-pre-0-s1.binance.org:80]()
 - [http://data-seed-pre-1-s1.binance.org:80]()
 - [http://data-seed-pre-2-s1.binance.org:80]()
 - [http://data-seed-pre-0-s3.binance.org:80]()
 - [http://data-seed-pre-1-s3.binance.org:80]()

**Rate limit​**

The rate limit of BSC endpoint on Testnet and Mainnet is 8K/5min.

**3rd Party Provider​**

 - [ANKR](): [https://app.ankr.com/api]()

 - [Chainstack](): [https://chainstack.com/build-better-with-binance-smart-chain/]()

 - [GetBlock.io](): [https://getblock.io/nodes/bsc]()

 - [QuickNode]() : [https://quicknode.com]()

 - [NodeReal](): [https://docs.nodereal.io/nodereal/meganode/introduction]()

 - [BlockVision](): [https://docs.blockvision.org/blockvision/chain-apis/bnb-chain-api]()


**Start​**

You can start the HTTP JSON-RPC with the --rpc flag

      ## mainnet
      geth attach https://bsc-dataseed1.binance.org

      ## testnet
      geth attach https://data-seed-prebsc-1-s1.binance.org:8545/

**JSON-RPC methods​**

Please refer to this [wiki page]() or use Postman: [https://documenter.getpostman.com/view/4117254/ethereum-json-rpc/RVu7CT5J?version=latest]()


## Deploy Smart Contract

### Using Remix IDE

Deploys a BEP20 smart contract with a message, and renders it in the front-end. You can interact with the smart contract easily!

This dapp implements a "Hello World" style application that echoes a message passed to the contract to the front end. This tutorial is intended to be followed using the online IDE available at [Remix IDE]().

**Setting up [Remix IDE​]()**

 - Remix is an online IDE to develop smart contracts.
 - You need to choose Solidity Compiler and Deploy and Run Transactions.

![Screenshot](img/pastedimage0.png)

 - Go to File Explorers, And Create a new file, Name it MegaCoin.sol
 - Copy/Paste the Smart contract below into the newly created file ``MegaCoin.sol``

**The smart contract​**

 - Create new contract BEP20Token.sol and copy contract code from the bep20 token template [here]()

 - Modify “name”, “symbol”, “decimals” and “totalSupply” according to your requirements.

![Screenshot](img/bep20Code.png)


The first line, ``pragma solidity ^0.5.16`` specifies that the source code is for a Solidity version greater than 0.5.16. [Pragmas]() are common instructions for compilers about how to treat the source code (e.g., pragma once).

A contract in the sense of Solidity is a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. Learn more about the [constructor]() and [memory]() in the docs.


**Compile Smart Contract​**

 - Step1: Click button to switch to compile page

 - Step2: Select “BEP20Token” contract

 - Step3: Enable “Auto compile” and “optimization”

 - Step4: Click “ABI” to copy the contract abi and save it.

![Screenshoot](img/bep20Compile.png)


Now, We have to deploy our smart contract on BNB Smart Chain Network. For that, we have to connect to web3 world, this can be done my many services like Metamask, Brave, Portis etc. We will be using Metamask. Please follow this [tutorial to setup a Metamask Account]().

 - Open Metamask and select Custom RPC from the networks dropdown

 - Go to setting page

![Screenshot](img/pastedimage01.png)

 - Add a new network

![Screenshot](img/pastedimage02.png)

 - Testnet


      * [RPC URLs](/docs/rpc)
      * ChainID: 97
      * Symbol: BNB
      * Block Explorer: https://testnet.bscscan.com


 - Mainnet

      * [RPC URLs](/docs/rpc)
      * ChainID: 56
      * Symbol: BNB
      * Block Explorer: https://bscscan.com

 - Go ahead and click save

 - Copy your address from Metamask

 - Head over to Faucet and request test BNB

 - Now, let's Deploy the Smart Contract on BNB Smart Chain Testnet

 - Select Injected Web3 in the Environment dropdown and your contract

![Screenshot](img/pastedimage03.png)

 - Accept the Connection Request!

![Screenshot](img/pastedimage04.png)

 - Once Metamask is connected to Remix, the ‘Deploy’ transaction would generate another metamask popup that requires transaction confirmation.

![Screenshot](img/pastedimage05.png)


**Congratulations!** You have successfully deployed a BEP20 Contract. Now you can interact with the Smart Contract. Check the deployment status here: [https://testnet.bscscan.com/]()


### Using Truffle

#### **Setting up the development environment​**

#### **Requirements​**

There are a few technical requirements before we start. Please install the following: Requirements:

 - Windows, Linux or Mac OS X
 - [Node.js v8.9.4 LTS or later]()
 - [Git]()

**Recommendations for Windows** If you're running Truffle on Windows, you may encounter some naming conflicts that could prevent Truffle from executing properly. Please see the section on resolving naming conflicts for solutions.

#### **Installing Truffle​**

Once we have those installed, we only need one command to install Truffle:

       npm install -g truffle

To verify that Truffle is installed properly, type ``truffle version`` on a terminal. If you see an error, make sure that your npm modules are added to your path.

#### **Project Creation, Compilation, and Configuration​**

The first step is to create a Truffle project. We'll use the *MegaCoin as an example, which creates a token that can be transferred between accounts:

##### **Create a new directory for your Truffle project​**

       mkdir MegaCoin
       cd MegaCoin

##### **Intialize your project:​**

To initialize your project use the following command

       truffle init

Once this operation is completed, you'll now have a project structure with the following items:

 - contracts/: Directory for Solidity contracts
 - migrations/: Directory for scriptable deployment files
 - test/: Directory for test files for testing your application and contracts
 - truffle-config.js: Truffle configuration file

##### **Create Contract​**

You can write your own smart contract or download the BEP20 token smart contract template.

##### **Compile Contract​**

To compile a Truffle project, change to the root of the directory where the project is located and then type the following into a terminal:

       truffle compile

##### **Config Truffle for BSC​**

 - Go to truffle-config.js
 - Update the truffle-config with bsc-network-crendentials.

         const HDWalletProvider = require('@truffle/hdwallet-provider');
         const fs = require('fs');
         const mnemonic = fs.readFileSync(".secret").toString().trim();
       
         module.exports = {
           networks: {
             development: {
             host: "127.0.0.1",     // Localhost (default: none)
             port: 8545,            // Standard BSC port (default: none)
             network_id: "*",       // Any network (default: none)
           },
           testnet: {
             provider: () => new HDWalletProvider(mnemonic, `https://data-seed-prebsc-1-s1.binance.org:8545`),
             network_id: 97,
             confirmations: 10,
             timeoutBlocks: 200,
             skipDryRun: true
          },
           bsc: {
             provider: () => new HDWalletProvider(mnemonic, `https://bsc-dataseed1.binance.org`),
             network_id: 56,
             confirmations: 10,
             timeoutBlocks: 200,
             skipDryRun: true
           },
         },
       
         // Set default mocha options here, use special reporters etc.
         mocha: {
           // timeout: 100000
         },
       
         // Configure your compilers
         compilers: {
           solc: {
             version: "^0.6.12", // A version or constraint - Ex. "^0.5.0"
           }
         }
        }


Notice, it requires mnemonic to be passed in for Provider, this is the seed phrase for the account you'd like to deploy from. Create a new .secret file in root directory and enter your 12 word mnemonic seed phrase to get started. To get the seedwords from metamask wallet you can go to Metamask Settings, then from the menu choose Security and Privacy where you will see a button that says reveal seed words.

#### **Deploying on BSC Network​**

Run this command in root of the project directory:

       $ truffle migrate --network testnet

Contract will be deployed on Binance Chain Chapel Testnet, it look like this:

       1_initial_migration.js
       ======================

       Deploying 'Migrations'
       ----------------------
       > transaction hash:    0xaf4502198400bde2148eb4274b08d727a17080b685cd2dcd4aee13d8eb954adc
       > Blocks: 3            Seconds: 9
       > contract address:    0x81eCD10b61978D9160428943a0c0Fb31a5460466
       > block number:        3223948
       > block timestamp:     1604049862
       > account:             0x623ac9f6E62A8134bBD5Dc96D9B8b29b4B60e45F
       > balance:             6.24574114
       > gas used:            191943 (0x2edc7)
       > gas price:           20 gwei
       > value sent:          0 ETH
       > total cost:          0.00383886 ETH

        Pausing for 5 confirmations...
       ------------------------------
       > confirmation number: 2 (block: 3223952)
       > confirmation number: 3 (block: 3223953)
       > confirmation number: 4 (block: 3223954)
       > confirmation number: 6 (block: 3223956)

       > Saving migration to chain.
       > Saving artifacts
       -------------------------------------
       > Total cost:          0.00383886 ETH

       Summary
       =======
       > Total deployments:   1
       > Final cost:          0.00383886 ETH

Remember your address, transaction_hash and other details provided would differ, Above is just to provide an idea of structure.

**Congratulations!** You have successfully deployed BEP20 Smart Contract. Now you can interact with the Smart Contract.

You can check the deployment status here: [https://bscscan.com/]() or [https://testnet.bscscan.com/]()

#### **Verify Your Contract on BscScan**

The recommended way to verify a smart contract is using plugin. It is easier to read, imports are maintained, licenses are maintained.

**Verified using Truffle**

Example: [https://testnet.bscscan.com/token/0x68D2E27940CA48109Fa3DaD0D2C8B27E64a0c6cf]()

GitHub Project: [https://github.com/huangsuyu/verify-example]()

##### **BscSCAN plugin for Truffle​**

Truffle has an BscScan plugin: [truffle-plugin-verify]()

You need to deploy with Truffle to verify with the Truffle verify plugin.

Get API key: [https://bscscan.com/myapikey]()

##### ***Install the plugin​**

       npm install -D truffle-plugin-verify

##### **Configure the plugin​**

Configure the plugin in ``truffle-config.js`` using the following command

       const HDWalletProvider = require("@truffle/hdwallet-provider");

       // const infuraKey = "fj4jll3k.....";
       //
       const { mnemonic, BSCSCANAPIKEY} = require('./env.json');

       module.exports = {

         plugins: [
        'truffle-plugin-verify'
        ],
        api_keys: {
        bscscan: BSCSCANAPIKEY
        },
        networks: {

        testnet: {
        provider: () => new HDWalletProvider(mnemonic, `https://data-seed-prebsc-1-s1.binance.org:8545`),
        network_id: 97,
        timeoutBlocks: 200,
        confirmations: 5,
        production: true    // Treats this network as if it was a public net. (default: false)
        }
       },

       // Set default mocha options here, use special reporters etc.
       mocha: {
        timeout: 100000
       },

        // Configure your compilers
       compilers: {
         solc: {
          version: "0.5.16",    // Fetch exact version from solc-bin (default: truffle's version)
          // docker: true,        // Use "0.5.1" you've installed locally with docker (default: false)
         settings: {          // See the solidity docs for advice about optimization and evmVersion
          optimizer: {
          enabled: false,
          runs: 200
        },
         evmVersion: "byzantium"
        }
         },
        },
       };

##### **Verification Command​**

       truffle run verify BEP20Token@{contract-address} --network testnet

You should see the following output:

       Verifying BEP20Token@0x68D2E27940CA48109Fa3DaD0D2C8B27E64a0c6cf
       Pass - Verified: https://testnet.bscscan.com/address/0x68D2E27940CA48109Fa3DaD0D2C8B27E64a0c6cf#contracts
       Successfully verified 1 contract(s).



### Using Hardhat

#### **What is Hardhat​**

Hardhat is a development environment to compile, deploy, test, and debug your smart contract.

#### **Setting up the development environment​**

There are a few technical requirements before we start. Please install the following: Requirements:

#### **Installing​**

There are a few technical requirements before we start. Please install the following: Requirements:

 - Windows, Linux or Mac OS X
 - [Node.js v8.9.4 LTS or later]()
 - [Git]()


First, you need to create an empty project ``npm init --yes``

Once your project is ready, you should run

       npm install --save-dev hardhat

It's recommeded to install some dependencies.

       npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers

To use your local installation of Hardhat, you need to use npx to run it (i.e. npx hardhat).

#### **Create A Project​**

To create your Hardhat project run npx hardhat in your project folder:

       mkdir MegaCoin
       cd MegaCoin

 - Intialize your project:

       $ npx hardhat
       888    888                      888 888               888
       888    888                      888 888               888
       888    888                      888 888               888
       8888888888  8888b.  888d888 .d88888 88888b.   8888b.  888888
       888    888     "88b 888P"  d88" 888 888 "88b     "88b 888
       888    888 .d888888 888    888  888 888  888 .d888888 888
       888    888 888  888 888    Y88b 888 888  888 888  888 Y88b.
       888    888 "Y888888 888     "Y88888 888  888 "Y888888  "Y888

       Welcome to Hardhat v2.0.8

       ? What do you want to do? …
       ❯ Create a sample project
          Create an empty hardhat.config.js
          Quit


Once this project is initialized, you'll now have a project structure with the following items:

 - contracts/: Directory for Solidity contracts
 - scripts/: Directory for scriptable deployment files
 - test/: Directory for test files for testing your application and contracts
 - hardhat-config.js: Hardhat configuration file

##### **Create Contract​**

You can write your own smart contract or download the [BEP20 token smart contract template]().

##### **Config Hardhat for BSC​**

 - Go to hardhat.config.js
 - Update the config with bsc-network-crendentials.


        require("@nomiclabs/hardhat-waffle");
        require('@nomiclabs/hardhat-ethers');
        const { mnemonic } = require('./secrets.json');

        // This is a sample Hardhat task. To learn how to create your own go to
        // https://hardhat.org/guides/create-task.html
        task("accounts", "Prints the list of accounts", async () => {
          const accounts = await ethers.getSigners();

         for (const account of accounts) {
           console.log(account.address);
          }
         });

        // You need to export an object to set up your config
        // Go to https://hardhat.org/config/ to learn more
 
        /**
         * @type import('hardhat/config').HardhatUserConfig
         */
        module.exports = {
         defaultNetwork: "mainnet",
         networks: {
          localhost: {
             url: "http://127.0.0.1:8545"
            },
             hardhat: {
            },
             testnet: {
             url: "https://data-seed-prebsc-1-s1.binance.org:8545",
             chainId: 97,
             gasPrice: 20000000000,
             accounts: {mnemonic: mnemonic}
            },
          mainnet: {
          url: "https://bsc-dataseed.binance.org/",
          chainId: 56,
          gasPrice: 20000000000,
          accounts: {mnemonic: mnemonic}
            }
           },
        solidity: {
        version: "0.5.16",
        settings: {
           optimizer: {
           enabled: true
           }
          }
         },
        paths: {
         sources: "./contracts",
         tests: "./test",
         cache: "./cache",
         artifacts: "./artifacts"
          },
        mocha: {
          timeout: 20000
          }
        };

!!! Note It requires mnemonic to be passed in for Provider, this is the seed phrase for the account you'd like to deploy from. Create a new ``.secret`` file in root directory and enter your 12 word mnemonic seed phrase to get started. To get the seedwords from metamask wallet you can go to Metamask Settings, then from the menu choose Security and Privacy where you will see a button that says reveal seed words.

##### **Compile Contract​**

To compile a Hardhat project, change to the root of the directory where the project is located and then type the following into a terminal:

       npx hardhat compile

##### **Deploying on BSC Network​**

Run this command in root of the project directory:

       $  npx hardhat run --network testnet scripts/deploy.js

  Remember your address, transaction_hash and other details provided would differ, Above is just to provide an idea of structure.

**Congratulations!** You have successfully deployed BEP20 Smart Contract. Now you can interact with the Smart Contract.

You can check the deployment status here: [https://bscscan.com/]() or [https://testnet.bscscan.com/]()

#### **Verify with Hardhat**

Hardhat has an Etherscan plugin: [Hardhat Etherscan plugin]()

   Note: Hardhat was previously Buidler.

##### **Install the plugin​**

       npm install --save-dev @nomiclabs/hardhat-etherscan

##### **Configure the plugin in buidler.config.js​**

 - Add require("@nomiclabs/hardhat-etherscan");
 - Add Bscscan API key

!!! warning keep secret and don’t commit to version control)

Go to register and get API key: [https://bscscan.com/myapikey]()

 - Set compiler version to match what was deployed

        // hardhat.config.js
        const { mnemonic, bscscanApiKey } = require('./secrets.json');

        require('@nomiclabs/hardhat-ethers');
        require("@nomiclabs/hardhat-etherscan");
        /**
         * @type import('hardhat/config').HardhatUserConfig
         */
        module.exports = {

         networks: {
          testnet: {
           url: `https://data-seed-prebsc-1-s1.binance.org:8545`,
          accounts: {mnemonic: mnemonic}
         },
         mainnet: {
          url: `https://bsc-dataseed.binance.org/`,
          accounts: {mnemonic: mnemonic}
          }
         },

          etherscan: {
            // Your API key for Etherscan
           // Obtain one at https://bscscan.com/
          apiKey: bscscanApiKey
           },
           solidity: "0.5.12"
        };

##### **Verify​**

!!! warning Remove any unnecessary contracts and clear the artifacts otherwise these will also be part of the verified contract.

Run the following command:

       npx buidler verify --network mainnet DEPLOYED_CONTRACT_ADDRESS "Constructor argument 1"

 - Example

        $ npx hardhat  verify --network testnet 0xbF39886B4F91F5170934191b0d96Dd277147FBB2
        Nothing to compile
        Compiling 1 file with 0.5.16
        Successfully submitted source code for contract
        contracts/BEP20Token.sol:BEP20Token at 0xbF39886B4F91F5170934191b0d96Dd277147FBB2
        for verification on Etherscan. Waiting for verification result...

        Successfully verified contract BEP20Token on Etherscan.
        https://testnet.bscscan.com/address/0xbF39886B4F91F5170934191b0d96Dd277147FBB2#code


### Verify Your Contract on BscScan

#### **How to Verify Your Contract on BscScan**

**Step 1:** Deploy your contract on BNB Smart Chain

**Step 2:** Go to [BSC Explorer]() or [Testnet Explorer]()

Click on "Verify and Publish"

![Screenshot](img/pastedimage06.png)


**Step 3:** Fill in the correct information of your contract

![Screenshot](img/pastedimage07.png)


 - Contract Address
 - Compiler Type you chose in Remix or other complier
 - Select Open Source License Type

**Step 4:** Enter the Solidity Contract Code

![Screenshot](img/pastedimage08.png)


You need to select "Yes" for Optimization, if that's enabled.

Contructor arguement is optional. If your contract do have one, you can go to [this page]() to generate the encoded ABI json.

!!! info

        The default BEP20 contract template does not have a constructor method

Click on "Verify and Publish" to finish this process. Now you are all set!


## Deploy NFTs

### NFT Metadata Standard

#### **Implementing token URI**

To facilitate a marketplace on BSC to pull in off-chain metadata for BEP721 assets, the NFT contract will need to return a URI where the metadata can be found. To find this URI, the tokenURI method in ERC721 and the uri method in ERC1155 are used to track your NFT. You should implement the function in the Contract:


       /**
        * @dev Returns an URI for a given token ID
        */
       function tokenURI(uint256 _tokenId) public view returns (string) {
         return Strings.strConcat(
           baseTokenURI(),
           Strings.uint2str(_tokenId)
         );
       }

The tokenURI function in your Contract should return an HTTP or IPFS URL. When queried, this URL should in turn return a JSON blob of data with the metadata for your token.

#### **Metadata structure**

Marketplaces on BSC support metadata that is structured according to [the official ERC721 metadata standard](). Additionally, several properties for your items are supported, giving you all the sorting and filtering capabilities on BSC Marketplaces. The below metadata structure, allows the BSC Marketplace to read and display the details about the assets which your NFTs represent.


       {
           "name":"NFT Name",
           "description":"NFT Description",
           "image":"https://somedomain.com/pic/xxxx.jpg",
           "external_url":"https://originalsite.io/2",
           "attributes":[...]
       }

Here's how each of these properties work:

| Property | Description |
| --------- | ---------- |
| name | Name of the item. Max 200 characters. |
| description | A human-readable description of the item. Markdown is supported. Max 500 characters. |
| image |	This is the URL to the image of the item. It can be just about any type of image. A 350 x 350 image is recommended. |
| animation_url | This is the URL to a multi-media attachment for the item. The file extensions GLTF, GLB, WEBM, MP4, M4V, OGV, and OGG are supported, along with the audio-only extensions MP3, WAV, and OGA. |
| animation_type | This is the file format of the multi-media attachment provided from animation_url. |
| external_url | This is the URL that will appear below the asset's image on the marketplace and will allow users to leave the marketplace and view the item on your site. |
| attributes | These are the attributes for the item to describe the detail of the NFT. (see array below) |


##### **Attributes​**

To present NFT traits, include the following array in the metadata:


        {
             "attributes":[
              {
                "trait_type":"Rarity Class",
                "value":"Normal"
            },
            {
                 "trait_type":"Type",
                "value":"Male"
            },
             {
               "trait_type":"Face",
              "value":"Mole"
              },
              {
                 "trait_type":"Beard",
                 "value":"Chinstrap"
             },
             {
                 "display_type":"boost_number",
                 "trait_type":"Power",
                 "value":"Power"
             },
             {
                 "display_type":"boost_percentage",
                 "trait_type":"Health Increase",
                 "value":"20"
             },
             {
                 "display_type":"number",
                 "trait_type":"Generation",
                 "value":"3"
             }
            ]
        }


Here ``trait_type`` is the name of the trait, ``value`` is the value of the trait, and ``display_type`` is a field indicating how you would like a numeric value should be displayed. For string traits, you don't have to worry about ``display_type``. All traits included in the attributes will be displayed in ``Attribute``. If you don't want to have a ``trait_type`` for a particular trait, you can include just a value in the trait and it will be set as a generic attribute.

**Numeric Traits​**

There are 3 supported options for ``display_type``: ``number`` will show the value in pure number, ``boost_number`` allows you to show the number with Plus or Minus symbol, and ``boost_percentage`` is similar to boost_number but will show a percent sign behind the number.

**Date​**

Marketplace also supports date traits in ``date`` ``display_type``. Pass in a unix timestamp as the value.


         {
          "display_type": "date", 
          "trait_type": "birthday", 
          "value": 1608490000
         }
    
### Deploy  NFT on BSC

This work is inspired by [this blog]()

In this tutorial we will create a [non-fungible token (NFT)]() and deploy to a public testnet.

ERC721 is a standard for representing ownership of non-fungible tokens, that is, where each token is unique such as in real estate or collectibles.

We will use [Presets]() contracts in [OpenZeppelin Contracts]() to create an ERC721 and deploy using Truffle.

#### **Setting up the Environment​**

We begin by creating a new project.

       $ mkdir mynft && cd mynft
       $ npm init -y

Then we install [OpenZeppelin Contracts]() which has an implementation of ERC721.

       $ npm i --save-dev @openzeppelin/contracts

Next we install a development tool for deployment, for this tutorial we will use [Truffle]() but we could use any other tools such as Buidler, Remix or [OpenZeppelin CLI]().

       $ npm i truffle

#### **Getting the contract artifacts​**

We will setup our Solidity project using ``truffle init`` to create a ``contracts`` directory and configuration to connect to a network.

       $ npx truffle init
       Starting init...
       ================

       > Copying project files to

       Init successful, sweet!


We are going to use Preset ``[ERC721PresetMinterPauserAutoId]()`` which is an ERC721 that is preset so it can be minted (with auto token ID and metadata URI), paused and burned.

The Preset contracts have already been compiled, so we only need to copy the artifacts to the ``build/contracts`` directory.

       $ mkdir -p build/contracts/
       $ cp node_modules/@openzeppelin/contracts/build/contracts/* build/contracts/

Using your favorite editor create ``2_deploy.js`` in the ``migrations`` directory with the following contents:

       // migrations/2_deploy.js
       // SPDX-License-Identifier: MIT
       const ERC721PresetMinterPauserAutoId = artifacts.require("ERC721PresetMinterPauserAutoId");

       module.exports = function(deployer) {
        deployer.deploy(ERC721PresetMinterPauserAutoId, "My NFT","NFT", "http://my-json-server.typicode.com/huangsuyu/nft/tokens");
       };


#### **Deploy the contract to a local blockchain​**

We will use ``[truffle develop]()`` to open a Truffle console with a development blockchain

 - Head over to [Faucet]() and request test BNB

        $ npx truffle develop
        Truffle Develop started at http://127.0.0.1:9545/

        Accounts:
        (0) 0xc7e4bbc4269fdc62f879834e363173aee7895f45

        Private Keys:
        (0) ef424b4dc91a9c9d6c1fc4ae0a50ce80668f3a955a7e982584b45577e2c70e27

        Mnemonic: mechanic cannon setup general indicate people notable frown poet friend credit true

        ⚠️  Important ⚠️  : This mnemonic was created for you by Truffle. It is not secure.
        Ensure you do not use it on production blockchains, or else you risk losing funds.

        truffle(develop)> migrate

        Compiling your contracts...
        ===========================
        > Compiling ./contracts/Migrations.sol
        > Artifacts written to /Users/Documents/work/mynft/build/contracts
        > Compiled successfully using:
           - solc: 0.5.16+commit.9c3226ce.Emscripten.clang

        Starting migrations...
        ======================
        > Network name:    'develop'
        > Network id:      5777
        > Block gas limit: 6721975 (0x6691b7)

        1_initial_migration.js
        ======================

         Deploying 'Migrations'
          ----------------------
        > transaction hash:    0x9a17a50e6efd52ba3e55245c76c52b065d20587add45aee732c233987033e567
        > Blocks: 0            Seconds: 0
        > contract address:    0x77409B688eA5461078a31450F3138EA8324F72C9
        > block number:        1
        > block timestamp:     1604387655
        > account:             0xc7e4bBc4269fdC62F879834E363173aeE7895F45
        > balance:             99.99616114
        > gas used:            191943 (0x2edc7)
        > gas price:           20 gwei
        > value sent:          0 ETH
        > total cost:          0.00383886 ETH


        > Saving migration to chain.
        > Saving artifacts
        -------------------------------------
        > Total cost:          0.00383886 ETH


        2_deploy.js
        ===========

         Deploying 'ERC721PresetMinterPauserAutoId'
         ------------------------------------------
        > transaction hash:    0xc1a3994c2ad2ba706ac49934b4f480c7b3d9b94241f526afa2dfe91545145a4e
        > Blocks: 0            Seconds: 0
        > contract address:    0xEaB17D581552123695f03F12b09e378EE9463b44
        > block number:        3
        > block timestamp:     1604387655
        > account:             0xc7e4bBc4269fdC62F879834E363173aeE7895F45
        > balance:             99.92142266
        > gas used:            3694586 (0x385ffa)
        > gas price:           20 gwei
        > value sent:          0 ETH
        > total cost:          0.07389172 ETH


        > Saving migration to chain.
        > Saving artifacts
        -------------------------------------
        > Total cost:          0.07389172 ETH


        Summary
        =======
        > Total deployments:   2
        > Final cost:          0.07773058 ETH

        truffle(develop)>


We can deploy our new NFT to our development blockchain using migrate.

        truffle(develop)> migrate

        Compiling your contracts...
        ===========================
        > Everything is up to date, there is nothing to compile.



        Starting migrations...
        ======================
        > Network name:    'develop'
        > Network id:      5777
        > Block gas limit: 6721975 (0x6691b7)


        1_initial_migration.js
        ======================

          Replacing 'Migrations'
          ----------------------
        > transaction hash:    0x5d71b0a45a0fe20e2ca645393bb44b83fbd47351c009c48be0b8b84b610fb3b7
        > Blocks: 0            Seconds: 0
        > contract address:    0x3797c825cAC4a1FA765F6D8cd7787fB195849555
        > block number:        1
        > block timestamp:     1590736865
        > account:             0x0445c33BdCe670D57189158b88c0034B579f37cE
        > balance:             99.99671674
        > gas used:            164163 (0x28143)
        > gas price:           20 gwei
        > value sent:          0 ETH
        > total cost:          0.00328326 ETH


        > Saving migration to chain.
        > Saving artifacts
        -------------------------------------
        > Total cost:          0.00328326 ETH


        2_deploy.js
        ===========

         Replacing 'ERC721PresetMinterPauserAutoId'
         ------------------------------------------
        > transaction hash:    0x166d7b28f4afb949585b5a0e5b4151daa54acbcb70566b202fd62ab380a6650c
        > Blocks: 0            Seconds: 0
        > contract address:    0xDEE9411430c7Dd9b67fC6DA723DE729AdAB50AD7
        > block number:        3
        > block timestamp:     1590736866
        > account:             0x0445c33BdCe670D57189158b88c0034B579f37cE
        > balance:             99.92191642
        > gas used:            3697675 (0x386c0b)
        > gas price:           20 gwei
              > value sent:          0 ETH
        > total cost:          0.0739535 ETH
 

        > Saving migration to chain.
        > Saving artifacts
        -------------------------------------
        > Total cost:           0.0739535 ETH


        Summary
        =======
        > Total deployments:   2
        > Final cost:          0.07723676 ETH


We can then use our deployed contract.

       truffle(develop)> nft = await ERC721PresetMinterPauserAutoId.deployed()
       undefined


#### **Interact with our Token​**

The accounts that we can use were displayed when we started ``truffle develop``

**Token metadata​**

We can call the contract to read token metadata such as ``name``, ``symbol`` and ``baseURI``

       truffle(develop)> await nft.name()
       'My NFT'
       truffle(develop)> await nft.symbol()
       'NFT'
       truffle(develop)> await nft.baseURI()

**Mint​**

We can send a transaction to mint tokens to a given account, from an account with the minter role. In our case we are minting from the account which deployed the token, which is given the minter role.

We will mint 1 NFT with token ID 0.

        truffle(develop)> await nft.mint("0x0445c33bdce670d57189158b88c0034b579f37ce")
        { tx:
           '0xd301a60dbb8ac187687f6639f200d4e6f2cfa065923092b3940330e35a26421d',
          receipt:
           { transactionHash:
              '0xd301a60dbb8ac187687f6639f200d4e6f2cfa065923092b3940330e35a26421d',
             transactionIndex: 0,
             blockHash:
              '0x3ad3cfcb26da0c969e9d5a5414a5e90a91a3a862c9e9082afc38a0ec0f1a5d00',
             blockNumber: 5,
             from: '0x0445c33bdce670d57189158b88c0034b579f37ce',
             to: '0xdee9411430c7dd9b67fc6da723de729adab50ad7',
             gasUsed: 156470,
        ...

We can check the owner of the token and the token URI for the metadata

        truffle(develop)> await nft.ownerOf(1)
        '0x0445c33BdCe670D57189158b88c0034B579f37cE'
        truffle(develop)> await nft.tokenURI(1)

**MetaData​**

[EIP-721 2]() includes an optional **metadata extension** with a ``name``, ``symbol`` and for each tokenID a tokenURI with can point to a JSON file with ``name``, ``description`` and ``image`` for the given token ID.

How you create and host this metadata is up to you. I would suggest using a domain that you control to point to where you host the data so that you can move it as required.

For this tutorial, we will use [My JSON Server]() where we can store a single JSON file in a GitHub repository that we can access via a fake JSON server.

⚠️ For production we need to store our metadata in a permanent location that can exist for the life of the token.

A sample JSON for tokenID 1 is: [http://my-json-server.typicode.com/huangsuyu/nft/tokens/1]()


**Deploy to a public testnet​**

Next we will deploy to BNB Smart Chain testnet .

To deploy, we will use the instructions for [Connecting to Public Test Networks with Truffle]()

You will need the following:

 - An Infura project ID (or a public node provider of your choice)
 - ``@truffle/hdwallet-provider`` installed
 - Configure ``truffle-config.js`` for Rinkeby network
 - A funded testnet account and mnemonic
 - A ``secrets.json`` or another secret-management solution. **Make sure you don’t commit this to GitHub!**

My ``truffle-config.js`` has the following ``rinkeby`` configuration:

       testnet: {
         provider: () => new HDWalletProvider(mnemonic, `https://data-seed-prebsc-1-s1.binance.org:8545`),
         network_id: 97,
         confirmations: 10,
         timeoutBlocks: 200,
         skipDryRun: true
         },
        bsc: {
          provider: () => new HDWalletProvider(mnemonic, `https://bsc-dataseed1.binance.org`),
          network_id: 56,
          confirmations: 10,
         timeoutBlocks: 200,
         skipDryRun: true
        },


**Deploy to BSC Testnet​**

        $ npx truffle migrate --network testnet

        Compiling your contracts...
        ===========================
        > Everything is up to date, there is nothing to compile.

        Starting migrations...
        ======================
        > Network name:    'develop'
        > Network id:      5777
        > Block gas limit: 6721975 (0x6691b7)


        1_initial_migration.js
        ======================

         Deploying 'Migrations'
         ----------------------
           > transaction hash:    0x9a17a50e6efd52ba3e55245c76c52b065d20587add45aee732c233987033e567
           > Blocks: 0            Seconds: 0
           > contract address:    0x77409B688eA5461078a31450F3138EA8324F72C9
           > block number:        1
           > block timestamp:     1604387655
           > account:             0xc7e4bBc4269fdC62F879834E363173aeE7895F45
           > balance:             99.99616114
           > gas used:            191943 (0x2edc7)
           > gas price:           20 gwei
           > value sent:          0 ETH
           > total cost:          0.00383886 ETH


           > Saving migration to chain.
           > Saving artifacts
           -------------------------------------
           > Total cost:          0.00383886 ETH


        2_deploy.js
        ===========

           Deploying 'ERC721PresetMinterPauserAutoId'
           ------------------------------------------
           > transaction hash:    0xc1a3994c2ad2ba706ac49934b4f480c7b3d9b94241f526afa2dfe91545145a4e
           > Blocks: 0            Seconds: 0
           > contract address:    0xEaB17D581552123695f03F12b09e378EE9463b44
           > block number:        3
           > block timestamp:     1604387655
           > account:             0xc7e4bBc4269fdC62F879834E363173aeE7895F45
           > balance:             99.92142266
           > gas used:            3694586 (0x385ffa)
           > gas price:           20 gwei
           > value sent:          0 ETH
           > total cost:          0.07389172 ETH


           > Saving migration to chain.
           > Saving artifacts
           -------------------------------------
           > Total cost:          0.07389172 ETH


        Summary
        =======
        > Total deployments:   2
        > Final cost:          0.07773058 ETH


**Mint​**

We can send a transaction to mint tokens to a given account, from an account with the minter role.

       truffle(develop)> nft = await ERC721PresetMinterPauserAutoId.deployed()
       undefined

In our case we are minting from the account which deployed the token, which is given the minter role.

To see configured accounts run the command ``accounts``.

       truffle(rinkeby)> accounts
       [ '0x133d144f52705ceb3f5801b63b9ebccf4102f5ed',

We will mint 1 NFT with token ID 1. Specify the address that you want to be the token holder (``0xc7e4bBc4269fdC62F879834E363173aeE7895F45`` is one of my test accounts)

       truffle(rinkeby)> await nft.mint("0x133d144f52705ceb3f5801b63b9ebccf4102f5ed")
       { tx:
          '0x0d90d4a2a4ac3f33d5220deb11e8f65adf14a6669afd18abd4cce8ca7ab58e04',
         receipt:
          { blockHash: '0x724ba66bc1d799820c05a93ae67991b21bb769fd1e9dddd5db9f725f5f633331',
            blockNumber: 3333746,
            contractAddress: null,
            cumulativeGasUsed: 164785,
            from: '0x77737a65c296012c67f8c7f656d1df81827c9541',
            gasUsed: 164785,
       ...



## BEP20 Tokens

### Introduction

A BEP20 token must implement the interface ``IBEP20`` in [IBEP20.sol](). This is a template contract [BEP20Token.template](). Users just need to fill in ``_name``, ``_symbol``, ``_decimals`` and ``_totalSupply`` according to their own requirements:

         constructor() public {
           _name = {{TOKEN_NAME}};
           _symbol = {{TOKEN_SYMBOL}};
           _decimals = {{DECIMALS}};
           _totalSupply = {{TOTAL_SUPPLY}};
           _balances[msg.sender] = _totalSupply;

           emit Transfer(address(0), msg.sender, _totalSupply);
         }

Then users can use [Remix IDE]() and [Metamask]() to compile and deploy the BEP20 contract to BSC.

#### Interact with Contract with [Web3]() and NodeJS.​

**Connect to BNB Smart Chain's public RPC endpoint​**

        const Web3 = require('web3');
        // mainnet
        const web3 = new Web3('https://bsc-dataseed1.binance.org:443');

        // testnet
        const web3 = new Web3('https://data-seed-prebsc-1-s1.binance.org:8545');

**Create a wallet**
​
       web3.eth.accounts.create([entropy]);

Output:

       web3.eth.accounts.create();
       {
         address: '0x926605D0729a968266f1BB299d8Df0471C4F5367',
         privateKey: '0x6b4618539d95f205f33e916e89404b301dde545c0c4acc181fd0c0b42708bad3',
         signTransaction: [Function: signTransaction],
         sign: [Function: sign],
         encrypt: [Function: encrypt]
       }

**Recover a wallet​**

       const account = web3.eth.accounts.privateKeyToAccount("0xe500f5754d761d74c3eb6c2566f4c568b81379bf5ce9c1ecd475d40efe23c577")

**Check balance​**

       web3.eth.getBalance(holder).then(console.log);

Output:

The balance will be bumped by e18 for BNB.

       6249621999900000000

##### **Create transaction​**

**Parameters**

 - Object - The transaction object to send:
 - from - String|Number: The address for the sending account. Uses the web3.eth.defaultAccount property, if not specified. Or an address or index of a local wallet in web3.eth.accounts.wallet.
 - to - String: (optional) The destination address of the message, left undefined for a contract-creation transaction.
 - value - Number|String|BN|BigNumber: (optional) The value transferred for the transaction in wei, also the endowment if it’s a contract-creation transaction.
 - gas - Number: (optional, default: To-Be-Determined) The amount of gas to use for the transaction (unused gas is refunded).
 - gasPrice - Number|String|BN|BigNumber: (optional) The price of gas for this transaction in wei, defaults to web3.eth.gasPrice.
 - data - String: (optional) Either a ABI byte string containing the data of the function call on a contract, or in the case of a contract-creation transaction the initialisation code.
 - nonce - Number: (optional) Integer of a nonce. This allows to overwrite your own pending transactions that use the same nonce.


           // // Make a transaction using the promise
           web3.eth.sendTransaction({
               from: holder,
               to: '0x0B75fbeB0BC7CC0e9F9880f78a245046eCBDBB0D',
               value: '1000000000000000000',
               gas: 5000000,
               gasPrice: 18e9,
           }, function(err, transactionHash) {
             if (err) {
               console.log(err);
               } else {
               console.log(transactionHash);
              }
           });

### Issue BEP20 Tokens
 
**Compile and Deploy BEP20 Contract**

1. Open Remix IDE: [https://remix.ethereum.org]()

![Screenshot](img/bep1.png)

2.Select solidity language

![Screenshot](img/bep2.png)
3. Create new contract BEP20Token.sol and copy contract code from the bep20 token template [here]()

4.Modify “name”, “symbol”, “decimals” and “totalSupply” according to your requirements.

![Screenshot](img/bep3.png)


  5.Compile the BEP20 token contract

a. Step1: Click button to switch to compile page

b. Step2: Select “BEP20Token” contract

c. Step3: Enable “Auto compile” and “optimization”

d. Step4: Click “ABI” to copy the contract abi and save it.

![Screenshot](img/bep4.png)


  6.Deploy the contract to BSC

a. Step1: Click button to switch to compile button.

b. Step2: Select “Injected Web3”

c. Step3: Select “BEP20Token”

d. Step4: Client “Deploy” button and Metamask will pop up

![Screenshot](img/bep5.png)

e. Client “confirm” button to sign and broadcast transaction to BSC.

![Screenshot](img/bep6.png)

### Bind Tokens
#### Cross-chain Token Management

The dual-chain architecture of Beacon Chain & BNB Smart Chain empowers you to build your own decentralized apps while also taking advantage of the fast trading performance offered on Binance DEX (decentralized exchange). The native cross-chain communication mechanism allows tokens to be transferred between BC and BSC easily.

BNB Smart Chain and Beacon Chain work together to ensure that one token can circulate in both formats with confirmed total supply and be used in different use cases.

**BEP2/BEP8 Token Owner​**

If you are BEP2/BEP9 token owner, please follow this [guideline]() to complete Bind process when you wish to migrate to BSC.

You can also use this [tool]().

**BEP20 Owner​**

If you are BEP20 token owner or anybody else, please follow this [guideline]() to complete Mirror process when you wish to migrate to BC or get listed on Binance DEX.

**Comparison Between Bind and Mirror​**

| | Bind | Mirror |
| ----- | -------- | ----------- |
| Initiator | BEP2/BEP8 Token Owner | Anyone, including BEP20 Token Owner and others |
| Fee | less than 1BNB | about 100 BNB, mirrorFee is a governable parameter |
| How long will it take | several minutes | ~30s |
| Supply Distribution |	Customized between BC & BSC |	All supplies are on BSC |

