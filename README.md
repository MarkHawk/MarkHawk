# Mark Hawkings

I solve production problems: failing logins and SSO, integrations that misbehave, systems that need understanding quickly under pressure. My background is enterprise infrastructure across financial services, broadcasting and the public sector. My current work is identity and access management (SAML, OIDC, MFA, RADIUS, LDAP).

Most of that work is with customers. I get a quick picture of how their environment fits together, explain what is going wrong in terms that make sense to them, and stay with it until it is fixed.

Alongside support I've delivered project work. At BBC News I rolled out the OpenMedia newsroom platform to over 50 sites worldwide, and my PowerShell automation cut each site's build from a month to six hours. Through Computacenter I worked on migrations and upgrades for clients in finance, insurance and the public sector.

I build tools to reproduce problems, automate the repetitive parts of support, and put AI to practical use. During a certificate expiry that affected tens of thousands of customers, I wrote a prompt that turned each customer's setup and errors into remediation steps they could follow themselves. I use AI-assisted tooling (Claude Code) and experiment with local LLMs.

**Featured**

**Start here:** [Walkthrough: one incident, every tool](https://github.com/MarkHawk/identity-lab/blob/main/docs/walkthrough.md), a support ticket followed from the first message to the fix, through the lab and the tools below.

- [hemisphere](https://github.com/MarkHawk/hemisphere): drives a Gakken WorldEye spherical display from a Raspberry Pi 3 or a Windows PC, with a calibrated lens model and a framework for new visuals
- [identity-lab](https://github.com/MarkHawk/identity-lab): a Docker identity lab that reproduces SAML, OIDC, LDAP and RADIUS failures on demand, each with a support runbook and automated tests, and runs in GitHub Codespaces with no local setup
- [token-inspector](https://github.com/MarkHawk/token-inspector): an offline SAML and OIDC troubleshooting tool that explains in plain English what is wrong with a token or response, gives the likely cause and the next step, and is tested on real captures from identity-lab
- [rate-limit-probe](https://github.com/MarkHawk/rate-limit-probe): diagnoses "429 Too Many Requests" tickets: finds the real limit, checks Retry-After and rate-limit headers, and says whether the fix belongs to the client or the API
- [identity-support-splunk](https://github.com/MarkHawk/identity-support-splunk): a Splunk app that answers "when did it start, who is affected, and what is the likely cause?" for identity failures, with runbook links, tested on real identity-lab data
- [psirt-watch](https://github.com/MarkHawk/psirt-watch): a dashboard that tracks Cisco security advisories through the public openVuln API
