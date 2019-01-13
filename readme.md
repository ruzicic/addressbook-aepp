# addressbook aepp 

## Prerequisites
- [Docker](https://docs.docker.com/compose/install/) - required for local aeternity node for compiling, testing and development environment
- [ForgAE](https://www.npmjs.com/package/forgae) æternity development framework which helps with setting up a project
- [Aecli](https://github.com/aeternity/aepp-cli-js) æternity’s JavaScript SDK command-line interface

## Running

Start docker and then start our local node with:

```bash
forgae node

# To stop the local node, simply run
forgae node --stop
```

Compile [Sophia](https://dev.aepps.com/aepp-sdk-docs/Sophia.html) contracts
```bash
forgae compile
```

## Testing
```bash
forgae test
```

## Useful links
- [hack.bg](https://hack.bg/blog/tutorials/build-your-first-decentralized-application-aepp-on-aeternity-blockchain-sophia-smart-contract-address-book/)