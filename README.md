
<h1 align="center">Data Ecosystem Proposals (DEPs)</h1>


# About

This is the Data Ecosystem Proposal project, which defines a set of open standards for the 
development of interoperable, decentralised data ecosystems.

You should consider adopting the DEP standards if:

- You need to orchestrate data services across multiple organisations / participants
- You need the ability to remotely invoke operations on a variety of data sources
- You wish to unlock the value of existing data assets and services to a broader ecosystem
- You plan to primarily make use of the capabilities of the Ocean Network, but wish to maintain a level of abstraction away from specific implementation details.


# Current DEPs

Short Name             | Title                                                        | Type         | Status     | Editor
-----------------------|--------------------------------------------------------------|--------------|------------|-------
[0/GLOSSARY](0)        | Data Ecosystem Glossary                                      | Reference    | Draft      | Mike Anderson
[1/C4](1)              | Collective Code Construction Contract                        | Meta         | Draft      | Mike Anderson
[2/COSS](2)            | Consensus-Oriented Specification System                      | Meta         | Draft      | Mike Anderson
[3/ARCH](3)            | Architecture & Principles                                    | Standard     | Draft      | Mike Anderson
[4/STARFISH](4)        | Starfish Abstract API                                        | Standard     | Raw        | Mike Anderson
[5/IDENTITY](5)        | Agent and Asset Identity                                     | Standard     | Raw        | Mike Anderson
[6/INVOKE](6)          | Invokable Services                                           | Standard     | Draft      | Kiran Karkera
[7/STORAGE](7)         | Universal Storage API                                        | Standard     | Draft      | Mike Anderson
[8/META](8)            | Asset Metadata Standard                                      | Standard     | Draft      | Mike Anderson
[9/SQUID-INT](9)       | Squid Integration for Ocean Network                          | Standard     | TBC        | Bill Barman
[10/TOKEN-PAY](10)     | Direct Payments with Ocean Tokens                            | Standard     | Raw        | Ilya Bukalov
[12/PROV](12)          | Publisher Declared Provenance                                | Standard     | Draft      | Kiran Karkera
[15/META-API](15)      | Metadata API                                                 | Standard     | Draft      | Mike Anderson
[19/ENDPOINTS](19)     | DEP Standard Endpoints                                       | Standard     | Draft      | Mike Anderson
[20/AUTHENTICATION](20)| Authentication Standard and API                              | Standard     | Raw        | TBD
[21/AUTHORISATION](21) | Authorisation Standard and API                               | Standard     | Raw        | TBD


# Contributing

DEPs are open source standard documents free for all in the community to use.

This repository of DEPs is maintained by DEX Pte. Ltd. as a contribution to the Ocean Protocol community and the broader data economy.

## Contribution process

The process to add or change a DEP is the following:
- A DEP is created and modified by pull requests according to [C4](./1).
- DEP lifecycle SHOULD follow the lifecycle defined in [COSS](./2).
- A DEP Should be licensed under the [Apache License Version 2.0](./LICENSE) (exceptions may be allowed).
- Non-cosmetic changes are allowed only on [Raw](./2#raw-deps) and [Draft](./2#draft-deps) specifications.
- The allocation of ID numbers to DEPs will be maintained by the project administrators.

## Language

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [BCP 14](https://tools.ietf.org/html/bcp14) \[[RFC2119](https://tools.ietf.org/html/rfc2119)\] \[[RFC8174](https://tools.ietf.org/html/rfc8174)\] when, and only when, they appear in all capitals, as shown here.


# Current Participants

## Contributors

The DEPs are open for anyone who wants to contribute.

Current contributors include:
- The DEX and Ocean technical team

We prefer small, focused PRs that address a specific issue with a specific DEP and provide
clear rationale for the where appropriate. PRs will be reviewed and 
if appropriate merged by the relevant DEP Editor(s).


## Editors

See table of current DEPs

## Administrators

- Mike - @mikera
