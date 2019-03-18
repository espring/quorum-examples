# 节点工作目录下需要准备的文件
node1/setup.conf;
node1/node/genesis.json;
node1/node/qdata/gethLogs
node1/node/qdata/constellationLogs

## setup.conf
```
# 节点名
NODENAME=node1
# 节点IP
CURRENT_IP= 10.50.0.2
THIS_NODEMANAGER_PORT=22004
# 
RPC_PORT=22000
RAFT_ID=1
# 节点的公钥 (并非是帐号)
PUBKEY=Tur5exkue9tExBZ/YCCzWbBwzNV0Ofj/1PL1Fa45cVM=
ROLE=


MODE=ACTIVE
STATE=I
# NodeManager启动后立刻安装的 NetworkManagerContract.sol 合约地址
CONTRACT_ADD=0x675b8d24a6d78c6d135add5d4e5c677ce366f1d8
REGISTERED=TRUE
```
