# How to use `privacy-routing-sdk`

You can use `privacy-routing-sdk` to transfer any FRC-20 asset (including FRA) on Findora Smart Chain from Address A to Address B, and remove the link between the two addresses. Both addresses can be classical user address or contract address. 

---

### Installation

```bash
npm install privacy-routing-sdk
```

### Requirement wasm package

- Add [findora-wallet-wasm](https://github.com/FindoraNetwork/privacy-routing-sdk/tree/main/findora-wallet-wasm) into your project

- Add the path into your `package.json` as a dependency
```json
// package.json
{
  // ...
  "dependencies": {
    "findora-wallet-wasm": "./findora-wallet-wasm",
  }
  // ...
}
```

### Usage
- #### [Documentation](https://docs.findora.org/developers/sdks/privacy-routing-sdk)
