# Profile

Last updated: 2026-06-13

## Role

**Design Engineer**  
UI / UX design, web design, frontend implementation, CMS development and operational support  
Implementation context design and production workflows using coding agents

## Overview

Kohei Saito, also known as Kohen, is a design engineer based in Osaka, Japan. He began his career in graphic design in 2003 and has expanded his work across print production, web design, HTML / CSS coding, CMS development, and frontend UI implementation. Today, this work spans UI / UX design, CMS development, frontend UI implementation, and post-launch operational support.

A particular strength is integrating design data from tools such as Figma into existing systems and operational workflows as usable UI. Beyond visual reproduction, the focus is on design rules, codebases, and update workflows, turning designs into structures that can be maintained over time.

Recent work also includes designing development workflows that incorporate coding agents into production processes, including implementation instructions and review steps.

## Areas of Focus

* UI implementation for CMS, SSG / SSR environments based on Figma designs
* UI design and implementation for websites, landing pages, and web services
* CMS development for maintainable content operations, including WordPress and Shopify
* UI updates aligned with existing codebases, components, and design rules
* Responsive implementation, display verification, and post-launch maintainability
* Production workflow design using coding agents
* Harnesses and guardrails using implementation prompt specifications, Rules, Agent Skills, and file structures
* UI specifications, operational documentation, and technical documentation

## Technical Stack

### Front End

* HTML / CSS / Sass
* JavaScript / TypeScript
* React / Next.js
* Vue.js / Nuxt.js
* Astro / Starlight
* Tailwind CSS
* Storybook
* Webpack / Vite

### CMS / E-Commerce

* WordPress / WooCommerce / WelCart
* Shopify

### UI Implementation and Integration

* CMS template design
* Field design for maintainable content updates
* UI integration into SSG / SSR environments
* UI integration into Ruby on Rails applications
* Site design and implementation using GitHub Primer, Material Design, and similar systems
* Adaptation to existing codebases and design systems

### Design

* Figma / Pencil / Paper
* Adobe Photoshop / Illustrator / InDesign

### Development and Operations

* GitHub / GitLab / Bitbucket
* Google Analytics / Google Search Console

### Coding Agents and Generative AI

* Cursor
* Codex
* Claude Code

## Working Principles

Design and implementation are treated as one continuous process, from requirements clarification, UI design, CMS development, and frontend UI implementation to post-launch operations.

Before implementation, project-specific design rules, codebases, existing components, naming conventions, directory structures, and design systems are reviewed. Based on that context, UI is implemented in a way that stays consistent with the existing environment and remains easy to update and improve.

For UI interactions, modals, animations, scroll-linked behavior, and responsive adjustments, the required scope is clarified before implementation or modification.

For projects centered on complex business logic, database design, or large-scale back-end development, the expected scope of responsibility is confirmed first.

## Work Style and Environment

* **Remote work readiness**  
  Work has been fully remote since 2017, with a strong fit for asynchronous communication based on text and documentation, as well as self-directed task management.
* **Development environment and tool requirements**  
  Because the workflow assumes coding agents for production efficiency and quality, Cursor or an equivalent AI-integrated IDE is considered essential for practical work.

## Implementation Context Design for Coding-Agent Workflows

Since late 2025, coding agents such as Cursor, Codex, and Claude Code have been introduced into production workflows.

The main target is frontend implementation that integrates design data into existing codebases or CMS templates. Before production starts, reference files, change scope, areas that should remain unchanged, and review steps are turned into task specifications.

Generated code is not used as-is. Instead, it is adjusted to the template structure, field design, naming conventions, responsive requirements, and post-launch update methods so that it can be maintained in production.

Rules, Commands, Workflows, and Agent Skills are also designed as harnesses and guardrails to keep agents from moving in unintended directions.

Work in this area includes:

* Turning implementation prompts into task specifications
* Referencing design data and supporting implementation through Figma MCP
* Designing harnesses and guardrails with Rules, Commands, Workflows, and Agent Skills
* Applying Progressive Disclosure to provide necessary information in stages
* Separating agent implementation from human review
* Reviewing the impact scope on existing codebases
* Organizing technical documentation and operational materials

Related article:

* [Harness Engineering for Figma to Code: Cursor Agents in Client Work](https://medium.com/@imkohenauser/harness-engineering-for-figma-to-code-cursor-agents-in-client-work-6c4a45525ad0) / 2026-06-13

## Personal Project

### MTP (Mapping the Prompt)

MTP is an interface for treating generative AI (large language model) output styles and response tendencies not only as natural language instructions, but also as coordinates, intensity values, and presets. The project aims to make output adjustments reusable with short specifications and to compare multiple response tendencies without writing long natural-language instructions each time.

![Key visual for MTP. The left panel shows Side A / Side B node sliders such as Open-Still and Power-Void, with Power set to 70. The right panel shows a 19x19 column:row color grid labeled A-S and 1-19.](https://raw.githubusercontent.com/imkohenauser/mtp/main/public/ogp%402x.png)

The project mainly consists of:

* Agent Skills
* Input compiler written in Python
* CLI and ZIP distribution
* Official documentation built with Astro / Starlight
* Deployment and releases through GitHub Actions
* Comparison records across multiple AI models
* Design history and implementation logs published on Zenn and Medium

Related links:

* Official site: [mappingtheprompt.com/](https://mappingtheprompt.com/)
* GitHub: [github.com/imkohenauser/mtp](https://github.com/imkohenauser/mtp)

Related articles:

* For development operations: [Packaging an Open Source Agent Skill: CLI Install, ZIP Releases, and Astro/Starlight Docs](https://medium.com/@imkohenauser/packaging-an-open-source-agent-skill-cli-install-zip-releases-and-astro-starlight-docs-8a57e75d8a0c) / 2026-05-28
* For users: [Mapping the Prompt: Steering LLM Output with a 3x3 Color Grid](https://medium.com/@imkohenauser/mapping-the-prompt-steering-llm-output-with-a-3x3-color-grid-a565452b7022) / 2026-06-05

---

## Professional Experience

### 2024/03-Present

| Item | Details |
|------|------|
| Type | Contract web production and frontend implementation support |
| Role | UI / UX design, web design, frontend implementation, production direction |
| Team | Solo or small-team projects |
| Main Stack / Tools | Figma, WordPress, Shopify, HTML, CSS, Tailwind CSS, JavaScript, TypeScript, React, Next.js, GitHub, Cursor, Codex, Claude Code |
| Overview | Handles contract web production work, including design, coding, CMS development, existing-site improvements, and operational support. |
| Main Work | Website and landing page design and implementation<br>Integration of Figma designs into CMS, SSG / SSR environments<br>WordPress theme adjustments and template modifications<br>Shopify site development<br>UI component implementation in React / Next.js environments<br>UI implementation with Tailwind CSS<br>Responsive support, display verification, and operational documentation<br>Improving implementation workflows using coding agents |

### 2023/08-2024/02

| Item | Details |
|------|------|
| Type | Corporate and product site operations for a major food manufacturer |
| Role | Web designer, coder |
| Main Stack / Tools | Adobe Photoshop, Adobe Illustrator, HTML, CSS, jQuery |
| Overview | Produced and updated pages, and handled design revisions for corporate and product sites according to existing operational rules. |
| Main Work | HTML / CSS / jQuery implementation based on design data<br>Updates to existing static pages and template modifications<br>Design revisions and banner production for product and campaign pages<br>Responsive support and display verification |

### 2017/03-2023/07

| Item | Details |
|------|------|
| Type | UI design and frontend implementation for large-scale web services |
| Role | UI / UX design, frontend implementation |
| Main Stack / Tools | Figma, Tailwind CSS, Vue.js, Nuxt.js, React, Next.js, Storybook, Webpack, GitHub |
| Overview | Participated for more than six years as an external product partner in a multi-brand group of web services operated by a company listed on the Tokyo Stock Exchange Prime Market and used by millions of users. Worked on UI design, component implementation, and design system maintenance across multiple services, balancing service-specific requirements with group-wide design consistency. |
| Main Work | UI design and component management in Figma<br>UI implementation with Tailwind CSS<br>Integration into Vue.js / Nuxt.js and React / Next.js environments<br>Component sharing and design system maintenance with Storybook<br>Collaboration with in-house engineers and designers<br>UI updates aligned with existing codebases, design rules, and brand requirements<br>Team development and code review using GitHub |
| Contributions | Contributed to adaptation within existing codebases, consistency of UI, and continuous improvement aligned with release cycles in an environment where multiple services were running in parallel. |

### 2012/04-2017/03

| Item | Details |
|------|------|
| Type | Web design and CMS development at a production company |
| Role | Web designer, coder |
| Main Stack / Tools | Adobe Photoshop, Adobe Illustrator, WordPress, HTML, CSS, Sass, JavaScript, jQuery, PHP |
| Overview | Worked on websites for companies, stores, and educational organizations, covering design, coding, CMS development, and operational support end to end. |
| Main Work | Web design<br>Implementation with HTML / CSS / Sass / jQuery<br>WordPress theme and plugin development<br>Small-scale e-commerce site development<br>CSS architecture with BEM / FLOCSS<br>Requirements clarification and content update support |

### 2009/03-2012/04

| Item | Details |
|------|------|
| Type | Web production and print production at a production company |
| Role | Web designer, coder |
| Main Stack / Tools | Adobe Photoshop, Adobe Illustrator, Adobe InDesign, WordPress, Concrete CMS, HTML, CSS, JavaScript, PHP |
| Overview | Worked on website production, CMS development, operational support, and print production. |
| Main Work | Website design, implementation, and operation<br>CMS development with WordPress and Concrete CMS<br>UI design for portal sites<br>DTP production for booklets and public relations materials |

### 2006/04-2009/03

| Item | Details |
|------|------|
| Type | Graphic design and web production at a production company |
| Role | Graphic designer, web designer, coder |
| Main Stack / Tools | Adobe Photoshop, Adobe Illustrator, HTML, CSS, JavaScript, PHP |
| Overview | Worked on branding, print production, and website development for new companies and stores. Also experienced project coordination and production guidance for the web production team. |
| Main Work | Logo, brand guideline, and print design<br>Website development with HTML / CSS / JavaScript<br>Web production coordination<br>Guidance for production members |
| Contributions | Worked extensively on logo design, typically proposing three directions per project. Delivered more than 30 logos per year for companies and organizations, using the golden ratio and providing brand color specifications and design sheets with the final deliverables. |

### 2003-2006/03

| Item | Details |
|------|------|
| Type | Independent graphic design work |
| Role | Graphic designer |
| Main Stack / Tools | Adobe Illustrator, Adobe Photoshop |
| Overview | Produced graphic design work, mainly event announcements, including flyers, posters, and logos. |

---

## Links

| Platform      | URL                                                          |
|---------------|--------------------------------------------------------------|
| GitHub        | [github.com/imkohenauser](https://github.com/imkohenauser)   |
| Medium        | [medium.com/@imkohenauser](https://medium.com/@imkohenauser) |
| Zenn          | [zenn.dev/imkohenauser](https://zenn.dev/imkohenauser)       |
| X             | [x.com/imkohenauser](https://x.com/imkohenauser)             |
