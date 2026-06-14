# infrastructure

Curated projects in this category.

Note: young repositories can show strong potential but still carry higher stability and maintenance risk.

### 1. karlderkaefer/cdk-notifier

- Link: https://github.com/karlderkaefer/cdk-notifier
- Title: karlderkaefer/cdk-notifier
- Description: CLI tool to post AWS CDK diff as comment to Github pull request
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2021-08-31
- Age: 4 years 9 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 9.0/10
- Stars: 130
- Reason: A highly practical Go-based CLI tool that bridges the developer feedback loop by posting AWS CDK diffs directly to GitHub Pull Requests, significantly improving CI/CD visibility.
- Strengths:
  - Significantly improves code review developer experience for AWS CDK users
  - Lightweight Go binary makes it fast and easy to integrate into CI/CD pipelines
  - Supports collapsing large diff outputs to keep PR comments readable
- Weaknesses:
  - Coupled tightly to GitHub, lacks native support for alternative providers like GitLab or BitBucket

### 2. pulumi/pulumi-command

- Link: https://github.com/pulumi/pulumi-command
- Title: pulumi/pulumi-command
- Description: No description available.
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2021-09-01
- Age: 4 years 9 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 8.0/10
- Small repo potential: 9.0/10
- Stars: 79
- Reason: An official Pulumi provider that acts as a reliable escape hatch, enabling local and remote command execution as lifecycle-managed IaC resources.
- Strengths:
  - Official Pulumi provider with robust support
  - Manages commands as proper resources with create/update/delete lifecycles
  - Supports secure remote execution via SSH
- Weaknesses:
  - Running raw commands can introduce side effects and non-deterministic behavior into deployments
  - Requires careful handling of environment dependencies

### 3. breml/terraform-provider-uptimekuma

- Link: https://github.com/breml/terraform-provider-uptimekuma
- Title: breml/terraform-provider-uptimekuma
- Description: Terraform provider for uptime kuma
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2025-09-28
- Age: 8 months
- Last pushed: 2026-06-14
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 8.0/10
- Novelty: 7.0/10
- Maturity: 6.0/10
- Small repo potential: 9.0/10
- Stars: 57
- Reason: An incredibly useful GitOps tool that bridges the gap between Terraform and Uptime Kuma, allowing declarative management of self-hosted monitoring.
- Strengths:
  - Enables Infrastructure as Code (IaC) for Uptime Kuma monitors
  - Written in Go, conforming to standard Terraform provider structures
  - Fills a highly requested integration gap for self-hosted homelab and SMB setups
- Weaknesses:
  - Relies on Uptime Kuma's non-standard API/WebSocket connection, which can be prone to breaking changes
  - Limited documentation compared to official HashiCorp providers

### 4. deploymenttheory/terraform-provider-microsoft365

- Link: https://github.com/deploymenttheory/terraform-provider-microsoft365
- Title: deploymenttheory/terraform-provider-microsoft365
- Description: A community terraform provider for Microsoft 365 for configuration as code workflows. It can interface with both MS Graph v1.0 & MS Graph beta API's. Built upon the terraform provider framework and MS kiota generated gra...
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2024-07-15
- Age: 1 years 11 months
- Last pushed: 2026-06-13
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 9.0/10
- Stars: 53
- Reason: Well-structured Terraform provider for Microsoft 365
- Strengths:
  - Leverages Terraform provider framework
  - Supports MS Graph v1.0 and beta APIs
  - Built with MS Kiota generated Graph SDKs in Go
- Weaknesses:
  - Limited community engagement (53 stars)
  - Dependence on Microsoft APIs and SDKs

### 5. IodeSystems/homelab-horizon

- Link: https://github.com/IodeSystems/homelab-horizon
- Title: IodeSystems/homelab-horizon
- Description: Manage your homelab with one tool: WireGuard VPN, split-horizon DNS, HAProxy reverse proxy with automatic wildcard SSL, and service monitoring on Ubuntu/Debian.
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2026-01-03
- Age: 5 months
- Last pushed: 2026-06-13
- Assessment context: young repo; potential is meaningful but stability is still forming
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 9.0/10
- Stars: 39
- Reason: Comprehensive homelab management with multiple features
- Strengths:
  - Integrates multiple tools for seamless homelab management
  - Automates wildcard SSL with Let's Encrypt
  - Supports split-horizon DNS and WireGuard VPN
- Weaknesses:
  - Limited to Ubuntu/Debian
  - Relatively low number of stars and community engagement

### 6. pulumi/pulumi-pulumiservice

- Link: https://github.com/pulumi/pulumi-pulumiservice
- Title: pulumi/pulumi-pulumiservice
- Description: No description available.
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2022-03-24
- Age: 4 years 2 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 8.0/10
- Small repo potential: 9.0/10
- Stars: 16
- Reason: An official, high-utility Pulumi provider that allows teams to programmatically manage their Pulumi Service resources (like teams, stacks, and webhooks) using Infrastructure as Code.
- Strengths:
  - Official provider maintained by Pulumi
  - Enables GitOps and self-hosting configurations for Pulumi Service itself
  - Robust and well-structured Go codebase
- Weaknesses:
  - Highly specific to users of the managed Pulumi Service (Pulumi Cloud)

### 7. jongwoo328/cloudip

- Link: https://github.com/jongwoo328/cloudip
- Title: jongwoo328/cloudip
- Description: CLI tool to identify whether an IP address belongs to AWS, GCP, or Azure.
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2024-10-26
- Age: 1 years 7 months
- Last pushed: 2026-06-14
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 9.0/10
- Stars: 15
- Reason: Focused and useful CLI tool
- Strengths:
  - Clear and specific purpose
  - Well-defined topics and keywords
- Weaknesses:
  - Limited functionality
  - Small community engagement

### 8. toricls/acos

- Link: https://github.com/toricls/acos
- Title: toricls/acos
- Description: An interactive CLI tool to retrieve and show your AWS costs 💸
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2022-09-17
- Age: 3 years 9 months
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 9.0/10
- Stars: 13
- Reason: Well-defined purpose and focused implementation
- Strengths:
  - Simple and interactive CLI
  - Specific use case for AWS costs
- Weaknesses:
  - Limited to AWS billing
  - Small community

### 9. argoproj-labs/gitops-promoter

- Link: https://github.com/argoproj-labs/gitops-promoter
- Title: argoproj-labs/gitops-promoter
- Description: GitOps Environment Promotion tool that lets you focus on the "what," not the "how"
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2024-04-09
- Age: 2 years 2 months
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 8.0/10
- Stars: 467
- Reason: Focused on environment promotion in GitOps
- Strengths:
  - Solves a specific problem in GitOps
  - Built with Go for performance
- Weaknesses:
  - Limited to Kubernetes environments
  - Dependent on Argo CD

### 10. oneclickvirt/oneclickvirt

- Link: https://github.com/oneclickvirt/oneclickvirt
- Title: oneclickvirt/oneclickvirt
- Description: Universal Virtualization Management Platform 可扩展的通用虚拟化管理平台，支持 Proxmox VE / LXD (GPU) / Incus (GPU) / Docker / Podman / Containerd / Qemu / Kubevirt
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2025-09-23
- Age: 8 months
- Last pushed: 2026-06-14
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 8.0/10
- Stars: 344
- Reason: Comprehensive support for various virtualization platforms
- Strengths:
  - Multi-platform support
  - Extensive topic coverage
  - Written in Go for performance
- Weaknesses:
  - Limited documentation
  - Relatively low star count

### 11. tarmac-project/tarmac

- Link: https://github.com/tarmac-project/tarmac
- Title: tarmac-project/tarmac
- Description: Write as Functions, Deploy as a Monolith or Microservice with WebAssembly
- Category: infrastructure
- Type: framework
- Language: Go
- Created: 2021-05-25
- Age: 5 years
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 7.0/10
- Maturity: 6.0/10
- Small repo potential: 8.0/10
- Stars: 343
- Reason: Unique approach to deploying functions as monoliths or microservices with WebAssembly
- Strengths:
  - Innovative use of WebAssembly
  - Flexible deployment options
  - Written in Go for performance
- Weaknesses:
  - Limited documentation
  - Still evolving with potential breaking changes

### 12. Files-com/files-cli

- Link: https://github.com/Files-com/files-cli
- Title: Files-com/files-cli
- Description: Files.com Command Line App for Windows, Linux, and macOS. Files.com is Cloud Storage, Cloud Gateway, and MFT, All In One. Our built-in storage is fast, affordable, and available in 7 Worldwide Regions. Access Any File on...
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2020-07-31
- Age: 5 years 10 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 7.0/10
- Small repo potential: 8.0/10
- Stars: 46
- Reason: Well-structured Go project for cloud storage management
- Strengths:
  - Multi-platform support
  - Support for various cloud services
  - Built-in storage with 7 worldwide regions
- Weaknesses:
  - Limited community engagement
  - Lack of topics or documentation

### 13. kubevirt/project-infra

- Link: https://github.com/kubevirt/project-infra
- Title: kubevirt/project-infra
- Description: Project infrastructure administrative tools
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2017-07-03
- Age: 8 years 11 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 4.0/10
- Maturity: 7.0/10
- Small repo potential: 8.0/10
- Stars: 41
- Reason: Focused infrastructure tools
- Strengths:
  - Infrastructure-as-code approach
  - Ansible integration
- Weaknesses:
  - Niche use case
  - Limited community engagement

### 14. aystro-com/apod

- Link: https://github.com/aystro-com/apod
- Title: aystro-com/apod
- Description: A single binary that turns any VPS into a hosting platform. Deploy sites, manage domains, handle SSL — all through Docker containers without the overhead of traditional panels. Why apod? Hosting panels are bloated. Paa...
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2026-04-20
- Age: 1 months
- Last pushed: 2026-06-13
- Assessment context: young repo; potential is meaningful but stability is still forming
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 4.0/10
- Small repo potential: 8.0/10
- Stars: 14
- Reason: Simplifies hosting platform setup
- Strengths:
  - Single binary deployment
  - Zero dependencies
  - Docker container management
- Weaknesses:
  - Limited documentation
  - Small community

### 15. hitesh22rana/chronoverse

- Link: https://github.com/hitesh22rana/chronoverse
- Title: hitesh22rana/chronoverse
- Description: Distributed job scheduler & Orchestrator on your infrastructure
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2025-01-26
- Age: 1 years 4 months
- Last pushed: 2026-06-13
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 4.0/10
- Small repo potential: 8.0/10
- Stars: 12
- Reason: Well-structured Go project with clear purpose
- Strengths:
  - Clear documentation
  - Modular design
  - Support for multiple databases and messaging systems
- Weaknesses:
  - Limited community engagement
  - Still in early stages of development

### 16. pulumi/pulumi-oci

- Link: https://github.com/pulumi/pulumi-oci
- Title: pulumi/pulumi-oci
- Description: An Oracle Cloud (OCI) Pulumi resource package, providing multi-language access to OCI
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2022-04-23
- Age: 4 years 1 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 8.0/10
- Small repo potential: 7.0/10
- Stars: 39
- Reason: Provides multi-language access to OCI
- Strengths:
  - Multi-language support
  - Official Pulumi resource package
- Weaknesses:
  - Limited community engagement
  - Niche use case

### 17. conda-forge/feedstocks

- Link: https://github.com/conda-forge/feedstocks
- Title: conda-forge/feedstocks
- Description: All conda-forge feedstocks, in one convenient place
- Category: infrastructure
- Type: tool
- Created: 2016-01-13
- Age: 10 years 5 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 2.0/10
- Maturity: 9.0/10
- Small repo potential: 6.0/10
- Stars: 71
- Reason: Centralized feedstock repository
- Strengths:
  - Convenient packaging
  - Large collection of feedstocks
- Weaknesses:
  - Limited innovation
  - Dependent on conda-forge ecosystem

### 18. pulumi/pulumi-github

- Link: https://github.com/pulumi/pulumi-github
- Title: pulumi/pulumi-github
- Description: A Pulumi package to facilitate interacting with GitHub
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2017-06-12
- Age: 9 years
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 4.0/10
- Maturity: 8.0/10
- Small repo potential: 6.0/10
- Stars: 70
- Reason: Focused GitHub integration for Pulumi
- Strengths:
  - Specific use case
  - Established owner
- Weaknesses:
  - Limited scope
  - Dependent on Pulumi

### 19. mondoohq/mql

- Link: https://github.com/mondoohq/mql
- Title: mondoohq/mql
- Description: open source, cloud-native, graph-based query language
- Category: infrastructure
- Type: framework
- Language: Go
- Created: 2022-08-16
- Age: 3 years 10 months
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 7.0/10
- Maturity: 6.0/10
- Small repo potential: 4.0/10
- Stars: 402
- Reason: Well-structured cloud-native graph query language
- Strengths:
  - Cloud-agnostic support
  - Graph-based query capabilities
  - Security-as-code features
- Weaknesses:
  - Limited documentation
  - Relatively small community

### 20. pulumi/pulumi-gcp

- Link: https://github.com/pulumi/pulumi-gcp
- Title: pulumi/pulumi-gcp
- Description: A Google Cloud Platform (GCP) Pulumi resource package, providing multi-language access to GCP
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2017-07-17
- Age: 8 years 11 months
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 8.0/10
- Small repo potential: 4.0/10
- Stars: 212
- Reason: Well-maintained GCP resource package
- Strengths:
  - Multi-language support
  - Official Pulumi package
- Weaknesses:
  - Limited to GCP ecosystem

### 21. KDE/akonadi

- Link: https://github.com/KDE/akonadi
- Title: KDE/akonadi
- Description: Cross-desktop storage service for PIM data providing concurrent access
- Category: infrastructure
- Type: library
- Language: C++
- Created: 2015-09-18
- Age: 10 years 9 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 6.0/10
- Maturity: 9.0/10
- Small repo potential: 4.0/10
- Stars: 34
- Reason: Established PIM data storage solution
- Strengths:
  - Cross-desktop compatibility
  - Concurrent access support
  - Mature codebase
- Weaknesses:
  - Limited community engagement
  - Narrow focus on PIM data

### 22. pulumi/pulumi-cloudflare

- Link: https://github.com/pulumi/pulumi-cloudflare
- Title: pulumi/pulumi-cloudflare
- Description: Pulumi's Cloudflare package, providing multi-language infrastructure as code for Cloudflare
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2019-03-04
- Age: 7 years 3 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 5.0/10
- Maturity: 9.0/10
- Small repo potential: 3.0/10
- Stars: 150
- Reason: Official Pulumi provider for Cloudflare, offering robust, multi-language infrastructure-as-code capabilities bridged from the Terraform provider.
- Strengths:
  - Official Pulumi support and active maintenance
  - Supports multiple languages including TypeScript, Python, Go, and .NET
  - Kept up-to-date with Cloudflare's API via the upstream Terraform bridge
- Weaknesses:
  - Inherits upstream bridge limitations and potential translation issues
  - Primarily a generated wrapper rather than a native implementation

### 23. pulumi/pulumi-azuread

- Link: https://github.com/pulumi/pulumi-azuread
- Title: pulumi/pulumi-azuread
- Description: A Microsoft Azure Active Directory (Azure AD) Pulumi resource package, providing multi-language access to Azure AD
- Category: infrastructure
- Type: library
- Language: Go
- Created: 2019-04-25
- Age: 7 years 1 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 8.0/10
- Novelty: 5.0/10
- Maturity: 9.0/10
- Small repo potential: 3.0/10
- Stars: 21
- Reason: An essential, officially maintained Pulumi provider for managing Azure Active Directory (Entra ID) resources programmatically across multiple languages.
- Strengths:
  - Official, production-grade Pulumi provider
  - Supports TypeScript, Python, Go, and C#
  - Maintained and kept up-to-date with upstream changes
- Weaknesses:
  - Largely auto-generated code based on upstream Terraform providers
  - Low direct repository engagement as users consume it packaged via package managers

### 24. garybowers/bootimus

- Link: https://github.com/garybowers/bootimus
- Title: garybowers/bootimus
- Description: A Complete enhanced version of the PXE server supporting booting from ISOs written in Golang and Deployable via containers or binaries.
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2025-12-27
- Age: 5 months
- Last pushed: 2026-06-14
- Assessment context: young repo; potential is meaningful but stability is still forming
- Score: 7.0/10
- Novelty: 6.0/10
- Maturity: 5.0/10
- Small repo potential: 9.0/10
- Stars: 118
- Reason: An elegant, containerizable Go-based PXE server that simplifies network booting from ISOs, addressing a common pain point for homelabs and bare-metal provisioning.
- Strengths:
  - All-in-one DHCP, TFTP, and HTTP server designed to ease ISO booting
  - Containerized deployment model makes it highly portable
  - Supports both legacy BIOS and UEFI architectures
- Weaknesses:
  - Niche audience as modern infrastructure shifts toward HTTP Boot and cloud-init
  - Limited community scale and enterprise-grade testing

### 25. home-operations/flate

- Link: https://github.com/home-operations/flate
- Title: home-operations/flate
- Description: A Flux resource inflator ⇄
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2026-05-21
- Age: 24 days
- Last pushed: 2026-06-13
- Assessment context: very young repo; promising signals need extra validation
- Score: 7.0/10
- Novelty: 6.0/10
- Maturity: 8.0/10
- Small repo potential: 9.0/10
- Stars: 45
- Reason: Focused Flux resource inflator with clear purpose
- Strengths:
  - Specific use case
  - Clear description
  - Small and maintainable codebase
- Weaknesses:
  - Limited scope
  - Dependence on Flux ecosystem

### 26. 0xjeffro/astroclaw

- Link: https://github.com/0xjeffro/astroclaw
- Title: 0xjeffro/astroclaw
- Description: Cloud-native agent-as-a-service framework with one-click IaC deployment.
- Category: infrastructure
- Type: framework
- Language: Go
- Created: 2026-03-27
- Age: 2 months
- Last pushed: 2026-06-13
- Assessment context: young repo; potential is meaningful but stability is still forming
- Score: 7.0/10
- Novelty: 6.0/10
- Maturity: 5.0/10
- Small repo potential: 8.0/10
- Stars: 174
- Reason: Well-structured Go codebase
- Strengths:
  - Cloud-native design
  - One-click IaC deployment
- Weaknesses:
  - Limited documentation
  - Unclear use cases

### 27. GustavoCaso/docker-dash

- Link: https://github.com/GustavoCaso/docker-dash
- Title: GustavoCaso/docker-dash
- Description: A full TUI managemnet tool for containers 🏗️
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2026-02-08
- Age: 4 months
- Last pushed: 2026-06-14
- Assessment context: young repo; potential is meaningful but stability is still forming
- Score: 7.0/10
- Novelty: 6.0/10
- Maturity: 4.0/10
- Small repo potential: 8.0/10
- Stars: 14
- Reason: Well-structured TUI management tool for containers
- Strengths:
  - Simple and focused functionality
  - Uses established TUI library (bubbletea)
- Weaknesses:
  - Limited features compared to established tools
  - Small community

### 28. ZaparooProject/zaparoo-core

- Link: https://github.com/ZaparooProject/zaparoo-core
- Title: ZaparooProject/zaparoo-core
- Description: Core Zaparoo service software
- Category: infrastructure
- Type: app
- Language: Go
- Created: 2024-01-02
- Age: 2 years 5 months
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 6.0/10
- Novelty: 4.0/10
- Maturity: 7.0/10
- Small repo potential: 8.0/10
- Stars: 168
- Reason: Lack of topics and low star count despite mature codebase
- Strengths:
  - mature Go codebase
- Weaknesses:
  - limited community engagement

### 29. github/gh-aw-mcpg

- Link: https://github.com/github/gh-aw-mcpg
- Title: github/gh-aw-mcpg
- Description: Github Agentic Workflows MCP Gateway
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2025-12-10
- Age: 6 months
- Last pushed: 2026-06-13
- Assessment context: established enough for stronger comparison, but maintenance trend still matters
- Score: 6.0/10
- Novelty: 4.0/10
- Maturity: 7.0/10
- Small repo potential: 8.0/10
- Stars: 133
- Reason: Lack of topics and documentation
- Strengths:
  - Written in Go
  - Specific use case
- Weaknesses:
  - Limited information available
  - Low community engagement

### 30. rwlove/home-ops

- Link: https://github.com/rwlove/home-ops
- Title: rwlove/home-ops
- Description: Lovenet Cluster Configuration
- Category: infrastructure
- Type: example
- Language: YAML
- Created: 2021-03-09
- Age: 5 years 3 months
- Last pushed: 2026-06-14
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 6.0/10
- Novelty: 2.0/10
- Maturity: 4.0/10
- Small repo potential: 8.0/10
- Stars: 18
- Reason: Well-structured Kubernetes configuration
- Strengths:
  - Clear YAML configuration
  - Specific use case
- Weaknesses:
  - Limited scope
  - Dependence on specific tools

### 31. openshift-kni/oran-o2ims

- Link: https://github.com/openshift-kni/oran-o2ims
- Title: openshift-kni/oran-o2ims
- Description: No description available.
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2023-10-31
- Age: 2 years 7 months
- Last pushed: 2026-06-13
- Assessment context: older repo; long-term activity and recent maintenance matter more than age alone
- Score: 6.0/10
- Novelty: 4.0/10
- Maturity: 6.0/10
- Small repo potential: 8.0/10
- Stars: 14
- Reason: Strong foundation despite small size
- Strengths:
  - Written in Go
  - Focused on OpenShift and ORAN integration
- Weaknesses:
  - Limited community engagement
  - Lack of documentation

### 32. caic-xyz/caic

- Link: https://github.com/caic-xyz/caic
- Title: caic-xyz/caic
- Description: Coding Agents in Containers
- Category: infrastructure
- Type: tool
- Language: Go
- Created: 2026-02-06
- Age: 4 months
- Last pushed: 2026-06-13
- Assessment context: young repo; potential is meaningful but stability is still forming
- Score: 6.0/10
- Novelty: 4.0/10
- Maturity: 3.0/10
- Small repo potential: 8.0/10
- Stars: 12
- Reason: Clear concept, but lacks documentation and community engagement
- Strengths:
  - Unique approach to coding agents
- Weaknesses:
  - Limited topics and low star count

