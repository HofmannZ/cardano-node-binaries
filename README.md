##
***A repo where we will keep various versions of the cardano node and cli binaries built for ARM CPUs*** 🏴‍☠️🦾

BIG Thanks to SPO's [ZW3RK](https://twitter.com/zw3rkpool/) who provides the amazing Static Binaries, [SRN](https://armada-alliance.com/stake-pools/cc1b1c03798884c636703443a23b8d9e827d6c0417921600394198a0) who provides dynamic builds and maintains repo with [PIADA](https://armada-alliance.com/stake-pools/b8d8742c7b7b512468448429c776b3b0f824cef460db61aa1d24bc65) and our friend [Daniel](https://github.com/rekuenkdr) ₳🏴‍☠️🙏
## Cardano Node RTS Parameter Notebook

**This contains information about various run time optimizations Armada Alliance SPOs are using to improve their cardano-node's performance. For more information about GHC RTS parameters and running compiled programs read the Haskell document ["Using GHC"](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/runtime_control.html)**

***[Armada Alliance Cardano RTS Notebook](https://docs.google.com/spreadsheets/d/1sw_fzqoubOEG6lMpWKVzCF8yISfY4YFAvnx_5E5T-1s/edit#gid=0)***

Thank you to [PGWAD](https://armada-alliance.com/stake-pools/7e45a7e6ab3afcf99120e97aedf84e706e43d829ddc610ad667a85a3) for setting it up and all our members who have contributed 🙏🏴‍☠️

##
### Static build (Compatible for all arm based linux. Recommended)
[1.33.0](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_33_0.zip?raw=true) (Official)

```
wget -O 1_33_0.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_33_0.zip?raw=true
```

[1.33.1 with cardano-submit-api](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_33_1.zip?raw=true) (Latest)

```
wget -O 1_33_1.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_33_1.zip?raw=true
```

##
### Dynamic build (Ubuntu 20.04 and above. Requires libsodium.)
[1.34.0](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.0/cardano-1_34_0-aarch64-ubuntu_2004.zip?raw=true) (Official)

```
wget -O cardano-1_34_0-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.0/cardano-1_34_0-aarch64-ubuntu_2004.zip?raw=true
```

[1.34.1](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.1/cardano-1_34_1-aarch64-ubuntu_2004.zip?raw=true) (Latest)

```
wget -O cardano-1_34_1-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.1/cardano-1_34_1-aarch64-ubuntu_2004.zip?raw=true
```

[cardano-submit-api-3.1.2](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.0/cardano-submit-api.zip?raw=true) (Built with cardano-node-1.34.0)

```
wget -O cardano-submit-api.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.0/cardano-submit-api.zip?raw=true
```

[Building Libsodium](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.0/README.MD)

##
### Current Configuration files for the Cardano Blockchain Protocol

[Cardano Configuration Files](https://hydra.iohk.io/build/7654130/download/1/index.html)

##
### Alonzo Purple Testnet build (deprecated)
[1.31.0](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.31.0/cardano-1_31_0-aarch64-ubuntu_2004.zip?raw=true)

### Alonzo Purple Testnet Configuration Files (deprecated)
[Alonzo Purple Configuration Files](https://hydra.iohk.io/build/7366583/download/1/index.html)

##
### Latest Unnoffical Mainnet/Testnet Configuration Files
[Latest Configuration Files](https://hydra.iohk.io/job/Cardano/iohk-nix/cardano-deployment/latest-finished/download/1/index.html)
