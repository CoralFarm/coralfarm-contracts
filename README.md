# CoralFarm Contracts

https://www.coralfarm.finance 

UML and description will be provided ASAP.

## Deployed Contracts / Hash

### BSCMAINNET

- CRLToken - https://bscscan.com/token/
- MasterChef - https://bscscan.com/address/
- Timelock - https://bscscan.com/address/
- MultiCall - https://bscscan.com/address/

### DEVELOP

install ganache cli `npm install -g ganache-cli truffle`

run `yarn`

in a window start
```ganache-cli --fork https://bsc-dataseed4.defibit.io/ -d```

copy `.env-develop` to `.env`

deploy contract

``` truffle deploy --network fork ```


