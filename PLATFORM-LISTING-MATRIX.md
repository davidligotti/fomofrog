# FomoFrog platform listing matrix

Last reviewed: 2026-09-03

Canonical mint: `H7N8GMFegfmFvV2Vrqkm7DpAoK1CBj6KdvwBkSdQpump`

Status meanings: metadata found, indexed, tradable, submitted, approved, rejected, unavailable, or unresolved. These states are intentionally separate.

| Platform | Current state | Evidence | Next legitimate action | Owner/platform gate |
|---|---|---|---|---|
| Jupiter Tokens API | Metadata found; not tradable | Token record returned; buy and sell quotes returned `TOKEN_NOT_TRADABLE` | Recheck after a genuine executable route exists | Provider route and liquidity |
| DexScreener | No pair returned at last check | Canonical token lookup returned no pair | Recheck after a real pool has trades | Provider indexing |
| GeckoTerminal | Indicative Pump.fun-origin pool; inactive in returned windows | Approximately $2.2K reserve; zero reported recent activity | Recheck pool identity, reserves, and activity | Pool/provider data |
| Raydium | No verified pool | No canonical Raydium pool established | Create or verify a genuine pool only through owner-controlled signing | Owner funding and on-chain transaction |
| Pump.fun | Launch reference exists | Canonical mint launch URL resolves as a project reference | Verify current bonding-curve or pool execution state | On-chain state |
| Phantom/Solflare | Not independently verified | No provider approval record in current evidence | Use official asset-support process if available | Wallet provider |
| CoinGecko/GeckoTerminal requests | Not approved as a broader listing | Existing data is not an approval | Submit through official request path only after a valid pool | Provider review |
| Coinbase | Not submitted/approved | Coinbase’s process requires issuer, legal, compliance, technical, and business information | Prepare truthful packet; obtain owner/legal review before submission | Coinbase discretion and owner information |
| Other centralized exchanges | Not submitted/approved | No current approval evidence | Evaluate one platform at a time using official channels | Platform review and legal requirements |
| GitHub metadata | Public repository metadata | `davidligotti/fomofrog` on main with passing CI | Maintain canonical identity and evidence documents | Repository owner |
| Website | Reachable but production-stale | Live route verifier rejects API/admin SPA fallbacks | Bind candidate, preview, verify, then publish through controlled Replit release | Work ID, verifier, rollback |

## Required evidence before changing a state

- Metadata found: provider response includes the canonical mint.
- Indexed: provider’s public asset page or API record resolves to the canonical mint.
- Tradable: independent buy and sell quotes succeed with current timestamp.
- Submitted: official provider receipt or authenticated submission record exists.
- Approved: provider explicitly confirms approval.
- Liquid: pool address, reserves, timestamp, and relevant lock/withdrawal facts are independently verified.
- Published: deployment URL, deployment identifier, source commit or artifact hash, route checks, and rollback target are recorded.

No state may be upgraded based on a logo, ticker, website claim, search result, first-party assertion, or a successful deployment status alone.
