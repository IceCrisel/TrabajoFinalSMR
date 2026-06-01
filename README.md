# NAS with OpenMediaVault, Docker, Jellyfin and WireGuard

## Initial Presentation (English)

This project consists of creating a private cloud using a mini PC configured as a NAS server. The system allows users to store and manage files in a centralized location while maintaining control over permissions and access.

Remote access is provided through a WireGuard VPN, ensuring secure connections from outside the local network. Additionally, Jellyfin is used as a multimedia server, allowing users to organize and stream movies, series, photos and videos stored on the NAS.

The project combines storage, remote access and multimedia services in a single low-cost solution.

---

## Technical Justification of the Solution

OpenMediaVault was selected because it provides an easy-to-use web interface for managing storage, users and shared folders. It simplifies NAS administration without requiring advanced Linux knowledge.

Docker was used to deploy Jellyfin in an isolated environment, making installation, maintenance and future updates easier.

WireGuard was chosen as the VPN solution because it is lightweight, secure and easy to configure. It allows authorized users to access NAS resources remotely while keeping services protected from direct Internet exposure.

This solution offers a balance between functionality, security and ease of administration using open-source software.

---

## Answers to the Proposed Questions

### Why use OpenMediaVault?

OpenMediaVault makes it easy to create and manage a NAS through a web interface. It allows the administration of disks, users, groups and shared folders without requiring extensive command-line knowledge.

### Why use Jellyfin?

Jellyfin provides a multimedia platform where users can store, organize and stream movies, series, photos and videos. It is free, open source and does not require paid subscriptions.

### Why use WireGuard?

WireGuard allows secure remote access to the NAS from outside the local network. It encrypts communications and ensures that only authorized users can connect to the system.

### Why use Docker?

Docker simplifies the deployment of applications by running them inside isolated containers. This makes services easier to install, update and maintain without affecting the operating system.
