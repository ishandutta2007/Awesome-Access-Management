# Awesome-Access-Management

## Similar Projects to Access Management Platforms

**Access Management / Identity and Access Management (IAM)** platforms provide Single Sign-On (SSO), multi-factor authentication (MFA), user lifecycle management, directory services, federation (SAML, OIDC), and fine-grained access control for workforce and customer identities. Leading commercial tools include Okta, Microsoft Entra ID, JumpCloud, OneLogin, Ping Identity, ForgeRock, Auth0, WorkOS, Frontegg, and ManageEngine ADSelfService Plus.

Below is a **curated list** of notable platforms and their open-source equivalents. The open-source ecosystem for identity is mature and production-ready, with several projects serving as direct alternatives to commercial IAM suites.

## 🏢 SaaS / Hosted Platforms

- **[Okta](https://www.okta.com/)** — Leading cloud identity platform for workforce and customer identity, SSO, MFA, and lifecycle management.
- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)** (formerly Azure AD) — Microsoft’s cloud identity and access management service, deeply integrated with Microsoft 365 and Azure.
- **[JumpCloud](https://jumpcloud.com/)** — Cloud directory platform that unifies identity, access, and device management.
- **[OneLogin](https://www.onelogin.com/)** — Cloud-based IAM solution focused on SSO, MFA, and directory integration.
- **[Ping Identity](https://www.pingidentity.com/)** — Enterprise identity security platform with strong federation and access management capabilities.
- **[ForgeRock](https://www.forgerock.com/)** — Comprehensive identity platform for large-scale workforce and customer identity use cases.
- **[Auth0](https://auth0.com/)** (Okta) — Developer-friendly identity platform for authentication and authorization in applications.
- **[WorkOS](https://workos.com/)** — Platform that helps SaaS companies add enterprise features (SSO, Directory Sync, etc.).
- **[Frontegg](https://frontegg.com/)** — User management and authentication platform aimed at SaaS applications.
- **[ManageEngine ADSelfService Plus](https://www.manageengine.com/products/self-service-password/)** — Self-service password management and identity-related tools, often used alongside Active Directory.

## 🔓 Open-Source Software

### Full-Featured Identity Providers
- **[Keycloak](https://github.com/keycloak/keycloak)** — The most mature and widely deployed open-source IAM solution (Apache 2.0). Supports OIDC, OAuth 2.0, SAML, LDAP/AD federation, fine-grained authorization, user federation, and social login. Backed by a large community (originally Red Hat).
- **[Authentik](https://github.com/goauthentik/authentik)** — Modern, flexible open-source identity provider with excellent UX, forward-auth support, LDAP/SCIM, and strong self-hosting experience (MIT core).
- **[ZITADEL](https://github.com/zitadel/zitadel)** — Cloud-native, API-first identity platform with native multi-tenancy, event sourcing, and strong support for B2B SaaS use cases (Apache 2.0).
- **[Ory](https://github.com/ory)** (Hydra, Kratos, Oathkeeper, Keto) — Modular, cloud-native identity stack. Highly flexible and API-first; popular for teams that want to build custom identity experiences.
- **[SuperTokens](https://github.com/supertokens/supertokens-core)** — Open-source authentication solution focused on developer experience, session management, and self-hosting (with optional managed cloud).

### Lightweight & Specialized SSO / Auth Tools
- **[Authelia](https://github.com/authelia/authelia)** — Lightweight authentication and authorization server designed for reverse-proxy SSO and 2FA (Apache 2.0). Excellent for protecting internal services.
- **[Logto](https://github.com/logto-io/logto)** — Modern open-source CIAM / identity platform with great developer experience and pre-built UI components.
- **[Casdoor](https://github.com/casdoor/casdoor)** — UI-first Identity and Access Management / SSO platform with support for multiple protocols.
- **[Kanidm](https://github.com/kanidm/kanidm)** — Modern, secure identity management system written in Rust, focused on simplicity and security.

### Enterprise & Directory-Focused
- **[FreeIPA](https://www.freeipa.org/)** — Open-source identity management solution integrating LDAP, Kerberos, DNS, and certificate management (common in Linux environments).
- **[WSO2 Identity Server](https://github.com/wso2/product-is)** — Full-featured open-source IAM platform supporting a wide range of standards (SAML, OIDC, SCIM, XACML, etc.).
- **Gluu / Janssen Project** — Long-standing open-source digital identity platform with strong federation capabilities.

### Typical Open-Source Stack
Many organizations combine:
1. **Primary IdP** — Keycloak, Authentik, or ZITADEL
2. **Lightweight protection** — Authelia in front of internal apps
3. **Directory** — FreeIPA or existing LDAP/AD
4. **Standards layer** — OpenID Connect / SAML for application integration

These solutions provide full data ownership, no per-user licensing fees, and production-grade features that can replace or significantly reduce reliance on commercial IAM platforms.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects for identity, SSO, authentication, or access management.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open-source identity tooling gives organizations real control over authentication and access! 🔐
