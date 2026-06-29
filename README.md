# CAST - Making AI smarter

A Kiro Power that empowers your AI with deep software intelligence from CAST Imaging.

## Overview

Explore application architecture, trace business flows, analyze quality issues, and understand complex codebases through natural language queries. Connect CAST Imaging's enterprise-grade analysis platform directly to your AI assistant for instant insights into your entire application portfolio.

## Features

- **Portfolio Analysis** - View and compare all applications in your organization
- **Architecture Exploration** - Visualize application structure at multiple abstraction levels
- **Transaction Analysis** - Trace business flows through your codebase
- **Data Flow Mapping** - Understand how data moves across your application
- **Quality & Security Insights** - Identify CVEs, structural flaws, ISO-5055 violations
- **Code Object Deep Dive** - Examine classes, methods, with caller/callee analysis
- **Knowledge Preservation** - Add notes and tags to document findings

## Installation

### In Kiro:

1. Open Command Palette (`Ctrl+Shift+P`)
2. Search for "Powers" or click the Powers icon
3. Click "Add Custom Power"
4. Enter this repository URL or browse to the local folder

### Configuration:

When first used, you'll be prompted for:
- **CAST Imaging URL** (e.g., `https://your-instance.castsoftware.com`)
- **API Key** (generate from your CAST Imaging profile)
- **Tenant** (optional, only for multi-tenant setups)

## Usage Examples

```
Show me all applications in CAST Imaging
List transactions for application MyApp
Explain the architecture of MyApp at component level
Show quality insights for MyApp
Find all CVE vulnerabilities in MyApp
```

## Requirements

- Kiro AI IDE
- CAST Imaging ≥ 3.4.0-funcrel (recommended ≥ 3.5.9-funcrel)
- Valid CAST Imaging API key
- Network access to your CAST Imaging instance

## Author

Created by AMT

## License

MIT