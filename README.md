# awesome-ton

## TON original
- [C++ node with minimal tools & services](https://github.com/ton-blockchain/ton)

## [TON Labs](https://tonlabs.io/)
TON Labs is focused on developing the core infrastructure and an Open Source ecosystem for the Free TON
### [docs.ton.dev](https://docs.ton.dev/)
- [Validator FAQ](https://docs.ton.dev/86757ecb2/p/83dfff-validator-faq)
- [SMART CONTRACT LORE Security](https://docs.ton.dev/86757ecb2/p/55f73e-security)
- [Getting started with TON smart contracts](https://docs.ton.dev/86757ecb2/p/12d2bf-getting-started-with-ton-smart-contracts)
- [GraphQL API, SDK, CLI](https://docs.ton.dev/86757ecb2/p/39fc5e-products)
### https://github.com/tonlabs
- Solidity compiler for TON ([Sol2TVM](https://github.com/tonlabs/TON-Solidity-Compiler))
- Sample smart-contracts by TON Labs https://github.com/tonlabs/samples
- TON Labs smart contracts (safemultisig, setcodemultisig, cpp/tokens-fungible) https://github.com/tonlabs/ton-labs-contracts
- Original (C++) node fork with patches https://github.com/tonlabs/ton-1
- net.ton.dev validator environment https://github.com/tonlabs/net.ton.dev
- main.ton.dev validator environment https://github.com/tonlabs/main.ton.dev
- TON Labs own stack:
[ton-labs-node](https://github.com/tonlabs/ton-labs-node),
[tonos-cli](https://github.com/tonlabs/tonos-cli),
[ton-client-js](https://github.com/tonlabs/ton-client-js),

## Free TON
### [Free TON Community](https://freeton.org/)
### [forum.freeton.org](https://forum.freeton.org/)
- [Free TON to complete original TON development](https://forum.freeton.org/t/free-ton-to-complete-original-ton-development/1325)


## [ton-rocks](https://github.com/ton-rocks)

## admin tools
- FreeTon simple scripts (ask-return-stake, Update_Node, resend_stake) https://github.com/Custler/FreeTon-simple-scripts
- [FreeTON Toolbox](https://github.com/serge-medvedev/freeton-toolbox) -
dockerized validator node up & running, dashboard based on TICK stack
- [FreeTON Staking Manager](https://github.com/serge-medvedev/freeton-staking-manager)
- [ansible-freeton](https://github.com/br3d/ansible-freeton) –
Roles of Ansible for install and monitor FreeTon node.

## unsorted

```bash
# blockchain in RAM
killall validator-engine
ps aux | grep validator
sudo mv /var/ton-work /dev/shm
sudo ln -s /dev/shm/ton-work /var/ton-work
ls /var/ton-work
stat /var/ton-work
./run.sh

# blockchain in ROM
killall validator-engine
rm /var/ton-work
mv /dev/shm/ton-work /var
ls /var/ton-work
stat /var/ton-work
./run.sh
```

[GRAM SDK for TON](https://github.com/gram-net/gram-sdk)

[Listen and decode messages](https://docs.ton.dev/86757ecb2/p/312aa6-listen-and-decode-messages)

This is set of guides that outlines a process of bootstrapping Telegram Open Network node on FreeBSD systems.
[sonofmom/freebsd_ton_guide](https://github.com/sonofmom/freebsd_ton_guide)

[How come each program or service has an account of its own in /etc/passwd?](https://unix.stackexchange.com/questions/115177/how-come-each-program-or-service-has-an-account-of-its-own-in-etc-passwd/115184#115184)


## other useful tools
- [UFW](https://help.ubuntu.com/community/UFW) -  default firewall configuration tool for Ubuntu
- [anything-sync-daemon (asd)](https://wiki.archlinux.org/index.php/Anything-sync-daemon) is a tiny pseudo-daemon
designed to manage user specified directories referred to as sync targets from here on out, in tmpfs
and to periodically sync them back to the physical disc (HDD/SSD).
This is accomplished via a symlinking step and an innovative use of rsync to maintain synchronization
between a tmpfs copy and media-bound backups. Additionally, asd features several crash recovery features.



