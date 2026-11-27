# Awesome-Identity-Access-Management-IAM-SSO

# Awesome-Identity-Access-Management-IAM-SSO



Top Identity Access Management IAM SSO (Opensource) 🌟 Star if you like it! 🌟



A curated list of top Identity & Access Management (IAM), Single Sign-On (SSO), Customer Identity (CIAM), Multi-Factor Authentication (MFA), OAuth2/OIDC providers, and Privileged Access Management (PAM) platforms—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [Full-Featured Enterprise IAM & SSO Identity Providers](#full-featured-enterprise-iam--sso-identity-providers)

  - [Modern Lightweight Self-Hosted SSO & Reverse-Proxy Auth](#modern-lightweight-self-hosted-sso--reverse-proxy-auth)

  - [Developer-First CIAM, OAuth2 & OIDC Servers](#developer-first-ciam-oauth2--oidc-servers)

  - [Multi-Factor Authentication (MFA) & Passkey/WebAuthn Tools](#multi-factor-authentication-mfa--passkeywebauthn-tools)

  - [Privileged Access Management (PAM) & Identity Governance (IGA)](#privileged-access-management-pam--identity-governance-iga)

  - [Directory Services & LDAP / Active Directory Alternatives](#directory-services--ldap--active-directory-alternatives)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, cloud-hosted enterprise identity providers, managed CIAM APIs, cloud directory services, and proprietary PAM/MFA suites.



* **[Okta](https://okta.com)** - Market-leading cloud Identity-as-a-Service (IDaaS) platform providing workforce SSO, universal directory, lifecycle management, and adaptive MFA.

* **[Microsoft Entra ID (formerly Azure AD)](https://microsoft.com)** - Enterprise cloud identity and access management service tightly integrated with Microsoft 365, Azure, and Conditional Access policies.

* **[Ping Identity](https://pingidentity.com)** - Enterprise hybrid and cloud identity security platform supporting complex federation, OAuth/OIDC, SAML, and zero-trust access.

* **[CyberArk](https://cyberark.com)** - Industry-standard proprietary Privileged Access Management (PAM) and identity security platform protecting high-privilege credentials and sessions.

* **[OneLogin](https://onelogin.com)** - Cloud-based unified access management platform offering enterprise SSO, smart-factor authentication, and automated user provisioning.

* **[ForgeRock (Ping Identity)](https://forgerock.com)** - Enterprise digital identity platform for large-scale workforce, consumer, and IoT identity orchestration.

* **[Auth0 (by Okta)](https://auth0.com)** - Developer-centric managed authentication and authorization platform for rapid B2C, B2B, and SaaS CIAM integration.

* **[JumpCloud](https://jumpcloud.com)** - Open cloud directory platform unifying device management (MDM), RADIUS, LDAP, SAML SSO, and multi-OS user authentication.

* **[Cisco Duo Security](https://duo.com)** - Cloud-based zero-trust access security and Multi-Factor Authentication (MFA) provider verifying user identity and device health.

* **[SecureAuth](https://secureauth.com)** - Commercial adaptive authentication and passwordless CIAM/workforce identity platform with behavioral risk scoring.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) identity providers, self-hosted SSO portals, OAuth2/OIDC engines, passwordless authentication servers, and PAM/IGA suites.



### Full-Featured Enterprise IAM & SSO Identity Providers



* **[authentik](https://github.com)** - Open-source, modern Identity Provider emphasizing flexibility and versatility with SAML, OAuth2/OIDC, LDAP, SCIM, and forward-auth proxy support.

* **[Keycloak](https://github.com)** - CNCF-incubating open-source Identity and Access Management solution for modern applications and services supporting OIDC, OAuth 2.0, SAML 2.0, and social login.

* **[ZITADEL](https://github.com)** - Cloud-native, open-source identity infrastructure written in Go featuring event-sourced audit trails, multi-tenancy, B2B delegation, and passkeys.

* **[Casdoor](https://github.com)** - UI-first open-source Identity and Access Management (IAM) / Single-Sign-On (SSO) platform built on Casbin supporting OAuth 2.0, OIDC, SAML, and CAS.

* **[WSO2 Identity Server](https://github.com)** - Extensible, API-driven open-source IAM and CIAM server supporting enterprise federation, adaptive auth, and privacy compliance.

* **[Gluu Server / Janssen Project](https://github.com)** - Linux Foundation open-source cloud-native identity and access management platform built for high-scale OAuth, OIDC, and FIDO2 deployments.



### Modern Lightweight Self-Hosted SSO & Reverse-Proxy Auth



* **[Authelia](https://github.com)** - Open-source authentication and authorization server providing 2FA and SSO for self-hosted applications via reverse proxies (Traefik, Nginx, Caddy).

* **[Pocket ID](https://github.com)** - Simple, lightweight open-source OIDC provider engineered exclusively around passwordless Passkeys/WebAuthn authentication.

* **[Tinyauth](https://github.com)** - Minimalist, ultra-lightweight authentication middleware protecting Docker and reverse-proxy apps with simple login screens or OAuth.

* **[OAuth2 Proxy](https://github.com)** - Reverse proxy and static file server providing authentication using providers like Google, GitHub, Keycloak, and OIDC.

* **[Pomerium](https://github.com)** - Open-source identity-aware access proxy enforcing zero-trust, context-aware access policies without requiring a corporate VPN.



### Developer-First CIAM, OAuth2 & OIDC Servers



* **[Ory Hydra & Ory Kratos](https://github.com)** - Certified, cloud-native open-source OAuth 2.0 & OpenID Connect provider (Hydra) paired with a headless identity/user management system (Kratos).

* **[Logto](https://github.com)** - Modern open-source alternative to Auth0 offering passwordless sign-in, RBAC, multi-tenancy organizations, and SDKs for web and mobile apps.

* **[SuperTokens](https://github.com)** - Open-source user authentication solution providing session management, social login, passwordless, and multi-tenant B2B flows.

* **[Hanko](https://github.com)** - Open-source authentication and user management solution built around FIDO2/WebAuthn passkeys and modern frontend web components.

* **[Dex](https://github.com)** - Federated OpenID Connect provider acting as a portal to external identity sources (LDAP, SAML, GitHub, GitLab) for Kubernetes and cloud apps.

* **[Kanidm](https://github.com)** - Modern, simple, and ultra-secure identity management platform written in Rust with native Passkeys, OAuth2, LDAP, and POSIX/SSH integration.



### Multi-Factor Authentication (MFA) & Passkey/WebAuthn Tools



* **[privacyIDEA](https://github.com)** - Modular, open-source multi-factor authentication server supporting OTP tokens, FIDO2/WebAuthn, push notifications, and RADIUS/PAM.

* **[LinOTP](https://github.com)** - Flexible open-source enterprise solution for two-factor authentication with one-time passwords and hardware tokens.

* **[2FAuth](https://github.com)** - Self-hosted open-source web app for managing Two-Factor Authentication (TOTP/HOTP) accounts and generating security codes across devices.



### Privileged Access Management (PAM) & Identity Governance (IGA)



* **[Teleport (Community Edition)](https://github.com)** - Open-source identity-native infrastructure access plane replacing SSH keys, VPNs, and static credentials with short-lived certificates.

* **[JumpServer](https://github.com)** - Popular open-source Privileged Access Management (PAM) bastion host supporting SSH, RDP, Kubernetes, and database session auditing.

* **[Apache Syncope](https://github.com)** - Open-source enterprise system for managing digital identities, provisioning, reconciliation, and Identity Governance (IGA).

* **[MidPoint (Evolveum)](https://github.com)** - Comprehensive open-source Identity Governance and Administration (IGA) platform for lifecycle workflows, RBAC, and compliance.



### Directory Services & LDAP / Active Directory Alternatives



* **[FreeIPA](https://github.com)** - Integrated open-source security information management solution combining Linux (Fedora/RHEL), 389 Directory Server, MIT Kerberos, NTP, DNS, and Dogtag CA.

* **[Samba Active Directory](https://github.com)** - Open-source software suite providing full Active Directory Domain Controller compatibility, Kerberos, LDAP, and SMB/CIFS services.

* **[LLDAP (Light LDAP)](https://github.com)** - Opinionated, lightweight open-source LDAP implementation designed specifically for easy user management and self-hosted authentication.

* **[OpenLDAP](https://openldap.org)** - Mature, high-performance open-source implementation of the Lightweight Directory Access Protocol.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source IAM platforms, OIDC/OAuth2 providers, PAM bastion hosts, or directory services.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
