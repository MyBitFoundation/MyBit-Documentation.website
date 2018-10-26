# Glossary



| Term | Definition |
| :--- | :--- |
| API contract | API contract used to easily fetch variables from MyBit network. It allows easy interaction wiht the protocol. |
| Access contracts | Set of network contracts used to manage user access levels and restrictions based on roles. See contract categories. |
| Account balance | Each account \(either contract or individual\) has a balance in Ether \(in “Wei” to be exact\) and/or ERC20 token which can be modified by sending transactions to the account. |
| Address | Refers to contract addresses associated with MyBit Chain package contracts deployed in the local instance of mybit network blockchain. It can also refer to a user account, called external accounts in the Ethereum blockchain. |
| Asset ID | ID variable associated with the asset being crowdfunded. It can be either a physical or digital asset. |
| Asset Manager | An user responsible mostly for initiating the asset crowdsale, managing real-world aspects of the asset and delivering ROI on the asset to investors. The asset manager puts down MYB tokens in escrow as colateral, which can be burned in case of negligence or investor disatisfaction. Refer to network roles. |
| Asset creation | Function enabling the creation of a new asset initiated by the asset manager to start a crowdsale event. It provides the terms of asset crowdsale e.g. funding goal, duration of crowdsale, associated fees etc. |
| Asset crowdsale terms | Terms set at the creation of the asset to start the crowdsale. e.g. funding goal, duration of crowdsale, associated fees, accepted currencies \(Eth and/or ERC20\). |
| Asset crowdsale | Crowdfund event initiated to fund a digital asset by investors. See asset creation. |
| Asset exchange | Decentralised exchange of assets created by the asset manager. It allows trading of asset orders betweeen investors. Also refered to as AssetExchange contract. See MYDAX. |
| Asset funding | Function enabling investors to finance an asset ID created through the crowdsale by the asset manager. It passes the invested amount and the investor address associated. |
| Contract address | See address. |
| Contract categories | Categories of smart contracts underlying MyBit SDK network. e.g. Crowdsale contract, Access contract, Database contract etc. |
| Contract management | To set a platform and create digital assets contracts must be registered in a ContractManager before getting recorded in the Database contract. Platform owners add new contracts. Contract addition and change to contract state requires approval by users. |
| Contracts | All the Ethereum Solidity Smart Contracts that compress the business logic of the MyBit Network |
| Contracts | See smart contracts. |
| Crowdsale contracts | Contracts involved in funding new assets. Asset contracts can be funded in Ether or ERC20 tokens. Funding a crowdsale contract deploys a DividendToken, each Wei/Token representing a share in the asset. See contract categories. |
| Database contracts | Contracts related to the storing of data on the blockchain. All essential data for the ecosystem is stored here. Write privileges to the database are determined by the contract manager, which is managed by the owner/owners of the platform. See contract categories. |
| Digital asset | A digital asset is any entity that can generate income and send crypto currency payments, directly or indirectly. Digital assets can be funded, owned and exchanged. |
| Digital asset order | A digital asset order is the result of the creation of an asset crowdsale by the Asset Manager. Investors can purchase these asset tokens, which will later receive income generated from ownership on the asset. Users can exchange these asset tokens on decentralized asset exchanges \(DAX\) according to ERC20 standards. |
| Dividend issuance | Function enabling holders with asset ownership to receive income payments. |
| Dividend token | This token is used to represent assets funded by Ether on the MyBit platform. Asset ownership allows the token contract to receive payment as distribution of income. See dividend issuance. |
| Dividend token ERC20 | This token is used to represent assets funded by ERC20 on the MyBit platform. Asset ownership allows the token contract to receive payment as distribution of income. See dividend issuance. |
| ERC20 | Technical Ethereum standard used in smart contracts that provides basic functionality to transfer tokens, as well as to allow tokens to be approved so they can be spent by another on-chain third party. |
| Ecosystem contracts | See contract categories. |
| Escrow order | The Asset Manager put down tokens in escrow, which can get burned if the owners of the asset find negligence. Escrow orders are a lending service \(i.e. collateral\) that allows other users to lend tokens to an Asset Manager in exchange for a percentage of the brokers fee for managing the asset. |
| Funding goal | The amount needed to fund the assset through the crowdsale, set at asset creation. |
| Gas | Upon creation, each transaction is charged with a certain amount of gas. The gas price is a value set by the creator of the transaction, who has to pay gas\_price \* gas up front from the sending account. |
| Interfaces | See contract categories. |
| Investor | Also called asset investor. |
| MYDAX | A decentralised exchange, part of MyBit ecosystem. It provides liquidity and trading opportunities of digital assets. See asset exchange. |
| MicroDapps | Applications built with the MyBitUI library. e.g.MyBit Trust |
| Multisig | Contract which gives owners access to function execution based on majority approval. |
| MyBit Chain | Pre-compiled local instance of the MyBit Network for application development. |
| MyBit Go | A decentralised investing platform, part of MyBit ecosystem. It allows direct investment in assets crowdsales and receive income on ROI in the form of dividends. |
| MyBit Network | The main JavaScript-based web client for interacting with the MyBit Network protocol. |
| MyBit SDK | A software development kit for MyBit contracts. The Network SDK is a protocol that allows the creation of decentralised digital assets, funding and trading. It also enables the distribution of revenue generated by assets |
| MyBit UI | A series of UI Web components that allows anyone to build WM Dapps quickly. |
| MyBit | Usually refers to MyBit Foundation, the entity behind the development of MyBit ecosystem and protocol. |
| NPM | Npm is a package manager for JavaScript. Used to install, share and distribute code. |
| Network.js | A node.js library for interacting with the MyBit Network SDK. See MyBit Network. |
| Operator | Producer of the asset, physical or digital. Also responsible for installing and delivering the asset to the Asset Manager. |
| Operator ID | ID variable representing the account of the operator, needed for new asset crowdsale creation. |
| Owner | See Platform owner. |
| Ownership contracts | See contract categories. |
| Platform owner | Owner of the asset invesment platform e.g. MyBitGo. Responsible for general upgrades and changes made to the platform. |
| Platform | Synonym for investment platform. E.g. MyBitGo. |
| Revenue distribution | Result of income distribution to token holders who own digital assets. Function issueDividend\(\) allows reception of payment. And withdraw\(\) gives the investor the right to retrieve funds from the DividendToken contract. |
| Smart contracts | Collection of code \(its functions\) and data \(its state\) that resides at a specific contract address on the Ethereum blockchain. Think of it as a single slot in a database that can be queried and altered by calling functions of the code that manages the database. |
| Stakeholder | Stakeholders are users who can "lend" tokens to Asset Managers as escrow to initiate crowdsale, against percentage of fees destinated to asset managers. Currently, not active yet. |
| Staking | Staking is the process of putting down tokens as collateral on behalf of the Asset Manager. |
| Token | Usually refered to as a representation of a particular asset or a utility on a blockchain. Can also be synonnym of token contract. |
| Token burning | The total supply of tokens can be decreased by burning existing tokens, called burning. Tokens can be burnt by a user or another contract as long as approval has been given. |
| Token contracts | Token contracts are used to represent fungible divisible assets, which can be burnable, mintable and receive income. See contract categories. |
| Token fee | Refered to as the asset manager fee paid for creating the crowdsale, ensuring asset maintenance and delivering return on investment. |
| Token minting | Token process where the total supply starts at 0 and all tokens are created by the mint\(\) function. This is used for asset tokens where investors purchase crowdsale assets. |
| Transaction | A transaction is a message that is sent from one account to another account \(which might be the same or the special zero-account, see below\). It can include binary data \(its payload\) and Ether. |
| Truffle ganache | Personal blockchain for Ethereum development. It can be used to run tests, execute commands and inspect contract state. |
| UI Kit | See MyBit UI. |
| Wealth Management Decentralised Application \(WMDApp\) | Any application that can transfer, manage, fund and control the representation of digital assets through Ethereum Smart Contracts. |
| Web3 | Ethereum JavaScript API. web3.js is a collection of libraries which allow you to interact with a local or remote ethereum node, using a HTTP or IPC connection. |
| Yarn | A JavaScript Package Manager. |

