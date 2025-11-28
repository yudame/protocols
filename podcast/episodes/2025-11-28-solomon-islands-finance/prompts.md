# Prompts Used for Episode: Financial Infrastructure in the Solomon Islands: From Cash to Crypto

This document tracks all prompts used during the creation of this episode for reproducibility and learning.

---

## Setup Phase

**Episode Details:**
- Date: 2025-11-28
- Slug: solomon-islands-finance
- Title: Financial Infrastructure in the Solomon Islands: From Cash to Crypto
- Type: Standalone episode

---

## Research Phase

### Research Prompt

**Tools Used:** Gemini Deep Research, Claude

**Prompt:**
```
Research the financial ecosystem and payment infrastructure in the Solomon Islands.

**Context:** Target audience is intelligent listeners interested in understanding how financial
systems work in developing Pacific Island nations, with practical implications for someone
considering entering the telecommunications market there. Cover the full spectrum from
traditional cash economies to emerging digital payment solutions.

**Key areas to explore:**

1. Current payment landscape
   - Cash vs. digital payment prevalence
   - Mobile money adoption and platforms (e.g., M-Sese, YouSave)
   - Banking infrastructure and access rates
   - Point-of-sale systems in urban vs. rural areas

2. Utility and bill payment systems
   - How do Solomon Islanders pay for electricity (Solomon Power), water, and existing telecom services?
   - Pre-paid vs. post-paid models
   - Payment channels available (bank, mobile, agent networks)

3. Remittance flows
   - Scale of remittances from diaspora (Australia, New Zealand, seasonal workers)
   - Current remittance channels (Western Union, KlickEx, bank transfers)
   - Fees, friction points, and receiving mechanisms
   - How recipients access and use remittance funds

4. Income segments
   - Financial behaviors of middle and high-income urban residents (Honiara)
   - Banking relationships, payment preferences, smartphone penetration

5. Regulatory environment
   - Central Bank of Solomon Islands (CBSI) stance on digital payments
   - Licensing requirements for payment service providers
   - Any existing crypto/stablecoin regulations or guidance

6. Emerging and potential payment solutions
   - Regional payment integration (Pacific islands initiatives)
   - Stablecoin possibilities - existing on/off-ramp services, if any
   - International examples of successful telecom-led payment systems in similar markets

**Research methodology:**
- Prioritize official sources: CBSI reports, World Bank financial inclusion data, IMF assessments
- Distinguish between urban (Honiara) and rural realities
- Note infrastructure constraints (internet connectivity, electricity access)
- Include specific statistics on banking penetration, mobile ownership, remittance volumes
- Identify gaps in current systems that represent opportunities
- Report on any pilot programs or recent developments (2023-2025)
- Note challenges: geography (900+ islands), population distribution, infrastructure limitations

**Output:** Comprehensive research report with specific data points, named services/providers,
regulatory citations, and source links throughout.
```

**Date:** 2025-11-28

**Additional Tools Used:** ChatGPT, Perplexity

---

## Audio Generation Phase

### NotebookLM Audio Overview Prompt

**Tool Used:** NotebookLM

**Format:** Deep Dive / Long

**Files to Upload to NotebookLM:**
- report.md (synthesized research report)
- research/research-results.md (raw research from all four tools)

**Prompt:**
```
Create an intellectually rigorous podcast that balances analytical depth with clear explanation.

Opening:
• Begin with "Yudame Research" and introduce the episode topic
• Pronunciation: "Yudame" is pronounced "you-duh-may" (three syllables, emphasis on first)
• Set up what makes this topic interesting or valuable to explore

Core principles:
• Spell out acronyms on first use: "Central Bank of Solomon Islands, or CBSI"
• For short, clear terms like CBDC, prefer saying the full phrase in speech when natural: "Central Bank Digital Currency"
• Define technical terms immediately with plain language THEN build on them - assume intelligent but not expert audience
• Use concrete examples and stories ONLY when they exist in the source material - never fabricate or speculate
• When stories exist, include human elements: what people said, felt, decided - not just mechanics
• HIGHLIGHT surprising findings, spectacular failures, and unexpected successes - these are the memorable moments
• Extract frameworks and principles from the research findings
• Connect findings to practical implications and broader patterns
• Maintain scientific rigor: distinguish correlation from causation, note effect sizes, acknowledge uncertainties

What to emphasize:
• Spell-first approach: "The Real-Time Gross Settlement system, called SOLATS..." not "SOLATS requires..."
• Definition-first explanations: "M-SELEN - meaning mobile money in local Pijin where selen means money - is..."
• Evidence-based analysis: cite specific statistics like "80% of transactions are cash" or "350,000 users in two years"
• Human elements in stories: the journey from 20,000 users to 350,000 in under two years
• Practical insights: what does this mean for someone considering entering the telecom market?
• Pattern recognition: what principles emerge from M-Pesa, Fiji's M-PAiSA, and PNG's experiences?
• Conversational check-ins: "Let me define that term..." or "To be clear, what we mean by mobile money is..."

SURPRISING MOMENTS - actively look for and highlight these:
• Counter-intuitive findings: "75% lack bank accounts, but 70% have mobile phones..."
• Spectacular growth: "From zero to 350,000 users in just two years - nearly half the entire population"
• Dramatic costs: "Sending money costs 11% - four times the global average"
• Geographic extremes: "900 islands, 15 bank branches, 30% of customers arrive by canoe"
• The Bokolo Cash CBDC experiment: Solomon Islands piloting a central bank digital currency
• YouSave LoMobile: the world-first pension savings via mobile airtime top-up
• Non-obvious connections: how prepaid electricity meters became the gateway to financial inclusion

Signal these moments with phrases like:
• "Here's where it gets really interesting..."
• "And this is the shocking part..."
• "You wouldn't expect this, but..."
• "The numbers here are staggering..."
• "This completely flips conventional wisdom..."

What to avoid:
• Acronyms without spelling them out first (CBSI, SOLATS, PALM, RSE, etc.)
• Technical jargon without immediate plain-language definition
• Academic language when simpler words work
• Concept stacking - introducing 3+ new technical terms in one sentence
• Fabricated examples or hypothetical stories not in the research
• Over-simplification that loses accuracy
• Excessive hedging that obscures clear findings
• Dry mechanical explanations when human stories exist in the research
• Repeatedly restating context - establish once, then focus on content

Target audience: Intelligent listeners who want to deeply understand Pacific Island financial systems and the practical implications for telecom/fintech market entry. They appreciate technical depth but need terms defined to follow along.

Tone: Intellectually rigorous but accessible. Think "conversational expert explaining to a bright student" - maintain depth while ensuring clarity.

Closing:
• Summarize 2-3 key takeaways: the mobile phone/bank account gap as opportunity, agent networks as the real infrastructure, remittances as the killer use case
• Close with information about learning more: "Find full research and sources at research dot yuda dot me - that's Y-U-D-A dot M-E"

When presenting stories:
• Include human drama if it exists: how seasonal workers in Australia send money home through expensive channels
• Build narrative tension: "Only 25% have bank accounts, but then M-SELEN launched..."
• Make it memorable through specifics: "$8.67 average travel cost just to reach a financial access point"
• Emphasize the spectacular: "350,000 users - nearly half the population - signed up in under two years"

When presenting research:
• Focus on what the numbers mean and why they matter
• Use comparisons: "11% remittance cost versus the 3% UN target"
• Translate statistics to implications: "80% cash transactions means the entire economy runs on physical currency"

Balance precision with engagement - neither dumbed down nor unnecessarily complex.
```

**Date:** 2025-11-28

---

<!-- Additional prompts will be added below as we progress through the workflow -->


## Cover Art Generation

**Tool Used:** OpenAI dall-e-3

**Original Prompt:**
```
Modern podcast episode cover art for "2025 11 28 Solomon Islands Finance":

Style: Clean, professional, scientific
Layout: Bold typography with subtle data visualization elements
Color palette: Deep blues and teals with white/silver accents
Concept: The Solomon Islands presents one of the most dramatic financial inclusion stories unfolding in the Pacific today. In a nation where **80% of all transactions are conducted in cash** and only **25% of 

Design as a square format (1400x1400px) with space for episode title overlay.
Professional, minimalist aesthetic suitable for Apple Podcasts.
No text in the image - pure visual design.
```

**Revised Prompt:**
```
Design a clean, professional, and scientific cover art for a modern podcast episode about finance in the Solomon Islands. The image should be in a square format with dimensions 1400x1400 pixels, and it should be suitable for Apple Podcasts, with a minimalist aesthetic. The dominant colors should be deep navy blue and dark blue, filling most of the canvas, while bright teal, white, and silver should be used only as accent colors. The design should be purely abstract with a subtle hint of data visualization elements linked to the financial transformation unfolding in the nation. No typography or graphic elements should be involved in the design, keeping it pure and without text, numbers, labels, annotations, icons, logos, symbols, or letterforms.
```

**Output:** cover.png

**Date:** 2025-11-28
