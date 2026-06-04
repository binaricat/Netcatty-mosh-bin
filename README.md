# Netcatty-mosh-bin

Pre-built mosh-client binaries for Netcatty packaging.

## Current release

- Release: [mosh-bin-1.4.0-2](https://github.com/binaricat/Netcatty-mosh-bin/releases/tag/mosh-bin-1.4.0-2)
- Upstream source: [mobile-shell/mosh](https://github.com/mobile-shell/mosh)
- Upstream ref: `mosh-1.4.0`
- Built by Netcatty workflow: [run 25430802591](https://github.com/binaricat/Netcatty/actions/runs/25430802591)
- Netcatty build-script commit: `8efdd1c9cbcfef97de2f51f9dc5a5b54603c2533`

## Traceability

Each release should let a user trace the binary back to where it came from:

- The release notes link the exact Netcatty workflow run that produced the binaries.
- The release notes record the upstream mosh ref, upstream tag object, and upstream source commit.
- `SHA256SUMS` records checksums for the published files.
- `BUILD-PROVENANCE.json` records the same provenance in a machine-readable form.
- GitHub also shows a sha256 digest for every uploaded release asset.

## Platform notes

- Linux x64 and Linux arm64 are built from upstream mosh source in manylinux2014 containers.
- macOS is built from upstream mosh source as a universal binary.
- Windows x64 is built from upstream mosh source in CI using Cygwin and bundles required runtime DLLs.
- Windows arm64 is not included in the current release.
