## Dylan San Gabriel

Software engineer in Northern Virginia. I built and run the ERP, the ERP a
six-channel dental distributor operates on — order intake, inventory, repricing,
shipping, customer service and the books, one codebase, as its only engineer.

**~520** orders a day · **32K** products · **6** sales channels · **180** scheduled jobs

<sub>Measured on the production database, August 2026. Orders were ~270 a day when I started.</sub>

### What's readable here

The ERP is the company's and stays private. These are the parts that stand on their own.

- **[Portfolio/code](https://github.com/Dylansg318/Portfolio/tree/main/code)** — thirteen
  sanitized production modules, with their tests and the reasoning kept: GS1 barcode
  parsing, a ZPL thermal-label renderer, carrier-invoice parsers whose column meanings
  were derived against invoice totals rather than trusted from a spec, a self-updating
  device agent that is never allowed to update its own rollback path, and the file locks
  that let 5–8 concurrent AI coding sessions share one git checkout.
- **[SplitApp](https://github.com/Dylansg318/SplitApp)** — photograph a receipt, tap who
  had what, get the split. On-device OCR, no language model, nothing leaves the phone.
  A receipt prints its own answer key, so a split that doesn't reconcile against the
  printed total is never shown.
- **[Portfolio](https://github.com/Dylansg318/Portfolio)** — the site linked below.
  Astro, TypeScript, Cloudflare Workers.

### Elsewhere

[portfolio.dylansg0318.workers.dev](https://portfolio.dylansg0318.workers.dev) ·
[Résumé](https://portfolio.dylansg0318.workers.dev/resume) ·
[LinkedIn](https://www.linkedin.com/in/dylan-san-gabriel/) ·
dylansg0318@gmail.com

Open to backend / full-stack roles, remote or in Northern Virginia.
