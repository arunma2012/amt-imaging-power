# Getting Started with CAST Imaging

This guide helps you get started using CAST Imaging through Kiro.

## First Steps

### 1. Activate the Power

When you first use CAST Imaging tools, you'll be prompted for:

- **URL**: Your CAST Imaging instance URL (e.g., `https://your-instance.castsoftware.com`)
- **API Key**: Generate this from your CAST Imaging profile
- **Tenant**: Optional - only if you use multiple tenants/domains

### 2. Verify Connection

Test your connection with a simple query:

```
List all applications
```

If successful, you'll see a list of applications available in your CAST Imaging instance.

## Common Workflows

### Exploring Your Portfolio

**See all applications:**
```
Show me all applications in CAST Imaging
```

**Compare application sizes:**
```
Which applications are the largest by lines of code?
```

**Check dependencies:**
```
Show me inter-application dependencies
```

### Analyzing an Application

**Get overview:**
```
Show me stats for application MyApp
```

**Explore architecture:**
```
Visualize the architecture of MyApp at component level
```

**List transactions:**
```
List the top 10 transactions in MyApp
```

**Check quality:**
```
List all structural flaws in MyApp
Show me CVE vulnerabilities in MyApp
```

### Deep Dive into Transactions

**Understand a transaction:**
```
Explain the customer-checkout transaction in MyApp
```

**See transaction complexity:**
```
Show me the most complex objects in the payment-process transaction
```

**Find quality issues:**
```
List quality insights in the customer-login transaction
```

### Working with Data Flows

**List data graphs:**
```
Show me all data call graphs in MyApp
```

**Analyze a data flow:**
```
Explain the CUSTOMER_ORDERS data graph
```

**Find data-related issues:**
```
Show me quality insights in the USER_PROFILE data graph
```

### Object-Level Investigation

**Find objects:**
```
Search for objects named "Customer" in MyApp
```

**Get object details:**
```
Show me details about class CustomerService
```

**Understand dependencies:**
```
Show me all callers of method processPayment
What objects does CustomerRepository call?
```

**Find usage:**
```
Which transactions use the Customer class?
```

### Quality Analysis

**CVE vulnerabilities:**
```
List all CVE vulnerabilities in MyApp
```

**Structural issues:**
```
Show me the top 5 structural flaws by occurrence count
```

**ISO-5055 violations:**
```
List all ISO-5055 violations in MyApp
```

**Cloud patterns:**
```
Show me cloud maturity patterns in MyApp
```

**Green patterns:**
```
List green/sustainability patterns in MyApp
```

### Documentation & Knowledge Capture

**Add post-its:**
```
Add a post-it on transaction customer-checkout with title "Needs refactoring" and description "Complex logic should be simplified"
```

**Tag objects:**
```
Add tags "critical,security" to object CustomerService
```

## Tips for Best Results

1. **Be specific with names** - Use exact application, transaction, or object names
2. **Start broad** - List applications first, then narrow down
3. **Use filtering** - Most tools support filtering by name patterns
4. **Combine queries** - Ask for multiple related things in one query
5. **Preserve findings** - Use post-its to document important discoveries

## Troubleshooting

**Connection issues:**
- Verify your URL is correct and accessible
- Check that your API key is valid
- Ensure network access to CAST Imaging

**Empty results:**
- Confirm the application name is correct
- Check that data exists for your query
- Verify tenant selection (if applicable)

**Tool errors:**
- Check that your CAST Imaging version is compatible (≥ 3.4.0-funcrel)
- Ensure your API key has appropriate permissions

## Next Steps

Once comfortable with basic queries, explore:
- **Advisors** - Migration and modernization guidance
- **Custom views** - Create and manage custom aggregations
- **Package analysis** - Understand external dependencies
- **Architecture focus** - Zoom into specific architectural areas

For complete documentation, see:
https://doc.castsoftware.com/imaging/mcp-server/imaging/
