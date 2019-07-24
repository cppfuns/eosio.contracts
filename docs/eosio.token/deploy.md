## Steps to compile and deploy eosio.token contract

In order to deploy the eosio.token contract you need to build it first; instructions on how to build all system eosio.contracts can be found in the introduction section [here](../introduction.md), please go through those steps first before following below instructions.

### To deploy execute the following commands:

To deploy a contract you will need first an account to which to deploy it to.
Let's assume your account name is `testertoken`

```
cleos set contract testertoken you_local_path_to/eosio.contracts/build/contracts/eosio.token/ -p testertoken
```