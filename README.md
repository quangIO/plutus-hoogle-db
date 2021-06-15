# Hoogle
Download [plutus.hoo](https://github.com/quangIO/plutus-hoogle-db/blob/main/plutus.hoo?raw=true) and place it somewhere, for example `~/hoogle-db/`

## Hoogle usage
You can use the CLI like this

```
hoogle -d ~/hoogle-db/plutus.hoo -n 25 Wallet
hoogle -d ~/hoogle-db/plutus.hoo -n 25 'EmulatorConfig -> InitialChainState'
```

or start the server on port `8081` and go to localhost:8081 to use the web ui

`hoogle server --database ~/hoogle-db/plutus.hoo -p 8081`
