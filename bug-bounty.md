---
description: Join our bug bounty program!
---

# 🐞 Bug Bounty

| Smart Contract |                   |
| -------------- | ----------------- |
| Critical       | Up to USD 500,000 |
| High           | USD 100,000       |
| Medium         | USD 10,000        |
| Low            | USD 1,000         |

| Website and Application |                   |
| ----------------------- | ----------------- |
| Critical                | Up to USD 100,000 |
| High                    | USD 20,000        |
| Medium                  | USD 2,000         |

## Reporting

Please submit your bug reports \[ ADD LINK !!!!! ]!

To prevent any attack on Wombat, kindly allow us ample time to fix the problem before publishing your findings publicly. Doing so may lead to your rewards being rescinded.

## Assets in Scope

All smart contracts of SLR.Finance can be found at[ https://github.com/wombat-exchange/v1-core](https://github.com/slr-finance/slr-finance-contracts). However, only those in the Assets in Scope table are considered as in-scope of the bug bounty program.

If a Critical or High severity impact can be caused to any other asset managed by SLR.Finance that isn’t on this table but for which the effect is in the Impacts in Scope section below, you are encouraged to submit it for the consideration by the project.

## Impacts in Scope

Only the following impacts are accepted within this bug bounty program. All other impacts are not considered as in-scope, even if they affect something in the assets in scope table.

### Smart Contracts

#### Critical&#x20;

* Any governance voting result manipulation&#x20;
* Direct theft of any user funds, whether at rest or in motion, other than unclaimed yield&#x20;
* Permanent freezing of funds&#x20;
* Miner-extractable value (MEV)&#x20;
* Insolvency

#### High&#x20;

* Theft of unclaimed yield&#x20;
* Permanent freezing of unclaimed yield&#x20;
* Temporary freezing of funds for at least 24 hours

#### Medium&#x20;

* Smart contract unable to operate due to lack of token funds&#x20;
* Block stuffing for profit&#x20;
* Griefing (e.g. no profit motive for an attacker but damage to the users or the protocol)&#x20;
* Theft of gas&#x20;
* Unbounded gas consumption

#### Low&#x20;

* Smart contract fails to deliver promised returns but doesn’t lose value

### Web/App

#### Critical&#x20;

* Execute arbitrary system commands&#x20;
* Retrieve sensitive data/files from a running server such as /etc/shadow, database passwords, and blockchain keys(this does not include non-sensitive environment variables, open source code, or usernames)&#x20;
* Taking down the application/website&#x20;
* Taking state-modifying authenticated actions (with or without blockchain state interaction) on behalf of other users without any interaction by that user, such as changing registration information, commenting, voting, making trades, withdrawals, etc. Subdomain takeover with already-connected wallet interaction&#x20;
* Direct theft of user funds&#x20;
* Malicious interactions with an already-connected wallet such as modifying transaction arguments or parameters, substituting contract addresses, submitting malicious transactions

#### High

* Injecting/modifying the static content on the target application without Javascript (Persistent) such as HTML injection without Javascript, replacing the existing text with arbitrary text, arbitrary file uploads, etc.&#x20;
* Changing sensitive details of other users (including modifying browser local storage) without already-connected wallet interaction and with up to one click of user interaction, such as email or password of the victim, etc.&#x20;
* Improperly disclosing confidential user information such as email address, phone number, physical address, etc.&#x20;
* Subdomain takeover without already-connected wallet interaction

#### Medium&#x20;

* Changing non-sensitive details of other users (including modifying browser local storage) without already-connected wallet interaction and with up to one click of user interaction, such as changing the first/last name of a user or enabling/disabling notifications&#x20;
* Injecting/modifying the static content on the target application without Javascript (Reflected), such as reflected HTML injection or loading external site data&#x20;
* Redirecting users to malicious websites (Open Redirect)

## Out of Scope & Rules

The following vulnerabilities are excluded from the rewards for this bug bounty program:

* Attacks that the reporter has already exploited themselves, leading to damage&#x20;
* Attacks requiring access to leaked keys/credentials&#x20;
* Attacks requiring access to privileged addresses (governance, strategist)

### Smart Contracts and Blockchain&#x20;

* Incorrect data supplied by third party oracles&#x20;
  * Not to exclude oracle manipulation/flash loan attacks&#x20;
* Basic economic governance attacks (e.g. 51% attack)&#x20;
* Lack of liquidity Best practice critiques&#x20;
* Sybil attacks&#x20;
* Centralization risks&#x20;

### Websites and Apps&#x20;

* Theoretical vulnerabilities without any proof or demonstration&#x20;
* Content spoofing / Text injection issues&#x20;
* Self-XSS&#x20;
* Captcha bypass using OCR&#x20;
* CSRF with no security impact (logout CSRF, change language, etc.) Missing HTTP Security Headers (such as X-FRAME-OPTIONS) or cookie security flags (such as “httponly”)&#x20;
* Server-side information disclosure such as IPs, server names, and most stack traces&#x20;
* Vulnerabilities used to enumerate or confirm the existence of users or tenants&#x20;
* Vulnerabilities requiring unlikely user actions&#x20;
* URL Redirects (unless combined with another vulnerability to produce a more severe vulnerability)&#x20;
* Lack of SSL/TLS best practices&#x20;
* DDoS vulnerabilities&#x20;
* Attacks requiring privileged access from within the organization&#x20;
* Feature requests&#x20;
* Best practices&#x20;
* Vulnerabilities primarily caused by browser/plugin defects&#x20;
* Any vulnerability exploit requiring CSP bypass resulting from a browser bug

The following activities are prohibited by this bug bounty program:

* Any testing with mainnet or public testnet contracts; all testing should be done on private testnets
* Any testing with pricing oracles or third party smart contracts&#x20;
* Attempting phishing or other social engineering attacks against our employees and/or customers&#x20;
* Any testing with third-party systems and applications (e.g. browser extensions) as well as websites (e.g. SSO providers, advertising networks)&#x20;
* Any denial of service attacks&#x20;
* Automated testing of services that generates significant amounts of traffic&#x20;
* Public disclosure of an unpatched vulnerability in an embargoed bounty
