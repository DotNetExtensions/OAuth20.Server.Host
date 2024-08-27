# DotNetExtensions.OAuth20.Host - Hosted OAuth 2.0 Authorization Server

## Repository Overview

**DotNetExtensions.OAuth20.Host** provides an ASP.NET Core hosted web application that implements a fully functional OAuth 2.0 Authorization Server. It leverages the core libraries from the **DotNetExtensions.OAuth20** repository to offer OAuth 2.0 endpoints, a Blazor-based Admin Panel, and Personal Account UI, along with multiple data storage options.

For a comprehensive overview of the entire project, including how this repository fits into the larger architecture, visit the [DotNetExtensions.OAuth20 GitHub Project Page](https://github.com/orgs/DotNetExtensions/projects/17).

## Table of Contents
- [Repository Overview](#repository-overview)
- [Key Features](#key-features)
- [Installation](#installation)
  - [Kubernetes Installation](#kubernetes-installation)
  - [Helm Installation](#helm-installation)
  - [Windows Service or IIS Installation](#windows-service-or-iis-installation)
- [Running Tests](#running-tests)
- [Demo Projects](#demo-projects)
- [Linked Repositories](#linked-repositories)
- [Community and Support](#community-and-support)
- [References](#references)
- [License](#license)
- [Contributing](#contributing)
- [Security](#security)
- [Change Log](#change-log)

### Key Features
- **Ready-to-Deploy:** Complete OAuth 2.0 Authorization Server with built-in UI and data storage.
- **Cross-Platform:** Supports deployment on Docker, Kubernetes, Helm, and as a Windows Service or IIS application.
- **Integration:** Uses core and UI libraries from **DotNetExtensions.OAuth20**.
- **Security and Compliance:** Adheres to OAuth 2.0 [RFC 6749](https://datatracker.ietf.org/doc/html/rfc6749) with additional security measures.
- **Comprehensive Testing:** Integration tests, load tests, and demo scenarios included.

## Installation

### Kubernetes Installation
Deploy the server on a Kubernetes cluster:

```
kubectl apply -f https://dotnetextensions.com/oauth20/kubernetes-manifest.yaml
```

### Helm Installation
Install using Helm:

```
helm install your-release-name dotnetextensions/oauth20 --version x.x.x
```

### Windows Service or IIS Installation
Install your OAuth 2.0 Server as a Windows Service or IIS website by following the instructions in the [DotNetExtensions/OAuth20.Host](https://github.com/DotNetExtensions/OAuth20.Server.Host) repository.

## Running Tests

Run integration and load tests:

```
dotnet test
```

## Demo Projects

The repository includes demo scenarios and configuration samples. Explore these demos to understand the server’s capabilities.

## Linked Repositories

- **Library Repository:** [DotNetExtensions/OAuth20](https://github.com/DotNetExtensions/OAuth20)

## Community and Support
For discussions, support, and feedback, visit:

- [Project Website](https://dotnetextensions.com/oauth20)
- [Community Board](https://dotnetextensions.com/oauth20/community)
- [Support Page](https://dotnetextensions.com/oauth20/support)

## References
This project is based on the OAuth 2.0 Authorization Framework, specifically following the guidelines set forth in [RFC 6749](https://datatracker.ietf.org/doc/html/rfc6749).

## License
This project is licensed under the [MIT License](./LICENSE).

## Contributing
We welcome contributions! Please read our [Contributing Guidelines](./CONTRIBUTING.md) to get started.

## Security

If you find a vulnerability, please report it by emailing [security@dotnetextensions.com](mailto:security@dotnetextensions.com). For more details, refer to our [SECURITY.md](./SECURITY.md).

## Security

We take the security of our project seriously. If you discover any security vulnerabilities, please follow the instructions below to report them:

### Security Policy

Our security policy ensures that any discovered vulnerabilities are addressed promptly and responsibly. We are committed to maintaining the security of the DotNetExtensions.OAuth20 project and its related repositories.

### Reporting a Vulnerability

If you find a vulnerability, please report it by emailing [security@dotnetextensions.com](mailto:security@dotnetextensions.com). Provide as much information as possible, including:

- A description of the vulnerability.
- Steps to reproduce the issue.
- Potential impact of the vulnerability.
- Any possible mitigations you may have already implemented.

We will respond to your report as quickly as possible and keep you informed of the progress in resolving the issue.

For more details, please refer to our [SECURITY.md](./SECURITY.md) file.

## Change Log
All notable changes to this project will be documented in [CHANGELOG.md](./CHANGELOG.md).
