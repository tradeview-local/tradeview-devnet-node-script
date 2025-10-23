# tradeview-devnet-script

This repository provides ubuntu 22.04 and 24.04 script for running a node on tradeview devnet:

System Requirements:

- Operating System: Ubuntu 22.04 or 24.04
- Memory: At least 4GB RAM
- Storage: Minimum 20GB available disk space
- Network: Stable internet connection

Clone this repo using:
git clone '<https://github.com/tradeview-local/tradeview-devnet-node-script.git>'

Setup the node:
open a terminal window and run the following command:

./tradeview_ubuntu_node.sh

NOTE: The blockchain  is syncing in a background as a service. You can print the logs and check the logs of the node with the following command :

journalctl -u tradeviewchain.service -f
