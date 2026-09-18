# Site Graph

**[Click here to open the live application](https://robertpotter-dev.github.io/sitegraph/)**

> **Note:** This repository hosts the compiled, stable production build of Site Graph.

## What is Site Graph?

Site Graph is a browser-native, offline-first network documentation and planning tool.

It replaces messy spreadsheets and outdated Visio diagrams by modeling your IT infrastructure as a strict property graph—mapping the exact relationships between devices, interfaces, IP addresses, circuits, and physical locations.

### Key Features:

- **Client-Side Application:** No SiteGraph backend, database server, or telemetry. Working data is held in browser IndexedDB; portable JSON exports remain under your control. The hosted app and any external page assets require network access when first loaded unless they are already cached.
- **Data Custody:** Export your topology as a JSON file that you control. Save it to an encrypted drive, sync it through infrastructure you select, or share it through an approved channel.
- **Schema and Graph Validation:** The system enforces IP assignment rules, duplicate checking, and valid physical cabling paths.
- **AI-Ready Exports:** Generate instant LLM digests, Neo4j Cypher graphs, or traditional Excel `.xlsx` spreadsheets straight from your topology data.

## Versioning & Architecture

- **Application Version:** v1.0.0 (Stable Production Build)
- **Schema Version:** v4 (strict IPv4 property graph with document-local roles and typed fields)
- **Architecture:** Self-contained compiled HTML application with no application backend services (Progressive Web App compatible).

The public repository contains the compiled deployment. The source repository and build pipeline are private. Public visibility of compiled assets does not grant an open-source license or permission to copy, modify, or redistribute SiteGraph.

Copyright © 2026 Robert E. Potter. All Rights Reserved.
