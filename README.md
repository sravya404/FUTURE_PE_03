# Future Interns – Prompt Engineering Task 2
## AI SEO Blog & Content Cluster Generator for Business Websites



---

## About This Project

This project demonstrates a reusable AI-powered SEO content generation 
system built using structured prompt templates. It produces a complete 
content cluster - 1 pillar blog + 5 supporting blogs - optimised for 
Google search, local SEO, and business lead generation.

---

## Business Context

**Business Type:** Digital Marketing Agency  
**Location:** Hyderabad, Telangana  
**Primary Goal:** Rank for local search terms and generate inbound leads

---

## Content Cluster Structure

| # | Blog | Keyword | Type |
|---|------|---------|------|
| 1 | Best Digital Marketing Agency in Hyderabad | digital marketing agency hyderabad | Pillar |
| 2 | Social Media Marketing Services Hyderabad | social media marketing hyderabad | Supporting |
| 3 | How to Choose a Digital Marketing Agency | how to choose digital marketing agency | Supporting |
| 4 | SEO Services for Small Business Hyderabad | seo services small business hyderabad | Supporting |
| 5 | Google Ads vs Facebook Ads | google ads vs facebook ads india | Supporting |
| 6 | Digital Marketing Cost in Hyderabad | digital marketing cost hyderabad 2026 | Supporting |

---

## Prompt System

4 reusable prompt templates are in the `/prompts` folder:

1. **Pillar Blog Prompt** – Generates a 1200–1500 word authority blog
2. **Supporting Blog Prompt** – Generates 600–800 word cluster blogs
3. **Local SEO Adaptation Prompt** – Localises any blog for a specific city
4. **SEO Outline Prompt** – Generates structured H1–H3 outlines with meta tags

Each prompt uses fill-in variables like `[CITY]`, `[KEYWORD]`, 
`[BUSINESS_NAME]` making it fully reusable for any client.

---

## How to Reuse This for Another Business

1. Pick a new business type and city
2. Replace variables in the prompt templates
3. Run prompts through Claude / ChatGPT / Gemini
4. Edit the output for brand voice
5. Publish to the business website

---

## Tools Used

- Claude (claude.ai) – Primary content generation
- Google Search Autosuggest – Keyword discovery
- MS Word / GitHub – Documentation & submission

