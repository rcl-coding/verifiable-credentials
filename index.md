---
title: Introduction
description: Verifiable Credentials
nav_order: 1
---

# Verifiable Credentials

[W3C Verifiable Credentials](https://www.w3.org/TR/vc-data-model/) are digital credentials that are expressed on the Web in a way that is cryptographically secure, privacy respecting, and machine-verifiable.

## Roles

### Holder

A role an entity might perform by possessing one or more verifiable credentials and generating verifiable presentations from them. Example holders include students.

### Issuer

A role an entity performs by asserting claims about one or more subjects, creating a verifiable credential from these claims, and transmitting the verifiable credential to a holder. Example issuers include educators.

### Verifier

A role an entity performs by receiving one or more verifiable credentials, optionally inside a verifiable presentation, for processing. Example verifiers include employers.

## ION

Our verifiable credentials uses the [ION](https://didproject.azurewebsites.net/docs/ion-sidetree.html) method. ION is a is a public, permissionless, Decentralized Identifier (DID) network that implements the blockchain-agnostic Sidetree protocol on top of Bitcoin (as a 'Layer 2' overlay). ION anchors verifiable credentials in the Bitcoin block chain. This ensures the verifiable credentials are crytographically secure, tamper proof and immutable (cannot be changed once created).

## Microsoft Active Directory Verifiable Credentials

[AAD Verifiable Credentials](https://docs.microsoft.com/en-us/azure/active-directory/verifiable-credentials/) provide a cloud service for the creation, issuance and verification of verifiable credentials using the ION method. Our verifiable credentials use this service.

## Mobile Wallet Application

Our verifiable credentials are stored in the [Microsoft Authenticator](https://www.microsoft.com/en-us/security/mobile-authenticator-app) mobile application. Holders will claim, download and install verifiable credentials in the app. Holders will also use the app to display their credentials to verifiers



