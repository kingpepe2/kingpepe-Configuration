## 📢 Important Announcement for KingPepe Users – Wallet & Node Configuration

If you're running a KingPepe full node or wallet, please make sure your configuration file is set up as follows:

### 🧾 kingpepe.conf Configuration

Create or edit the file located at `~/.kingpepe/kingpepe.conf` with the following content:

```ini
rpcuser=rpc_kingpepe
rpcpassword=dR2oBQ3K1zYMZQtJFZeAerhWxaJ5Lqeq9J2
rpcbind=127.0.0.1
rpcallowip=127.0.0.1
p2pport=24028
rpcport=24027
listen=1
server=1
txindex=1
daemon=1
addnode=node3.walletbuilders.com   or http://85.237.211.140:24028
