---
layout: post
title: "On KYC checks and Persona"
slug: "on-kyc-checks-and-persona"
date: "2026-03-13T18:09:22.453Z"
author: "Lauren Gardner"
tags: []
original_url: "https://opencollective.com/opensource/updates/on-kyc-checks-and-persona"
---

As a nonprofit fiscal host, OSC supports over 2,500 open-source projects worldwide. Last year, as part of ongoing improvements to our risk and compliance processes, we began verifying the identity of users requesting payments when:

-   When we cannot verify that the person requesting payment is the holder of an account
-   When a payment involves a nation sanctioned by the US government
-   When a payment provider requires additional verification

We identified users once and stored the results as ‘pass’ or ‘fail’. We do **not send user data from our platform to Persona**, we do not store identity documents, we performed these checks on a fraction of a percentage of the payments we process, and only in the cases listed above. 

Like all organizations that transfer money, we are subject to the U.S. Anti-Money Laundering (AML) regulations and sanction requirements set by the [Office of Foreign Assets Control](https://opencollective.com/redirect?url=https%3A%2F%2Fofac.treasury.gov%2F) ("OFAC") of the US Department of the Treasury. These rules require organizations to verify the identity of recipients in certain cases to reduce the risk of fraud, identity theft, sanctions violations, or other financial crimes.

Last year we paid maintainers in 96 countries, including maintainers in active warzones where our primary payment providers refuse to operate. As a team of five, we do not have the resources to validate the identities across such a wide range of nations. We chose a service provider to help streamline our operations. After a review of available solutions, we chose Persona, predominantly for its customer-defined data retention policy, which we set to delete identifying documents once we verify a result. 

**
On Persona**

Persona has answered questions regarding their data sharing, their government contracts, and their relationship with Peter Thiel and Palantir. We are not here to parrot their responses. Our review did not extend to Persona’s investors and the stakeholders in those investment vehicles. While that is our error, and an error we will correct, we feel it’s necessary to point out that most providers in this space _will_ most likely offer their services to government agencies, and may also be funded by institutions we do not wish to support. Capitalism is a complex web, and we will do our best to select tools that align with our values, however, we cannot always guarantee we will achieve that outcome.

**What we are doing
**

Most of our requests to verify identities come from requests to pay PayPal addresses. PayPal operates its own verification program, which we will utilize for those who cannot accept payments by bank transfer. 

In addition, we will be identifying alternative providers for identity verification services, both in the US and in Europe, in order to give our European users the additional peace of mind that their identity documents do not pass into American processors. 

Finally, we will halt the use of Persona for identity verification until we are able to implement the alternative arrangements described above. 

Thank you to everyone in our community who shared their perspective. We hear you, and we are grateful to be a part of a community that cares so deeply about transparency and accountability. Openness is at the heart of everything we do.

The folks at OSC

\-Lauren, Ben, Grace, Sourav, and Caitlin

Helpful link:

-   What is fiscal hosting - [https://docs.oscollective.org/welcome-and-introduction-to-osc/what-is-fiscal-hosting](https://docs.oscollective.org/welcome-and-introduction-to-osc/what-is-fiscal-hosting)
