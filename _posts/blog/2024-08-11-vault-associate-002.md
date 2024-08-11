---
title: "Hashicorp Certified: Vault Associate 002"
excerpt: "How to prepare for the Vault Associate 002 exam."
tags: vault
header:
  overlay_image: /assets/images/vault-associate-002-badge.png
  overlay_filter: 0.7
  actions:
    - label: "View My Certificate"
      url: https://www.credly.com/badges/052be2f5-715e-4df7-aaa0-e7f576d626cf/public_url
classes: wide
featured: true
---

## Important links

From official source,

- Exam details - [https://developer.hashicorp.com/certifications/security-automation#vault-associate-(002)-details](https://developer.hashicorp.com/certifications/security-automation#vault-associate-(002)-details){:target="\_blank"}

## Study materials

- Learning path - [https://developer.hashicorp.com/vault/tutorials/associate-cert/associate-study](https://developer.hashicorp.com/vault/tutorials/associate-cert/associate-study){:target="\_blank"}
- Exam content list - [https://developer.hashicorp.com/vault/tutorials/associate-cert/associate-review](https://developer.hashicorp.com/vault/tutorials/associate-cert/associate-review){:target="\_blank"}
- Sample questions - [https://developer.hashicorp.com/vault/tutorials/associate-cert/associate-questions](https://developer.hashicorp.com/vault/tutorials/associate-cert/associate-questions){:target="\_blank"}

## Key points

### 1. Authentication Methods

Vault offers various ways to authenticate users and systems. Make sure you know the different authentication methods available, such as token-based, LDAP, and OAuth. Know how each method works, and understand when to use human versus system authentication. You should know when to choose the right method for different scenarios.

### 2. Vault Policies

Vault policies control who can access what within Vault. Revise how to create and manage these policies. Get comfortable with policy syntax, including paths and capabilities, so you can craft policies that meet specific requirements. Knowing how to manage these policies is very important for securing Vault environment.

### 3. Vault Tokens

Tokens are a core part of Vault’s security model. Learn about the different types of tokens eg service, batch, root along with their uses and lifecycles. Understand how to create and manage these tokens effectively. Also, make sure you understand the concept of token accessors and the significance of time-to-live (TTL) for tokens.

### 4. Vault Leases

Vault uses leases to manage the lifetime of secrets. Understand what a lease ID is, and how to renew or revoke leases. This knowledge is important in order for one to ensure that secrets are managed securely and are valid only for as long as needed.

### 5. Secrets Engines

Secrets engines are Vault components that store and manage secrets. Get familiar with different types of secrets engines and their use cases. Learn the difference between dynamic and static secrets, and understand the purpose of the transit secrets engine for encryption.

### 6. Vault CLI and UI

Vault provides both a command-line interface (CLI) and a user interface (UI) for managing Vault environment. Learn how to authenticate, configure policies, access secrets, and enable secret engines using both CLI and UI.

### 7. Vault API

The Vault API allows us to interact with Vault programmatically. Learn how to authenticate and access secrets using tools like `curl`, which is a common tool for interacting with APIs.

### 8. Vault Architecture

Vault's architecture includes several important components. Learn about data encryption, cluster strategies, storage backends, and the Vault agent. Also, understand concepts like secrets caching, Shamir secret sharing, and replication.

### 9. Encryption as a Service

Learn how to configure the transit secret engine, what's the benefit of using it, how to perform encryption and decryption, and rotate encryption keys.

## Useful Links for Reference

These are some documents I reviewed when preparing

- [Vault Agent Auto-Auth](https://developer.hashicorp.com/vault/docs/agent-and-proxy/autoauth)
- [Vault Agent Caching](https://developer.hashicorp.com/vault/docs/agent-and-proxy/agent/caching#caching-and-renewals)
- [Vault AppRole Auth Method](https://developer.hashicorp.com/vault/docs/auth/approle)
- [Vault Auto-Unseal](https://developer.hashicorp.com/vault/docs/concepts/seal#auto-unseal)
- [Vault Disaster Recovery](https://developer.hashicorp.com/vault/tutorials/enterprise/disaster-recovery)
- [Vault Dynamic Secrets](https://developer.hashicorp.com/vault/docs/concepts/dynamic-secrets)
- [Vault HTTP API Authentication](https://developer.hashicorp.com/vault/api-docs#authentication)
- [Vault Identity Group](https://registry.terraform.io/providers/hashicorp/vault/latest/docs/resources/identity_group)
- [Vault Key Rotation](https://developer.hashicorp.com/vault/docs/internals/rotation#key-rotation)
- [Vault KV Secrets Engine](https://developer.hashicorp.com/vault/docs/commands/kv#examples)
- [Vault LDAP Authentication](https://developer.hashicorp.com/vault/docs/auth/ldap)
- [Vault Lease Renew Command](https://developer.hashicorp.com/vault/docs/concepts/lease#lease-durations-and-renewal)
- [Vault Lease](https://developer.hashicorp.com/vault/docs/concepts/lease)
- [Vault Performance Replication](https://developer.hashicorp.com/vault/tutorials/enterprise/performance-replication)
- [Vault PKI Secrets Engine](https://developer.hashicorp.com/vault/docs/secrets/pki)
- [Vault Seal Configuration](https://developer.hashicorp.com/vault/docs/configuration/seal)
- [Vault Storage Configuration](https://developer.hashicorp.com/vault/docs/configuration/storage)
- [Vault Tokens](https://developer.hashicorp.com/vault/docs/concepts/tokens)
- [Vault Userpass Auth Method](https://developer.hashicorp.com/vault/docs/auth/userpass)
- [Transit Secrets Engine](https://developer.hashicorp.com/vault/tutorials/encryption-as-a-service/eaas-transit)
