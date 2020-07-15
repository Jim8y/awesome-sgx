# awesome-sgx

Collection of material for learning SGX.

## Table of Contents
1. [Hardware](#Hardware)
1. [Side-Channels](#Side-Channels)
1. [SDK](#SDK)
1. [Samples](#Samples)
1. [Study](#Study)
1. [Security](#Security)
1. [Paper](#Paper)
1. [GAME](#GAME)
1. [EMULATOR](#emulator)
1. [LibOS](#LibOS)
1. [Container](#Container)
1. [CRYPTO](#CRYPTO)
1. [NETWORK](#NETWORK)
1. [DATABASE](#DATABASE)
1. [Programming Language](#ProgrammingLanguage)
1. [Tool&&DEBUG](#Tool&&DEBUG)
1. [BlockChain](#BlockChain)
1. [MachineLearning](#MachineLearning)

## Hardware

* [ayeks/SGX-hardwarep](https://github.com/ayeks/SGX-hardware) - This is a list of hardware which is supports Intel SGX - Software Guard Extensions.

## Side-Channels

* [jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step) - A practical attack framework for precise enclave execution control
* [jovanbulck/sgx-pte](https://github.com/jovanbulck/sgx-pte) - Telling your secrets without page faults: Stealthy page table-based attacks on enclaved execution
* [jovanbulck/sgx-tutorial-space18](https://github.com/jovanbulck/sgx-tutorial-space18) - Tutorial: Uncovering and mitigating side-channel leakage in Intel SGX enclaves
* [HE-Wenjian/SGXlinger](https://github.com/HE-Wenjian/SGXlinger) - A side-channel attack vector based on interrupt latency against enclave execution of Intel SGX

## SDK

* [01org/linux-sgx](https://github.com/01org/linux-sgx) - Intel(R) Software Guard Extensions for Linux* OS 
* [baidu/rust-sgx-sdk](https://github.com/baidu/rust-sgx-sdk) - Rust SGX SDK provides the ability to write Intel SGX applications in Rust Programming Language. 
* [adombeck/python-sgx](https://github.com/adombeck/python-sgx) - Python interface to the SGX SDK.
* [apache/incubator-teaclave-sgx-sdk](https://github.com/apache/incubator-teaclave-sgx-sdk) - Rust SGX SDK provides the ability to write Intel SGX applications in Rust Programming Language.
* [rust-optee-trustzone-sdk](https://github.com/mesalock-linux/rust-optee-trustzone-sdk) - Rust OP-TEE TrustZone SDK: Enabling Safe, Functional, and Ergonomic Development of Trustlets
* [fortanix/rust-sgx](https://github.com/fortanix/rust-sgx) - The Fortanix Rust Enclave Development Platform https://edp.fortanix.com
* [openenclave/openenclave](https://github.com/openenclave/openenclave) - SDK for developing enclaves https://openenclave.io/sdk/

## Samples
* [intel/sgx-ra-sample](https://github.com/intel/sgx-ra-sample) - The only official remote attestation sample that support the real and complete attestation.
* [TinySecurityLab/SGXRemoteAttestation](https://github.com/TinySecurityLab/SGXRemoteAttestation/blob/master/sgxinstall) - A "real" remote attestation flamework of Intel SGX. (This one simulate the whole attestation process)

## Study
* [dingelish/SGXfail](https://github.com/dingelish/SGXfail) - SGX从入门到放弃

## Security

* [lsds/spectre-attack-sgx](https://github.com/lsds/spectre-attack-sgx) - Spectre attack against SGX enclave.
* [bl4ck5un/mbedtls-SGX](https://github.com/bl4ck5un/mbedtls-SGX) - mbedtls-SGX: a SGX-friendly TLS stack (ported from mbedtls).
* [jaebaek/SGX-Shield](https://github.com/jaebaek/SGX-Shield) - SGX-Shield: Enabling Address Space Layout Randomization (ASLR) for SGX Programs.
* [tudinfse/sgxbounds](https://github.com/tudinfse/sgxbounds) - SGXBounds: Memory Safety for Shielded Execution (compiler pass and runtime).
* [IAIK/sgxrop](https://github.com/IAIK/sgxrop) - The code to the SGX-ROP paper.


## Paper

* [vschiavoni/sgx-papers](https://github.com/vschiavoni/sgx-papers) - A list of system papers using/about Intel SGX.

## GAME

* [utds3lab/sgx-biniax2](https://github.com/utds3lab/sgx-biniax2) - A Linux game with SGX 
* [djwessel/sgx-snake](https://github.com/djwessel/sgx-snake) - A simple snake game implemented with SGX.
* [suinkang/SGX-Doom3](https://github.com/suinkang/SGX-Doom3) - Doom3 with SGX.

## EMULATOR

* [tristartom/sgx-emulator](https://github.com/tristartom/sgx-emulator) - An Emulator and SDK for Intel SGX extension
* [intel/qemu-sgx](https://github.com/intel/qemu-sgx) - qemu with SGX 
* [sslab-gatech/opensgx](https://github.com/sslab-gatech/opensgx) - OpenSGX: An open platform for Intel SGX 
* [intel/kvm-sgx](https://github.com/intel/kvm-sgx) - This repository hosts preliminary Linux/KVM patches to support SGX virtualization on KVM


## LibOS

* [Anjuna](https://www.anjuna.io) - Anjuna Runtime - a solution for executing unmodified applications in Intel SGX enclaves.
* [oscarlab/graphene](https://github.com/oscarlab/graphene) - Graphene / Graphene-SGX Library OS - a library OS for Linux multi-process applications, with Intel SGX support https://github.com/oscarlab/graphene/… 
* [SCONE](https://www.usenix.org/system/files/conference/osdi16/osdi16-arnautov.pdf) - SCONE: Secure Linux Containers with Intel SGX
* [SGXKernel](http://delivery.acm.org/10.1145/3080000/3075572/p35-Tian.pdf?ip=113.240.234.248&id=3075572&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E1C775F1AC6329F5A%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=1000423527&CFTOKEN=74748264&__acm__=1509418666_8d60f199060353b9d2e3a828901a729e) - SGXKernel: A Library Operating System Optimized for Intel SGX
* [Haven](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-baumann.pdf) - Shielding Applications from an Untrusted Cloud with Haven.
* [shwetasshinde24/Panoply](https://github.com/shwetasshinde24/Panoply) - Low-TCB Linux Applications with SGX Enclaves.
* [lsds/sgx-lkl](https://github.com/lsds/sgx-lkl) - SGX-LKL Library OS for running Linux applications inside of Intel SGX enclaves.
* [occlum/occlum](https://github.com/occlum/occlum) - Occlum: Secure and Efficient Multitasking Inside a Single Enclave of Intel SGX

## Container

* [tozd/docker-sgx](https://github.com/tozd/docker-sgx) - A Docker image with Intel SGX support. https://hub.docker.com/r/tozd/sgx/
* [alibaba/inclavare-containers](https://github.com/alibaba/inclavare-containers) - A set of tools for running trusted applications in containers with the hardware-assisted enclave technology.

## CRYPTO

* [intel/intel-sgx-ssl](https://github.com/intel/intel-sgx-ssl) - Intel® Software Guard Extensions SSL.
* [WolfSSL](https://github.com/NickolasLapp/linux_sgx) - WolfSSL with SGX for Linux OS using Eclipse IDE and SGX Plugin.
* [momalab/SGXCrypter](https://github.com/momalab/SGXCrypter) - SGXCrypter is a novel approach on encryption based binary packing. 
* [rscosta/SGXCryptoFile](https://github.com/rscosta/SGXCryptoFile) - SgxCryptoFile - App for Encrypting and Decrypting Files using Intel SGX.
* [oweisse/sgx_crypto_wrapper](https://github.com/oweisse/sgx_crypto_wrapper) - A Python wrapper for sgx_tlibcrypto library.
* [sparkly9399/SGX-OpenSSL](https://github.com/sparkly9399/SGX-OpenSSL) - OpenSSL library for SGX application.
* [ayeks/TresorSGX](https://github.com/ayeks/TresorSGX) - Securing storage encryption by using Intel SGX enclaves. First attempt for the isolation of OS components with trusted enclaves.
* [kudelskisecurity/sgx-reencrypt](https://github.com/kudelskisecurity/sgx-reencrypt) - PoC of an SGX enclave performing symmetric reencryption.

## NETWORK

* [kaist-ina/SGX-Tor](https://github.com/kaist-ina/SGX-Tor) - https://github.com/kaist-ina/SGX-Tor
* [jnferguson/pwd](https://github.com/jnferguson/pwd) - SGX password storage / authentication subsystem.

## DATABASE

* [yerzhan7/SGX_SQLite](https://github.com/yerzhan7/SGX_SQLite) - SQLite database inside a secure Intel SGX enclave (Linux). 


## Programming Languages

* [Rust](https://github.com/baidu/rust-sgx-sdk) - Rust SGX SDK provides the ability to write Intel SGX applications in Rust Programming Language.
* [C#](https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX) - A C# example project downloaded from intel with GUI implemented with SGX
* [GO](https://github.com/rupc/go-with-intel-sgx) - Intel SGX with GoLang
* [Python](https://github.com/adombeck/python-sgx) - Python interface to the SGX SDK.
* [JAVA](https://github.com/sm67nono/Intel_SGX_Proj) - Trusted Computing Base with Intel SGX and Java JNI.
* [lishen-nt/sgx-language-adapter](https://github.com/lishen-nt/sgx-language-adapter) - SGX language adapter for java and python.

## Tool&&DEBUG

* [jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step) - A practical attack framework for precise enclave execution control. 
* [swarupchandra/secure-analytics-sgx](https://github.com/swarupchandra/secure-analytics-sgx) - Securing Data Analytics on Intel SGX using Randomization.
* [Glamdring](https://www.usenix.org/system/files/conference/atc17/atc17-lind.pdf) - Glamdring: Automatic Application Partitioning for Intel SGX.
* [kudelskisecurity/sgxfun](https://github.com/kudelskisecurity/sgxfun) - SGX command-line tools and paper.
* [ireed/SGX](https://github.com/ireed/SGX) - Code samples and tutorials for using intel software guard extensions.
* [jethrogb/sgx-utils](https://github.com/jethrogb/sgx-utils) - Various utilities for Intel SGX hardware.

## BlockChain

* [LedgerHQ/bolos-enclave](https://github.com/LedgerHQ/bolos-enclave)
* [luckychain/lucky](https://github.com/luckychain/lucky) - Proof of luck Intel SGX and IPFS based blockchain.
* [Town Crier](https://github.com/bl4ck5un/Town-Crier) - Town Crier: an Authenticated Data Feeds for Smart Contracts http://town-crier.org
* [infobiac/eEVM](https://github.com/infobiac/eEVM) - Enclave ready EVM (eEVM) is an open-source, standalone, embeddable, C++ implementation of the Ethereum Virtual Machine. http://microsoft.com/blockchain 
* [hyperledger-labs/fabric-private-chaincode](https://github.com/hyperledger-labs/fabric-private-chaincode) - This lab enables Secure Chaincode Execution using Intel SGX for Hyperledger Fabric.
* [scs/substraTEE](https://github.com/scs/substraTEE) - Trusted Off-Chain Compute Framework for substrate blockchains
* [hyperledger/avalon](https://github.com/hyperledger/avalon) - Hyperledger Avalon (formerly Trusted Compute Framework) https://wiki.hyperledger.org/display/…
* [smartcontractkit chainlink](https://github.com/smartcontractkit/chainlink) - node of the decentralized oracle network, bridging on and off-chain computation https://chain.link
* [scs substraTEE](https://github.com/scs/substraTEE) - Trusted Off-Chain Compute Framework for substrate blockchains

## MachineLearning

* [zeyu-zh/TrustFL](https://github.com/zeyu-zh/TrustFL) - Enabling Execution Assurance of Federated Learning at Untrusted Participants
* [ftramer/slalom](https://github.com/ftramer/slalom) - Slalom: Fast, Verifiable and Private Execution of Neural Networks in Trusted Hardware
