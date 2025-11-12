# Privacy Policies
Metropolis Nexus is a suite of services provided by Thien (Tommy) Tran and affiliated contributors (“we,” “us,” “our”) as a free hobby project (“Services”). Some Services are centralized; others—like Matrix, XMPP, and Mastodon—federate with third‑party servers. This policy covers only systems we operate; it does not cover other providers with whom we federate.

## Who we are & how to contact us
Controller: Metropolis Nexus (Thien Tran)  
Contact: tommy@metropolis.nexus

## What we collect
- **Account data**: email, display name, account identifiers, authentication events.
- **Service content**: messages, files, posts you upload (for federated Services, copies may be distributed to other servers you interact with).
- **Operational metadata**: IP addresses, timestamps, user‑agent/device info, protocol details, URLs visited.
- **Cookies**: we do not use advertising or cross‑site analytics cookies. Our providers (e.g., Cloudflare) may set functional security cookies such as `__cf_bm` for bot mitigation and DDoS protection.

## Why we process data (purposes)
- Provide and secure the Services; operate federation; prevent abuse and fraud.
- Performance, debugging, and capacity planning.
- Legal compliance and responding to lawful requests.
- Backups and disaster recovery.

## Legal bases (EEA/UK users)
- **Contract**: to create your account and deliver the Services you request.
- **Legitimate interests**: security, abuse prevention, service analytics (strictly internal), and federation operations. We balance these against your rights.
- **Consent**: where required (e.g., optional features where we ask first).

## Data Sharing and Disclosure
We do not sell, rent, or share your personal information with third parties for marketing purposes. Data may be disclosed only in the following limited circumstances:
- To comply with legal obligations, such as subpoenas or court orders.
- To protect the rights, property, or safety of our users, the Services, or the public.
- In federated networks, when you interact across servers (your profile, messages, and metadata may be copied to those servers).
- In connection with Intrusion Prevention Systems or DDoS protection, as described below.

## Tracking and Analytics
We do not utilize third-party tracking services, such as Google Analytics. Any analytics we perform are conducted entirely on our systems or occur by default through our service providers. Currently, we host static sites and certain static content on Cloudflare Pages. For details on their data practices, please refer to Cloudflare's privacy policy [here](https://www.cloudflare.com/privacypolicy/).

Analytics data collected by us is used solely for internal purposes.

## Network Security
We employ Intrusion Prevention Systems, including CrowdSec, Proofpoint ET Threat Protection Telemetry, and ZenArmor. Under certain conditions, these systems may transmit network connection information (e.g., IP addresses, timestamps, protocols, SNI) to the software vendors. We pass packets through these systems without TLS termination, ensuring that the vendors do not have visibility into the content of your encrypted network requests.

In exceptional circumstances, such as severe DDoS attacks, we may utilize reverse proxies from providers like Cloudflare for protection. In such cases, TLS termination occurs at the provider's end. We will avoid using such solutions whenever feasible.

## Disk Encryption
A comprehensive list of our Services and their hosting locations is available on our [status tracker](https://uptime.metropolis.nexus). Systems designated as "Colocated" or "Bare Metal" employ full disk encryption. Where supported, we also enable memory encryption to safeguard disk encryption keys during system operation.

Services hosted on "VPS" environments do not utilize disk encryption, and may be subject to provider access.

## Backups
Backups from Services marked as "Colocation" or "Bare Metal" are encrypted before leaving our systems, with keys controlled exclusively by us.

## Data Erasure
To submit a data erasure request, please email us at tommy@metropolis.nexus. We will verify your identity to ensure the request is legitimate before processing it. Upon receiving and verifying a valid request, we will take the following steps, where feasible:
- Delete your account entirely from non-federated Services.
- Disassociate your email address from our Single Sign-On (SSO) systems and any remaining Services. Please note that this may not always be possible due to technical limitations in certain systems. For example, refer to [this issue](https://github.com/element-hq/matrix-authentication-service/issues/5207) regarding the Matrix Authentication Service.
- Redact your messages on federated platforms only when it is technically feasible and does not cause significant disruptions to the network. In the case of Matrix, your account will be compelled to leave all rooms in which you participated. Messages in empty rooms (including those where you were the sole member) will be automatically deleted after 30 days. However, messages in rooms with other members will remain unredacted, as mass redaction could render rooms unusable across the entire network.
- Mark your account as "inactive" in our SSO system, revoking all access privileges.
- Retain your username indefinitely in our authentication system to prevent impersonation.

Please be aware that:
- We will honor data erasure requests only from legitimate users who have not violated our Terms of Service or applicable laws. In cases of violations, we reserve the right to retain your data as necessary to prevent future abuses, in accordance with our legitimate interests.
- Data erasure applies solely to our live systems and does not extend to backups. We do not keep backups for longer than 10 years.

We aim to process erasure requests within 30 days, and we will notify you of the outcome or any delays.

## Retention Policy
- Email communications with us, including automated emails (e.g., notifications, new logins), are retained indefinitely, even following data erasure requests.
- The SSO system is configured to retain authentication logs for 90 days. After 90 days, all authentication events and associated IP addresses are deleted from our SSO database.
- Our Matrix server is configured to retain user IP addresses for 90 days. After 90 days, IP addresses are deleted from our Matrix database.

System logs vary depending on the software in use. We document our system configurations on our [GitHub organization](https://github.com/orgs/Metropolis-nexus/repositories). If we do not explicitly set a retention policy for a particular element, it defaults to the software's standard settings. Our goal is not to retain IP addresses or connection logs for more than 90 days, except to prevent abuse or when required by law. We encourage you to contact us if there is a retention setting in our software stack that we should adjust.

## Children
The Services are intended for users aged 18 years or older (or the age of majority in your jurisdiction). Minors are not permitted to use the Services.

## Law enforcement and legal requests
We respond to valid legal processes in jurisdictions where we are subject to the court's authority. We will notify affected users unless legally prohibited or where notification would create a risk of harm.

## Changes to This Policy
We may update this Privacy Policy from time to time to reflect changes in our practices or legal requirements. We will notify you of material changes by posting the updated policy or through other reasonable means. Your continued use of the Services after such changes constitutes acceptance of the updated policy.

## Contact
For questions or requests, please contact us at tommy@metropolis.nexus.
