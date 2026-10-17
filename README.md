# Decarboxulator V4 — PR #3 Preview

Temporary **GitHub Pages preview**, isolated from the production `thelabcorner/decarboxulator` repository's Pages deployment.

- Source repository: https://github.com/thelabcorner/decarboxulator
- Pull request: https://github.com/thelabcorner/decarboxulator/pull/3
- Exact source commit: `8f1636ef7aae2984f9faef670f5f787bfbfaf697`
- Preview URL: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/
- Seal/Vent pressure tracker: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/pressure-tracker/
- Vacuum-aware pressure heatmap: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/max-pressure/
- Scale readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/scale-resolution/
- Gauge readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/gauge-resolution/
- Update: slider-first, light/dark New York style resolution workbenches, interactive 2× and 5× sample-mass thresholds, instrument display-step comparisons, and optional equilibrium CO2 dissolution in pressure tools.
- Verification before publishing: source build and unit suite, 126 resolution/Henry calculator QA checks, and 144 Chromium/WebKit slider checks at 320, 390, 768 and 1440 px. Pages workflow independently builds the pinned source commit.
- The preview build excludes production analytics and new service-worker registration. A one-time migration worker retires cached offline assets from prior preview deployments.
- Pages deployment: GitHub Actions, not Cloudflare.
- No commits or Pages releases are made to the production repository by this preview.
- Temporary test instance; remove this repository when the preview is no longer needed.

The workflow pins the PR commit and runs automated tests and build verification before publishing. All preview assets use the independent GitHub Pages subpath.