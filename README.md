# InsightfulPipe Local Marketing Skills

**12 free Claude skills for local businesses: Google Business Profile, reviews, local rank tracking, citations, Local Services Ads and multi-location plans.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/local-skills
/plugin install insightfulpipe-local@insightfulpipe-local
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/local-skills
```

Add `--skill local-citation-nap-audit` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (12)

| Skill | What it does | |
|---|---|---|
| [Fake Review Removal Handler](skills/review-removal-handler/) | Tests negative or fake Google, Yelp and Amazon reviews against each site's content policy, spots review bombing, drafts report notes and calm replies, and tracks appeals. |  |
| [Google Business Profile Manager](skills/google-business-profile-manager/) | Audits Google Business Profile locations on Google Maps, grading completeness, hours, photos, posts, reviews and calls, ranks the locations, and drafts posts and review… |  |
| [Local Business Marketing Report](skills/local-business-marketing-report/) | Builds a local business marketing report from Google Business Profile and Search Console with a 30/60/90-day local SEO plan, or a 90-day marketing plan for one location. |  |
| [Local Citation and NAP Audit](skills/local-citation-nap-audit/) | Audits local citations and NAP consistency, comparing name, address, phone, website and hours on each listing with the Google Business Profile, and flags duplicate Maps… |  |
| [Local Competitor Gap Analysis](skills/local-competitor-gap/) | Compares a local business with the Google Maps listings that outrank it in the map pack on categories, reviews, photos, hours and website, and ranks the gaps by impact. |  |
| [Local Lead Ads Planner](skills/local-lead-ads-planner/) | Grades Yelp Ads, Angi, Thumbtack and Nextdoor Ads spend by booked jobs, not leads, sets the most a lead can cost, picks services and ZIP codes to keep, and drafts lead… |  |
| [Local Rank Tracker by Area](skills/local-rank-grid-tracker/) | Tracks local map pack rankings by area, checking each service keyword from every town, neighborhood or ZIP code served, and maps strong and gap areas and who holds them. |  |
| [Local Services Ads Manager](skills/local-services-ads-manager/) | Reviews Google Local Services Ads by cost per booked job, with leads by job type and area, missed charged calls, budget use, bids and lead feedback drafts for credits. |  |
| [Multi-Location and Franchise Marketing Plan](skills/multi-location-marketing-plan/) | Builds a franchise or multi-location marketing plan, tiering locations by Google Business Profile views and actions, splitting the brand fund and co-op, and setting… |  |
| [Review Generation Planner](skills/review-generation-planner/) | Plans how to get more Google reviews and product reviews, setting a target and monthly pace against local rivals, checking asks against Google review policy and the FTC… |  |
| [Review Insights Analyzer](skills/review-insights-analyzer/) | Analyzes Google, Amazon, Yelp or WooCommerce reviews, coding them into themes that drive 1-star and 5-star ratings, with trends by location or product and what each fix… |  |
| [Reviews and Comments Responder](skills/reviews-and-comments-responder/) | Drafts replies to unanswered Google reviews, Facebook, Instagram, YouTube, LinkedIn and Meta ad comments, X mentions and App Store and Google Play reviews, ranked by… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
