# SEO Backlink Hub

Remote MCP server for link building: search a curated directory of guest-post sites, look up site profiles, match link partners, draft outreach pitches, and track outcomes.

- Website: https://recmoment.net/hub/
- MCP endpoint: `https://hub.recmoment.net/mcp` (streamable HTTP, JSON-RPC)
- Privacy: https://hub.recmoment.net/hub/public/privacy
- Terms: https://hub.recmoment.net/hub/public/terms

## Configuration

Set one variable when installing the plugin:

| Variable | Description |
| --- | --- |
| `SEO_BACKLINK_HUB_API_KEY` | Your Hub member key (starts with `rmh_`). Sent as `Authorization: Bearer <key>`. |

## Tools (13)

`hub_search_sites`, `hub_get_site_profile`, `hub_submit_site`, `hub_request_match`, `hub_auto_match`, `hub_report_outcome`, `hub_link_gap_watch`, `hub_analyze_content`, `hub_draft_pitch`, `hub_set_wishlist`, `hub_my_account`, `hub_ring_balance`, `hub_proposal_message`.

## Quick test

1. Install the plugin and set `SEO_BACKLINK_HUB_API_KEY`.
2. Ask the agent to run `hub_my_account` or `hub_search_sites` (read-only).

## Support

hub@recmoment.net
