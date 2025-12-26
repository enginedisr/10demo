# 10Demo

**AI Agent for Instant, Personalized Product Demos**

## Project Overview

**10Demo** is an AI-powered demo agent that instantly joins live video calls with prospects to deliver personalized product demonstrations—eliminating wait times, scheduling friction, and demo no-shows.

### The Problem

VPs of Sales at B2B SaaS companies face a critical pipeline problem:
- **24-120 hour wait times** for product demos
- **40-60% demo no-show rates** leading to massive pipeline leakage
- **Generic, one-size-fits-all** presentations that don't resonate
- **Inability to scale demos** without expensive headcount additions
- **Lost revenue** from delayed or missed opportunities

### The Solution

10Demo is an AI agent that:
- ✨ **Instantly joins** live video calls the moment prospects request demos
- 🎯 **Delivers personalized**, context-aware product demonstrations
- 🌍 **Operates 24/7** in any language
- 🔗 **Integrates with CRM** systems to pull relevant prospect data
- 📈 **Scales demo capacity** without hiring more sales reps

### Target Market

**Primary**: VPs of Sales at B2B SaaS companies
- Company size: 50-500 employees
- Revenue: $10M-$100M ARR
- Pain points: Demo scheduling delays, high no-show rates, scaling challenges

**Secondary Personas**:
- Sales Enablement Leaders (demo quality and consistency)
- Account Executives (daily workflow and time optimization)
- Founders/CEOs at early-stage companies (resource constraints)

---

## Current Phase: Ideation (Recipe 1.1 - Problem Validation)

This repository is in the **Problem Validation** phase, focused on conducting customer discovery interviews to validate:
1. **Problem severity**: Is the demo scheduling/no-show problem real and painful?
2. **Solution resonance**: Does the AI demo agent concept resonate with target buyers?
3. **Willingness to pay**: Do prospects have budget and intent to purchase?

### Validation Approach

Following **The Mom Test** principles, we're conducting 10-15 structured interviews across 4 target personas to gather quantitative and qualitative validation data.

---

## Repository Structure

```
10demo/
├── memory/                          # Core venture definition
│   └── statement.md                 # Idea and solution statements
│
├── phases/                          # Development phases
│   └── ideation/                    # Current phase: Ideation
│       └── artifacts/
│           └── 1.1/                 # Recipe 1.1: Problem Validation
│               ├── artifact.md                      # Package overview
│               └── materials/
│                   ├── interview-execution-guide.md # 4 personas + 27-question script
│                   └── interview-tracking-template.md # KPI data collection
│
├── .mcp.json                        # MCP server integrations
├── CLAUDE.md                        # Claude Code agent guidance
└── README.md                        # This file
```

### Key Directories

- **`memory/`**: Source of truth for the venture's problem and solution statements
- **`phases/ideation/artifacts/1.1/`**: Complete Recipe 1.1 interview materials for customer discovery
- **`.mcp.json`**: Configuration for external data sources (Tavily, Reddit, Weather)

---

## Key Features

### 1. Phase-Based Development

The repository follows a structured venture development methodology:
- **Ideation Phase** (Current): Problem and solution validation
- **Validation Phase** (Future): MVP testing and iteration
- **Build Phase** (Future): Full product development
- **Launch Phase** (Future): Go-to-market execution

### 2. Recipe System with KPIs

Each "Recipe" is a discrete validation milestone with:
- **Artifacts**: Templates, guides, and execution materials
- **Quantitative KPIs**: Specific success criteria with target thresholds
- **Analyzer Agent**: Post-execution analysis for Pass/Fail determination
- **Clear Next Steps**: Transition logic based on validation results

### 3. Interview-Driven Validation

Recipe 1.1 centers on 10-15 customer discovery interviews following **The Mom Test**:
- Talk about their life, not your idea
- Ask about specifics in the past, not hypotheticals
- Listen 70%, talk 30%
- Never pitch—present neutrally
- Seek commitments, not compliments

---

## Target Personas (Recipe 1.1)

### 1. VP of Sales (Primary Buyer)
**Target**: 5-6 interviews (40-50%)
- **Company**: 50-500 employees, $10M-$100M ARR
- **Role**: Economic buyer with budget authority
- **Pain Points**: Pipeline leakage, scaling challenges, demo inefficiency
- **Focus Areas**: ROI, team productivity, conversion rates

### 2. Sales Enablement Leader (Influencer)
**Target**: 3-4 interviews (25-30%)
- **Company**: 100-1000 employees, $20M-$200M ARR
- **Role**: Tool selection influencer, quality owner
- **Pain Points**: Demo consistency, training overhead, tech stack complexity
- **Focus Areas**: Standardization, quality metrics, adoption

### 3. Account Executive (End User)
**Target**: 2-3 interviews (15-20%)
- **Company**: 25-1000 employees, $5M-$200M ARR
- **Role**: Daily user, adoption critical
- **Pain Points**: Time spent on repetitive demos, scheduling friction
- **Focus Areas**: Workflow integration, time savings, AI concerns

### 4. Founder/CEO (Budget Constrained)
**Target**: 1-2 interviews (10-15%)
- **Company**: 5-25 employees, $500K-$5M ARR
- **Role**: Buyer but limited budget
- **Pain Points**: Time constraints, growth bottlenecks
- **Focus Areas**: Scrappy solutions, willingness to pay, growth ambitions

---

## Validation KPIs (Recipe 1.1)

To achieve **"Problem Validated"** status, all 10 KPIs must hit target thresholds:

| KPI | Metric | Target | Description |
|-----|--------|--------|-------------|
| **I1.1** | Problem Confirmation Rate | ≥70% | Percentage confirming the problem exists |
| **I1.2** | Pain Intensity Score | ≥7/10 | Average pain score (1-10 scale) |
| **I1.3** | Problem Recency | ≥60% | Experienced problem within last 30 days |
| **I1.4** | Workaround Existence | ≥50% | Currently using workarounds/hacks |
| **I1.5** | Solution Interest Score | ≥3.5/5 | Initial reaction to AI demo concept (1-5 scale) |
| **I1.6** | Competitive Displacement | ≥60% | Willing to switch from current solution |
| **I1.7** | Outcome Alignment | ≥70% | Solution aligns with desired outcomes |
| **I1.8** | Budget Existence | ≥50% | Have budget for this problem |
| **I1.9** | Current Spend | ≥$50K/year | Average spend on demo-related costs |
| **I1.10** | Purchase Intent Score | ≥3.5/5 | Likelihood to purchase if available (1-5 scale) |

### Validation Outcomes

- **✅ All targets met**: Problem Validated → Move to Recipe 1.2 (Solution Validation)
- **⚠️ Partial validation**: Refine ICP, adjust positioning, conduct 3-5 more targeted interviews
- **❌ Most targets missed**: Problem not severe enough, wrong ICP, or solution misaligned → Pivot or deeper exploration

---

## MCP Server Integrations

The repository includes Model Context Protocol (MCP) server integrations for enhanced research and validation capabilities:

### 1. Tavily Web Search (`disrupt_tavily-web-search`)
- **Purpose**: Real-time web research and competitive intelligence
- **Use Cases**:
  - Research target companies before interviews
  - Validate market trends and competitive landscape
  - Find industry statistics and benchmarks
- **URL**: `https://mcp.tavily.com/mcp/`

### 2. Reddit MCP Server (`disrupt_reddit-mcp-server`)
- **Purpose**: Community insights and market sentiment
- **Use Cases**:
  - Explore sales and B2B SaaS communities
  - Discover pain points from Reddit discussions
  - Identify language and terminology used by target personas
- **URL**: `http://144.91.76.33:8080/mcp`

### 3. Weather MCP (`disrupt_weather-mcp`)
- **Purpose**: Example integration (not core to venture)
- **Use Cases**: Demonstrates MCP integration patterns
- **URL**: `https://mcp-weather-j5kl.onrender.com/mcp`

---

## Usage Instructions: Conducting Customer Discovery Interviews

### Week 1-2: Recruitment & Scheduling

1. **Review Interview Materials**
   - Read `/phases/ideation/artifacts/1.1/materials/interview-execution-guide.md`
   - Understand the 4 target personas and ideal candidate profiles
   - Study the 27-question interview script

2. **Launch Outreach Campaign**
   - Use provided LinkedIn search filters and outreach templates
   - Target: 20-30 outreach messages
   - Goal: 10-15 scheduled interviews
   - Tools: LinkedIn, email, warm intros, communities

3. **Track Recruitment Pipeline**
   - Use recruitment pipeline tracker in `interview-tracking-template.md`
   - Monitor response rates and adjust messaging
   - Schedule interviews using Calendly or similar tool

### Week 3-4: Conduct Interviews

**Before Each Interview** (10 min):
- Review interview script section-by-section
- Research interviewee on LinkedIn and company website
- Open tracking template for real-time notes
- Test video/audio setup

**During Interview** (30 min):
- Follow 27-question script structure:
  - Section 1: Problem Discovery (Q1-Q8, 20 min)
  - Section 2: Solution Exploration (Q9-Q16, 20 min)
  - Section 3: Willingness to Pay (Q17-Q27, 20 min)
- Record with permission (for reference, not transcription)
- Take notes in tracking template
- **Listen 70%, talk 30%**

**After Each Interview** (15 min):
- Complete tracking template row immediately
- Capture Van Westendorp pricing data (4 price points)
- Note key quotes verbatim
- Send thank you email + incentive (gift card)
- Add referrals to recruitment pipeline

**Mid-Way Check** (After 5-7 interviews):
- Calculate quick KPIs using calculator in tracking template
- Review patterns in insights section
- Adjust persona mix if needed
- Refine follow-up questions based on patterns

### Week 5: Analysis & Next Steps

1. **Complete All Interviews** (10-15 total)
2. **Validate Data Completeness** in tracking template
3. **Submit to Recipe 1.1 Analyzer Agent**:
   - Completed tracking template
   - Additional notes or observations
   - Interview recordings (optional)

4. **Receive Validation Report**:
   - All 10 KPIs calculated with precision
   - Pass/Fail status on Problem Validation
   - Persona-level insights and recommendations
   - Clear next steps based on results

---

## Interview Best Practices

### DO ✅
- Ask about **specific past experiences** (not hypotheticals)
- Dig into **emotions and consequences**
- Get **specific numbers, timelines, and workflows**
- Ask "why" repeatedly to find root causes
- Seek **commitments** (time, money, referrals), not compliments
- Document **red flags** and contradictions

### DON'T ❌
- Pitch your solution or explain features
- Accept generic answers ("yeah, that's a problem")
- Skip pricing questions because they're uncomfortable
- Talk more than you listen (70/30 rule)
- Ignore lukewarm reactions or politeness
- Only interview friendly personas or fans

### Common Pitfalls to Avoid

1. **Pitching Instead of Learning**
   - ❌ "We built this amazing AI that will revolutionize demos"
   - ✅ "Tell me about your demo process today"

2. **Accepting Generic Answers**
   - ❌ Them: "Yeah, demos are challenging"
   - ✅ You: "Tell me about the last time you had a demo no-show"

3. **Avoiding Money Conversations**
   - ❌ Skipping pricing questions
   - ✅ "What do you currently spend on solving this problem?"

4. **Leading the Witness**
   - ❌ "Don't you think demo no-shows are a huge problem?"
   - ✅ "How often do you experience demo no-shows?"

---

## Timeline & Effort

**Total Duration**: 4-5 weeks
**Total Time Investment**: 30-40 hours

| Week | Activity | Time | Output |
|------|----------|------|--------|
| 1-2 | Recruitment & Scheduling | 8-10 hours | 10-15 interviews scheduled |
| 3 | First 5-7 interviews | 8-10 hours | Mid-way KPI check |
| 4 | Remaining 5-8 interviews | 8-10 hours | All interviews complete |
| 5 | Analysis & Review | 2-3 hours | Validation status + next steps |

---

## Getting Started

### For Founders Conducting Interviews

1. **Clone this repository**
   ```bash
   git clone <repository-url>
   cd 10demo
   ```

2. **Read the core materials**
   - Start with `memory/statement.md` for context
   - Review `phases/ideation/artifacts/1.1/artifact.md` for overview
   - Study `interview-execution-guide.md` thoroughly

3. **Begin recruitment**
   - Use provided outreach templates
   - Target 20-30 prospects across 4 personas
   - Schedule first interview ASAP to gain momentum

4. **Execute interviews**
   - Follow 27-question script strictly
   - Complete tracking template after each interview
   - Document patterns and insights as you go

5. **Submit for analysis**
   - After 10-15 interviews, submit tracking template
   - Receive validation report with clear next steps

### For Contributors

This is a documentation-driven repository with no code builds or deployments:
- Follow existing directory structure for new phases/recipes
- Maintain The Mom Test principles in all customer discovery content
- Include specific KPIs and success criteria for each artifact
- Use descriptive commit messages referencing Recipe numbers

---

## Documentation Philosophy

This repository follows lean documentation principles:
- **Action-oriented**: Every artifact has clear "how to use" instructions
- **Data-driven**: Specific targets, KPIs, and success criteria
- **No fluff**: No restated obvious information or generic startup advice
- **Founder-ready**: Materials designed for direct execution, not theory

---

## Future Roadmap

### Immediate Next Steps (Based on Recipe 1.1 Results)
- **✅ Problem Validated** → Recipe 1.2: Solution Validation
- **⚠️ Partial Validation** → Refine ICP and iterate
- **❌ Not Validated** → Pivot or deeper problem exploration

### Future Phases
- **Validation Phase**: MVP prototype testing with target users
- **Build Phase**: Full AI demo agent development
- **Launch Phase**: Go-to-market execution and scaling

---

## Resources

### Interview Materials
- **Execution Guide**: `/phases/ideation/artifacts/1.1/materials/interview-execution-guide.md`
- **Tracking Template**: `/phases/ideation/artifacts/1.1/materials/interview-tracking-template.md`
- **Package Overview**: `/phases/ideation/artifacts/1.1/artifact.md`

### Core Statements
- **Venture Definition**: `/memory/statement.md`

### Claude Code Guidance
- **Agent Instructions**: `/CLAUDE.md`

### Configuration
- **MCP Servers**: `/.mcp.json`

---

## Questions or Support

If during execution you encounter:
- **Low response rates**: Try warm intros, communities, or adjust messaging
- **Scheduled no-shows**: Send reminders, offer flexible rescheduling
- **Generic answers**: Follow The Mom Test more strictly, probe deeper
- **Defensive interviewees**: Build more rapport, emphasize learning not selling
- **Conflicting feedback**: Document patterns, let analyzer identify segments

**Remember**: The goal is to learn the truth, not to validate assumptions. If the problem isn't real or the solution doesn't resonate, that's valuable information that saves you from building the wrong thing.

---

**Disrupt - Spec Driven Development**
