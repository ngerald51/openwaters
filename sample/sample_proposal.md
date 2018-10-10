# Open Waters : Decentralised-Identifier (sample proposal)

## Abstract
A DID is a unique identifier that can be resolved or de-referenced to a standard resource describing the entity (a DID Document or DDO).
If we apply this to Ocean, the DID would be the unique identifier of an object represented in Ocean (ie. the Asset ID of an ASSET or the Actor ID of a USER).
## Motivation

The main motivations of this OEP are:

* Design a solution to extend the current architecture to use **Decentralized Identifiers (DID)** and **DID description objects (DDO)**
* Understand how to register information on-chain with off-chain integrity associated
* Understand how to resolve DID's into DDO's


## Specification

Requirements are:

* The DID resolving capabilities MUST be exposed in the client libraries, enabling to resolve a DDO directly in a totally transparent way
* ASSETS are DATA objects describing RESOURCES under control of a PUBLISHER
* KEEPER stores on-chain only the essential information about ASSETS
* PROVIDERS store the ASSET metadata off-chain
* KEEPER doesn't store any ASSET metadata
* OCEAN doesn't store ASSET files contents


## Implementation

![Sequence Diagram](ddo-integrity-sequence.png)


## References

* https://w3c-ccg.github.io/did-spec/
* https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2016/blob/master/topics-and-advance-readings/did-spec-working-draft-03.md

## Open Questions 
## Notes
This sample is referenced from [OEP-7](https://github.com/oceanprotocol/OEPs/tree/master/7) and is intended to be used only as a sample for creating sample proposal for open bounty.
