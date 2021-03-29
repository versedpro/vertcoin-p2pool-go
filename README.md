# P2Pool Implementation in Go

**WARNING: This is very early pre-beta work. Don't use it yet.**

This is a re-implementation of P2Pool in Go. Initially this supports Vertcoin, but it's aimed to be multicoin.

## Status

Currently the following things are planned/completed:

- [X] Allow connecting to p2pool nodes (wire protocol implementation)
- [X] Peermanager for managing connections to other peers
- [X] Retrieving the sharechain from other peers
- [X] Building the sharechain
- [X] Validating the sharechain
- [ ] Connecting to a fullnode over RPC
- [ ] Retrieve block template from fullnode
- [ ] Compose block from share data
- [ ] Stratum server
- [ ] Submit shares to p2pool network
- [ ] Web frontend

If you have any ideas, feel free to submit them as either issues or (better yet) pull requests.

## Donate

If you want to support the development of this project, feel free to donate!

Vertcoin: `VoNdwM7b6XSmH5L2geRfAzo1gP7n5A13AQ`
Bitcoin: `3E2Qfm8BPabZFLoSDtV7f33EYdLysxY3tB`