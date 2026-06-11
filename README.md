# PaymentTestCases

A single, self-contained reference page cataloging **284 payment / money-handling security test cases** across **26 categories** — with where each weakness lives, how to test for it, and how to fix it. Many entries include concrete examples, sample `curl` requests, and side-by-side vulnerable vs. fixed code.

Everything lives in **`index.html`** — no build step, no dependencies, no server.

## ⚖️ Authorized testing only

This is a **defensive / educational** reference. Use these techniques only against systems you **own** or are **explicitly authorized** to test through a bug-bounty program's defined scope. Unauthorized testing of systems you don't have permission for is illegal (e.g. CFAA in the US, the Computer Misuse Act in the UK, and equivalents elsewhere) — even if you intend to report what you find. The `curl` examples deliberately target `https://localhost`.

## What's inside

- **Live search** box and **category filter** chips (with counts).
- Each card shows **Where/Why**, **How to test**, and **Fix**.
- Detailed entries additionally show **Concrete example → Sample request → Vulnerable code → Fixed code**.

### Categories

Money Math · Currency/FX · Intl Payments · Cart & Pricing · Coupons & Gift Cards · Refunds & Chargebacks · Authorization · Authentication · Race & Concurrency · Replay & Idempotency · Webhooks · Gateway Integration · 3DS & SCA · Tokenization & PCI · Subscriptions · Wallets & P2P · Payouts · Fraud & Limits · Configuration · API Security · Crypto Payments · Trading Platforms · Mobile IAP · Marketplace & Split · Fees & Tax · Disclosure & Logging

## View it locally

Open `index.html` in any browser. That's it.

## Publish with GitHub Pages

1. Merge this branch to `main` (or keep it on the branch and select it below).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the branch (e.g. `main`) and folder **`/ (root)`**, then **Save**.
5. After a minute it will be served at:
   `https://manishigautam.github.io/PaymentTestCases/`

## Practice environments (legitimate)

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — free labs on business logic and race conditions.
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) — intentionally broken e-commerce app.
- [OWASP API Security Top 10](https://owasp.org/API-Security/editions/2023/en/0x11-t10/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- Bug bounty platforms: HackerOne, Bugcrowd, Intigriti, YesWeHack — always stay inside the program's scope.
