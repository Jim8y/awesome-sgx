<div align="center">
	<img width="500" height="350" src="https://github.com/sindresorhus/awesome/blob/main/media/logo.svg" alt="Awesome">
</div>

# Awesome SGX [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Liaojinghui/awesome-sgx) 

> Collection of material for learning SGX.

## Table of Contents

- [BlockChain](#BlockChain)
- [Container](#Container)
- [CRYPTO](#CRYPTO)
- [DATABASE](#DATABASE)
- [EMULATOR](#emulator)
- [GAME](#GAME)
- [Hardware](#Hardware)
- [LibOS](#LibOS)
- [MachineLearning](#MachineLearning)
- [NETWORK](#NETWORK)
- [Paper](#Paper)
- [Programming Language](#ProgrammingLanguage)
- [Side-Channels](#Side-Channels)
- [SDK](#SDK)
- [Samples](#Samples)
- [Study](#Study)
- [Security](#Security)
- [Tool&&DEBUG](#Tool&&DEBUG)

## BlockChain

* [LedgerHQ/bolos-enclave](https://github.com/LedgerHQ/bolos-enclave)
* [luckychain/lucky](https://github.com/luckychain/lucky) - Proof of luck Intel SGX and IPFS based blockchain.
* [Town Crier](https://github.com/bl4ck5un/Town-Crier) - Town Crier: an Authenticated Data Feeds for Smart Contracts http://town-crier.org 
* [infobiac/eEVM](https://github.com/infobiac/eEVM) - Enclave ready EVM (eEVM) is an open-source, standalone, embeddable, C++ implementation of the Ethereum Virtual Machine. http://microsoft.com/blockchain  
* [hyperledger-labs/fabric-private-chaincode](https://github.com/hyperledger-labs/fabric-private-chaincode) - This lab enables Secure Chaincode Execution using Intel SGX for Hyperledger Fabric. 
* [hyperledger/avalon](https://github.com/hyperledger/avalon) - Hyperledger Avalon (formerly Trusted Compute Framework) https://wiki.hyperledger.org/display/…
* [smartcontractkit chainlink](https://github.com/smartcontractkit/chainlink) - node of the decentralized oracle network, bridging on and off-chain computation https://chain.link. 
* [skalenetwork/sgxwallet](https://github.com/skalenetwork/sgxwallet) - sgxwallet is the first-ever opensource high-performance hardware secure crypto wallet that is based on Intel SGX technology. 
* [Secret Network](https://github.com/enigmampc/SecretNetwork) - Secret Network is the first blockchain with data privacy by default for smart contracts and entirely based on Intel SGX technology. https://scrt.network/
* [phala-blockchain](https://github.com/Phala-Network/phala-blockchain) - Phala Network is a blockchain-based confidential computing cloud.
* [substraTEE](https://github.com/integritee-network/substraTEE) - Trusted Off-Chain Compute Framework for substrate blockchains
* [automata](https://github.com/automata-network) - Automata Network is a modular attestation layer that extends machine trust to Ethereum with TEE Coprocessors.

## Container

* [tozd/docker-sgx](https://github.com/tozd/docker-sgx) - A Docker image with Intel SGX support. https://hub.docker.com/r/tozd/sgx/. 
* [alibaba/inclavare-containers](https://github.com/alibaba/inclavare-containers) - A novel container runtime, aka enclave container, for confidential computing and cloud-native ecosystem. 
* [deislabs/mystikos](https://github.com/deislabs/mystikos) - Tools and runtime for launching unmodified container images in Trusted Execution Environments

## CRYPTO

* [intel/intel-sgx-ssl](https://github.com/intel/intel-sgx-ssl) - Intel® Software Guard Extensions SSL. 
* [WolfSSL](https://github.com/NickolasLapp/linux_sgx) - WolfSSL with SGX for Linux OS using Eclipse IDE and SGX Plugin. 
* [momalab/SGXCrypter](https://github.com/momalab/SGXCrypter) - SGXCrypter is a novel approach on encryption based binary packing. 
* [rscosta/SGXCryptoFile](https://github.com/rscosta/SGXCryptoFile) - SgxCryptoFile - App for Encrypting and Decrypting Files using Intel SGX. 
* [oweisse/sgx_crypto_wrapper](https://github.com/oweisse/sgx_crypto_wrapper) - A Python wrapper for sgx_tlibcrypto library. 
* [sparkly9399/SGX-OpenSSL](https://github.com/sparkly9399/SGX-OpenSSL) - OpenSSL library for SGX application. 
* [ayeks/TresorSGX](https://github.com/ayeks/TresorSGX) - Securing storage encryption by using Intel SGX enclaves. First attempt for the isolation of OS components with trusted enclaves. 
* [kudelskisecurity/sgx-reencrypt](https://github.com/kudelskisecurity/sgx-reencrypt) - PoC of an SGX enclave performing symmetric reencryption. 

## DATABASE

* [yerzhan7/SGX_SQLite](https://github.com/yerzhan7/SGX_SQLite) - SQLite database inside a secure Intel SGX enclave (Linux).  

## EMULATOR

* [tristartom/sgx-emulator](https://github.com/tristartom/sgx-emulator) - An Emulator and SDK for Intel SGX extension. 
* [intel/qemu-sgx](https://github.com/intel/qemu-sgx) - qemu with SGX. 
* [sslab-gatech/opensgx](https://github.com/sslab-gatech/opensgx) - OpenSGX: An open platform for Intel SGX. 
* [intel/kvm-sgx](https://github.com/intel/kvm-sgx) - This repository hosts preliminary Linux/KVM patches to support SGX virtualization on KVM. 

## GAME

* [utds3lab/sgx-biniax2](https://github.com/utds3lab/sgx-biniax2) - A Linux game with SGX. 
* [djwessel/sgx-snake](https://github.com/djwessel/sgx-snake) - A simple snake game implemented with SGX. 
* [suinkang/SGX-Doom3](https://github.com/suinkang/SGX-Doom3) - Doom3 with SGX. 

## Hardware

* [ayeks/SGX-hardwarep](https://github.com/ayeks/SGX-hardware) - This is a list of hardware which is supports Intel SGX - Software Guard Extensions.

## LibOS

* [Anjuna](https://www.anjuna.io) - Anjuna Runtime - a solution for executing unmodified applications in Intel SGX enclaves.
* [oscarlab/graphene](https://github.com/oscarlab/graphene) - Graphene / Graphene-SGX Library OS - a library OS for Linux multi-process applications, with Intel SGX support https://github.com/oscarlab/graphene/… 
* [SCONE](https://www.usenix.org/system/files/conference/osdi16/osdi16-arnautov.pdf) - SCONE: Secure Linux Containers with Intel SGX
* [SGXKernel](http://delivery.acm.org/10.1145/3080000/3075572/p35-Tian.pdf?ip=113.240.234.248&id=3075572&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E1C775F1AC6329F5A%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=1000423527&CFTOKEN=74748264&__acm__=1509418666_8d60f199060353b9d2e3a828901a729e) - SGXKernel: A Library Operating System Optimized for Intel SGX
* [Haven](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-baumann.pdf) - Shielding Applications from an Untrusted Cloud with Haven.
* [shwetasshinde24/Panoply](https://github.com/shwetasshinde24/Panoply) - Low-TCB Linux Applications with SGX Enclaves. 
* [lsds/sgx-lkl](https://github.com/lsds/sgx-lkl) - SGX-LKL Library OS for running Linux applications inside of Intel SGX enclaves. 
* [occlum/occlum](https://github.com/occlum/occlum) - Occlum: Secure and Efficient Multitasking Inside a Single Enclave of Intel SGX. 


## MachineLearning

* [zeyu-zh/TrustFL](https://github.com/zeyu-zh/TrustFL) - Enabling Execution Assurance of Federated Learning at Untrusted Participants. 
* [ftramer/slalom](https://github.com/ftramer/slalom) - Slalom: Fast, Verifiable and Private Execution of Neural Networks in Trusted Hardware. 

## NETWORK

* [kaist-ina/SGX-Tor](https://github.com/kaist-ina/SGX-Tor) - https://github.com/kaist-ina/SGX-Tor. 
* [jnferguson/pwd](https://github.com/jnferguson/pwd) - SGX password storage / authentication subsystem. 

## Paper

* [vschiavoni/sgx-papers](https://github.com/vschiavoni/sgx-papers) - A list of system papers using/about Intel SGX.

## Programming Languages

* [Rust](https://github.com/baidu/rust-sgx-sdk) - Rust SGX SDK provides the ability to write Intel SGX applications in Rust Programming Language. 
* [C#](https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX) - A C# example project downloaded from intel with GUI implemented with SGX. 
* [GO](https://github.com/rupc/go-with-intel-sgx) - Intel SGX with GoLang. 
* [Python](https://github.com/adombeck/python-sgx) - Python interface to the SGX SDK. 
* [JAVA](https://github.com/sm67nono/Intel_SGX_Proj) - Trusted Computing Base with Intel SGX and Java JNI. 
* [lishen-nt/sgx-language-adapter](https://github.com/lishen-nt/sgx-language-adapter) - SGX language adapter for java and python. 

## Side-Channels

* [jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step) - A practical attack framework for precise enclave execution control. 
* [jovanbulck/sgx-pte](https://github.com/jovanbulck/sgx-pte) - Telling your secrets without page faults: Stealthy page table-based attacks on enclaved execution. 
* [jovanbulck/sgx-tutorial-space18](https://github.com/jovanbulck/sgx-tutorial-space18) - Tutorial: Uncovering and mitigating side-channel leakage in Intel SGX enclaves. 
* [HE-Wenjian/SGXlinger](https://github.com/HE-Wenjian/SGXlinger) - A side-channel attack vector based on interrupt latency against enclave execution of Intel SGX. 
* [plundervolt](https://plundervolt.com/doc/plundervolt.pdf) - Software-based Fault Injection Attacksagainst Intel SGX.

## SDK

* [01org/linux-sgx](https://github.com/01org/linux-sgx) - Intel(R) Software Guard Extensions for Linux* OS. 
* [adombeck/python-sgx](https://github.com/adombeck/python-sgx) - Python interface to the SGX SDK. 
* [apache/incubator-teaclave-sgx-sdk](https://github.com/apache/incubator-teaclave-sgx-sdk) - Rust SGX SDK provides the ability to write Intel SGX applications in Rust Programming Language. 
* [rust-optee-trustzone-sdk](https://github.com/mesalock-linux/rust-optee-trustzone-sdk) - Rust OP-TEE TrustZone SDK: Enabling Safe, Functional, and Ergonomic Development of Trustlets. 
* [fortanix/rust-sgx](https://github.com/fortanix/rust-sgx) - The Fortanix Rust Enclave Development Platform https://edp.fortanix.com. 
* [openenclave/openenclave](https://github.com/openenclave/openenclave) - SDK for developing enclaves https://openenclave.io/sdk/. 
* [SOFAEnclave/KubeTEE](https://github.com/SOFAEnclave/KubeTEE) - KubeTEE is a collection of TEE development, deployment, maintenance middleware frameworks, and services. Especially, it is for cloud-native workflows. 
* [edgelesssys/edgelessrt](https://github.com/edgelesssys/edgelessrt) - Edgeless RT is an SDK for Trusted Execution Environments (TEE) built on top of Open Enclave. 

## Samples
* [intel/sgx-ra-sample](https://github.com/intel/sgx-ra-sample) - The only official remote attestation sample that support the real and complete attestation. 
* [TinySecurityLab/SGXRemoteAttestation](https://github.com/TinySecurityLab/SGXRemoteAttestation/blob/master/sgxinstall) - A "real" remote attestation flamework of Intel SGX. (This one simulate the whole attestation process). 

## Study
* [dingelish/SGXfail](https://github.com/dingelish/SGXfail) - SGX从入门到放弃

## Security

* [lsds/spectre-attack-sgx](https://github.com/lsds/spectre-attack-sgx) - Spectre attack against SGX enclave. 
* [bl4ck5un/mbedtls-SGX](https://github.com/bl4ck5un/mbedtls-SGX) - mbedtls-SGX: a SGX-friendly TLS stack (ported from mbedtls). 
* [jaebaek/SGX-Shield](https://github.com/jaebaek/SGX-Shield) - SGX-Shield: Enabling Address Space Layout Randomization (ASLR) for SGX Programs. 
* [tudinfse/sgxbounds](https://github.com/tudinfse/sgxbounds) - SGXBounds: Memory Safety for Shielded Execution (compiler pass and runtime). 
* [IAIK/sgxrop](https://github.com/IAIK/sgxrop) - The code to the SGX-ROP paper. 

## Tool&&DEBUG

* [jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step) - A practical attack framework for precise enclave execution control. 
* [swarupchandra/secure-analytics-sgx](https://github.com/swarupchandra/secure-analytics-sgx) - Securing Data Analytics on Intel SGX using Randomization. 
* [Glamdring](https://www.usenix.org/system/files/conference/atc17/atc17-lind.pdf) - Glamdring: Automatic Application Partitioning for Intel SGX.
* [kudelskisecurity/sgxfun](https://github.com/kudelskisecurity/sgxfun) - SGX command-line tools and paper. 
* [ireed/SGX](https://github.com/ireed/SGX) - Code samples and tutorials for using intel software guard extensions. 
* [jethrogb/sgx-utils](https://github.com/jethrogb/sgx-utils) - Various utilities for Intel SGX hardware. 
