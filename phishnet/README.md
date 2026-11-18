# PhishNet — Research Dashboard

An original, static research dashboard focused on phishing reporting, financial harms, model evaluation, verifiable contributions, and a fully free/open-source infrastructure strategy. This is a research/architecture dashboard, **not** a live phishing detector or an operational crypto-payment application.

## Preview

Open `phishnet/index.html` in a browser or serve this directory as static HTML. No build process, external JavaScript libraries, secrets, or API keys are required.

## Features

- FBI IC3 2025 crime-category complaint counts vs. financial losses, with a visible denominator distinction.
- Three-year comparison of directly categorized phishing/spoofing losses.
- Four-stage phishing funnel with research gaps.
- PhishNet datathon, SCAMBENCH, and EMBER2024 benchmark comparison and limitations.
- Interactive, hypothetical contributor compensation and verification-cost model.
- FOSS-based reference architecture: AGPLv3 as a licensing *candidate*, no proprietary/open-core feature gating.
- Searchable reference notes and CSV export.

## License decisions pending

This branch does not impose a license on existing repository content. Before a standalone release, confirm the rights of all contributors and add a suitable FOSS license (AGPLv3 is one candidate). Referenced papers, dataset contents, and third-party materials keep their own licenses.

## Independent GitHub Pages publication

**Do not configure the existing `ubc-agent-dashboard` repository's Pages deployment to this branch.** GitHub Pages supports one site per repository and changing the Pages source would replace the existing dashboard.

To publish this as a second GitHub Pages website:

1. Create a **new public repository**, for example `watsoncsulahack/phishnet-research`.
2. Copy `phishnet/index.html` from this branch to `index.html` at the **root** of the new repository.
3. Open the new repository's **Settings → Pages**, and select **Deploy from a branch**, branch **main**, folder **/(root)**.
4. Once published, the independent URL will be `https://watsoncsulahack.github.io/phishnet-research/`.

The existing `watsoncsulahack.github.io/ubc-agent-dashboard/` site and its main-branch workflow remain unchanged.

## Data integrity

- FBI 2025 category values: https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf (printed pp. 7–8; three-year comparison printed p. 26).
- Original PhishNet team datathon: `Phish-Net-Official.pdf`, presented November 13, 2026 (provided separately; not redistributed here).
- SCAMBENCH: https://aclanthology.org/2026.findings-emnlp.404.pdf
- EMBER2024: https://arxiv.org/abs/2506.05074

The reward calculator is an illustrative scenario, not measured costs or evidence of buyer demand. Never equate all IC3 fraud losses with phishing-caused losses.
