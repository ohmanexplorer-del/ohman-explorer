# infrastructure-as-code

Curated projects in this category.

Note: young repositories can show strong potential but still carry higher stability and maintenance risk.

### 1. pulumi/pulumi-command

- Link: https://github.com/pulumi/pulumi-command
- Title: pulumi/pulumi-command
- Description: No description available.
- Category: infrastructure-as-code
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

### 2. breml/terraform-provider-uptimekuma

- Link: https://github.com/breml/terraform-provider-uptimekuma
- Title: breml/terraform-provider-uptimekuma
- Description: Terraform provider for uptime kuma
- Category: infrastructure-as-code
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

### 3. deploymenttheory/terraform-provider-microsoft365

- Link: https://github.com/deploymenttheory/terraform-provider-microsoft365
- Title: deploymenttheory/terraform-provider-microsoft365
- Description: A community terraform provider for Microsoft 365 for configuration as code workflows. It can interface with both MS Graph v1.0 & MS Graph beta API's. Built upon the terraform provider framework and MS kiota generated gra...
- Category: infrastructure-as-code
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

### 4. pulumi/pulumi-pulumiservice

- Link: https://github.com/pulumi/pulumi-pulumiservice
- Title: pulumi/pulumi-pulumiservice
- Description: No description available.
- Category: infrastructure-as-code
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

### 5. pulumi/pulumi-cloudflare

- Link: https://github.com/pulumi/pulumi-cloudflare
- Title: pulumi/pulumi-cloudflare
- Description: Pulumi's Cloudflare package, providing multi-language infrastructure as code for Cloudflare
- Category: infrastructure-as-code
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

### 6. pulumi/pulumi-azuread

- Link: https://github.com/pulumi/pulumi-azuread
- Title: pulumi/pulumi-azuread
- Description: A Microsoft Azure Active Directory (Azure AD) Pulumi resource package, providing multi-language access to Azure AD
- Category: infrastructure-as-code
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

