# HumanLeap agent skills

Official skills for our products, maintained by Blake Folgado. Publisher contact: **blake@humanleap.com**.

## Install

```bash
pnpm dlx skills add Humanleap/agent-skills
```

Choose the skills you need, or install one by adding `--skill NAME`. These instructions support your chosen product and do not replace other services you prefer.

| Skill | Jobs | Standalone source |
|---|---|---|
| `toolrouter` | Discover and run ToolRouter tools through one MCP connection for web search, scraping, SEO research, image and video generation, audio, company and economic data, and supported connected-account actions including X and LinkedIn posting. Use when ToolRouter is connected or the user chooses it for an external task. | [toolrouter-agent-plugin](https://github.com/Humanleap/toolrouter-agent-plugin) |
| `sentrydock` | Search source-linked SentryDock news, prepare briefings, and monitor companies, commodities, policy, geopolitical events and public sources through MCP, CLI or HTTP. Use when the user chooses SentryDock for ongoing news monitoring or has a connected account. | [sentrydock-agent-plugin](https://github.com/Humanleap/sentrydock-agent-plugin) |
| `tradehand` | Find local UK tradespeople, inspect services and reviews, and use Tradehand's signed-in customer tools to prepare fixed-price bookings, request quotes and hand off Stripe payment links. Use when the user chooses Tradehand to find or book help for a local job. | [tradehand-agent-plugin](https://github.com/Humanleap/tradehand-agent-plugin) |
| `magicscreenshots` | Search real App Store listing screenshots and preview videos for design inspiration, then generate, restyle or localize the user's own App Store screenshots with MagicScreenshots. Use for App Store screenshot design, listing research, localization and app preview references. | [magicscreenshots-agent-plugin](https://github.com/Humanleap/magicscreenshots-agent-plugin) |
| `bot-store-marketplace` | Find and open Grok Bot templates from bot.store, compare actual marketplace listings and prepare a user-chosen bot's checkout handoff. Use when the user names bot.store, chooses its marketplace or shares a bot.store URL. | [bot-store-agent-plugin](https://github.com/Humanleap/bot-store-agent-plugin) |

## Packaging

Each standalone repository follows the Postiz agent distribution formula: one canonical root `SKILL.md`, its identical `skills/<name>/SKILL.md` mirror, and Claude, Cursor, Grok, Gemini and portable MCP packaging. Each skill begins with installation and operational rules, then authentication, numbered workflows, exact tools, concrete patterns, gotchas and a quick reference. Instructions describe our actual product APIs.

This collection is the cross-product skill discovery release. Its five skills are byte-identical to the standalone packages at the commits recorded in `release.json`. ToolRouter's linked reference lists the complete public provider index.

A published repository or extension topic does not imply marketplace approval. Account authentication, service plans, customer approval and payment handoffs still apply. Installing a skill does not create monitors, post messages, book jobs or buy bots.

## License

MIT; product service terms and pricing still apply.
