# LocalChatKit

A Swift framework exploring **local-first, peer-to-peer messaging between nearby Apple devices**.

The primary goal is to investigate whether devices connected to the same local network can exchange messages directly, without routing local communication through a remote cloud server.

## Vision

Enable nearby Apple devices to communicate directly whenever they are reachable through a local network or peer-to-peer connection.

```text
iPhone A
   │
   │ Local Network / P2P
   │
iPhone B
```

Instead of unnecessarily routing local communication through:

```text
iPhone A
   │
   ▼
Remote Server
   │
   ▼
iPhone B
```

## Initial Areas of Exploration

- Peer discovery
- Local network communication
- Peer-to-peer connectivity
- Device identity
- Message transport
- Reliable message delivery
- Offline-first messaging
- Local message persistence
- Encryption and security
- Message synchronization
- Internet/cloud fallback

## Project Status

**Early Research / Exploration**

The architecture and technical approach are intentionally under investigation. Implementation decisions will be documented as the project evolves.

## Goals

This project is primarily an exploration of networking and distributed-systems concepts on Apple platforms.

The long-term goal is to build a reusable Swift networking/messaging framework rather than simply a standalone chat application.

## Platform

- Swift
- iOS
- Apple networking frameworks

## License

To be determined.
