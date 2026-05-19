<div align="center">

# NikaProxy

**Residential MITM proxy with real-browser TLS, JA3, TCP & HTTP/2 fingerprints.**

[![Website](https://img.shields.io/badge/Website-nikaproxy.com-d4af37?style=for-the-badge)](https://nikaproxy.com)
[![Docs](https://img.shields.io/badge/Docs-Read-cyan?style=for-the-badge)](https://nikaproxy.com/docs)
[![Telegram](https://img.shields.io/badge/Telegram-Support-26a5e4?style=for-the-badge&logo=telegram)](https://t.me/Nikaproxy_support)

</div>

---

A residential proxy that matches a real browser at every layer of the stack — not just the User-Agent string, not just the source IP. We sign outbound TLS handshakes with configurable browser profiles, control the TCP window/MSS pattern via T4-T7 exit coordination, and emit HTTP/2 frames in real-browser order. Anti-bot systems that fingerprint at L4 + L5 + L7 see what they expect to see.

## What we ship

- **67+ TLS profiles** — Chrome 131, Firefox 124, Safari 17, mobile Safari, OkHttp, Fuel, Volley, node-fetch, Go net/http, more
- **50M+ residential IPs** across 195+ countries via residential routing
- **TCP fingerprint coordination** — Win11 / mobile / iOS exits matched to the browser profile at handshake time
- **Sticky or rotating sessions** — sub-second swap, customer-pickable lifetime
- **REST scrape API** — fire-and-forget URL → JSON, no proxy plumbing
- **HTTP/SOCKS5 proxy** — drop-in replacement for whatever client you're already using
- **Pay-as-you-go from $2/GB** — bandwidth credit, never expires; TLS engine is a separate subscription tier

## Repos here

### Get started

| Repo | What for |
|---|---|
| 🚀 [**nikaproxy-examples**](https://github.com/Nika-Proxy/nikaproxy-examples) | Runnable starter code in Python, Node, Go, PHP, and curl |
| 📚 [**nikaproxy-docs**](https://github.com/Nika-Proxy/nikaproxy-docs) | Customer-facing docs (mirror of [nikaproxy.com/docs](https://nikaproxy.com/docs)) |

### Learn

| Repo | What for |
|---|---|
| 🎓 [**tls-fingerprint-101**](https://github.com/Nika-Proxy/tls-fingerprint-101) | From-scratch guide to TLS / TCP / HTTP fingerprinting for web scraping engineers |
| 📊 [**tls-fingerprint-research**](https://github.com/Nika-Proxy/tls-fingerprint-research) | Quarterly empirical data on the residential proxy market — device-family distributions, methodology, raw datasets |
| 🌟 [**awesome-tls-fingerprinting**](https://github.com/Nika-Proxy/awesome-tls-fingerprinting) | Curated list of tools, libraries, and services in the TLS-fingerprinting ecosystem |

## Get an account

1. Sign up at [nikaproxy.com](https://nikaproxy.com) — 100 MB free credit on signup, no card needed
2. Grab your API key + proxy password from the dashboard
3. Pick an example from [nikaproxy-examples](https://github.com/Nika-Proxy/nikaproxy-examples), paste in your creds, run it

## What we don't open-source

The engine. The TLS profiles. The T4-T7 coordinator. The prober. These are the moat.

What we *do* publish — the example code, the docs, the educational guides, the market research data — is the on-ramp + the reason people in the anti-bot ecosystem talk to us. Use it, file issues, send PRs. The engine itself stays in the vault.

## Need help?

- **Telegram** (fastest): [@Nikaproxy_support](https://t.me/Nikaproxy_support)
- **Docs**: [nikaproxy.com/docs](https://nikaproxy.com/docs)
- **Status / changelog**: [nikaproxy.com](https://nikaproxy.com)

---

<sub>NikaProxy is operated for anti-bot-grade web scraping and data collection. Use it lawfully — terms of service apply. See [nikaproxy.com/legal](https://nikaproxy.com/legal).</sub>
