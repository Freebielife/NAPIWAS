# NAPIWAS Observatory

- This repository is the independent NAPIWAS project, generated from TON-Observatory-Template 1.3.0.
- Token-specific settings belong in project.json. Match the exact master and decimals before collecting data.
- Keep the owner-provided banner and section image. Do not substitute a catalogue flag.
- Preserve verified data when sources fail. Do not fabricate missing history, wallet labels, staking, locks or NFTs.
- Tonkeeper accounts.json is the primary shared service-label registry; keep attribution provenance.
- Do not inherit another project's DEV wallets, NFT or staking rules.
- Before release, run build.py, verify.py and the existing Python/JS tests; inspect the final HTML on desktop and mobile, RU/EN, chart controls, filters, top 10 -> 20 holders, links, copy button and overflow.
- Rendering assets must be embedded in index.html; data refresh and manual wallet lookup can use the network.
- Preserve concurrent repository changes. Never force-push over someone else's commit.
- Distinguish code saved, HTML checked, GitHub update run verified, scheduled update observed and TON Storage/DNS publication. Never claim an unobserved run or deployment.
