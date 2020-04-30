# Wallet Protocol

## Library

### Java

#### 1. [newchain-web3j](https://github.com/newtonproject/newchain-web3j)

This library is forked from [web3j](https://github.com/web3j/web3j). 

See more at [newchain-web3j](https://github.com/newtonproject/newchain-web3j)

### Android 

#### 1. [newpay-android-example](https://github.com/newtonproject/newpay-android-example)

This is an Android demo of Newpay. You can refer to this demo to build your own Newpay Android wallet.

#### 2. [newpay-java-keystore](https://github.com/newtonproject/newpay-java-keystore)

This library is forked from [Bitcoinj](https://github.com/bitcoinj/bitcoinj), which is to support [bip44](https://github.com/satoshilabs/slips/blob/master/slip-0044.md) protocol. And it\`s a basic library for [newpay-android-example](#newpay-android-example) to depend on.

We changed [Bitcoin seed](https://github.com/bitcoinj/bitcoinj/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65) to [Nist256p1 seed](https://github.com/newtonproject/newpay-java-keystore/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65).

### iOS

#### 1. [newpay-ios-example](https://github.com/newtonproject/newpay-ios-example)

This is an iOS demo of Newpay. You can refer to this demo to build your own Newpay iOS wallet。

#### 2. [newpay-ios-crypto](https://github.com/newtonproject/newpay-ios-crypto)

A CocoaPods wrapper around the [trezor-crypto](https://github.com/trezor/trezor-crypto) C library.

#### 3. [newpay-ios-contract-utility](https://github.com/newtonproject/newpay-ios-contract-utility)

Core Ethereum data structures and algorithms, which is forked and modified from [trust-core](https://github.com/trustwallet/trust-core).

#### 4. [newpay-ios-keystore](https://github.com/newtonproject/newpay-ios-keystore)

A general-purpose Ethereum keystore for managing wallets, which is forked and modified from [trust-keystore](https://github.com/trustwallet/trust-keystore).

### Python

#### 1. [HD-Wallet-Python](https://github.com/weixuefeng/newton-bip44-python)

This repo support the bip44 protocol about newpay wallet with python.

## Example

### [newchain-sdk-example](https://github.com/newtonproject/newchain-sdk-example)

This document describes how to get started with Newton's NewChain SDK.

#### 1. [Java example](https://github.com/newtonproject/newchain-sdk-example/tree/master/examples/java)

Example of NewChain SDK for java.

#### 2. [Node example](https://github.com/newtonproject/newchain-sdk-example/tree/master/examples/node)

#### 3. [Python example](https://github.com/newtonproject/newchain-sdk-example/tree/master/examples/python)



