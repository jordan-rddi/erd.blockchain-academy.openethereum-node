# Details
This basic node configuration includes an existing account with a large amount of Ether.

Address: `0xa66001530562410Ad370E1C48a04512B9F436512`

Private Key: `0x3ca97f7ceddd93784c8de298dc2b35bfe13b90734da6973471a65daa0cb0388c`

Keystore password: `password`

# Create an account
OpenEthereum provides a command line that allows us to interact with the node. To create an account we can use the `account new` command as follows:

`openethereum account new --chain spec.json --keys-path ./data/keys`

# Starting the node
To start the node with our customised configuration we can use:

`openethereum --config config.toml`
