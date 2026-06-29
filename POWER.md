# CAST Imaging Power

Connect to CAST Imaging for comprehensive software intelligence, architecture analysis, and quality insights across your application portfolio.

## Overview

CAST Imaging is an enterprise-grade software intelligence platform that automatically analyzes your applications to reveal their architecture, dependencies, and quality issues. This power enables AI-assisted exploration of:

- **Application Portfolio** - Compare metrics and dependencies across all applications
- **Architecture** - Visualize structure at multiple abstraction levels
- **Transactions** - Understand business flows through your codebase  
- **Data Graphs** - Trace data flows across your application
- **Quality Insights** - Identify CVEs, structural flaws, ISO-5055 violations, cloud & green patterns
- **Code Objects** - Deep dive into classes, methods, tables with caller/callee analysis
- **Documentation** - Add post-its and tags to preserve knowledge

## Setup

When you first activate this power, you'll be prompted for:

1. **CAST Imaging URL** (required)
   - Example: `https://presales-in.castsoftware.com`
   - The base URL of your CAST Imaging instance

2. **API Key** (required)
   - Generate from your CAST Imaging profile
   - See: [Generating an API key](https://doc.castsoftware.com/imaging/administer/profile/#generating-an-api-key)

3. **Tenant/Domain** (optional)
   - Only needed if you work with multiple tenants
   - Leave empty for single-tenant setups

## Example Queries

**Portfolio Level:**
```
Show me all applications in CAST Imaging
Which application has the largest number of transactions?
List quality insights across all applications
```

**Application Level:**
```
List 5 transactions for application Shopizer
Explain the architecture of Shopizer at User Interaction Level
List the top 5 structural flaws by occurrence count in Shopizer
Show all ISO-5055 quality insights in Shopizer
```

**Transaction & Data Flow:**
```
Explain the entire graph of customer-create-link transaction in Shopizer
List all data call graphs in Shopizer containing "CATEGORIES"
Add a post-it on transaction customer-create-link with title "Review needed"
```

**Code Objects:**
```
Get details about class CustomerService in Shopizer
Find all transactions using object pageProductReviews
Show me the callers and callees of method processPayment
```

## Available Tool Categories

### Portfolio Tools
Explore applications, dependencies, quality insights, transactions, and data graphs across your entire portfolio

### Application Tools  
Deep dive into architecture, transactions, data graphs, quality insights, advisors, packages, and statistics for specific applications

### Object Tools
Examine individual code artifacts (classes, methods, tables) with detailed dependency analysis and relationship mapping

## Best Practices

- **Use specific application names** - Tools work best with exact app names
- **Start broad, then narrow** - List apps first, then drill into specific areas
- **Leverage filtering** - Most tools support name-based filtering
- **Preserve knowledge** - Use post-its to document findings directly in CAST Imaging

## Recommended AI Models

Based on CAST's testing with tool invocation and reasoning:

- **Claude Sonnet 4.5/4.6** - Best for complex, multi-step queries
- **Claude Haiku 4.5** - Fast and cost-effective for simpler queries
- **GPT-5/5.1/5.2** - Good for moderate complexity

## Requirements

- CAST Imaging ≥ 3.4.0-funcrel (recommended ≥ 3.5.9-funcrel)
- Valid API key with appropriate permissions
- Network access to your CAST Imaging instance

## Learn More

- [CAST Imaging MCP Documentation](https://doc.castsoftware.com/imaging/mcp-server/imaging/)
- [CAST Imaging API Reference](https://doc.castsoftware.com/imaging/imaging-api/)
- [Available Toolsets Guide](https://doc.castsoftware.com/imaging/mcp-server/imaging/windows/#available-toolsets)
