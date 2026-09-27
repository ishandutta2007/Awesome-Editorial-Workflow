# Awesome-Editorial-Workflow

# Top Editorial Workflow Platform Ecosystem

**A curated list of SaaS products and open-source GitHub projects**

*Focusing on newsroom workflow, task allocation, content planning, and multi-channel publishing*

**Last Updated: September 2026**

This repository tracks prominent **SaaS platforms** and **open-source projects** in the **editorial workflow** space. These tools help news organizations, publishers, and corporate content teams manage the full content lifecycle—from story pitching and task assignment to editorial review and multi-channel distribution.

**Examples** include Desk-Net, Avid iNEWS, Arc XP, WoodWing Studio, ContentFlow, CUE, Shorthand, Kontent.ai, and Desk-Net (leaders in this domain).

**Open-Source Highlight**: There is one **standout open-source leader** in the editorial workflow space: **Superdesk**. It is a production-grade open-source newsroom management system widely adopted by news agencies globally, including NTB (Norway), Belga (Belgium), The Canadian Press, and AAP (Australia). Meanwhile, open-source CMSs like **Wagtail** can be customized to build editorial workflow features (such as The Ubyssey's Stove project). This list highlights both types of self-hostable solutions.

Contributions are welcome! Submit a PR to add or update entries. Keep descriptions factual and link to official websites.

## Table of Contents

- [SaaS / Managed Platforms](#saas--managed-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Managed Platforms

- **[Desk-Net](https://www.desk-net.com/)**  
  An editorial workflow and story planning platform that helps newsrooms manage story ideas, task assignments, deadlines, and content calendars. Widely used across German-language media organizations.

- **[Avid iNEWS](https://www.avid.com/)**  
  A broadcast newsroom computer system (NRCS) for scripting, rundown management, and news production workflows. Deeply integrated into Avid's media production ecosystem.

- **[Arc XP](https://www.arcxp.com/)**  
  A cloud-native content platform developed by The Washington Post, providing editorial workflows, content management, multi-platform publishing, and analytics. Suitable for enterprise news organizations.

- **[WoodWing Studio](https://www.woodwing.com/)**  
  A multi-channel editorial management and content creation platform supporting unified workflows across print, digital, and mobile publishing.

- **[ContentFlow](https://contentflow.io/)**  
  An editorial workflow automation platform focusing on content planning, task management, and team collaboration.

- **[CUE](https://cue.group/)**  
  A newsroom planning and workflow tool for managing story topics, assignments, and editorial calendars.

- **[Shorthand](https://shorthand.com/)**  
  A visual storytelling and digital content creation platform for building scrollytelling experiences and interactive content, often paired with an existing CMS.

- **[Kontent.ai](https://kontent.ai/)**  
  A cloud-based headless CMS offering structured content modeling, editorial workflows, localization, and API-driven multi-channel publishing.

- **[Desk-Net](https://www.desk-net.com/)**  
  *(Duplicate entry as listed above)*

## Open-Source GitHub Projects

- **[Superdesk](https://github.com/superdesk/superdesk)**  
  An **open-source newsroom management system** developed by Sourcefabric, providing end-to-end workflows from content creation and editorial review to multi-channel publishing. Core features include: **editorial workflows** (organizing teams into "Desks" like News, Sports, Features with inter-desk routing and approval), **content planning** (editorial calendar, assignments, coverage plans), **multi-source aggregation** (NewsML-G2, IPTC standards, RSS, FTP, email), **real-time collaboration** (concurrent editing), **multi-channel publishing** (web, mobile, print, social media), **Newshub** (client content portal), and **analytics modules** (tracking newsroom efficiency metrics). Stack: Python/Flask, MongoDB, Elasticsearch, AngularJS. Used in production by major agencies like NTB, Belga, The Canadian Press, and AAP. **AGPL-3.0**.

- **[Wagtail](https://github.com/wagtail/wagtail)**  
  A Django-based open-source CMS used by organizations like NASA JPL and Google. While Wagtail is not exclusively an editorial workflow tool out-of-the-box, its flexible page models, workflow engine, and granular permission management make it a **solid foundation for building custom newsroom editorial flows**. For instance, *The Ubyssey* built the **Stove** system on top of Wagtail, integrating a task manager and manuscript editor directly into the CMS to bridge the Google Docs to CMS gap. Wagtail supports multi-stage approvals, draft/published state management, and editorial collaboration. **BSD-3-Clause**.

- **[Payload](https://github.com/payloadcms/payload)**  
  A TypeScript-first open-source headless CMS with built-in admin UI, draft modes, access control, and editorial workflows. 73.1k stars, MIT license. Ideal for teams requiring a **code-first, deeply customizable** editorial process. Its blocks editor and field system enable structured content planning and assignment UI design.

- **[Strapi](https://github.com/strapi/strapi)**  
  A leading open-source headless CMS built on 100% JavaScript, customizable and extensible. Features a content-type builder, role-based access permissions, and workflow management. Ideal for dev teams needing **complete control over data models and editorial flows**.

- **[Directus](https://github.com/directus/directus)**  
  Turns any SQL database into a headless CMS with an admin app, role-based access control, and instant REST/GraphQL APIs. 37.7k stars. Useful for teams wanting to **layer editorial workflows on top of an existing database**.

- **[Manuskript](https://github.com/olivierkes/manuskript)**  
  An open-source writing tool for authors providing a **structured planning environment**: Snowflake method outline expansion, character management, plot development, index cards, outline view, distraction-free mode, and story line visualization. Primarily focused on fiction writing, but its **chapter/scene organization, metadata tagging, and export capabilities** (HTML, ePub, OpenDocument, DocX) apply well to long-form content planning and editorial workflows. **GPL-3.0**.

### Other Notable Open-Source Options

- **General CMS Foundations**: **Wagtail** (Django, workflow system), **Payload** (TypeScript, deep customization), **Strapi** (JavaScript, flexibility), **Directus** (SQL database layer).
- **Writing & Planning Tools**: **Manuskript** (Snowflake method, character/plot management), **novelWriter** (plain-text writing, metadata syntax).
- **Newsroom-Specific**: **Superdesk** (production-ready, AGPL-3.0, used by major news agencies).

**Framework for Building Custom Systems**: Use **Superdesk** as an out-of-the-box newsroom editorial workflow platform, or start with **Wagtail**, **Payload**, or **Strapi** to build customized editorial pipelines leveraging their workflow engines and access control models (similar to The Ubyssey's Stove project pattern). For content planning stages, **Manuskript**'s Snowflake method and character management can serve as auxiliary planning tools.

## How to Contribute

1. Fork the repository.
2. Add or edit entries in `README.md` following the existing format.
3. Include: Name, link, a 1–2 sentence description, and whether it is SaaS or Open-Source.
4. Submit a PR with a brief summary of your changes.

If you find this repository helpful, please give it a star!

## Disclaimer

- This is a **community-curated** list—it is neither exhaustive nor an endorsement.
- Editorial workflow platforms handle potentially sensitive draft content and internal communications; ensure proper access controls and data protection.
- **Open-Source Reality**: **Superdesk** is the only mature, production-grade open-source alternative built specifically for editorial workflows and actively used by major news agencies. Other open-source CMSs (Wagtail, Payload, Strapi) require custom development to achieve full newsroom-level editorial workflow features. For teams seeking an out-of-the-box solution, Superdesk is the most direct starting point.
