# Awesome-Software-Asset-Management

## Top Software Asset Management (SAM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Software License Management, Entitlement Tracking, Discovery, Compliance & Optimization*  

**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Software Asset Management (SAM)**. These tools help organizations discover software installations, track licenses and entitlements, optimize spend, and maintain compliance with complex publisher agreements (Microsoft, Oracle, IBM, SAP, and others).

**Examples** include Flexera, Snow Software (now part of Flexera), USU SAM, Certero, License Dashboard, OpeniT, Xensam, ServiceNow SAM, ManageEngine, and SAM Pro (the category leaders).

**Open-source emphasis**: Enterprise-grade SAM platforms with deep publisher entitlement intelligence and audit-ready Effective License Position calculations are predominantly commercial. Open-source options excel at IT asset and license tracking (**Snipe-IT**), open-source license compliance (**FOSSology**), and lighter inventory systems. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Description | Pricing (Starting Tier) | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Flexera (Flexera One / Snow Atlas)](https://www.flexera.com/)** | Market-leading SAM platform providing deep entitlement intelligence, hybrid discovery, Effective License Position, and optimization across on-premises, cloud, and SaaS estates. | Starting at ~$50,000/year (or ~$1,000/month minimum for Cloud Cost Optimization on AWS Marketplace) | No free-forever plan. 14-day free trial available for Spot module (up to 20 VMs); enterprise SAM platform evaluated via sales-guided demo. |
| **[USU Software Asset Management](https://www.usu.com/)** | Specialist enterprise SAM solution with strong focus on complex publisher estates (including SAP, Oracle, and IBM) and managed-services options. | Starting at ~$10,000/year (managed SAM bundles starting at ~$70,000/year on enterprise frameworks) | No free-forever plan. Offers a 90-day free trial for ITAM Managed Services or guided sales demo. |
| **[Certero](https://www.certero.com/)** | Enterprise and mid-market SAM platform emphasizing discovery, license management, and practical compliance workflows. | Starting at £4.28 (~$5.50) per unit/month (~$66/unit/year; base packages starting at ~£1,000/year) | No free-forever plan. 30-day free trial available for limited user/device scope upon request. |
| **[ServiceNow Software Asset Management (SAM Pro)](https://www.servicenow.com/)** | SAM capabilities tightly integrated with the ServiceNow platform, CMDB, and ITSM workflows for organizations invested in the Now ecosystem. | Starting at ~$50,000/year (or ~£6.40/unit/month on public procurement frameworks) | No free-forever production plan. Free Personal Developer Instances (PDIs) for sandbox testing & 3-day course access to simulated environments via Now Learning. |
| **[OpeniT](https://www.openit.com/)** | Specialized metering, license optimization, and software usage intelligence across engineering and enterprise environments. | Starting at ~$5,000/year for base metering licenses | No free-forever plan. 30-day guided proof-of-concept evaluation trial available upon request. |
| **[Xensam](https://www.xensam.com/)** | AI-driven SAM platform specializing in automated software discovery, SaaS management, and cloud entitlement tracking. | Starting at 2.00 SEK (~$0.20 USD) per user/year nominal base rate (mid-market entry tiers starting ~$2,500/year) | No free-forever plan. 30-day free trial (no credit card required) for targeted endpoints upon request. |
| **[License Dashboard](https://www.licensedashboard.com/)** | License management and IT asset optimization platform for automated entitlement reconciliation and compliance reporting. | Starting at ~£1,000/year (~$1,300/year) for base tier software asset management licenses | No free-forever plan. Free IT Health Check assessment & guided 14 to 30-day proof-of-concept trial upon request. |
| **[ManageEngine AssetExplorer](https://www.manageengine.com/)** | IT asset and software license management solutions suitable for mid-market organizations, paired with broader ManageEngine suites. | Starting at $955/year (for up to 250 IT assets) | Free Edition available forever for up to 25 nodes (on-premise) or 50 nodes (cloud); 30-day fully functional free trial managing up to 250 IT assets. |

## Open-Source GitHub Projects

- **[Snipe-IT](https://github.com/snipe/snipe-it)**  
  Leading free and open-source IT asset and license management system. Tracks hardware, software licenses, assignments, depreciation, and more. Actively maintained and widely deployed.

- **[FOSSology](https://github.com/fossology/fossology)**  
  Open-source license compliance toolkit and system for scanning software for licenses, copyrights, and export-control obligations—essential for managing open-source usage and obligations.

- **[ITAMbox](https://itambox.dev/)**  
  Open-source IT asset management application focused on assets, custody, maintenance, costs, and protected license data, designed for self-hosting.

- **[Other ITAM & inventory tools](https://github.com/search?q=IT+asset+management+OR+software+license+management+open+source)**  
  Community projects for hardware/software inventory, license tracking, and basic compliance reporting.

- **[License scanning & SCA tools](https://github.com/search?q=software+composition+analysis+OR+license+scan+OR+dependency+license)**  
  Open-source Software Composition Analysis (SCA) tools that detect third-party and open-source licenses in codebases.

- **[GLPI and related GLPI plugins](https://github.com/glpi-project/glpi)**  
  Open-source IT service management and asset management platform that includes inventory and license-related capabilities.

- **[OCS Inventory / FusionInventory](https://github.com/search?q=OCS+Inventory+OR+FusionInventory)**  
  Open-source hardware and software inventory agents and servers commonly used as discovery sources for SAM processes.

- **[LicenseDb and compliance helpers](https://github.com/fossology)**  
  Supporting projects around centralized license and obligation management that complement FOSSology and similar tools.

### Additional Strong Open-Source Options

- **Discovery agents**: Open-source agents that collect installed software data from endpoints and servers.
- **CMDB / inventory systems**: Broader open-source configuration management databases that can feed SAM processes.
- **SaaS usage trackers**: Experimental tools for discovering and tracking SaaS subscriptions.
- **Reporting & dashboards**: Grafana or custom dashboards built on inventory and license data.
- **Policy-as-code for licenses**: Tools that help enforce approved license lists and open-source policies.
- Integration scripts that connect open-source inventory with commercial SAM or ERP systems.

**Frameworks for building custom systems**:  
For practical open-source IT asset and license tracking, start with **Snipe-IT**.  
For open-source license compliance and obligation management, use **FOSSology** (often alongside SCA tools).  
Enterprise publisher-specific entitlement logic, audit defense for Oracle/IBM/SAP/Microsoft, hybrid discovery at scale, and SaaS optimization remain the domain of commercial platforms (Flexera, USU, Certero, ServiceNow SAM, etc.).  
Many organizations run Snipe-IT or similar tools for day-to-day asset tracking while relying on commercial SAM for high-stakes compliance and optimization.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Software license compliance carries legal and financial risk. Publisher audit terms, metric definitions, and entitlement rules are complex and change over time. Open-source tools do not replace professional SAM expertise or publisher-specific guidance.
- Organizations remain responsible for accurate inventory, correct license interpretation, and compliance with all applicable agreements. Use open-source tools as part of a broader SAM program, not as a complete substitute for enterprise solutions when audit exposure is significant.

---

**Made for SAM managers, IT asset managers, procurement teams, compliance officers, and FinOps practitioners.**  
Let's improve visibility, reduce waste, and make software asset management more transparent and accessible.
