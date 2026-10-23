# Decarboxulator V4 — PR #3 Preview

Temporary **GitHub Pages preview**, isolated from the production `thelabcorner/decarboxulator` repository's Pages deployment.

- Source repository: https://github.com/thelabcorner/decarboxulator
- Pull request: https://github.com/thelabcorner/decarboxulator/pull/3
- Exact source commit: `457d07cc111c30faaaa5febea5e68826a0e4e0f6` (feature/v4-multi-acid-cannabinoids-20261014)
- Preview URL: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/
- Seal/Vent pressure tracker: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/pressure-tracker/
- Atmospheric and vacuum starting-pressure controls / heatmap: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/max-pressure/
- Cartridge formulation with starting batch ingredient weigh-out: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/cartridge-formulation/
- Extract formulation with the same ingredient controls and mass model: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/extract-formulation/
- Scale readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/scale-resolution/
- Gauge readability: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/gauge-resolution/
- Update: Vessel Pressure now exposes initial sealed-gas pressure in the main model controls (previously hidden in advanced assumptions). It supports editable PSIA, negative PSIG for vacuum, outside atmospheric reference pressure, an atmospheric shortcut, an illustrative half-ambient preset, and immediate recomputation of the 49-cell heatmap. Pressure units preserve the same physical gas state on conversion. The FAQ distinguishes initial evacuated sealed gas from a pump continuously maintaining vacuum, which this sealed-vessel model does not simulate.
- Previously introduced: two distinct sidebar and preview routes, Cartridge formulation and Extract formulation, use one workbench and shared saved recipe. Both support transfer loss, separate starting ingredient weigh-out, CO2 mass balance, and gross/recoverable yield.
- Previous update retained: slider-first scale/gauge workbenches and optional equilibrium CO2 dissolution in pressure tools.
- Verification before publishing: 212 unit tests, 904 calculator-studio Chromium/WebKit checks across mobile and desktop, TypeScript, SEO and production source build. Pages workflow independently rebuilds and tests the pinned source commit.
- The preview build excludes production analytics and new service-worker registration. A one-time migration worker retires cached offline assets from prior preview deployments.
- Pages deployment: GitHub Actions, not Cloudflare.
- No commits or Pages releases are made to the production repository by this preview.
- Temporary test instance; remove this repository when the preview is no longer needed.

The workflow pins the PR commit and runs automated tests and build verification before publishing. All preview assets use the independent GitHub Pages subpath.