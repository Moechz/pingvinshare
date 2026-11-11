# Changelog

All notable user-visible changes to the pingvin-share TOS application package.

## 1.13.0-2 — 2026-11-12

### Changed
- Icon: replaced the letter monogram with a functional vector mark that describes what the app does (the upstream project does not publish a compliant SVG).

## 1.13.0-1 — 2026-11-11

### Added
- First release. pingvin-share (`stonith404/pingvin-share:v1.13.0`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8078 and running
  as a non-root user (1000:1000).
- Persistent data is kept under `/Volume1/DockerAppData/pingvinsharedocker/`.
