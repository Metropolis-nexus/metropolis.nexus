# Privacy Policies
Metropolis Nexus is a suite of services provided by Thien (Tommy) Tran and affiliated contributors (collectively, "we," "us," or "our") as a free hobby project (collectively, the "Services"). Certain Services are hosted solely on our infrastructure, while others—such as Matrix, XMPP, and Mastodon—are decentralized and federated services, similar to email. This Privacy Policy governs only the systems under our control and does not extend to other providers with whom we federate.

We are committed to protecting your privacy and handling your data responsibly. This policy outlines how we collect, use, store, and protect information in connection with the Services. By using the Services, you consent to the practices described herein.

## Tracking and Analytics
We do not employ third-party tracking services, such as Google Analytics, nor do we attempt to track your activities across the internet. Any analytics we perform are conducted entirely on our systems or occur by default through our service providers. Currently, we host static sites and certain static content on Cloudflare Pages. For details on their data practices, please refer to Cloudflare's privacy policy [here](https://www.cloudflare.com/privacypolicy/).

Analytics data collected by us is used solely for internal purposes, including maintaining system security, improving performance, load balancing, and rate limiting. This data is not shared with third parties.

## Network connection logs
To ensure system security, optimize performance, and comply with regulatory requirements, we collect network connection logs. We utilize Intrusion Prevention Systems, including CrowdSec, ET Threat Protection Telemetry, and ZenArmor. In certain scenarios, these systems may transmit network logs to the software vendors. When TLS encryption is in use, packets are processed by these systems without TLS termination, preserving the privacy of your network request content.

In exceptional circumstances, such as severe DDoS attacks, we may employ reverse proxies from providers like Cloudflare for protection. In these cases, TLS termination occurs at the provider's end. We will avoid using such solutions whenever feasible.

We do not maintain a fixed retention period for network logs; however, for privacy considerations, users should assume indefinite storage. If you are concerned about records of your IP address being retained by us or our Intrusion Prevention providers, we recommend using a VPN or similar privacy-enhancing tools.

## Disk Encryption
A comprehensive list of our Services and their hosting locations is available on our [status tracker](https://uptime.metropolis.nexus). Systems designated as "Colocated" or "Bare Metal" employ full disk encryption. Where supported, we also enable memory encryption to safeguard disk encryption keys during system operation.

Services hosted on "VPS" environments do not utilize disk encryption, and our hosting providers may have access to data stored on those systems.

## Backups
Users are responsible for maintaining their own data backups. However, we perform regular backups of the Services to ensure reliability. Backups from colocated services and bare metal servers are encrypted locally before transmission to third-party backup providers. We retain exclusive access to the decryption keys, ensuring that no unauthorized parties can access the encrypted data.

## Data Sharing and Disclosure
We do not sell, rent, or share your personal information with third parties for marketing purposes. Data may be disclosed only in the following limited circumstances:
- To comply with legal obligations, such as subpoenas or court orders.
- To protect the rights, property, or safety of our users, the Services, or the public.
- In connection with Intrusion Prevention Systems or DDoS protection, as described above.

## Data Erasure
To submit a data erasure request, please email us at tommy@metropolis.nexus. We will verify your identity to ensure the request is legitimate before processing it. Upon receiving and verifying a valid request, we will take the following steps, where feasible:
- Delete your account entirely from non-federated Services.
- Disassociate your email address from our Single Sign-On (SSO) systems and any remaining Services. Please note that this may not always be possible due to technical limitations in certain systems. For example, refer to [this issue](https://github.com/element-hq/matrix-authentication-service/issues/5207) regarding the Matrix Authentication Service.
- Redact your messages on federated platforms only when it is technically feasible and does not cause significant disruptions to the network. In the case of Matrix, your account will be compelled to leave all rooms in which you participated. Messages in empty rooms (including those where you were the sole member) will be automatically deleted after 30 days. However, messages in rooms with other members will remain unredacted, as mass redaction could render rooms unusable across the entire network.
- Mark your account as "inactive" in our SSO system, revoking all access privileges.
- Retain authentication logs for 90 days following the inactivation of your account, after which they will be deleted. Your IP addresses will also be removed from our Matrix database after this 90-day period.
- Retain your username indefinitely in our authentication system to prevent impersonation and maintain system integrity.

We will honor data erasure requests only from legitimate users who have not violated our Terms of Service or applicable laws. In cases of violations, we reserve the right to retain your data as necessary to prevent future abuses, in accordance with our legitimate interests.

Please be aware that data erasure applies solely to our live systems and does not extend to backups. While we do not guarantee the deletion of data from backups, we will not retain backups for more than 10 years. We aim to process erasure requests within 30 days, and we will notify you of the outcome or any delays.

## Changes to This Policy
We may update this Privacy Policy from time to time to reflect changes in our practices or legal requirements. We will notify you of material changes by posting the updated Privacy Policies or through other reasonable means. Continued use of the Services after such changes constitutes acceptance of the updated policies.

