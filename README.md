# IoTeX-config

## Build binary
```
git clone https://github.com/iotexproject/iotex-core.git
cd iotex-core && git checkout v1.8.0
make build-all
sudo cp ./bin/server /usr/local/bin/iotex-server
```

## Launch command:
### First node:
`/usr/local/bin/iotex-server -config-path=/home/ansible/nodes/iotex_mainnet_full_1/etc/config.yaml -genesis-path=/home/ansible/nodes/iotex_mainnet_full_1/etc/genesis.yaml -plugin=gateway`
### Second node:
`/usr/local/bin/iotex-server -config-path=/home/ansible/nodes/iotex_mainnet_full_2/etc/config.yaml -genesis-path=/home/ansible/nodes/iotex_mainnet_full_2/etc/genesis.yaml -plugin=gateway`

