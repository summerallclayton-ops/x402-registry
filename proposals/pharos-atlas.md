# Pharos Atlas

## Basic details

- Project name: Pharos Atlas
- Publisher/operator: Pharos Atlas / Summerall Capital; founder Clayton Summerall.
- What does it do? Pharos Atlas publishes structured editorial trade references for researchers, developers and AI-assisted workflows through existing paid x402 endpoints. The offset-printing API returns one fixed English reference covering job records, material questions, registration and sample checks, process limits and provenance; it does not inspect a production run or authorize work.
- Type: APIs & data
- Official website: https://pharosatlas.com
- Logo URL: https://pharosatlas.com/brand/pharos-mark.png
- Documentation/getting started: https://billing.pharosatlas.com/payments?product=offset-printing-review
- Public support/contract destination: https://summerall.capital/ — the official https://pharosatlas.com/commercial page links this as “Support and existing contracts.” This proposal does not add a new response-time or support-service promise.
- Public repository: The production API source is not published; no public source repository is claimed.

## Networks and ownership

- Supported payment network in this proposal: Base mainnet, CAIP-2 `eip155:8453`.
- Official project reference: https://pharosatlas.com/commercial links the buyer catalog, Pharos Atlas network and Summerall Capital for support/existing contracts. https://pharosatlas.info/network describes the source collection.
- This proposal is submitted on behalf of the project owner through the existing `summerallclayton-ops` account. No wallet ownership signature is supplied or claimed.
- Merchant receiving address on Base: `0x6Ac716842c089AaeeC8B3041F8096e0823254A84`.
- Public existing marketplace reference: https://payapi.market/api/pharos-atlas-offset-printing-review-reference
- No transaction-count, unique-customer, organic-demand or revenue-growth claim is made. Wallet totals can include controlled tests and unrelated resource activity.

## Payments — one evidenced API resource

- Exact endpoint: `GET https://billing.pharosatlas.com/api/x402/resources/offset-printing-review`
- Input: No request body or topic parameters. This retrieves a fixed snapshot; it does not accept arbitrary printing questions, uploaded job files or samples.
- Facilitator used: Coinbase Developer Platform x402, https://api.cdp.coinbase.com/platform/v2/x402 . Pharos Atlas is a merchant, not a new facilitator applicant.
- Payment protocol: x402 v2, `exact`; EIP-3009 authorization flow.
- Price: `0.01` native USDC per immutable English reference snapshot; `10000` atomic units.
- Token contract on Base: `0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913`; decimals: `6`.
- Public successful Base payment: https://basescan.org/tx/0x9765f1c8268fb5bb8afbe3be146f8fb637d1228ee0f1a725add11fbd95f73b90
- Evidence scope: The existing PayAPI listing states that PayAPI paid from its own wallet and received real data. The published transaction matches the reconciled native-USDC receipt. PayAPI publishes no client payload checksum. This is one-route provider-funded verification, not proof of full-network delivery or organic demand.

## Output contract and limits

- Format: `application/json`, `pharos.trade-review.v1`, English.
- Snapshot: `pharos-offset-printing-20261019-r1`; source date `2026-10-19`.
- Complete immutable reference: 4,050 UTF-8 bytes; SHA-256 `b5821acbf4e9bb6180bf6e6f469b221e635f18c2ed7a9f2d3fc67fbac9933d66`; response limit 24,576 bytes.
- Top-level fields: `schema`, `product`, `question`, `language`, `snapshot`, `source_date`, `site`, `review`, `subjects`, `provenance`. Review includes question/workflow arrays; subjects map named printing topics to editorial notes; provenance records source context and rights.
- Machine-readable complete nested schema and captured excerpt: https://billing.pharosatlas.com/openapi.json (operation `/api/x402/resources/offset-printing-review`, GET).
- Free catalog: https://billing.pharosatlas.com/.well-known/pharos-paid-products.json
- Captured excerpt, not the complete purchased response: `{"schema":"pharos.trade-review.v1","product":"offset-printing-review","language":"en","snapshot":"pharos-offset-printing-20261019-r1","review":{"questions":["Which artwork and plate revision define the job?"],"workflow":["Identify the job specification and materials"]}}`
- Limitations: Fixed editorial reference only. No inspection of a job, machine, material or sample; no certification, professional approval, compliance determination or work authorization. Source dates do not establish current conditions or continuous updates.
- Rights: `search=yes`, `ai-input=yes`, `ai-train=no`. Single purchased snapshot for internal reference. Bulk redistribution, sublicensing and a training license are not conferred.

## Catalog scope

There are 197 named English snapshot products and 200 specialist source profiles. These are different inventories. The links above permit inspecting each exact available resource and its contract. This proposal uses offset printing as the evidenced example and does not extend PayAPI's verification badge to other routes, promise every locale/geographic leaf, or request a fabricated MCP listing. Unavailable source content is excluded from the offered inventory.

## Website application

- Canonical application path: https://x402blockchains.com/ai-agents-apps/?view=submit
- Existing application: No earlier Pharos proposal or matching directory search result was observed on October 26, 2026.
- This is a free listing review request; no sponsored promotion or paid plan is requested.
- Review status: Submitted proposal is not automatic approval, publication or transaction indexing. No credentials, private contact information, signed payment authorizations or private result bodies are included.
