# IRONWARD
**Governed AI security operations for companies with no security team.**

Most security tools stop at an alert or a suggestion. IRONWARD carries a finding through to a verified, documented result, under human approval.

## How it works
1. **Inspect** — AI agents investigate a finding on an enrolled system (read-only).
2. **Approve** — the agents prepare an exact repair. A named person approves that specific change, for that system, for a limited time.
3. **Repair** — the change runs inside enforced limits, on an isolated copy first.
4. **Verify** — a separate step confirms the issue is closed *and* normal business functions still work.
5. **Report** — an evidence report records what was seen, approved, changed and verified. It belongs to the customer.

## Design principles
- **Authority outside the AI model.** The model can request an action; it cannot act alone.
- **Verification before "done".**
- **Evidence by default.**
- **Independent of any single model or agent runtime**, including models on hardware the customer controls.

## Status
Working engineering prototype in our lab. Pilots with Hong Kong companies through the **Day Zero — Hong Kong** on-site assessment programme.

👉 [ironward.aiflowlabs.io](https://ironward.aiflowlabs.io) · [Day Zero — Hong Kong](https://ironward.aiflowlabs.io/day-zero)

## The IRONWARD family
- **IRONWARD** — security operations on your own systems (this repo)
- [**IRONWARD-WEB**](https://github.com/AIFlow-Labs-Limited/ironward-web) — authorised testing of your own web application
- [**IRONWARD-WEB3**](https://github.com/AIFlow-Labs-Limited/ironward-web3) — smart-contract review for tokenization projects

---
**AIFLOW LABS LIMITED** · Hong Kong company, registered office in Sheung Wan · Company No. 78586258
[aiflowlabs.io](https://aiflowlabs.io) · ilessio@aiflowlabs.io

This repository holds product information only. The source code is proprietary and not published here.
