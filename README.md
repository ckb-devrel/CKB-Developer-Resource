# CKB-Developer-Resource

This is a comprehensive developer resource hub for CKB

## **Understanding CKB:**

1. **CKB Academy**: https://academy.ckb.dev/
    
    This resource includes a comprehensive collection of CKB documentation along with two interactive courses designed to teach the principles of CKB:
    
    - **[CKB Fundamentals](https://academy.ckb.dev/courses)** - A course on the foundational theories of CKB.
    - **[CKB Operations](https://academy.ckb.dev/courses)** - A practical course on how to execute transactions on CKB.
    
2. **CKB Cookbook**:
    
    The CookCKB features a variety of example codes, with each demo focused on a specific feature or functionality crucial to CKB application development. These code examples are intended as hands-on learning tools for developers. Comprehensive documentation for each example project is available at [CookCKB Developer Guide](https://docs.cookckb.dev/docs/category/developer-guide/). Developers can use these resources to grasp detailed implementation insights and best practices for incorporating specific features into their applications.
    
    It also serves as a development framework, including functionalities like wallet connection and transaction creation:
    
    [CookCKB on GitHub](https://github.com/CKBFansDAO/cookckb/tree/master)
    
3. **CKB Official Documentation**: [https://docs.nervos.org/](https://docs.nervos.org/)

4. **CKB Resource Hub by orange-xc**: [Nervos Network Developer Resources Hub](https://talk.nervos.org/t/nervos-network-developers-resources-hub/7261)

5. **Nervos Network RFCs**: https://github.com/nervosnetwork/rfcs
    
    This repository houses proposals, standards, and documentation pertinent to the Nervos Network.
    
6. **CKB Glossary**: [https://docs.nervos.org/docs/tech-explanation/glossary](https://docs.nervos.org/docs/tech-explanation/glossary)


## Faucet:

https://faucet.nervos.org/

## CKB exploerer:

https://explorer.nervos.org/


## **SDKs Related to the CKB Ecosystem**

### **RGB++ Documentation and SDKs:**

1. **RGB++ SDK**: Access the software development kit on GitHub [here](https://github.com/ckb-cell/rgbpp-sdk).
2. **RGB++ Code Example**: View a practical code example [here](https://github.com/ckb-cell/rgbpp-sdk/tree/develop/examples/rgbpp).
3. **Draft of the RGB++ Protocol Whitepaper**: Read the draft whitepaper [here](https://github.com/ckb-cell/RGBPlusPlus-design/blob/main/docs/light-paper-cn.md).
4. **RGB++ Contract Specifications**: Detailed contract specifications are available [here](https://github.com/ckb-cell/RGBPlusPlus-design/blob/main/docs/locscript-design-prd-cn.md).



### **Spore Protocol and DOB Documentation:**
#### DOB(Digital Objects):
1. **DOB Protocol Family**: https://docs.spore.pro/category/dob-digital-object
2. ** DOB/0 Protocol**: https://docs.spore.pro/dob0/protocol



#### Spore Basics
1. **Spore Documentation**: Comprehensive guides and resources can be found [here](https://docs.spore.pro/).
2. **Getting Started with Spore**: Essential basics to get started with Spore are detailed [here](https://docs.spore.pro/category/get-started).
3. **Create Your First Spore**: A tutorial on creating your first Spore is available [here](https://docs.spore.pro/tutorials/create-first-spore/).
4. **Creating an On-Chain Blog Using Spore Protocol**: Learn how to create a blog on the blockchain [here](https://docs.spore.pro/tutorials/create-on-chain-blog/).
5. **Managing Spore Operations**: Instructions for creation, transfer, melting, and data handling of Spores are detailed [here](https://docs.spore.pro/category/how-to-recipes).
6. **Spore Glossary**: A glossary of terms used in Spore documentation is accessible [here](https://docs.spore.pro/category/glossary).
7. **Spore Demo Source Code**: The source code for the Spore demo can be found on GitHub [here](https://github.com/sporeprotocol/spore-demo).
8. **Spore Application Example**: Explore an application sample on Spore [here](https://github.com/SpectreMercury/PhilosopherStone).


### **CKB Script Programming Examples:**

1. **CKB Script Templates**: [Explore the GitHub repository](https://github.com/cryptape/ckb-script-templates)
    
    This repository offers a collection of CKB script templates ready to be used with [cargo-generate](https://github.com/cargo-generate/cargo-generate). These templates are designed for straightforward development on mainstream operating systems including Linux, macOS, and Windows, utilizing the latest stable versions of Rust and the Clang C compiler.
    
2. **Sample Code**: [Simple UDT GitHub Repository](https://github.com/xcshuan/simple-udt)
3. **Implementation Guide**: [Learn how to use sUDT with Capsule]([https://docs.nervos.org/docs/labs/sudtbycapsule](https://docs-old.nervos.org/docs/labs/sudtbycapsule))


## Wallets


#### Supported Wallets
 - Neuron Wallet (Desktop, Window, MacOS, Linux)
 - CKBull (Mobile, Android, iOS)
 - JoyID (Web, PassKey)
 - Portal Wallet (Web)
 - Rei Wallet (Browser, Extension)
 - SafePal (Hardware, Android, iOS)
 - Ledger (Hardware)
 - Opera Wallet (Mobile, Android)
 - imToken (Mobile, Android, iOS)
 - Gate Web3 Wallet (Mobile/Extension)
 - OneKey (Desktop/Mobile/Extension)
 - to be continue

#### Integrations
1. **Consult the Wallet Integration Module in the CKB Cookbook**: [CKB Cookbook Wallet Manager](https://github.com/CKBFansDAO/cookckb/tree/master/src/walletmgr).
2. [Introduction for the Omnilock](https://blog.cryptape.com/omnilock-a-universal-lock-that-powers-interoperability-1)
3. References for Omnilock: [Omnilock](https://github.com/nervosnetwork/rfcs/blob/master/rfcs/0042-omnilock/0042-omnilock.md)
4. Reference for JoyID Lock: [JoyID Lock](https://docs.joyid.dev/guide/sdk)
5. Practical example of JoyID Lock: 
    - [Philosopher’s Stone](https://github.com/SpectreMercury/PhilosopherStone/blob/main/src/utils/joyid.ts)
6. Reference to Rei Wallet: [Docs](https://docs.reiwallet.io)

## Demos

**General:**

1. [CKB CookBook](https://github.com/CKBFansDAO/cookckb/tree/master)

**Spore:**

1. [Spore Demo](https://github.com/SpectreMercury/PhilosopherStone/tree/main)
2. [Philosopher’s Stone](https://github.com/sporeprotocol/spore-demo)

## **Development Toolkit for CKB**

1. **Testnet Faucet**: Before initiating development, ensure to claim testnet tokens from the faucet [here](https://faucet.nervos.org/).
2. **CKB Command Line Tool(CKB Cli)**: Access this essential tool for interaction with the CKB network on GitHub [here](https://github.com/nervosnetwork/ckb-cli).
3. **Rust SDK**: Visit the repository containing a variety of CKB script templates [here](https://github.com/cryptape/ckb-script-templates). These templates, which can be instantiated using [cargo-generate](https://github.com/cargo-generate/cargo-generate), support native development across Linux, macOS, and Windows using the latest stable versions of Rust and the Clang C compiler.
4. **Rust/C/Lua SDK - Capsule**: [Discover Capsule](https://github.com/nervosnetwork/capsule), an out-of-the-box development framework tailored for building smart contracts on CKB.
    
    Capsule includes:
    
    - **Capsule CLI**: A tool for project scaffolding.
    - **[CKB-testtool](https://github.com/nervosnetwork/capsule/tree/develop/crates/testtool)**: A framework for testing CKB scripts.
    
    CKB supports script development in multiple languages. The libraries for these are maintained in:
    
    - **[ckb-std](https://github.com/nervosnetwork/ckb-std)** for Rust
    - **[ckb-c-stdlib](https://github.com/nervosnetwork/ckb-c-stdlib)** for C
    - **[ckb-lua](https://github.com/nervosnetwork/ckb-lua)** for Lua
5. **JS/TS SDK - Lumos**: [Lumos](https://github.com/ckb-js/lumos) is a full-featured JavaScript/TypeScript framework designed to simplify DApp development on the CKB network. The project's name symbolizes its purpose: to illuminate the expansive yet uncharted territory of CKB, guiding developers into this new realm.
6. **Spore Protocol SDK**: Enhance your development capabilities with the [Spore Protocol SDK](https://github.com/sporeprotocol/spore-sdk). For more information, visit [Spore Protocol's homepage](https://spore.pro/).

## **Tutorials**

**Overview:**

For an introduction to the Nervos Network, please visit the official documentation page:
https://docs.nervos.org/docs/reference/introduction/

**Creating and Sending Your First CKB Transaction:**

Learn how to construct and transmit your first transaction on the CKB network by following this step-by-step guide available at:
https://blog.cryptape.com/construct-and-send-your-first-ckb-transaction

## **How to Utilize RPC:**
1. **Public RPC Nodes**: [List of Public JSON-RPC Nodes for CKB](https://github.com/nervosnetwork/ckb/wiki/Public-JSON-RPC-nodes).
2. **Retrieving Cells and Transactions via CKB’s GraphQL Layer**: [Explore the GraphQL discussion on Nervos Forum](https://talk.nervos.org/t/a-graphql-layer-for-ckb/7476).

## **Running a CKB Node:**

**Tutorials for Running a CKB Node**: [Access the tutorial collection here](https://linktr.ee/nodeckb).

1. **Monitor CKB Node Status Online**: [Check CKB Node Probe](https://nodes.ckb.dev/).
2. **Finding Your CKB Node ID**: [Locate your node ID here](https://nodes.ckb.dev/findNode).

## **Using SDKs (Detailed Instructions and Examples Included):**

1. **Building CKB Scripts in Rust**:
    - Write an SUDT Script using Capsule: [SUDT Script Tutorial](https://docs-old.nervos.org/docs/labs/sudtbycapsule).
    - Implement Dynamic Loading in Capsule.
2. **Developing Standalone CKB DApps in JavaScript**:
    - Get Started with Lumos via NervosDAO: [Introduction to Lumos](https://docs-old.nervos.org/docs/labs/lumos-nervosdao).
3. **Dynamically Loading Shared Libraries in Rust Contracts**:
    - Learn about Dynamic Loading in Capsule: [Capsule Dynamic Loading Tutorial](https://docs.nervos.org/docs/labs/capsule-dynamic-loading-tutorial).


## **Developer Communities**

1. **Nervos Discord Dev Chat(Please leave your questions here)**
   - English: https://discord.com/channels/657799690070523914/671647247024521217
   - Chinese: https://discord.com/channels/657799690070523914/1242826741777432667
1. **Nervos Talk**: [Visit Nervos Talk](https://talk.nervos.org/)
    - A comprehensive archive of all technical discussions and podcast transcripts since 2017.
1. **Nervos/CKB Dev Community Telegram Group** https://t.me/ckbdev
    - A community group for developers and enthusiasts.

## **Community Works**
1. **xUDT Logos**: https://xudtlogos.cc/faq
   - Help you display xUDT logo on Dapps
1. **CKBDapp** https://ckbdapps.com/
   - Collections of tools for CKB Dapps.
1. **CKB Tools** https://ckb.tools/
   - Tools for generating addresses and other usefull info.

## Videos

1. Youtube channel of Cryptape Vanguard：https://www.youtube.com/@cryptape
2. Youtube channel of Nervos Network: https://www.youtube.com/@NervosNetwork/videos

## **Applying for CKB-related Grants and Accessing Resources**

1. **Grants Application**: Access the CKB Community Fund DAO [here](https://talk.nervos.org/c/ckb-community-fund-dao/65)
    - Learn about the rules and procedures of the CKB Community Fund DAO: [CKB Community Fund DAO Guidelines](https://talk.nervos.org/t/ckb-community-fund-dao/6873)
2. **Cryptape Blog**: Discover insights and research findings on the design and development of CKB: [Read the Cryptape Blog](https://blog.cryptape.com/)
3. **CKB Developer's Blog**: Explore detailed developer blogs and articles: [Visit the CKB Developer's Blog](https://accu.cc/content/ckb/neuron/)
