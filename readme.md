# Projects Details [UML BASED]

## Activity Diagram
![](/designArchitecture/activity_diagram.png)

## Data Modeling
![](/designArchitecture/data_modeling.png)

## Sequence Diagram
![](/designArchitecture/sequence_diagram.png)

## State Diagram
![](/designArchitecture/state_diagram.png)

# Libraries & Depdencies
## *Depedencies*
- truffle@5.4.1
- Solidity compiler version '0.8.2'
- Solidity version >=0.6.8

## *Libraries*
- @truffle/hdwallet-provider: "^1.4.3" <br>
libraries for connecting to rinkeby & infura

- "dotenv": "^10.0.0" <br>
libraries for the env

- "truffle-assertions": "^0.9.2" <br>
libraries testing smart contract with latest best practices
# *Prerequisites & Steps*

## *ask to the repository owner or use your env to try*
- change `.env.example` into `.env` and fill it with your environments
## *Launch Ganache Local or you can use Ganache GUI*
```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

## *check your ganache port*
```
put your ganache port into .env
```
## *Delete build folder if any*
```
rm -rf build
```

## *Compile your smart contract*
```

truffle compile
```
## *Migrate Contract* 
```
truffle migrate --reset
```
## *Migrate Contract into Rinkeby* 
```
truffle migrate --network rinkeby
```

## *Testing truffle code*
```
truffle test
```
![](/screenshoot/test.png)

## *
## Contract Creations ( Rinkeby )
* FarmerRole
    * TX : [0x1b2395624acac62a5dad5a16cab15b326be8d3c60aaf9d17f379f0197a1b2ae1](https://rinkeby.etherscan.io/tx/0x1b2395624acac62a5dad5a16cab15b326be8d3c60aaf9d17f379f0197a1b2ae1)
    * Contract Address : [0x24D79082085Ae98B131D0c6B8D1C8E5cC71DD3aF](https://rinkeby.etherscan.io/address/0x24D79082085Ae98B131D0c6B8D1C8E5cC71DD3aF)

* DistributorRole
    * TX : [0x1cdfd110a64021c0d7f327d90c3907a88f330b9ffa732d702939c830eb3a3ab5](https://rinkeby.etherscan.io/tx/0x1cdfd110a64021c0d7f327d90c3907a88f330b9ffa732d702939c830eb3a3ab5)
    * Contract Address : [0x5A3C37D1372a9E0fB140E1D2DfDD933b31f05CBf](https://rinkeby.etherscan.io/address/0x5A3C37D1372a9E0fB140E1D2DfDD933b31f05CBf)

* RetailerRole
    * TX : [0xef72d7803351bc57ed13e243e22ec98dd31d44447fcb9144796f24dcc58235f8](https://rinkeby.etherscan.io/tx/0xef72d7803351bc57ed13e243e22ec98dd31d44447fcb9144796f24dcc58235f8)
    * Contract Address : [0x4A1b1bF10d8DDb25414a2C4c09a378DE54d557e9](https://rinkeby.etherscan.io/address/0x4A1b1bF10d8DDb25414a2C4c09a378DE54d557e9)

* ConsumerRole
    * TX : [0x9f139ef746b12953d24aacfcac44355d6ddf0759cf948caff17b51a230c5e9bf](https://rinkeby.etherscan.io/tx/0x9f139ef746b12953d24aacfcac44355d6ddf0759cf948caff17b51a230c5e9bf)
    * Contract Address : [0x0312Bae303B4608A52420C154389fBfEccddB1C7](https://rinkeby.etherscan.io/address/0x0312Bae303B4608A52420C154389fBfEccddB1C7)

* SupplyChain
    * TX : [0xce79a2fc5db0dfdb030ea9d0fcf1b8a083bd2cc23955f0199fe5b0e2a1788f57](https://rinkeby.etherscan.io/tx/0xce79a2fc5db0dfdb030ea9d0fcf1b8a083bd2cc23955f0199fe5b0e2a1788f57)
    * Contract Address : [0x18489712ae1797F76Da2d1723CB9a540265eA444](https://rinkeby.etherscan.io/address/0x18489712ae1797F76Da2d1723CB9a540265eA444)

* Ownable
    * TX : [0xa4a69288b6011e984dd763530346384d750ddd73151636f98802e4e3f78a9425](https://rinkeby.etherscan.io/tx/0xa4a69288b6011e984dd763530346384d750ddd73151636f98802e4e3f78a9425)
    * Contract Address : [0x385C5910e38D5638E9eaAfF938E7E8FE231D0462](https://rinkeby.etherscan.io/address/0x385C5910e38D5638E9eaAfF938E7E8FE231D0462)