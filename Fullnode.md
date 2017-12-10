## Fullnode

A Bitcoin fullnode is a computer on which the bitcoin software is running.  Bitcoin can be run on various platforms, with or without a wallet and with or without a Graphical User Interface (GUI) and can be configured in variety of  ways.

Various configuration types have names, a node with a full copy of the blockchain is known as an archive node, a node without an entire copy of the blockchain is known as a pruned node.

Running a node affords you a certain level of security and privacy by default, as you are not relying on anyone else to validate the blockchain for you and you are not revealing information to third parties when querying your balance.

A fullnode needs to be connected to a datasource in order to receive new blocks from the miners as and when they are broadcast.   Usually nodes are connected via the Internet however it is also possible to connect a fullnode to a satellite.

In order to initialise a fullnode the entire blockchain must be downloaded and validated.  The blockchain is now in excess of 150Gb and the validation is processor intensive, so the amount of time it will take you to fully sync with the blockchain will depend upon the speed of your connection and the specification of the machine being used.

It is possible to run a fullnode on a low power low cost computer such as a Raspberry Pi, although we suggest performing the initial blockchain download and sync with something a little more powerful.

Using the bitcoin.conf configuration file it is possible to instruct your node to connect to TOR only for added privacy.  It is also then possible to configure SPV mobile wallets such as [Samourai](https://samouraiwallet.com) to connect to your fullnode.
