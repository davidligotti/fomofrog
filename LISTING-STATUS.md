# FomoFrog listing and metadata status

Last checked: 2026-09-03 17:34 UTC  
Canonical mint: `H7N8GMFegfmFvV2Vrqkm7DpAoK1CBj6KdvwBkSdQpump`

This document records observed platform state. It is not a claim that any platform has approved, endorsed, or guaranteed FomoFrog.

## Verified discovery status

| Surface | Current observation |
|---|---|
| Jupiter Tokens API | Returns FomoFrog metadata and market fields (20 holders and approximately $2.9K liquidity in its response), but the live quote endpoint returns `TOKEN_NOT_TRADABLE` for both buy and sell checks. The response is not proof of executable liquidity. |
| GeckoTerminal | Returns a FOMO/SOL Pump.fun-origin pool at approximately $2.2K reserve, with zero reported buys, sells, traders, and volume across returned windows. |
| DexScreener token API | Returned no pair at the 2026-09-03 check. |
| Raydium mint lookup | Returned no Raydium pool at the 2026-09-03 check. |
| Coinbase | No listing or approval has been established. Coinbase requires its own free, merit-based Asset Hub review. |
| Solana legacy token-list repository | Archived; it is not a current listing submission path. |

A DEX or aggregator display is not proof of liquidity, safety, legitimacy, or future performance. Provider responses can disagree or be stale; the 2026-09-03 Jupiter quote check explicitly returned TOKEN_NOT_TRADABLE. Verify the mint address and an executable quote before every transaction.

## Verified project references

- Website: https://fomofrog.com
- Channel identity status: [CHANNEL-STATUS.md](CHANNEL-STATUS.md)
- Logo: https://raw.githubusercontent.com/davidligotti/fomofrog/main/fomofrog_logo_512.png
- Solscan: https://solscan.io/token/H7N8GMFegfmFvV2Vrqkm7DpAoK1CBj6KdvwBkSdQpump
- Pump.fun: https://pump.fun/coin/H7N8GMFegfmFvV2Vrqkm7DpAoK1CBj6KdvwBkSdQpump
- DexScreener lookup: https://dexscreener.com/solana/H7N8GMFegfmFvV2Vrqkm7DpAoK1CBj6KdvwBkSdQpump

X, Telegram, and Discord are not listed here as independently verified official channels; their current evidence and conflicts are tracked in CHANNEL-STATUS.md.

## Legitimate path to broader availability

1. Keep token name, symbol, mint, decimals, logo, and official links identical across all submissions.
2. Establish a real, disclosed trading venue and sufficient organic liquidity before requesting additional index coverage.
3. Publish current pool identity, liquidity, holder distribution, token allocation, and risk disclosures with timestamps.
4. Submit truthful applications to each platform. Coinbase’s process includes legal, compliance, technical-security, business, and ongoing-monitoring review; approval is discretionary.
5. Never purchase fake volume, fabricate holders or users, create duplicate pools to imply traction, or describe an application as an approval.

Current exchange availability is controlled by each platform. GitHub metadata can improve identity consistency and discovery, but it cannot force a listing or create market value.
