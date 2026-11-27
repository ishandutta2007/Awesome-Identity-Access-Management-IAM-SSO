# Awesome Identity & Access Management (IAM) & SSO 🔐

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Identity and Access Management IAM SSO Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO?style=flat-square&logo=github&color=gold" alt="GitHub Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO?style=flat-square&logo=github&color=blue" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO?style=flat-square" alt="Issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🌟 **A curated list of top Identity & Access Management (IAM), Single Sign-On (SSO), Customer Identity & Access Management (CIAM), Multi-Factor Authentication (MFA), OAuth2/OIDC servers, Passkeys/FIDO2, and Privileged Access Management (PAM) architectures.** Features enterprise SaaS leaders alongside vetted open-source alternatives.

---

## 📑 Table of Contents
- [🌐 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Hosted Enterprise Platforms](#-saas--hosted-enterprise-platforms)
- [🔓 Open-Source Equivalents & Tools](#-open-source-equivalents--tools)
  - [🛡️ Full-Featured Enterprise IAM & SSO Identity Providers](#️-full-featured-enterprise-iam--sso-identity-providers)
  - [⚡ Modern Lightweight Self-Hosted SSO & Reverse-Proxy Auth](#-modern-lightweight-self-hosted-sso--reverse-proxy-auth)
  - [💻 Developer-First CIAM, OAuth2 & OIDC Servers](#-developer-first-ciam-oauth2--oidc-servers)
  - [🔑 Multi-Factor Authentication (MFA) & Passkey/WebAuthn Tools](#-multi-factor-authentication-mfa--passkeywebauthn-tools)
  - [🏰 Privileged Access Management (PAM) & Identity Governance (IGA)](#-privileged-access-management-pam--identity-governance-iga)
  - [📂 Directory Services & LDAP / Active Directory Alternatives](#-directory-services--ldap--active-directory-alternatives)
- [📈 Star History](#-star-history)
- [🤝 Contributing](#-contributing)
- [💖 Support & Sponsorship](#-support--sponsorship)

---

## 🌐 Sector Overview & Market Dynamics

The global **Identity and Access Management (IAM)** market is estimated at **$21 billion to $27 billion** (expanding at an annualized CAGR of **11%–15%** towards $45B+). The sector exhibits a **moderately concentrated, top-heavy structure** where hyperscalers and specialized cybersecurity giants (such as Microsoft, Okta, CyberArk, and Cisco) capture the majority of high-contract enterprise workforce and PAM budgets, yet it remains **dynamically fragmented across emerging sub-segments**—particularly developer-first CIAM, passwordless/Passkey infrastructure, zero-trust reverse proxies, and Kubernetes-native authorization engines where nimble open-source solutions frequently win out.

---

## 🏢 SaaS & Hosted Enterprise Platforms

Commercial, cloud-hosted enterprise identity providers, managed CIAM APIs, cloud directory services, and proprietary PAM/MFA suites, sorted descending by company size (valuation / annual revenue).

| Platform | Description | Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Entra ID](https://microsoft.com)** | Enterprise cloud identity and access management service tightly integrated with Microsoft 365, Azure, and Conditional Access policies. | **$3.1T+ Valuation** ($245B+ Annual Revenue) | **$7.00 / user / month** (Entra ID P1; billed annually) | **Permanent Free Tier** (bundled with Microsoft Azure/365 cloud subscriptions; includes basic SSO & Security Defaults MFA; External ID free up to 50,000 MAU) |
| **[Cisco Duo Security](https://duo.com)** | Cloud-based zero-trust access security and Multi-Factor Authentication (MFA) provider verifying user identity and device health. | **$235B+ Valuation** ($53.8B+ Annual Revenue) | **$3.00 / user / month** (Duo Essentials; billed annually) | **Permanent Free Tier** (up to 10 users max; includes basic MFA & Duo Mobile app) / 30-day full-feature free trial |
| **[CyberArk](https://cyberark.com)** | Industry-standard proprietary Privileged Access Management (PAM) and identity security platform protecting high-privilege credentials and sessions. | **$15B+ Valuation** ($1.0B+ Annual Revenue) | **~$3,726 / month** ($44,712/year minimum for Privilege Cloud starter bundle of 25 users, ~$1,788/user/yr) | **No Permanent Free Tier** (14 to 30-day guided enterprise Proof of Concept / trial via sales request, scoped to evaluation environment) |
| **[Okta](https://okta.com)** | Market-leading cloud Identity-as-a-Service (IDaaS) platform providing workforce SSO, universal directory, lifecycle management, and adaptive MFA. | **$15B+ Valuation** ($2.6B+ Annual Revenue) | **$6.00 / user / month** (Starter Suite; billed annually, $1,500 annual minimum spend floor) | **No Permanent Workforce Free Tier** (Developer integrator plan free up to 10 active users; Workforce platform offers a 30-day free trial limited to 10 users, 1 admin, and 5 workflows) |
| **[Auth0 (by Okta)](https://auth0.com)** | Developer-centric managed authentication and authorization platform for rapid B2C, B2B, and SaaS CIAM integration. | **$6.5B Valuation** (Acquired by Okta; part of Okta's $2.6B+ ARR) | **$35.00 / month** (B2C Essentials, 500 MAU tier) / **$150.00 / month** (B2B Essentials, 500 MAU tier) | **Permanent Free Tier** (up to 25,000 Monthly Active Users (MAUs), 5 organizations, 1 enterprise SAML/OIDC connection, unlimited social connections) |
| **[Ping Identity](https://pingidentity.com)** | Enterprise hybrid and cloud identity security platform supporting complex federation, OAuth/OIDC, SAML, and zero-trust access. | **$2.8B Valuation** (Acquired by Thoma Bravo; combined Ping/ForgeRock ARR ~$1B) | **$3.00 / user / month** (PingOne Workforce Essential; typically 5,000 user contract minimum) | **No Permanent Free Tier** (30-day free trial via PingOne, limited to 5 environments and up to 1,000 active test identities) |
| **[JumpCloud](https://jumpcloud.com)** | Open cloud directory platform unifying device management (MDM), RADIUS, LDAP, SAML SSO, and multi-OS user authentication. | **$2.6B Valuation** (~$200M Annual Recurring Revenue) | **$9.00 / user / month** (Device Management; billed annually) / **$11.00 / user / month** (SSO Plan) | **No Permanent Free Tier for New Accounts** (30-day unrestricted free trial with full platform access; legacy free tier up to 10 users/devices grandfathered pre-Feb 2024) |
| **[ForgeRock (Ping Identity)](https://forgerock.com)** | Enterprise digital identity platform for large-scale workforce, consumer, and IoT identity orchestration. | **$2.3B Valuation** (Acquired by Thoma Bravo; integrated into Ping Identity) | **~$2,916 / month** (~$35,000/year enterprise base package minimum) | **No Permanent Free Tier** (30-day Proof of Concept / sandbox evaluation trial via sales engagement) |
| **[OneLogin](https://onelogin.com)** | Cloud-based unified access management platform offering enterprise SSO, smart-factor authentication, and automated user provisioning. | **$500M Valuation** (Acquired by One Identity/Quest; parent valuation $5.4B) | **$2.00 / user / month** (Starter plan; billed annually) | **No Permanent Free Tier** (30-day free trial, no credit card required, includes core SSO, MFA, and cloud directory) |
| **[SecureAuth](https://secureauth.com)** | Commercial adaptive authentication and passwordless CIAM/workforce identity platform with behavioral risk scoring. | **$225M Valuation** (~$44M - $95M Annual Revenue) | **$1.00 / user / month** (Baseline entry tier index; sales-quoted annual contract) | **No Permanent Free Tier** (14 to 30-day production-ready tenant free trial / POC without credit card) |

---

## 🔓 Open-Source Equivalents & Tools

Free and open-source software (FOSS) identity providers, self-hosted SSO portals, OAuth2/OIDC engines, passwordless authentication servers, and PAM/IGA suites. Repositories in each category are ranked and sorted in descending order by GitHub star count.

### 🛡️ Full-Featured Enterprise IAM & SSO Identity Providers

* **[Keycloak](https://github.com/keycloak/keycloak)** [![GitHub Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) - CNCF-incubating open-source Identity and Access Management solution for modern applications and services supporting OIDC, OAuth 2.0, SAML 2.0, and social login.
* **[authentik](https://github.com/goauthentik/authentik)** [![GitHub Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers) - Open-source, modern Identity Provider emphasizing flexibility and versatility with SAML, OAuth2/OIDC, LDAP, SCIM, and forward-auth proxy support.
* **[ZITADEL](https://github.com/zitadel/zitadel)** [![GitHub Stars](https://img.shields.io/github/stars/zitadel/zitadel?style=social&color=white)](https://github.com/zitadel/zitadel/stargazers) - Cloud-native, open-source identity infrastructure written in Go featuring event-sourced audit trails, multi-tenancy, B2B delegation, and passkeys.
* **[Casdoor](https://github.com/casbin/casdoor)** [![GitHub Stars](https://img.shields.io/github/stars/casbin/casdoor?style=social&color=white)](https://github.com/casbin/casdoor/stargazers) - UI-first open-source Identity and Access Management (IAM) / Single-Sign-On (SSO) platform built on Casbin supporting OAuth 2.0, OIDC, SAML, and CAS.
* **[Apereo CAS](https://github.com/apereo/cas)** [![GitHub Stars](https://img.shields.io/github/stars/apereo/cas?style=social&color=white)](https://github.com/apereo/cas/stargazers) - Enterprise multilingual Single Sign-On solution supporting CAS protocol, SAML, OAuth 2.0, OpenID Connect, and multifactor authentication.
* **[WSO2 Identity Server](https://github.com/wso2/product-is)** [![GitHub Stars](https://img.shields.io/github/stars/wso2/product-is?style=social&color=white)](https://github.com/wso2/product-is/stargazers) - Extensible, API-driven enterprise open-source IAM and CIAM server supporting federation, adaptive auth, and compliance.
* **[Gluu Server / Janssen Project](https://github.com/JanssenProject/jans)** [![GitHub Stars](https://img.shields.io/github/stars/JanssenProject/jans?style=social&color=white)](https://github.com/JanssenProject/jans/stargazers) - Linux Foundation open-source cloud-native identity and access management platform built for high-scale OAuth, OIDC, and FIDO2.

### ⚡ Modern Lightweight Self-Hosted SSO & Reverse-Proxy Auth

* **[Authelia](https://github.com/authelia/authelia)** [![GitHub Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white)](https://github.com/authelia/authelia/stargazers) - Open-source authentication and authorization server providing 2FA and SSO for self-hosted applications via reverse proxies (Traefik, Nginx, Caddy).
* **[OAuth2 Proxy](https://github.com/oauth2-proxy/oauth2-proxy)** [![GitHub Stars](https://img.shields.io/github/stars/oauth2-proxy/oauth2-proxy?style=social&color=white)](https://github.com/oauth2-proxy/oauth2-proxy/stargazers) - Reverse proxy and static file server providing authentication using providers like Google, GitHub, Keycloak, and OIDC.
* **[Pocket ID](https://github.com/pocket-id/pocket-id)** [![GitHub Stars](https://img.shields.io/github/stars/pocket-id/pocket-id?style=social&color=white)](https://github.com/pocket-id/pocket-id/stargazers) - Simple, lightweight open-source OIDC provider engineered exclusively around passwordless Passkeys/WebAuthn authentication.
* **[Tinyauth](https://github.com/steveiliop56/tinyauth)** [![GitHub Stars](https://img.shields.io/github/stars/steveiliop56/tinyauth?style=social&color=white)](https://github.com/steveiliop56/tinyauth/stargazers) - Minimalist, ultra-lightweight authentication middleware protecting Docker and reverse-proxy apps with simple login screens or OAuth.
* **[Pomerium](https://github.com/pomerium/pomerium)** [![GitHub Stars](https://img.shields.io/github/stars/pomerium/pomerium?style=social&color=white)](https://github.com/pomerium/pomerium/stargazers) - Open-source identity-aware access proxy enforcing zero-trust, context-aware access policies without requiring a corporate VPN.

### 💻 Developer-First CIAM, OAuth2 & OIDC Servers

* **[Ory Hydra](https://github.com/ory/hydra)** [![GitHub Stars](https://img.shields.io/github/stars/ory/hydra?style=social&color=white)](https://github.com/ory/hydra/stargazers) - Certified, hardened OAuth 2.0 and OpenID Connect (OIDC) server built on Go for scalable enterprise authorization.
* **[SuperTokens](https://github.com/supertokens/supertokens-core)** [![GitHub Stars](https://img.shields.io/github/stars/supertokens/supertokens-core?style=social&color=white)](https://github.com/supertokens/supertokens-core/stargazers) - Open-source user authentication solution providing session management, social login, passwordless, and multi-tenant B2B flows.
* **[Logto](https://github.com/logto-io/logto)** [![GitHub Stars](https://img.shields.io/github/stars/logto-io/logto?style=social&color=white)](https://github.com/logto-io/logto/stargazers) - Modern open-source alternative to Auth0 offering passwordless sign-in, RBAC, multi-tenancy organizations, and SDKs for web and mobile apps.
* **[Ory Kratos](https://github.com/ory/kratos)** [![GitHub Stars](https://img.shields.io/github/stars/ory/kratos?style=social&color=white)](https://github.com/ory/kratos/stargazers) - Certified, API-first, cloud-native headless user management and authentication system.
* **[Dex](https://github.com/dexidp/dex)** [![GitHub Stars](https://img.shields.io/github/stars/dexidp/dex?style=social&color=white)](https://github.com/dexidp/dex/stargazers) - Federated OpenID Connect provider acting as a portal to external identity sources (LDAP, SAML, GitHub, GitLab) for Kubernetes and cloud apps.
* **[Hanko](https://github.com/teamhanko/hanko)** [![GitHub Stars](https://img.shields.io/github/stars/teamhanko/hanko?style=social&color=white)](https://github.com/teamhanko/hanko/stargazers) - Open-source authentication and user management solution built around FIDO2/WebAuthn passkeys and modern frontend web components.
* **[Kanidm](https://github.com/kanidm/kanidm)** [![GitHub Stars](https://img.shields.io/github/stars/kanidm/kanidm?style=social&color=white)](https://github.com/kanidm/kanidm/stargazers) - Modern, simple, and ultra-secure identity management platform written in Rust with native Passkeys, OAuth2, LDAP, and POSIX/SSH integration.
* **[Ory Keto](https://github.com/ory/keto)** [![GitHub Stars](https://img.shields.io/github/stars/ory/keto?style=social&color=white)](https://github.com/ory/keto/stargazers) - Open-source implementation of Google Zanzibar cryptographic access control and permission management server.
* **[Cerbos](https://github.com/cerbos/cerbos)** [![GitHub Stars](https://img.shields.io/github/stars/cerbos/cerbos?style=social&color=white)](https://github.com/cerbos/cerbos/stargazers) - Cloud-native, open-source authorization layer for context-aware role-based (RBAC) and attribute-based (ABAC) access control.

### 🔑 Multi-Factor Authentication (MFA) & Passkey/WebAuthn Tools

* **[2FAuth](https://github.com/Bubka/2FAuth)** [![GitHub Stars](https://img.shields.io/github/stars/Bubka/2FAuth?style=social&color=white)](https://github.com/Bubka/2FAuth/stargazers) - Self-hosted open-source web app for managing Two-Factor Authentication (TOTP/HOTP) accounts and generating security codes across devices.
* **[privacyIDEA](https://github.com/privacyidea/privacyidea)** [![GitHub Stars](https://img.shields.io/github/stars/privacyidea/privacyidea?style=social&color=white)](https://github.com/privacyidea/privacyidea/stargazers) - Modular, open-source multi-factor authentication server supporting OTP tokens, FIDO2/WebAuthn, push notifications, and RADIUS/PAM.
* **[LinOTP](https://github.com/LinOTP/LinOTP)** [![GitHub Stars](https://img.shields.io/github/stars/LinOTP/LinOTP?style=social&color=white)](https://github.com/LinOTP/LinOTP/stargazers) - Flexible open-source enterprise solution for two-factor authentication with one-time passwords and hardware tokens.

### 🏰 Privileged Access Management (PAM) & Identity Governance (IGA)

* **[JumpServer](https://github.com/jumpserver/jumpserver)** [![GitHub Stars](https://img.shields.io/github/stars/jumpserver/jumpserver?style=social&color=white)](https://github.com/jumpserver/jumpserver/stargazers) - Popular open-source Privileged Access Management (PAM) bastion host supporting SSH, RDP, Kubernetes, and database session auditing.
* **[Teleport](https://github.com/gravitational/teleport)** [![GitHub Stars](https://img.shields.io/github/stars/gravitational/teleport?style=social&color=white)](https://github.com/gravitational/teleport/stargazers) - Open-source identity-native infrastructure access plane replacing SSH keys, VPNs, and static credentials with short-lived certificates.
* **[MidPoint (Evolveum)](https://github.com/Evolveum/midpoint)** [![GitHub Stars](https://img.shields.io/github/stars/Evolveum/midpoint?style=social&color=white)](https://github.com/Evolveum/midpoint/stargazers) - Comprehensive open-source Identity Governance and Administration (IGA) platform for lifecycle workflows, RBAC, and compliance.
* **[Apache Syncope](https://github.com/apache/syncope)** [![GitHub Stars](https://img.shields.io/github/stars/apache/syncope?style=social&color=white)](https://github.com/apache/syncope/stargazers) - Open-source enterprise system for managing digital identities, provisioning, reconciliation, and Identity Governance (IGA).

### 📂 Directory Services & LDAP / Active Directory Alternatives

* **[LLDAP (Light LDAP)](https://github.com/lldap/lldap)** [![GitHub Stars](https://img.shields.io/github/stars/lldap/lldap?style=social&color=white)](https://github.com/lldap/lldap/stargazers) - Opinionated, lightweight open-source LDAP implementation designed specifically for easy user management and self-hosted authentication.
* **[FreeIPA](https://github.com/freeipa/freeipa)** [![GitHub Stars](https://img.shields.io/github/stars/freeipa/freeipa?style=social&color=white)](https://github.com/freeipa/freeipa/stargazers) - Integrated open-source security information management solution combining Linux, 389 Directory Server, Kerberos, DNS, and CA.
* **[Samba Active Directory](https://github.com/samba-team/samba)** [![GitHub Stars](https://img.shields.io/github/stars/samba-team/samba?style=social&color=white)](https://github.com/samba-team/samba/stargazers) - Open-source software suite providing full Active Directory Domain Controller compatibility, Kerberos, LDAP, and SMB/CIFS services.

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Identity-Access-Management-IAM-SSO&type=date&legend=top-left)

---

## 🤝 Contributing

Contributions are always welcome! Feel free to open a Pull Request to add more open-source IAM platforms, OIDC/OAuth2 providers, PAM bastion hosts, or directory services.

1. 🍴 Fork the repository.
2. 🌿 Create a feature branch: `git checkout -b feature/new-iam-platform`.
3. 📝 Add your project under the appropriate category with its repository link, star badge, and a concise description.
4. 🚀 Submit a Pull Request.

---

## 💖 Support & Sponsorship

If you find this curated collection helpful for your engineering, DevOps, or enterprise security architecture, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it!
- 🍴 **Fork and share** with colleagues and security teams.
- ☕ **Buy a coffee & sponsor**: Support continued curation and open-source maintenance via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).
