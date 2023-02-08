# lamina1

# lamina1

Base repository for a Lamina1 validation node.

## Building (When open-sourced)

Execute `BUILD.sh` at root, which will generate the requisite node binary and plugins.

## Running binary

  Download the latest release (up and to the right if viewing this README on the github page), extract, then cd lamina1/, or run ./BUILD.sh in this repository, then

## Join testnet

```
    curl https://lamina1.github.io/lamina1/config.testnet.tar | tar xf -
    ./lamina1-node  --config-file configs/testnet/default.json
```

## or run a local net (running on http/staking ports 19650/19671)

```
    ./run-l1-localnet.sh
```

## TESTNET

Testnet is currently located at `rpc-testnet.lamina1.com`

### Running testnet (for Lamina1 internal use only)

Make sure binaries have been built and `lamina1-node` is available at current directory.

```
. ./run-l1-testnet.sh
```

This began with a fork of Avalanche 1.8.6 of which the documentation for is at <https://web.archive.org/web/20220921203040/https://docs.avax.network/>

## Fork us, please  

Modify ./rebrand.sh as desired.

## How to stake on a node

Get the node-id with ./get_my_nodeid.sh

Use the web wallet at https://testnet.lamina1.network to stake your tokens on the returned node ID, under the "earn" option from the dropdown menu on the upper right.  You may need to use "cross chain" first to transfer tokens to the P chain first. 

## Further documentation

Visit https://testnet.lamina1.network for more information and guidance
