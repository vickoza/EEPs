---
EEP: 10
title: Update EOSIO build enviroment
author: Vishal Oza (@vickoza)
status: Draft
type: Standard
category: Core
created: 2024-10-09
---

## Simple Summary
To Update the EOSIO build enviroment to using C++ 20 and later version as well as use a more current versions of OpenSSL. This might extend to smart contract to use C++ 20 or later features.

## Abstract
These change should allow EOS to be used on more platforms and might add some more security benifits as the security defualts as added to newer C++ version. This might relax the build script to support more Unix/Linux platforms not just

* Amazon Linux 2
* CentOS Linux 8.x
* CentOS Linux 7.x
* Ubuntu 20.04
* Ubuntu 18.04
* macOS 10.14 (Mojave) or later

## Motivation
By making these changes it should allow more people to use EOSIO and a blockchian project.

## Rationale
These changes might encourage the adpotion of more EOSIO projects and make EOS relivant agian.

## Backwards Compatibility
This might break backward compatibility in contracts if the contract depends on OpenSSL 1.x. However, this fix should allow the EOSIO platform to spread on more platforms.

## Test Cases
## Implementations
## Security Considerations
## Intellectual Property
I hereby agree that this EEP is subject to this copyright waiver and I certify that I have all necessary rights and permissions to make this submission and to agree to such waiver.
