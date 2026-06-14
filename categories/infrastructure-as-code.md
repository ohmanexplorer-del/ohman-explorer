# infrastructure-as-code

Curated projects in this category.

### 1. pulumi/pulumi-command

- Link: https://github.com/pulumi/pulumi-command
- Title: pulumi/pulumi-command
- Description: No description available.
- Category: infrastructure-as-code
- Type: library
- Language: Go
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

### 2. pulumi/pulumi-azuread

- Link: https://github.com/pulumi/pulumi-azuread
- Title: pulumi/pulumi-azuread
- Description: A Microsoft Azure Active Directory (Azure AD) Pulumi resource package, providing multi-language access to Azure AD
- Category: infrastructure-as-code
- Type: library
- Language: Go
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

