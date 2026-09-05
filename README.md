# Jesse Brookins

Software engineer — iOS/Swift and backend/Python. BS in Computer Science, UMass Amherst (2023); formerly Fidelity Investments. Open to backend, iOS, and security/privacy roles — full-time, available now; remote, or relocating to Boston, Austin, or Seattle.

## Resecta

[![Download on the App Store](https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us?releaseDate=1786492800)](https://apps.apple.com/us/app/resecta/id6786922787)

Open-source, on-device iOS 26 PDF and image redaction — no accounts, no telemetry, and a binary that contains zero `URLSession`/`NWConnection` references. Sole engineer across product, architecture, security model, build pipeline, and the App Store release (v1.1.0 live). About 171k lines across a Swift 6.2 app + `RedactionEngine` package and a deterministic, hash-locked Python 3.12 data pipeline; 3,759 test functions.

| Repository | What it is |
|---|---|
| [resecta](https://github.com/Merlin1A/resecta) | The iOS app and the `RedactionEngine` SwiftPM package — Swift 6.2 strict concurrency, PDFKit/CoreGraphics/Vision, 5- and 10-layer output verification, a written threat model |
| [resecta-datapipeline](https://github.com/Merlin1A/resecta-datapipeline) | The build-time data pipeline — Python 3.12, `mypy --strict`, SHA-256 hash-locked artifacts, the ~11.8M-key Bloom name filter |
| [resecta-sample-doc](https://github.com/Merlin1A/resecta-sample-doc) | Synthetic-PII sample documents with ground-truth annotations for testing redaction |

Site: [resecta.app](https://resecta.app)

## Contact

[jessebrookins@protonmail.com](mailto:jessebrookins@protonmail.com) · [linkedin.com/in/jessebrookins](https://www.linkedin.com/in/jessebrookins)
