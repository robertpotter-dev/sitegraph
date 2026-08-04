# Site Graph

**[Click here to open the live application](https://robertpotter-dev.github.io/sitegraph/)**

> **Note:** This repository hosts the compiled, stable production build of Site Graph.

## What is Site Graph?

Site Graph is a browser-native, offline-first network documentation and planning tool.

It replaces messy spreadsheets and outdated Visio diagrams by modeling your IT infrastructure as a strict property graph—mapping the exact relationships between devices, interfaces, IP addresses, circuits, and physical locations.

### Key Features:

- **100% Client-Side:** No server, no database, no internet connection required. The entire application runs directly in your browser.
- **Data Sovereignty:** Your entire network topology is stored in a single JSON file that you control. Save it to an encrypted drive, sync it via your enterprise cloud, or securely email it to a colleague.
- **Enterprise-Grade Validation:** The system strictly enforces IP assignment rules, duplicate checking, and valid physical cabling paths.
- **AI-Ready Exports:** Generate instant LLM digests, Neo4j Cypher graphs, or traditional Excel `.xlsx` spreadsheets straight from your topology data.

## Versioning & Architecture

- **Application Version:** v1.0.0 (Stable Production Build)
- **Schema Version:** v4 (strict IPv4 property graph with document-local roles and typed fields)
- **Architecture:** Zero-dependency single-file HTML application (Progressive Web App compatible).

_For source code access, issue tracking, or development contributions, please refer to the private development repository._
