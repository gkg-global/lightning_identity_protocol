# Lightning Identity protocol
This repository is a modification of [Lightning
Network's](lightning.network) protocol for identity routing. The Lightning Network
used for private route HTLC's
(Hash-Time-Locked-Contracts) within the
network.

The Lightning Identity protocol is composed for "direct channels" approach between two participants. By linking these channels in a pair-wise
manner, a network of connect channels are created. 

Spirit of decentralization and censorship resistance, it use routing scheme within the [Lightning
protocol](https://github.com/lightningnetwork/lightning-rfc) to prevent the
ability of participants on the network to easily censor payments, as the
participants are not aware of the final destination of any given transaction.

