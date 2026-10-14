Version: NAFATH-V1
Track: Software

## Overview
A national login service lets people use one account to access different government services on a website or mobile app. Software engineering helps make these services work together and keeps the login process organised. AI may help find unusual login activity, but it is important to check its risks first. Mobile apps should protect user information and only ask for permissions when they are needed. Networking helps the service communicate and explains what DNS over HTTPS can protect. Cybersecurity helps keep accounts safe from phishing attacks. Data protection is also important because people’s personal information must be handled according to Omani law. These areas work together to make the service safer, especially when verifying users' identities and limiting access to services.

## Software
OAuth 2.0 and OpenID Connect have different roles. OAuth 2.0 allows an app to access resources with permission. OpenID Connect helps the app check who the user is when they sign in. Both are useful for a government login service. OAuth 2.0 focuses on access to resources, while OpenID Connect focuses on the user's identity.

Resource: OpenID Connect Core 1.0 - https://openid.net/specs/openid-connect-core-1_0.html

## AI
AI can help a government login service detect unusual sign-in activity. However, it may flag normal logins by mistake or miss suspicious activity. Before using it, the team should check these risks and test how well the system works. The NIST AI Risk Management Framework helps organisations manage AI risks during design, development, use, and evaluation. The team should also review the results to help keep the service safe and reliable.

Resource: Artificial Intelligence Risk Management Framework (AI RMF) - https://www.nist.gov/itl/ai-risk-management-framework

## Mobile
Android apps run in a limited environment to help protect user data. If an app needs access to personal data, it may need to ask the user for permission. The app should only request permissions it really needs and ask at the right time, when the user uses a feature that needs them. It should also explain why the permission is needed and handle the user's choice if they refuse.

Resource: Request runtime permissions - https://developer.android.com/training/permissions/requesting

## Networking
DNS over HTTPS (DoH) sends DNS requests through an encrypted HTTPS connection. This makes it harder for people on the same network or an internet provider to see the website names a user looks up. However, the DNS provider can still see these requests, and DoH may affect some network filters or parental controls. It improves privacy, but it does not hide all online activity.

Resource: About DNS over HTTPS - https://support.mozilla.org/en-US/kb/firefox-dns-over-https

## Cybersecurity
Multi-factor authentication (MFA) helps protect accounts by asking users to prove their identity in two or more ways. However, not all MFA methods provide the same level of protection. CISA explains that FIDO/WebAuthn is the only widely available phishing-resistant authentication method. It can use a physical security key or a feature built into a phone or computer. For a government login service, phishing-resistant MFA can help protect users from fake websites that try to steal their login details.

Resource: Implementing Phishing-Resistant MFA - https://www.cisa.gov/sites/default/files/2023-01/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf

## Data
Oman's Personal Data Protection Law helps protect people's personal information. It generally requires consent before personal data is processed, although some legal exceptions apply. The law also sets rules for protecting personal data and gives people rights over their information. A government login service should follow the applicable rules when collecting and handling users' personal information.

Resource: Royal Decree 68/2026 amending the Personal Data Protection Law - https://mtcit.gov.om/ar/3/8/75/1481

## Misconception in My Track
A common misconception is that OAuth 2.0 and OpenID Connect do the same thing. They are related, but they have different roles. OAuth 2.0 allows an app to access resources with permission. OpenID Connect helps the app verify who the user is. OAuth 2.0 alone does not provide a standard way to confirm a user's identity. For a government login service, knowing this difference helps developers choose the right tools for sign-in and access control.

## Open Question
How can a government login service verify a user's identity while making sure the user can only access the services they are allowed to use?
