# Some Transaction records

```json
# contract deploy
Contract mined! address: 0x0be1427087970611dc9ba30f617bd5d3e73593c2 transactionHash: 0xffa36be9b84517cc8289438b3118890e757576faf0ed12bc0f1c3d8cbadb7e46
> eth.blockNumber
22

> eth.getTransaction("0xffa36be9b84517cc8289438b3118890e757576faf0ed12bc0f1c3d8cbadb7e46");
{
  blockHash: "0x4b3e8518efdc133c5d11594e7657ddd2ae5dfb734ef17adde9a71ac3e95c75ce",
  blockNumber: 22,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gas: 4700000,
  gasPrice: 20000000000,
  hash: "0xffa36be9b84517cc8289438b3118890e757576faf0ed12bc0f1c3d8cbadb7e46",
  input: "0x6060604052341561000c57fe5b5b6102428061001c6000396000f30060606040526000357c0100000000000000000000000000000000000000000000000000000000900463ffffffff16806331fe52e81461005c57806375a584b01461006e578063bae78d7b146100b3578063c59e9bfd146100ef575bfe5b341561006457fe5b61006c610101565b005b341561007657fe5b610099600480803590602001909190803560001916906020019091905050610176565b604051808215151515815260200191505060405180910390f35b34156100bb57fe5b6100d1600480803590602001909190505061019f565b60405180826000191660001916815260200191505060405180910390f35b34156100f757fe5b6100ff6101bd565b005b6000600090505b633b9aca00811015610172576000805480600101828161012891906101c5565b916000526020600020900160005b7f736f6d6520646174610000000000000000000000000000000000000000000000909190915090600019169055505b8080600101915050610108565b5b50565b600081600160008581526020019081526020016000208160001916905550600190505b92915050565b6000600160008381526020019081526020016000205490505b919050565b60006000fd5b565b8154818355818115116101ec578183600052602060002091820191016101eb91906101f1565b5b505050565b61021391905b8082111561020f5760008160009055506001016101f7565b5090565b905600a165627a7a72305820f14b9c0e7f0295dc3497594756305a922c771b9375443d2e2138f8797e2c5f7f0029",
  nonce: 0,
  r: "0x96c35f0d0455c922e6f026f6e22186589c4a49bcb335fa7721040bff347e8938",
  s: "0xd8866c42e2b3e11e5e9a4c96609cdcc5d7c5405c3c47392b50905f038187804",
  to: null,
  transactionIndex: 0,
  v: "0x1c",
  value: 0
}
> eth.getTransactionReceipt("0xffa36be9b84517cc8289438b3118890e757576faf0ed12bc0f1c3d8cbadb7e46");
{
  blockHash: "0x4b3e8518efdc133c5d11594e7657ddd2ae5dfb734ef17adde9a71ac3e95c75ce",
  blockNumber: 22,
  contractAddress: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  cumulativeGasUsed: 171761,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gasUsed: 171761,
  logs: [],
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  root: "0x4c5d45639434273de8c5492ab75042410c2e9762ac2ca015731c13fa53b34433",
  to: null,
  transactionHash: "0xffa36be9b84517cc8289438b3118890e757576faf0ed12bc0f1c3d8cbadb7e46",
  transactionIndex: 0
}
> eth.getBlock(22);
{
  difficulty: 132096,
  extraData: "0xd783010509846765746887676f312e362e32856c696e7578",
  gasLimit: 131363552,
  gasUsed: 171761,
  hash: "0x4b3e8518efdc133c5d11594e7657ddd2ae5dfb734ef17adde9a71ac3e95c75ce",
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  miner: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  mixHash: "0xd45439196c58e2c74a8f816eba45840614c63ea06fb963e6c37050442c304420",
  nonce: "0x3abffc94baaf6d45",
  number: 22,
  parentHash: "0xa36a917fd3362573e81ca1f68336cf7dea5f5eb1fcc5f8a2256aaaf6cd9e751a",
  receiptsRoot: "0x604df7e76dfedcf6ed6c723cfa95e75aa0ae797d9768046005ba50989f4ad71c",
  sha3Uncles: "0xe9e41d3bf49c8be9a62cbf0d9413c2e3332d93de6da82dc0268c41b15fd2ef79",
  size: 2297,
  stateRoot: "0x66a91c3f858811b40794a6dbfc94aa8f4f1796176b21fc2e5c5a140b96209e93",
  timestamp: 1494175016,
  totalDifficulty: 2896384,
  transactions: ["0xffa36be9b84517cc8289438b3118890e757576faf0ed12bc0f1c3d8cbadb7e46"],
  transactionsRoot: "0x8a483ff16fdb65df7f855134c593f6a8e8d4c2d77afac123c81c41bd7c757259",
  uncles: ["0xb59fdb9b32d5d203173a33ae7816b925372648bf469020a0b147b97beaaa6152", "0x86102f68b27ba493bda9a9bf5b9ce66df27950ca9ea4235ebf54a1b74969550b"]
}




## Add Entry success
> cmc_sol_democontract.addEntry(1, "ok", {from:eth.accounts[0], gas: 1000000});
"0xf452e5a1c01c861bbe72f4e91fa1578a681736414b617f4b0ea95339e90c2994"
> eth.blockNumber
23
> cmc_sol_democontract.getEntry(1);
"0x6f6b000000000000000000000000000000000000000000000000000000000000"


> eth.getTransaction("0xf452e5a1c01c861bbe72f4e91fa1578a681736414b617f4b0ea95339e90c2994");
{
  blockHash: "0x8b8ad5d53f3904eddaf9dc8cc81f2f02e976b8b6b15965564502c1c91ec1be57",
  blockNumber: 23,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gas: 1000000,
  gasPrice: 20000000000,
  hash: "0xf452e5a1c01c861bbe72f4e91fa1578a681736414b617f4b0ea95339e90c2994",
  input: "0x75a584b000000000000000000000000000000000000000000000000000000000000000016f6b000000000000000000000000000000000000000000000000000000000000",
  nonce: 1,
  r: "0xfe7e70f8ca7653e80d3894bc70c15ac36ee86a68484a213d58d5617f222a6815",
  s: "0x1a866af897c934dd85edfb390d4c2864285b7a702d371b9f759fe16009cdca79",
  to: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  transactionIndex: 0,
  v: "0x1c",
  value: 0
}
> eth.getTransactionReceipt("0xf452e5a1c01c861bbe72f4e91fa1578a681736414b617f4b0ea95339e90c2994");
{
  blockHash: "0x8b8ad5d53f3904eddaf9dc8cc81f2f02e976b8b6b15965564502c1c91ec1be57",
  blockNumber: 23,
  contractAddress: null,
  cumulativeGasUsed: 42103,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gasUsed: 42103,
  logs: [],
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  root: "0x15797b3c0f5c6f8af6f932e16a47edfc0dfa5b3f35bd5878b9e8a2c1216e360e",
  to: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  transactionHash: "0xf452e5a1c01c861bbe72f4e91fa1578a681736414b617f4b0ea95339e90c2994",
  transactionIndex: 0
}
> eth.getBlock(23)
{
  difficulty: 132032,
  extraData: "0xd783010509846765746887676f312e362e32856c696e7578",
  gasLimit: 131235520,
  gasUsed: 42103,
  hash: "0x8b8ad5d53f3904eddaf9dc8cc81f2f02e976b8b6b15965564502c1c91ec1be57",
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  miner: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  mixHash: "0x331e97ff59b2c7a9c2c9f2d51ede328f7cad4d1c0f2f150c6ed1b10973db3e63",
  nonce: "0x3f590a89e02a139e",
  number: 23,
  parentHash: "0x4b3e8518efdc133c5d11594e7657ddd2ae5dfb734ef17adde9a71ac3e95c75ce",
  receiptsRoot: "0xf0a9229c220e8e42df0f3b7ffd1d1d1b4a1dbbbb648d8b0dbb43a76004816616",
  sha3Uncles: "0x1a506a04d1dac0075fa1411ded3839216d51685abe794c90af9babb8342e7d56",
  size: 1244,
  stateRoot: "0xc5576ea5c05f0fa5f9e9d760dffa2455cd46d2c1fd275949a8448fbe4df8550d",
  timestamp: 1494175180,
  totalDifficulty: 3028416,
  transactions: ["0xf452e5a1c01c861bbe72f4e91fa1578a681736414b617f4b0ea95339e90c2994"],
  transactionsRoot: "0x3c638f8033d3b409f163edefdfe41084ea602095b8474c3bbe798870d477e59a",
  uncles: ["0xb8372666dce84de8d7f6d6fb6fa9c5f81dd48291e0634ef1694b3ca1c7c31a95"]
}



## Invalid Jup
> cmc_sol_democontract.invalidJump({from:eth.accounts[0], gas: 1000000});
"0x7c193a62df5edfebc29e3abca367d987df3622f9ece529a84a950a82486c8324"
> eth.blockNumber
24


> eth.getTransaction("0x7c193a62df5edfebc29e3abca367d987df3622f9ece529a84a950a82486c8324");
{
  blockHash: "0xec863ad3f6f6e5539d787b56e9844728c42bf26bd029441beef31ff8b6a783f9",
  blockNumber: 24,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gas: 1000000,
  gasPrice: 20000000000,
  hash: "0x7c193a62df5edfebc29e3abca367d987df3622f9ece529a84a950a82486c8324",
  input: "0xc59e9bfd",
  nonce: 2,
  r: "0x32e44e85e8ed8b1850e38c23589d961a1477c34d88b5c14263b393721a791b05",
  s: "0x7e15024f0d128474c47b23eabc2cd508f86d511d5835ce3f785ddf7dce1262b",
  to: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  transactionIndex: 0,
  v: "0x1c",
  value: 0
}
> eth.getTransactionReceipt("0x7c193a62df5edfebc29e3abca367d987df3622f9ece529a84a950a82486c8324");
{
  blockHash: "0xec863ad3f6f6e5539d787b56e9844728c42bf26bd029441beef31ff8b6a783f9",
  blockNumber: 24,
  contractAddress: null,
  cumulativeGasUsed: 1000000,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gasUsed: 1000000,
  logs: [],
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  root: "0x214f3d67a11db9434295e4e959298a927699f0de24269816301103ffeddc1455",
  to: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  transactionHash: "0x7c193a62df5edfebc29e3abca367d987df3622f9ece529a84a950a82486c8324",
  transactionIndex: 0
}
> eth.getBlock(24);
{
  difficulty: 131968,
  extraData: "0xd783010509846765746887676f312e362e32856c696e7578",
  gasLimit: 131107423,
  gasUsed: 1000000,
  hash: "0xec863ad3f6f6e5539d787b56e9844728c42bf26bd029441beef31ff8b6a783f9",
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  miner: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  mixHash: "0x7b3325627513583c493c324e4749106c357fd8238f8d256544666f63d1cdad26",
  nonce: "0x28d421197c227474",
  number: 24,
  parentHash: "0x8b8ad5d53f3904eddaf9dc8cc81f2f02e976b8b6b15965564502c1c91ec1be57",
  receiptsRoot: "0x3309d1ce28fb9cf0fac53a8d213e7b84bc2686ffb5e34b316a88f9ac26ef636b",
  sha3Uncles: "0x1dcc4de8dec75d7aab85b567b6ccd41ad312451b948a7413f0a142fd40d49347",
  size: 647,
  stateRoot: "0x0f21e8fc2ecd9d0e776222415bd8d73b936ab8ca6a53d7b31ae1f25c2f968cdf",
  timestamp: 1494175260,
  totalDifficulty: 3160384,
  transactions: ["0x7c193a62df5edfebc29e3abca367d987df3622f9ece529a84a950a82486c8324"],
  transactionsRoot: "0xa78107d2faf8a850b848dec5a3cc9703e3dc46d93d7e0c8b86d43aa2f8a55a67",
  uncles: []
}



## Out of Gas
> cmc_sol_democontract.outOfGas({from:eth.accounts[0], gas: 1000000});
"0x5ed62e17b9127aa749dace8c866a5b88fe132a5afe203d915f9f9d4469a7de5b"
> eth.blockNumber
25


> eth.getTransaction("0x5ed62e17b9127aa749dace8c866a5b88fe132a5afe203d915f9f9d4469a7de5b");
{
  blockHash: "0xa8dc9f9805a77b790395a79e7817285fe05679670f92648c58529c53e2c4d421",
  blockNumber: 25,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gas: 1000000,
  gasPrice: 20000000000,
  hash: "0x5ed62e17b9127aa749dace8c866a5b88fe132a5afe203d915f9f9d4469a7de5b",
  input: "0x31fe52e8",
  nonce: 3,
  r: "0xe70dcf0b00192d96008aabd664b4dc0a778388cd6cb6876ce051a18f6c505aa2",
  s: "0x3df70211fb623284d8bdc0aa7d36965989507a269d9eb37793c758a0de61490a",
  to: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  transactionIndex: 0,
  v: "0x1b",
  value: 0
}

> eth.getTransactionReceipt("0x5ed62e17b9127aa749dace8c866a5b88fe132a5afe203d915f9f9d4469a7de5b");
{
  blockHash: "0xa8dc9f9805a77b790395a79e7817285fe05679670f92648c58529c53e2c4d421",
  blockNumber: 25,
  contractAddress: null,
  cumulativeGasUsed: 1000000,
  from: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  gasUsed: 1000000,
  logs: [],
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  root: "0xa154a96a1fa3924a48c1d72c81ca72a23fee84a90371e626455cb92456f9d420",
  to: "0x0be1427087970611dc9ba30f617bd5d3e73593c2",
  transactionHash: "0x5ed62e17b9127aa749dace8c866a5b88fe132a5afe203d915f9f9d4469a7de5b",
  transactionIndex: 0
}
> eth.getBlock(25);
{
  difficulty: 131904,
  extraData: "0xd783010509846765746887676f312e362e32856c696e7578",
  gasLimit: 130980854,
  gasUsed: 1000000,
  hash: "0xa8dc9f9805a77b790395a79e7817285fe05679670f92648c58529c53e2c4d421",
  logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  miner: "0x4c51098b8f7547476f85ed24dec890f835a841c5",
  mixHash: "0x4ef80af28248c58b2eb00b24d79378ee255aff90345b66caab0907e20d9f5132",
  nonce: "0x507a640c7fd2779b",
  number: 25,
  parentHash: "0xec863ad3f6f6e5539d787b56e9844728c42bf26bd029441beef31ff8b6a783f9",
  receiptsRoot: "0x29fa3889906f45b2874890974f58da3d815c91094d60feab9fb99afd79d3f704",
  sha3Uncles: "0x1dcc4de8dec75d7aab85b567b6ccd41ad312451b948a7413f0a142fd40d49347",
  size: 647,
  stateRoot: "0x88579ae206fa7b0ed322845fcc4f23187c058143ea5ef91e280c27faf0833139",
  timestamp: 1494175372,
  totalDifficulty: 3292288,
  transactions: ["0x5ed62e17b9127aa749dace8c866a5b88fe132a5afe203d915f9f9d4469a7de5b"],
  transactionsRoot: "0x6032d5930bc9a6c86572d22722758cd22b944da90430aaf9815b4832f3f6c746",
  uncles: []
}

```

```js

// calculate the method hash
web3.sha3("outOfGas()").substr(0,10);
// -> "0x31fe52e8"

web3.sha3("addEntry(uint256,bytes32)").substr(0,10);
// -> "0x75a584b0"

```
untitled_democontract.incrementCounter({from: eth.accounts[0], gas:3000000});
Z-Chain:  0xd32d3523b06bdb0741ef83d9efa8a9ecb082551e,   blockNumber: 615, 