# TDIS

*description of the project*

**Timeframe** 2026-06-30 - 2026-10-06

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/tdis-2026](https://cra-test-arc.canada.ca/tdis-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-07-14

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Sign in to your CRA account)
    node4(Tax information web service)
    node5(Sign in to verify your identity)
    node6(Identity validation service)
    node1 --x node2
    node2 --> node3
    node3 --x node4
    node3 --x node5
    node3 --x node6
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/e-services/auto-fill-return-express-noa.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/cra-login.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/identity-validation-service.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6 inscope
```
