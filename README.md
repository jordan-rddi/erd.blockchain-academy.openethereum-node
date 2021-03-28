# Create an account
OpenEthereum provides a command line that allows us to interact with the node. To create an account we can use the `account new` command as follows:

`openethereum account new --chain spec.json --keys-path ./data/keys`

# Starting the node
To start the node with our customised configuration we can use:

`openethereum --config config.toml`