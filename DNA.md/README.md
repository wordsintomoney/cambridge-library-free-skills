# DNA.md — The Brand Identity Standard

**A complete, structured brand identity system for small businesses, consultants, and AI-powered workflows.**

---

## What Is DNA.md?

DNA.md is a brand identity standard — a single document that captures everything an AI agent, designer, copywriter, or contractor needs to understand your brand and create on-brand work without constant back-and-forth.

Think of it as a living creative brief that travels with you across every tool you use.

It covers:

- Visual identity (colors, typography, photography, logo)
- Brand personality, tone, and voice
- Target audience and psychographics
- Market positioning and competitive landscape
- Messaging, headlines, and value propositions
- Sales context and objection handling
- Content guidelines and channel strategy
- Customer experience standards
- Business goals and KPIs
- Constraints and no-gos

---

## Who It's For

- **Small business owners** who want consistent branding across every touchpoint
- **Consultants and agencies** who need a structured way to capture client brand identity
- **AI power users** who want their AI tools to produce on-brand output automatically
- **Freelancers** who need a standard briefing format for client onboarding

---

## What's in This Repository

```
DNA.md/
├── README.md                       # You are here
├── LICENSE.md                      # Usage terms
├── DNA.md                          # The full standard and schema reference
├── HOW_TO_USE.md                   # Plain-English guide to compiling your DNA.md
├── compile-dna.py                  # Optional Python script for technical users
│
├── dna-questionnaires/             # 8 short intake questionnaires for client onboarding
│   ├── 01_visual-identity.md
│   ├── 02_brand-personality.md
│   ├── 03_audience-positioning.md
│   ├── 04_messaging.md
│   ├── 05_sales-context.md
│   ├── 06_content-channels.md
│   ├── 07_experience-goals.md
│   └── 08_constraints-nogos.md
│
└── samples/                        # Completed examples across different business types
    ├── DNA_Sample_Groundwork_Coffee.md     # DTC subscription coffee brand
    ├── DNA_Sample_WickAndWild.md           # Small-batch soy candle DTC brand
    └── DNA_Sample_LedgerAndLeaf.md         # Remote bookkeeping service (B2B)
```

---

## How to Use It

### Step 1 — Fill out the 8 questionnaires

Each questionnaire covers a different part of the brand and takes 10–20 minutes. No marketing background required.

### Step 2 — Compile into a DNA.md file (three options)

**Option A — Let an AI do it ⭐ Recommended**

Upload all 8 completed questionnaires + the `DNA.md` template to any AI chat session (Claude, ChatGPT, Gemini, etc.) and send this prompt:

> *"I've uploaded 8 completed brand questionnaires and a DNA.md template. Please read all of the questionnaire files, extract my answers, and compile them into a complete, filled-out DNA.md file based on the template. When you're done, give me the finished file to download."*

Done. Most AI platforms support up to 10 file uploads per session — enough for all 8 questionnaires plus the template.

**Option B — Use an AI agent with the script**

Upload your questionnaire folder to an agent platform (Manus, Viktor, etc.) and ask it to run `compile-dna.py` for your brand name.

**Option C — Run the Python script yourself**

```bash
python compile-dna.py "Brand Name"
```

See `HOW_TO_USE.md` for full instructions.

### Step 3 — Review and refine

Read through the output, fill in anything marked "Not specified," and polish. When it feels right, it's done.

---

## Using DNA.md with AI Agents

Once your DNA.md is complete, give it to any AI tool as a persistent brand context document. It works with:

| Platform | Method |
|---|---|
| Claude | Upload to a Project for permanent memory |
| ChatGPT | Custom Instructions + file upload |
| Gemini | Create a Gem with DNA.md attached |
| Perplexity | Spaces with custom instructions |
| Viktor (Slack) | Share in your channel — Viktor stores it automatically |
| Any AI | Paste at the start of your prompt |

**Master prompt:**

> "I'm sharing my brand DNA file below. Read it carefully and use it as the foundation for everything you create for me in this session. Always match my brand voice, speak to my target audience, and stay within the boundaries defined in this document."

---

## Sample Files

Three complete fictional examples are included to show what a finished DNA.md looks like across different business types:

**Groundwork Coffee Co.** — Small-batch specialty coffee subscription
> DTC, B2C product, subscription model, organic social growth

**Wick & Wild Co.** — Handmade soy candle brand
> DTC, B2C, TikTok/Etsy driven, Gen Z/millennial audience

**Ledger & Leaf Bookkeeping** — Remote bookkeeping for small businesses
> Service business, B2B, referral-driven, relationship-first

---

## Contributing

DNA.md is an evolving standard. If you've used it and have suggestions for new fields, improved structure, or additional sample industries, open an issue or submit a pull request.

---

## License

This project uses a custom license. Free to use, share, distribute, and adapt — with or without attribution.

**You may not sell this work** without making substantive changes (90%+ original content). See [LICENSE.md](LICENSE.md) for full terms.

---

*DNA.md is a branding standard developed for consultants, small business owners, and AI-powered workflows. It is not affiliated with Google's design.md project.*
