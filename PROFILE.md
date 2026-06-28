# Profile

Last updated: 2026-06-28

## Role

**Design Engineer**  
UI / UX design, web design, frontend implementation, CMS development, and operational improvement  
Implementation context design and production workflows using coding agents

## Overview

Kohei Saito, also known as Kohen, is a design engineer based in Osaka, Japan. He began his career in graphic design in 2003.

His work has expanded across print production, web design, HTML / CSS coding, CMS development such as WordPress, and UI implementation in React / Next.js and Vue / Nuxt environments.

Today, his main focus is frontend implementation that turns design data from tools such as Figma into maintainable UI for existing web services, CMS platforms, and SSG / SSR environments.

The scope is not limited to visual reproduction. It also covers existing codebases, component architecture, naming conventions, CMS update workflows, responsive quality, accessibility, SEO, and structured data.

He places importance on structures that are easy for non-engineer content operators to update, and on implementation rules that production teams can maintain and hand over.

Recent work also includes designing production workflows that incorporate coding agents such as Cursor, Codex, and Claude Code, including implementation instructions, reference files, change scope, review steps, and verification procedures.

## Areas of Focus

* UI implementation for CMS, SPA, SSG, and SSR environments based on Figma designs
* UI component implementation in React, Next.js, Vue, Nuxt, and TypeScript environments
* CMS development for maintainable content operations, including WordPress and ACF
* Design and organization of components, partials, sections, page templates, and landing page blocks
* UI updates aligned with existing codebases, existing components, and design systems
* Responsive implementation, display verification, accessibility, SEO, OGP, and structured data
* Storybook, implementation rules, technical documentation, and operational documentation
* Implementation flow design for AI-agent-based production
* Agent Skill design, ZIP distribution, and release workflows using GitHub Actions
* Documentation designed to be easy for AI assistants to reference
* Technical documents, research notes, and distribution materials using Markdown, YAML, JSON, LaTeX, and related formats

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

* WordPress / ACF / PHP
* WooCommerce / Welcart
* Shopify
* Project-specific CMS platforms

### UI Implementation and Integration

* CMS template design
* Field design for maintainable content updates
* UI integration into SSG / SSR environments
* UI integration into Ruby on Rails applications
* Adaptation to existing design systems
* UI adjustments that balance CMS preview behavior and frontend display quality

### Design

* Figma
* Adobe Photoshop / Illustrator / InDesign

### Development and Operations

* Git / GitHub / GitLab / Bitbucket
* GitHub Actions
* GitHub Pages
* GitHub Releases
* Google Analytics / Google Search Console
* Cursor / Codex / Claude Code

### Technical Writing

* Markdown
* YAML / JSON
* `llms.txt`
* Raw Markdown access paths
* LaTeX / BibTeX / TikZ

## Working Principles

Design and implementation are treated as one continuous process, from requirements clarification, UI design, CMS development, and frontend UI implementation to post-launch operations.

Before implementation, project-specific design rules, codebases, existing components, naming conventions, directory structures, design systems, and CMS update workflows are reviewed.

Based on that context, UI is implemented in a way that stays consistent with the existing environment and remains easy to update, improve, and hand over.

For UI interactions, modals, animations, scroll-linked behavior, and responsive adjustments, the required scope is clarified before implementation or modification.

For projects centered on complex business logic, database design, large-scale back-end development, authentication, or infrastructure, the expected scope is confirmed first and limited to frontend implementation when appropriate.

## Work Style and Environment

* **Remote work readiness**  
  Work has been fully remote since 2017.  
  The working style is based on asynchronous communication through text and documentation, along with self-directed task management.
* **Development environment and tool requirements**  
  Practical work starts by aligning the existing codebase, design data, implementation rules, and verification process.  
  When coding agents are used, generated output is not adopted as-is. It is adjusted to fit project-specific rules and operational conditions.

## Implementation Flow Design for AI-Agent Workflows

Since late 2025, coding agents such as Cursor, Codex, and Claude Code have been introduced into production workflows.

The main target is frontend implementation that integrates Figma designs into existing codebases or CMS templates.

Before production starts, reference files, change scope, areas that should remain unchanged, verification steps, and review procedures are turned into task specifications.

Implementation instructions are designed to provide information in stages instead of exposing everything at once.

This reduces the risk of agents moving too far ahead into implementation and makes it easier to review the impact on existing codebases as work progresses.

Generated code is adjusted to the template structure, field design, naming conventions, responsive requirements, and post-launch update methods.

After implementation, human verification is separated from review by another model when needed.

The review targets include visual output, maintainability, naming, responsive behavior, accessibility, and change scope.

Work in this area includes:

* Turning implementation prompts into task specifications
* Referencing design data and supporting implementation through Figma MCP
* Organizing implementation rules with AGENTS.md, CLAUDE.md, Rules, Commands, and Workflows
* Organizing repeatable tasks with Agent Skills
* Applying Progressive Disclosure to provide necessary information in stages
* Separating agent implementation from human verification
* Reviewing the impact scope on existing codebases
* Organizing technical documentation, operational materials, and review procedures

Related article:

* [Harness Engineering for Figma to Code: Cursor Agents in Client Work](https://medium.com/@imkohenauser/harness-engineering-for-figma-to-code-cursor-agents-in-client-work-6c4a45525ad0) / 2026-06-13

## Personal Project

### MTP (Mapping the Prompt)

MTP (Mapping the Prompt) is a personal project for treating generative AI output styles and response tendencies not only as natural-language instructions, but also as coordinates, intensity values, and presets.

The goal is to make output adjustments reusable through short specifications and to compare multiple response tendencies without writing long natural-language instructions each time.

![Key visual for MTP. The left panel shows Side A / Side B node sliders such as Open-Still and Power-Void, with Power set to 70. The right panel shows a 19x19 column:row color grid labeled A-S and 1-19.](https://raw.githubusercontent.com/imkohenauser/mtp/main/public/ogp%402x.png)

The project mainly consists of:

* Agent Skills
* Input compiler written in Python
* CLI and ZIP distribution
* Bilingual documentation site built with Astro / Starlight
* Deployment and release workflows through GitHub Actions
* Distribution management through GitHub Releases and release JSON
* `llms.txt`, Raw Markdown, and Copy Markdown access paths
* Comparison records across multiple AI models
* Design history and implementation logs published on Medium

MTP also provides machine-readable access paths so that AI assistants can reference the documentation more easily, in addition to human-facing documentation.

Related links:

* Official site: [mappingtheprompt.com/](https://mappingtheprompt.com/)
* GitHub: [github.com/imkohenauser/mtp](https://github.com/imkohenauser/mtp)

Related articles:

* [Packaging an Open Source Agent Skill: CLI Install, ZIP Releases, and Astro/Starlight Docs](https://medium.com/@imkohenauser/packaging-an-open-source-agent-skill-cli-install-zip-releases-and-astro-starlight-docs-8a57e75d8a0c) / 2026-05-28
* [Mapping the Prompt: Steering LLM Output with a 3x3 Color Grid](https://medium.com/@imkohenauser/mapping-the-prompt-steering-llm-output-with-a-3x3-color-grid-a565452b7022) / 2026-06-05

---

## Professional Experience

### 2024/03-Present

| Item | Details |
|------|------|
| Type | Contract web production and frontend implementation support |
| Role | UI / UX design, web design, frontend implementation, CMS template design, operational improvement |
| Team | Solo or small-team projects |
| Main Stack / Tools | Figma, WordPress / ACF / PHP, project-specific CMS platforms, Shopify, HTML, CSS, Sass, Tailwind CSS, JavaScript, TypeScript, React, Next.js, GitHub, Cursor, Codex, Claude Code |
| Overview | Handles contract web production work, including design, coding, CMS development, existing-site improvements, and operational support. Recent work includes frontend implementation and CMS template design for large corporate websites and recruitment-related content areas. |
| Main Work | Integration of Figma designs into CMS, SSG, and SSR environments<br>Theme implementation for WordPress-based CMS setups<br>ACF, CPT, category taxonomy, and editing-screen design<br>Section and page template implementation designed for CMS editability<br>UI component implementation in React / Next.js environments<br>Responsive support, display verification, and operational documentation<br>Implementation instructions, review procedures, and documentation for AI-agent-based workflows |
| Contributions | In WordPress-based projects, organized major templates, CPTs, ACF fields, shared components, and implementation rules for recruitment-related content areas. In projects using project-specific CMS platforms, handled template development for corporate sites with many sections and pages, balancing content editability with frontend display quality. |

### 2023/08-2024/02

| Item | Details |
|------|------|
| Type | Corporate and product site operations for a large company |
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
| Overview | Participated for more than six years as an external product partner in multiple web services operated by a company listed on the Tokyo Stock Exchange Prime Market. Worked on UI design, component implementation, and design system maintenance across multiple services. |
| Main Work | UI design and component management in Figma<br>UI implementation with Tailwind CSS<br>Integration into Vue.js / Nuxt.js and React / Next.js environments<br>Component sharing and design system maintenance with Storybook<br>Collaboration with in-house engineers and designers<br>UI updates aligned with existing codebases, design rules, and brand requirements<br>Team development and code review using GitHub |
| Contributions | Worked on adaptation to existing codebases, UI consistency, and continuous improvement aligned with release cycles in an environment where multiple services were running in parallel. |

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

### 2003-2006/03

| Item | Details |
|------|------|
| Type | Independent graphic design work |
| Role | Graphic designer |
| Main Stack / Tools | Adobe Illustrator, Adobe Photoshop |
| Overview | Produced graphic design work, mainly event announcements, including flyers, posters, and logos. |

---

## Selected Experience

### WordPress-Based Corporate Site Renewal

Handled recruitment-related content areas in a WordPress-based CMS setup.

Implemented section-level navigation, landing pages, and article-style listing and detail pages based on Figma designs.

The scope included CPTs, category taxonomies, ACF field groups, breadcrumbs, pagination, shared components, liquid layout, and accessibility support.

AGENTS.md was used to define change scope, files that should not be touched, Figma MCP usage, BEM + FLOCSS rules, ACF tab design, verification URLs, and prohibited operations.

### CMS Template Development and Large Corporate Site Builds

Handled frontend development for corporate websites using project-specific CMS platforms.

The scope included section development with Handlebars, SCSS, and JavaScript; interactions using Swiper, GSAP, and Lottie; CMS-editable structures; SEO settings; and structured data.

Work also included template design, page structure, and component organization to balance CMS editability from the admin interface with frontend display quality.

### UI Implementation and Design System Operations for Large-Scale Web Services

Participated long-term as an external product partner in multiple web services operated by a company listed on the Tokyo Stock Exchange Prime Market.

Using Figma, Tailwind CSS, Vue / Nuxt, React / Next.js, and Storybook, worked on UI improvements, component implementation, and design system operations aligned with existing codebases.

The work involved continuous UI improvement while balancing service-specific requirements with shared design system consistency.

---

## Writing and Publications

Articles are published on Medium.

Related articles:

* [Harness Engineering for Figma to Code: Cursor Agents in Client Work](https://medium.com/@imkohenauser/harness-engineering-for-figma-to-code-cursor-agents-in-client-work-6c4a45525ad0)
* [Packaging an Open Source Agent Skill: CLI Install, ZIP Releases, and Astro/Starlight Docs](https://medium.com/@imkohenauser/packaging-an-open-source-agent-skill-cli-install-zip-releases-and-astro-starlight-docs-8a57e75d8a0c)
* [Mapping the Prompt: Steering LLM Output with a 3x3 Color Grid](https://medium.com/@imkohenauser/mapping-the-prompt-steering-llm-output-with-a-3x3-color-grid-a565452b7022)

---

## Links

| Platform | URL |
|----------|-----|
| GitHub | [github.com/imkohenauser](https://github.com/imkohenauser) |
| Medium | [medium.com/@imkohenauser](https://medium.com/@imkohenauser) |
| Zenn | [zenn.dev/imkohenauser](https://zenn.dev/imkohenauser) |
| X | [x.com/imkohenauser](https://x.com/imkohenauser) |
| MTP | [mappingtheprompt.com/](https://mappingtheprompt.com/) |
