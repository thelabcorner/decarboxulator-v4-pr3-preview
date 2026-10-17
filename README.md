# Decarboxulator V4 — PR #3 Preview

Temporary **GitHub Pages preview**, isolated from the production `thelabcorner/decarboxulator` repository's Pages deployment.

- Source repository: https://github.com/thelabcorner/decarboxulator
- Pull request: https://github.com/thelabcorner/decarboxulator/pull/3
- Exact source commit: `d18d8c236bc7b65ba2ba648946ef34c64f0851f7`
- Preview URL: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/
- Seal/Vent pressure tracker: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/pressure-tracker/
- Vacuum-aware pressure heatmap: https://thelabcorner.github.io/decarboxulator-v4-pr3-preview/tools/max-pressure/
- Update: dense New York instrument-style pressure tracker, restored THCa → THC / THC → THCa names, and shared free-headspace estimator.
- Verification: 181 unit tests; 185 pressure/headspace interactive checks; 400 existing calculator UI checks (Chromium/WebKit).
- Pages deployment: GitHub Actions, not Cloudflare.
- No commits or Pages releases are made to the production repository by this preview.
- Temporary test instance; remove this repository when the preview is no longer needed.

The workflow pins the PR commit and runs automated tests and build verification before publishing. All preview assets use the independent GitHub Pages subpath.