# Week 0: Pre-Launch (Dec 15-28, 2025)

## Setup Completed
- [x] GitHub repo created (Dec 15)
- [x] Folder structure added
- [x] README with Q1-Q4 goals written
- [x] MCP server use case DEFINED (Dec 15)
- [ ] AWS study resource chosen (by Dec 16)
- [ ] AWS account ready (by Dec 16)
- [ ] Graph Studio access confirmed (by Dec 16)
- [ ] Weekly progress template saved (by Dec 15)
- [ ] Project README created (by Dec 15)

## MCP Server Use Case: Supply Chain Risk Intelligence

### Problem It Solves
GSI (Global System Integrator) partners need reference implementations showing how to build MCP servers on RapidMiner Graph Studio. Supply chain risk is a universal enterprise problem where graph databases provide clear advantages over traditional relational databases.

### Why MCP Is The Right Choice
MCP enables multi-hop graph traversals based on conversational context. Claude dynamically selects appropriate queries (impact analysis, alternative suppliers, risk assessment) based on user questions. This conversational workflow is superior to static REST APIs because:
- Context from previous queries informs next steps
- Natural language questions map to complex graph traversals
- Users don't need to know graph query languages (Cypher/SPARQL)

### Scope (MVP)
**Knowledge Graph:**
- 50-100 nodes (suppliers, products, manufacturing locations)
- Realistic synthetic data (generated via Python + Claude)
- Loaded into RapidMiner Graph Studio demo instance

**MCP Server - 5 Core Tools:**
1. **supply_chain_impact** - Analyze impact of supplier disruptions
2. **find_alternatives** - Identify alternative suppliers by distance/capacity
3. **risk_assessment** - Generate risk scores for products/suppliers
4. **dependency_map** - Visualize full supply chain dependencies
5. **generate_report** - Create formatted risk analysis reports

**Technology:**
- RapidMiner Graph Studio (company's graph database product)
- Python MCP server (FastMCP or official MCP SDK)
- Read-only queries (no write operations in V1)

### Target Audience
**Primary:** GSI partners who ask about MCP/Agent integration with knowledge graphs
**Secondary:** Internal presales team for prospect demos
**Tertiary:** Product marketing, technical prospects

### Success Metrics
- Partners can replicate the implementation
- Presales can demo convincingly
- Shows clear value of graph + AI integration
- Demonstrates technical depth + business thinking

## Project Timeline (Aggressive)

**Week 1 (Jan 6-12):** Foundation + synthetic data + graph loaded
**Week 2 (Jan 13-19):** First 3 MCP tools working end-to-end
**Week 3 (Jan 20-26):** Final 2 tools + polish + error handling
**Week 4 (Jan 27-Feb 2):** Partner playbook + demo video + internal tech talk

**Target Completion:** February 2, 2025

## Deliverables

### Technical Deliverables
- ✅ Working MCP server with 5 query tools
- ✅ Sample knowledge graph (exportable for partners)
- ✅ Clean, documented code in GitHub
- ✅ Architecture diagram

### Enablement Deliverables
- ✅ Partner playbook (step-by-step implementation guide)
- ✅ Demo video (5 minutes showing all queries + business value)
- ✅ Internal tech talk (25-minute Loom recording)
- ✅ GitHub repo with comprehensive README

### Portfolio Deliverables
- ✅ Blog post: "Building Supply Chain Risk MCP on Graph Studio"
- ✅ LinkedIn content series (weekly updates)
- ✅ Case study (if we get partner usage data)

## Why This Project Matters

**For Partners:**
Reference implementation they can customize for their enterprise clients. Supply chain risk is universally relevant (manufacturing, retail, healthcare).

**For Company:**
- Accelerates partner adoption of Graph Studio + MCP
- Ready-to-use demo asset for presales
- Shows thought leadership in AI + knowledge graphs

**For My Career:**
- Demonstrates product expertise (Graph Studio)
- Shows partner enablement thinking (not just internal focus)
- Combines technical depth (MCP, graphs) + business value (partner adoption)
- Creates reusable content (playbook, video, talk)

## Pre-Vacation Tasks (Dec 15-18)

**Dec 15 (Today):**
- [x] Finalize use case
- [ ] Create weekly template
- [ ] Create project README

**Dec 16:**
- [ ] Choose AWS study resource
- [ ] Set up AWS account
- [ ] Verify Graph Studio access

**Dec 17:**
- [ ] Design data model with Claude
- [ ] Set up Python environment
- [ ] Create data generation skeleton

**Dec 18:**
- [ ] Update project README with schema
- [ ] Create Week 1 execution plan
- [ ] Optional: LinkedIn announcement

## Vacation: Dec 19-28
**Zero guilt zone.** All setup complete. Just enjoy the break.

No coding. No studying. No planning.

Optional if genuinely bored:
- Skim AWS materials
- Think about supply chain scenarios
- But truly: just rest

## Post-Vacation Prep (Dec 29)
One-hour review:
- [ ] Confirm Graph Studio access still works
- [ ] Review Week 1 plan
- [ ] Set calendar blocks for 10 hrs/week starting Jan 6

## Commitment
I'm following the uncomfortable path: building assets with real business value, not just personal projects.

This MCP server will:
1. ✅ Help GSI partners integrate AI with our product
2. ✅ Enable presales to demo effectively
3. ✅ Demonstrate my technical depth + business acumen
4. ✅ Create reusable enablement content

**No browsing courses. No adding resources. Just: build → document → ship.**

---
*Created: December 15, 2025*
*Next Update: December 29, 2025 (post-vacation check-in)*
*Full Sprint Starts: January 6, 2025*
