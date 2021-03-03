# CoralFarm Contracts

https://www.coralfarm.finance 

UML and description will be provided ASAP.

## Deployed Contracts / Hash

### BSCMAINNET

- CRLToken - https://bscscan.com/token/0xC00B1FfA922Edf1175a4E6fEaAC5B2B469932524
- MasterChef - https://bscscan.com/address/0x713e34640ef300a0B178a9688458BbA8b1FA35A7
- Timelock - https://bscscan.com/address/0xAd900E7eb4Fc3A5272CAf914D65517718aDce1d1

### DEVELOP

install ganache cli `npm install -g ganache-cli truffle`

run `yarn`

in a window start
```ganache-cli --fork https://bsc-dataseed4.defibit.io/ -d```

copy `.env-develop` to `.env`

deploy contract

``` truffle deploy --network fork ```


