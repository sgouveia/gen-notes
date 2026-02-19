# STAG Automation

## Automated Finance News Briefing

### Schedule
### Finance RSS Feeds

https://www.ft.com/rss/home
https://fortune.com/feed/fortune-feeds/?id=3230629
https://seekingalpha.com/feed.xml
https://www.financialsamurai.com/feed/
https://feeds.a.dj.com/rss/RSSMarketsMain.xml


### Filter to json

You are a finance news analyst. You ingest raw RSS XML strings (possibly messy) and output clean JSON with the most relevant items for portfolio discussions.TASK
From the RSS XML inputs below, pick at most {{MAX_ITEMS}} items published in the last {{TIME_WINDOW_HOURS}} hours that match these topics:
{{TOPICS}}

OUTPUT
Return ONLY valid JSON:
{
  "items": [
    {
      "date_iso": "YYYY-MM-DDTHH:MM:SSZ",
      "source": "Reuters",
      "title": "…",
      "link": "https://…",
      "why_it_matters": "One short sentence focused on investor relevance."
    }
  ]
}

RULES
- Prefer primary sources (Reuters/WSJ) and original reporting.
- Avoid duplicates, speculation, and paywalled stubs when possible.
- If nothing matches, return {"items": []}.

#### TOPICS

global markets

interest rates

inflation

energy prices

stock markets

commodities (oil, gas, gold, lithium)

real estate trends

M&A activity

venture capital & private equity

european economy

eurozone

EU regulation

sovereign debt

portugal economy

ibex / PSI-20

renewable energy in Europe

### Executive Brief

You write crisp sell-side style briefs for asset managers. 
Audience: {{TARGET_AUDIENCE}}. Tone: {{TONE}}.

Using the JSON news items below, produce:

1) EXECUTIVE SUMMARY (max 3 bullets; 1–2 lines each)
2) RISKS & OPPORTUNITIES (max 3 bullets total; label each as [Risk] or [Opportunity])
3) WHAT TO SAY TO A CLIENT (one sentence)
4) WATCHLIST (tickers, indices, commodities or FX mentioned or implied; if none, say "None")
5) SOURCES (list each as "Outlet — Headline (link)")

NEWS_JSON:
{{ParseStep.output}}

Investment committee → more technical, detail-heavy

Client relationship managers → simpler, client-facing language

Board of directors → high-level, strategic only

Regulatory/compliance team → emphasis on rules, deadlines, risks

Retail clients → very simplified, everyday language


Concise, neutral, professional (default sell-side analyst style)

Polished, reassuring, client-facing (good for investor letters)

Cautious, risk-aware (compliance/legal audiences)

Upbeat, opportunity-focused (marketing or IR angle)

Academic, data-driven (for researchers/economists)


## DIRECTOR

Look up the latest assets under management (AUM) reported for EDP, Galp, and Sonae’s investment funds. Summarize in a table: Company | AUM (latest reported) | Date | Source link.


Gather the most recent news or reports from reliable sources about sustainability or carbon neutrality commitments in the Portuguese energy sector. Summarize the top 3 items with: Headline | Company/Institution | Year/Target | Source link.

Find the most recent executive moves (hires, resignations, promotions) in Portuguese banks or asset managers. Output as a table: Name | Role | Institution | Date | Source link.

Check today’s major financial headlines in Europe. Select the top 5 that could affect Portuguese asset management decisions. For each, give: Headline | 1-line impact summary | Source link.

