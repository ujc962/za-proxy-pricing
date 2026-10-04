# south africa proxy: how to pick a ZA residential IP for Takealot, google.co.za and geo-blocked video, and what 9Proxy charges for it

Searching for a South Africa proxy usually means one of four things: you need to see a South African version of a page, you're pulling price data off Takealot or PriceCheck, you're verifying ads as a local user would, or you want to watch something that only plays inside SA. All four come down to the same requirement. Your traffic has to leave from a South African IP that a website has no particular reason to distrust.

That's where most cheap options fall apart. This piece covers what actually matters when you buy a ZA proxy, the checks worth running before you spend anything, and how 9Proxy's packages are structured — including current prices for every package on its books, since they changed in mid-2026.

## What a South Africa proxy actually gets you

Concrete jobs, roughly in order of how often they come up:

- **SERP checks with real local results.** Google serves different results and different ad layouts for South African users. A Johannesburg IP gets you what a Johannesburg customer sees.
- **E-commerce price and stock tracking.** Takealot, Makro, PriceCheck and the local arms of international retailers all serve localised pricing, currency and availability. A US datacenter IP gets a redirect or a bot check.
- **Ad verification.** If you're buying placements on South African media, you need to see the creative the way a local reader sees it, not a placeholder or a geo-mismatch fallback.
- **Account work tied to the region.** Anything where the platform reads your IP as part of the session fingerprint — social accounts, marketplace seller accounts, ticketing.
- **Geo-restricted video and radio.** SABC, e.tv, DStv's streaming layer. Residential IPs give you the best odds here, but no provider can promise a specific streaming service will let you through, because detection changes constantly.
- **Market research that isn't guesswork.** Survey panels, review scraping, competitor pricing across provinces.

One note on the legal side, because it comes up: using a proxy isn't illegal in South Africa. South Africa's data protection law, POPIA, governs how personal information gets processed, not whether you can route traffic through a ZA address. What you do with the data is the part with consequences.

## Why datacenter ZA IPs are usually the wrong default

South Africa has a comparatively small hosting footprint. That's a problem, because datacenter ranges are short, published, and easy to blacklist at the ASN level. It doesn't matter how fast the connection is if Cloudflare hands you a challenge on the first request.

Residential IPs come from real subscriber connections — Vodacom, MTN, Telkom, Cell C, Rain and the fibre ISPs — so a request from one of them looks like a request from an actual household in Cape Town. Sites still flag residential IPs sometimes, but the base rate of false positives is far lower, and that's the entire product category in a sentence.

The trade-off is that residential IPs are borrowed, not owned. Any pool, from any provider, has addresses that go offline, and a ZA pool is smaller than a US or German one, so churn is more noticeable. Which brings us to the checks.

## Five checks worth running before you buy any ZA proxy

**1. City and ISP targeting, not just "South Africa."** Country-level filtering alone means your ZA IP could sit anywhere from Polokwane to Somerset West. If you're checking how prices display in Gauteng versus the Western Cape, you need city selection. If your target site fingerprints the ISP along with the IP, you need ISP filtering too.

**2. How IPs are billed — per address or per gigabyte.** These are genuinely different products, and mixing them up is the most common way people end up feeling ripped off. Per-IP suits long sessions and unpredictable bandwidth. Per-GB suits high-rotation work where each request is small.

**3. What happens when an IP dies.** Residential IPs expire naturally, usually within a few hours to about a day. The question is whether you're charged for an address that was forwarded and immediately dropped. Policies differ a lot here.

**4. Whether dead IPs can be reused.** Some providers let you reconnect to an address you already used that day without spending another unit. That's real money over a month of testing.

**5. Whether the plan needs a local app.** Some providers route everything through a desktop client with port forwarding; others work straight from a browser dashboard. If you're on a headless Linux box or a cloud VM, that difference decides whether the plan is usable at all.

## How 9Proxy handles South Africa

9Proxy is a residential-only network: it advertises 20M+ residential IPs across 90+ countries, targeting down to state, city, ZIP code and ISP level, over HTTP/HTTPS and SOCKS5. South Africa sits inside that 90+ country footprint, and the ZA pool is worth verifying on your own terms rather than trusting a marketing number — more on that below. For local checks, the app's filter is the source of truth: it shows which ZA cities and ISPs are live at the moment you look.

👉 [Check live ZA availability in 9Proxy's dashboard](https://bit.ly/9-Proxy)

There are two billing products, and the choice between them matters more than the brand name.

### Residential by IPs: pay per address, bandwidth unmetered

You buy a fixed number of IPs. An IP is deducted only when you forward it to a local port through the 9Proxy desktop app (Windows, macOS, Linux). Once it's live, traffic through it is unmetered — download 200 MB or 20 GB, the cost is the same. Unused IPs sit in your balance indefinitely.

Three features matter for ZA work specifically:

- **Filtering by country, state, city, ZIP code or ISP** before you forward anything.
- **Auto Refresh Proxy**, which replaces an IP that drops with a fresh one automatically.
- **Auto Rotation Proxy**, which cycles an IP on a schedule you set, per port.

There's also a **Today List**: proxies you used in the last 24 hours can be re-forwarded at no extra cost. For someone running daily ZA price checks, this alone changes the maths, because a stable Johannesburg address you used yesterday can be reused today.

If an IP fails within 60 seconds of being forwarded, you can swap it out — that policy is the one reviewers cite most often, both as a selling point and as a limitation, since a 60-second window is short.

### Residential by GB: pay per traffic, unlimited endpoints

The bandwidth model skips IP counting altogether. You buy gigabytes, then generate as many endpoints as you like from the dashboard — no local app required. Traffic is valid for 180 days, and Enterprise plans drop the expiry entirely. You can target country, state, city, ZIP or ISP, choose sticky sessions (same IP for a set window) or rotating (new IP per request), and authenticate with username/password or an IP whitelist.

For South Africa work, this is the better fit when your pattern looks like: check 500 localised product pages once each, get 500 different ZA addresses, never care about session continuity. Sticky sessions are the right call when you're logging into a seller account and need the address to hold still for twenty minutes.

### Enterprise and teams

Enterprise adds unlimited data validity, a team mode with one owner plus up to five members, per-member traffic controls, activity logs and unlimited share-code creation. Pricing is quoted per account, not published.

## 9Proxy pricing: every package currently on sale

Prices below are the post-June-2026 list prices in USD. IP-based and bundle pricing was adjusted on 1 June 2026; GB-based packages were left untouched. IP packages are prepaid and unused IPs don't expire; GB packages carry 180-day traffic validity unless you're on Enterprise.

| Package | What you get | Price | Billing model | Get it |
| --- | --- | --- | --- | --- |
| 100 IPs | 100 residential IPs, unlimited bandwidth | $24 ($0.24/IP) | Prepaid, no expiry on unused IPs | [ Buy the 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | 500 residential IPs, unlimited bandwidth | $72 ($0.144/IP) | Prepaid, no expiry | [ Buy the 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | 1,500 IPs total, unlimited bandwidth | $126 ($0.084/IP) | Prepaid, no expiry | [ Buy the 1,500 IP package](https://bit.ly/9-Proxy) |
| 2,500 IPs | 2,500 residential IPs | $210 ($0.084/IP) | Prepaid, no expiry | [ Buy the 2,500 IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | 5,000 residential IPs | $360 ($0.072/IP) | Prepaid, no expiry | [ Buy the 5,000 IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | 15,000 residential IPs | $720 ($0.048/IP) | Prepaid, no expiry | [ Buy the 15,000 IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | 25,000 residential IPs | $863 | Prepaid, no expiry | [ Buy the 25,000 IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | 50,000 residential IPs | $1,438 | Prepaid, no expiry | [ Buy the 50,000 IP package](https://bit.ly/9-Proxy) |
| Business 100,000 IPs | 100,000 residential IPs | $2,300 ($0.023/IP) | Prepaid, no expiry | [ See the 100,000 IP business package](https://bit.ly/9-Proxy) |
| Business 200,000 IPs | 200,000 residential IPs | $4,140 | Prepaid, no expiry | [ See the 200,000 IP business package](https://bit.ly/9-Proxy) |
| Business 500,000 IPs | 500,000 residential IPs | $8,625 | Prepaid, no expiry | [ See the 500,000 IP business package](https://bit.ly/9-Proxy) |
| 5 GB | 5 GB of residential traffic, unlimited endpoints | $15 ($3.00/GB) | 180-day validity | [ Buy the 5 GB package](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB | 55 GB of residential traffic | $105 ($2.10/GB) | 180-day validity | [ Buy the 55 GB package](https://bit.ly/9-Proxy) |
| 100 GB | 100 GB of residential traffic | $150 ($1.50/GB) | 180-day validity | [ Buy the 100 GB package](https://bit.ly/9-Proxy) |
| 200 GB | 200 GB of residential traffic | $200 ($1.00/GB) | 180-day validity | [ Buy the 200 GB package](https://bit.ly/9-Proxy) |
| 1,000 GB | 1,000 GB of residential traffic | $800 ($0.80/GB) | 180-day validity | [ Buy the 1,000 GB package](https://bit.ly/9-Proxy) |
| 2,000 GB | 2,000 GB of residential traffic | $1,500 ($0.75/GB) | 180-day validity | [ Buy the 2,000 GB package](https://bit.ly/9-Proxy) |
| Starter Bundle | 100 IPs + 5 GB | $30 | 180-day traffic validity | [ Buy the Starter Bundle](https://bit.ly/9-Proxy) |
| Popular Bundle | 1,500 IPs + 50 GB | $180 | 180-day traffic validity | [ Buy the Popular Bundle](https://bit.ly/9-Proxy) |
| Pro Bundle | 5,000 IPs + 500 GB | $720 | 180-day traffic validity | [ Buy the Pro Bundle](https://bit.ly/9-Proxy) |
| Enterprise | Custom volume, unlimited data validity, team of 1 owner + 5 members, activity logs, VIP pricing | Custom quote | Per-account agreement | [ Request Enterprise pricing](https://bit.ly/9-Proxy) |

Two things sit outside the table. The per-GB rate keeps sliding at the top end — the 10,000 GB tier works out at $0.68 per GB, with the total quoted on request. And payment is accepted by card, crypto, Google Pay, Apple Pay, Alipay and local methods, plus a 9Proxy wallet balance.

## Which package makes sense for a South Africa workload

The IP-based model only pays off if you keep addresses alive. If your ZA job is "check forty Takealot listings once a day," paying $24 for 100 IPs when you'd use maybe ten of them is fine only if you're going to come back tomorrow — and you are, which is why the Today List reuse matters. Over a month, those 100 IPs can cover a lot of daily checks.

The GB model wins when you're spreading requests wide. Forty product pages at roughly 1.5 MB of HTML each is about 60 MB, so a $15 five-gigabyte package would last a very long time at that rate. Add images, JSON APIs or a headless browser and consumption jumps fast; headless Chrome through a proxy can eat 1–3 MB per page load before you blink.

Rough rules:

- **Under 10 GB a month, high rotation, no login state** → GB-based.
- **Login state, sessions that need to hold, or bandwidth you can't predict** → IP-based.
- **Mixed workload** → a bundle. The $30 Starter bundle pairs 100 IPs with 5 GB, which covers a small ZA project end to end.
- **Any ZA job on a headless Linux server** → GB-based, since IP-based requires the desktop app and port forwarding.

If you're not sure which way you lean, put $24 or $15 in and measure your actual consumption for a week instead of estimating it. Unused IPs don't expire, and GB traffic is good for 180 days.

## Setting up a ZA proxy: the two paths

**Desktop app path (IP-based).** Install the app for Windows, macOS or Linux, then set your port range under Settings → Port Numbers. Open the proxy forwarding view and press F to filter — choose South Africa, then narrow to a city like Johannesburg, Cape Town or Pretoria, or to a specific ISP if your target site inspects provider fingerprints. Select an IP and forward it to a port. From there you either point your tool at `localhost:port` or, with proxy authentication on, at `username:password:localhost:port`.

The CLI follows the same logic, and the official docs use the country code as the argument — the examples there cover US, VN and UK, so a South African call follows the same format:


9proxy proxy -c <country code> -p 60000


Test it before you build anything on top of it:


curl -x socks5://127.0.0.1:60000 https://ipinfo.io/json


If the response shows a South African city and a local ISP, you're in business. If it doesn't, you've spent thirty seconds finding out.

**Dashboard path (GB-based).** No install. Pick your package, then either create a sub-user with credentials or whitelist your device IP. Choose South Africa and your city, decide between rotating and sticky mode, and generate endpoints — exportable as .txt or .csv, with ready-made code samples in the dashboard. Rotating mode swaps the IP automatically; sticky mode holds one for the window you configure.

👉 [Start with the smallest package and test your ZA targets](https://bit.ly/9-Proxy)

## Where 9Proxy is weak

Worth knowing before you commit real budget:

- **Residential only.** There's no datacenter line and no static ISP proxies as separate products. If part of your workflow needs cheap datacenter IPs for low-defence targets, you'll need a second provider.
- **No standing free trial.** Trial access has been handled case by case through support rather than offered on the site, so don't build a plan around getting one.
- **The 60-second replacement window is narrow.** It covers an IP that dies immediately after forwarding. An IP that dies after twenty minutes is a manual replacement. The Today List softens this, but reviewers have flagged the policy as tight.
- **Residential IP churn is real.** Addresses last a few hours to about 24 hours. For a ZA pool smaller than the US or European ones, expect to manage replacements.
- **Speeds are adequate rather than remarkable.** Reviews describe solid performance on Western targets with some variability elsewhere. It's a residential network; peak-hour dips come with the territory.
- **Reliability history.** More than one third-party review site reported a multi-day outage around late June 2026, with support channels silent during it and later speculation about what caused it. Other sources report the service running again. Whatever the cause, it's a reason to start with a $24 or $15 package rather than a $1,438 one.

## Common questions

**Can I target specific South African cities?** 9Proxy supports city-level filtering on both product lines, alongside state and ZIP or postal code. Whether a given ZA city has live IPs right now is something the filter answers better than any marketing page.

**Which SA ISPs show up?** Expect the majors — Vodacom, MTN, Telkom, Cell C, Rain — plus fibre providers. ISP filtering exists on both the app and the dashboard, so you can match a specific carrier if a target site checks it.

**Is a ZA proxy legal in South Africa?** Routing traffic through a proxy isn't prohibited. POPIA governs personal data handling, so what matters is whether the data you collect and how you collect it complies.

**Will this unblock DStv or SABC from abroad?** A ZA residential IP gets you the best chance, because it looks like a local household connection. It is not a guarantee. Streaming platforms combine IP reputation with account and device signals, and one ITWire review noted that 9Proxy IPs can still be detected by some streaming services while working well for e-commerce.

**Do I need to keep the app running?** Only for IP-based packages, which use local port forwarding. The GB model runs entirely from the dashboard.

**What if the ZA pool doesn't have what I need?** You find out in the filter before you buy anything large. Start small, check the city and ISP coverage against your actual targets, then scale. Unused IPs don't expire, so a small package isn't a wasted purchase — it's a test you keep.

👉 [Check current 9Proxy packages and ZA coverage](https://bit.ly/9-Proxy)
