---
nav_exclude: true
---
# Awala Protocol Suite Specifications

This website hosts the official [Awala](https://awala.network/) specifications. If you're new to Awala, you may want to start by watching a [high-level explanation of how it works](https://youtu.be/_4zP0CfcTj4) and the [demo of the proof of concept with Twitter](https://www.youtube.com/watch?v=fi_RKwmrXIY).

## Main Specifications

The following specifications provide the foundation of the network and are therefore the top priority of the project. At this point, the best way to contribute to the project is by providing feedback on these specs.

- [RS-000 (Awala Core)](rs000-core.md) defines the foundation of the protocol suite.
- [RS-001 (RAMF)](rs001-ramf.md) defines the _Awala Abstract Message Format_, an efficient binary format used to serialize messages.
- [RS-002 (Awala PKI)](rs002-pki.md) defines how to use the certificates for endpoints and gateways.
- [RS-003 (Key Agreement)](rs003-key-agreement.md) defines the key agreement protocol to establish and protect sessions.
- [RS-008 (CogRPC)](rs008-cogrpc.md) is the part of the technology that helps transport the data using alternative methods like sneakernets.
- [RS-016 (PoWeb)](rs016-poweb.md) defines a protocol that connects applications to the Awala network.
- [RS-007 (PoHTTP)](rs007-pohttp.md) defines a protocol that connects Awala to the Internet.
- [RS-018 (Cryptographic Algorithms)](rs018-algorithms.md) defines the cryptographic algorithms that can be used in Awala.
- [RS-014 (Ping)](rs014-ping.md) defines a trivial service to test end-to-end the implementation and integration of Awala components.

## Informational Specifications

The following specifications are available for informational purposes only, and there are no requirements for Awala software vendors to comply with them.

- [RS-019 (Security Threats)](rs019-threats.md) describes the general security threats that end users, service providers, couriers and software vendors should be aware of when implementing and using Awala.
- [RS-012 (Service Integration Scale)](rs012-service-integration.md) categorizes the degrees to which Awala can be integrated in a service. This can be useful to understand the vision of the project and how future applications could be built on top of Awala.

## Future Extensions

The following documents are placeholders for future extensions:

- [RS-017 (Adaptive Relay)](rs017-adaptive-relay.md) will keep latencies low when the underlying network (e.g., the Internet) is available.
- [RS-010](rs010-pdc-browser.md) will define a JavaScript interface that browsers or browser extensions can expose to make it easier and safer for client-side apps to send and receive parcels.
- [RS-011 (AsyncRPC)](rs011-asyncrpc.md) will define a service that encapsulates RPCs in Awala messages. Only meant as a steppingstone until the actual service supports Awala.
- [RS-013 (Message Broadcast)](rs013-pubsub.md) will add support for the [Publish-Subscribe pattern](https://www.enterpriseintegrationpatterns.com/patterns/messaging/PublishSubscribeChannel.html).
