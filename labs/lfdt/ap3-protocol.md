---                                         
layout: default
title: AP3 Protocol
parent: LFDT Labs
grand_parent: Approved Labs
---  

# Lab Name                                  
AP3 Protocol
                                          
# Short Description                                                                                                                                                                                          
AP3 is an open protocol for privacy-preserving computation in agentic commerce. It enables AI agents to negotiate, verify, and transact on behalf of users and organisations without the counterparty agent  ever accessing the underlying data. When sensitive data is exchanged inside an A2A message, such as income, identity, budget, pricing, AP3 intercepts the payload, runs the required computation across encrypted inputs using Multi Party Computation and returns a verifiable inference token to the receiving agent. The receiving agent gets what it needs to make a decision. It never gets the data, or sees it itself.                                                 
                                                            
# Scope of Lab 

AP3 is the privacy layer for agentic commerce, enabling agents to compute on sensitive data and return verifiable answers without any party ever reading the underlying input

## What is the problem that AP3 solves?

When two agents exchange sensitive data inside an A2A message today, the receiving agent sees the raw data. The agentic commerce defaults to full data exposure at the agent interaction layer. Some examples: An enterprise's procurement agent reveals its actual budget to negotiate with a supplier. A borrower's agent transmits full bank statements to a lender. A user's agent sends complete identity documents to a verification service. The agents can read, store, and use sensitive data, beyond the agreed purpose. A2A just governs how agents communicate. They don’t govern how the data is processed or what is shared. There is no cryptographic guarantee of non-exposure. It cannot promise:

1. That the agent did not read your private data
2. That reciever agent did not store your private data
3. That reciever did not share your private data with a third party
4. That the user agent did not send more data than necessary
5. That either party behaved honestly with what they received

Enter AP3. When sensitive data is exchanged inside an A2A message, such as income, identity, budget, pricing, AP3 intercepts the payload, runs the required computation across encrypted inputs, and returns a verifiable result to the receiving agent. No raw data is shared, seen or stored, ever. 

## **AP3 can promise:**

1. No data is seen, read or stored
2. Defines how sensitive data is being used
3. Defines how sensitive data is encrypted and computed upon so no one sees the raw input
4. AP3 fits in specifically in the message layer in the A2A protocols, when private data is being exchanged
5. AP3 produces a cryptographic proof in place of raw data, and provides an audit trail of cryptographically signed records confirming that no data was exposed, that every computation was authorised by the data owner, and that the result is accurate and verifiable. AP3 makes acting on data and reading data two different things.

## The scope of this lab covers:

1. The AP3 protocol specification: message interception model, computation trigger rules, underlying PSI protocols, output formats to be compliant with payment protocols wherever required, and audit trail schema
2. Reference SDK implementations for integrating AP3 into A2A and compliant agents (Python and JavaScript)
3. Interoperability with AP2 and other agentic payment protocols: AP3 output artifacts feed directly into AP2 payment flows
4. Interoperability with A2A and other agent orchestrator platforms

AP3 is built on Multi-Party Computation (MPC), Zero-Knowledge Proofs (ZKP), and Zero-Knowledge TLS (zkTLS). It is designed as composable infrastructure for any A2A compliant agent framework.               

All specifications contributed to this Lab will be subject to the [Community Specification License](https://spdx.org/licenses/Community-Spec-1.0.html); and all accompanying reference implementations will be licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).                                                                                                                                 
# Initial Committers

- https://github.com/ XX
- https://github.com/ XX                

# Sponsor

- [LFDT maintainer handle — optional]
                                                                                                                                                                                                               
# Pre-existing repository

https://github.com/Paintedstork28/ap3-protocol
