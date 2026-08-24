# Brand Clarity and Messaging Review

A Claude skill that analyzes an organization's brand and messaging the way a brand and marketing strategist would analyze a business problem: **"Why is this organization struggling with their marketing or capturing leads or getting new customers at this moment?"**

## What It Does

This skill has Claude research the organization and produce a structured report covering:

### 1. **Current Brand Strengths and Weaknesses**
From the Brand Clarity Test — reveals what and where the brand is weak against its top three competitors and how their current ICP's view them. 
- Decoded against common soft-language patterns
- Read across multiple sources from the same organization when available, since patterns across 3+ sources are a stronger signal than one

### 2. **Brand Clarity and Messaging Framework**
SWOT and other frameworks where they add real insight:
- Positioning framework
- Storybrand (7-Part Framework)
- April Dunford's Awesome Framework
- Brand Key for brand clarity messaging, marketing and content
- Applied only when they genuinely fit

### 3. **Competitive Landscape**
How peer organizations are positioned (top three), including:
- Differentiation strategies
- Value propositions

### 4. **What This Means for the Organization**
A synthesis of the real potential outcome behind the brand clarity and messaging change — from existing to new brand clarity and messaging.

### 5. **Open Questions**
Things worth asking because they could not be verified externally.

**Output:** A sourced Google Doc report, delivered before any application material gets drafted.

---

## How to Use It

1. **Download** `skill.md` from this repo
2. **In Claude**, go to **Customize > Skills**
3. Click **+ Create skill > Upload a skill** and upload the file (as a `.skill`/`.zip` package, or package it yourself — see [Anthropic's skill docs](https://docs.anthropic.com/))
4. **Paste or upload** an organization's website, marketing materials, sales materials, or strategic brief
5. **Ask Claude** to "analyze this organization's brand" or "run the strategic analysis"
6. *Optional:* Provide additional sources from the same org or your own background for a fuller read

---

## Requirements

- **Web search/web fetch capability** in Claude to research the organization
- **PDF access** to review marketing collateral and reports
- Works best with organizations that have some public footprint
- For very small or low-visibility organizations, the report leans more heavily on the web URL and contents of the website

---

## License & Attribution

No affiliation with or endorsement by Anthropic. Shared as-is; feel free to fork and adapt.
