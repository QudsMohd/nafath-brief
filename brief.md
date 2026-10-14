Version: NAFATH-V1
Track: Software

## Overview
A national login service lets people use one account to access different government services on a website or mobile app. Software engineering helps make these services work together and keeps the login process organised. AI may help find unusual login activity, but it is important to check its risks first. Mobile apps should protect user information and only ask for permissions when they are needed. Networking helps the service communicate and explains what DNS over HTTPS can protect. Cybersecurity helps keep accounts safe from phishing attacks. Data protection is also important because people’s personal information must be handled according to Omani law. These areas work together to make the service safer and easier for people to use.

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

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
