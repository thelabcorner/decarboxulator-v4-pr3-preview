# Decarboxulator V4 — PR #3 Preview

Temporary **GitHub Pages preview**, isolated from the production `thelabcorner/decarboxulator` repository's Pages deployment.

- Source repository: https://github.com/thelabcorner/decarboxulator
- Pull request: https://github.com/thelabcorner/decarboxulator/pull/3
- Exact source commit: `057a0807aceae6f5b3dc048279a0b0aa81ae59f0`
- Preview URL: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/
- Seal/Vent pressure tracker: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/pressure-tracker/
- Vacuum-aware pressure heatmap: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/max-pressure/
- Scale readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/scale-resolution/
- Gauge readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/gauge-resolution/
- Update: unified tracker sessions and saved calculations in IndexedDB with a 25,565-entry shared cap, shared New York style library drawer, legacy migration, transaction-safe import/export, cross-tab change handling, and scientific explanation of the THCa 0.877 conversion factor.
- Previous update retained: slider-first scale/gauge workbenches and optional equilibrium CO2 dissolution in pressure tools.
- Verification before publishing: 201 unit tests, 40 unified-library checks across Chromium/WebKit desktop/mobile, end-to-end tracker-session lifecycle and migration checks, TypeScript and source build. Pages workflow independently rebuilds and tests the pinned source commit.
- The preview build excludes production analytics and new service-worker registration. A one-time migration worker retires cached offline assets from prior preview deployments.
- Pages deployment: GitHub Actions, not Cloudflare.
- No commits or Pages releases are made to the production repository by this preview.
- Temporary test instance; remove this repository when the preview is no longer needed.

The workflow pins the PR commit and runs automated tests and build verification before publishing. All preview assets use the independent GitHub Pages subpath.