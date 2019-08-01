# Authentication Working Group

Join this group to contribute to standards and technology that designs and implements authentication protocols that rely upon open standards and cryptographic protocols, including DIDs and DID Documents. This group develops specifications, protocols, and formats for data structures used for authentication.

Get in touch with us on DIF Slack: `#wg-auth`.

# Work Items

## DID Authentication Profile for SIOP

This specification defines the SIOP DID AuthN flavor to use OpenID Connect (OIDC) together with the strong decentralization, privacy and security guarantees of DID for everyone who wants to have a generic way to integrate SSI wallets into their web applications.

- Status: **DRAFT**, **WIP**
- Use Case: Use your identity wallet to authenticate against a Web Application
- [Explainer](https://github.com/decentralized-identity/papers/blob/master/did-authn/siop/did-authn-siop-profile.md)
- [Repo](https://github.com/decentralized-identity/papers/blob/master/did-authn/siop/did-authn-siop-profile.md)

## Encrypted Envelope

This concept is borrowed from the HL Aries to create a standardized means of authenticated general message passing between DID controllers. DIF provides an implementation of pack/unpack that intends to meet the requirements of the DIF community.

- Status: **PROPOSAL**
- Use Case: Secure communication between DID controllers.
- [Explainer](https://github.com/hyperledger/aries-rfcs/blob/master/features/0019-encryption-envelope/README.md)
- [Repo](https://github.com/decentralized-identity/DIDComm-js)