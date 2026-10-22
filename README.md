# Decarboxulator V4 — PR #3 Preview

Temporary **GitHub Pages preview**, isolated from the production `thelabcorner/decarboxulator` repository's Pages deployment.

- Source repository: https://github.com/thelabcorner/decarboxulator
- Pull request: https://github.com/thelabcorner/decarboxulator/pull/3
- Exact source commit: `d25dd5252ce4d936fb76319d2ddea96e34d75a99` (feature/v4-multi-acid-cannabinoids-20261014)
- Preview URL: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/
- Seal/Vent pressure tracker: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/pressure-tracker/
- Vacuum-aware pressure heatmap: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/max-pressure/
- Cartridge formulation with starting batch ingredient weigh-out: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/cartridge-formulation/
- Scale readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/scale-resolution/
- Gauge readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/gauge-resolution/
- Update: cartridge formulation now includes a cannabinoid-only starting subtotal, starting mass without terpenes, separately reserved terpene addition, gross starting ingredients, theoretical CO2 release, post-decarb cannabinoid mass, finished non-terpene subtotal, and final gross blend. Every quantity is shown alongside individual THCa/CBD/terpene weigh-out amounts. Calculations still support multiple acidic cannabinoids, both batch workflows, and retained acidic forms. The saved calculation library, migration, and the THCa 0.877 conversion factor remain available.
- Previous update retained: slider-first scale/gauge workbenches and optional equilibrium CO2 dissolution in pressure tools.
- Verification before publishing: 206 unit tests, 520 calculator-studio Chromium/WebKit checks across mobile and desktop, TypeScript and production source build. Pages workflow independently rebuilds and tests the pinned source commit.
- The preview build excludes production analytics and new service-worker registration. A one-time migration worker retires cached offline assets from prior preview deployments.
- Pages deployment: GitHub Actions, not Cloudflare.
- No commits or Pages releases are made to the production repository by this preview.
- Temporary test instance; remove this repository when the preview is no longer needed.

The workflow pins the PR commit and runs automated tests and build verification before publishing. All preview assets use the independent GitHub Pages subpath.