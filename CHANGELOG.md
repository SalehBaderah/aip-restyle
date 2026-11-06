# Changelog

## Unreleased

- Moved AIP Restyle into the standalone `Sl-15-dev/aip-restyle` repository, preserving the skill's commit history.
- Updated CLI installation, manual setup, and migration instructions for the standalone package.
- Excluded local input and output folders from version control.

## v2.1

- Added white, purple, dark-purple, and navy team-emblem assets in SVG and transparent PNG, preserving the original seven-path geometry.
- Made on-object integration explicit: shirt/laptop requests must appear on those surfaces; no automatic footer substitute.
- Added surface-relative sizing and a required visibility check at normal viewing size.
- Corrected final delivery: verify/display the actual branded artifact, not a blank-shirt intermediate; distinguish exact masters from generative mockups.
- Documented preview MIME verification: use `image/png` or `image/jpeg` for verified image bytes instead of a generic octet-stream transport.
- Bundled all eight AIP colors in JSON, CSS, CSV, GPL, SVG, and PNG with RGB/source-CMYK data and documented label discrepancies.
- Added integrated shirt/laptop examples and expanded validation to 18 tests, including original PDF palette verification.

The original guideline PDF is unchanged. This is an updated package, not an automatic installation.
