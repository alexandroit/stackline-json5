# Stackline changelog

## 1.0.4 - 2026-11-04

- Publish the Stackline README with the correct package version.
- Preserve the original upstream README separately; runtime files remain unchanged.
- Verify the README inside the exact npm artifact before publication.

## 1.0.3

- Update the development dependencies, Rollup plugins, and TAP runner to remove known high and critical development-tool vulnerabilities. Preserve the parser payload and regression coverage.
- Publish accurate development dependency metadata and use patched Node.js 24.22.2 in CI.

## 1.0.0

- Adopt maintenance from `json5@2.2.3` with preserved source history and license.
- Maintenance adoption with preserved runtime payload. No runtime defect correction is claimed. Reports remain visible for subsequent targeted reproduction.
- Add tested, reproducible artifact publication with npm provenance and immutable release evidence.
