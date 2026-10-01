# Jesse Brookins

I'm a software engineer. I built and shipped [Resecta](https://resecta.app), an open-source iPhone app for redacting PDFs, on my own. Before that, I spent three summers at Fidelity Investments (Java/Spring Boot, Node.js, Angular) and earned a BS in Computer Science from UMass Amherst in 2023.

**Looking for** a full-time software engineering role. Available now; open to remote work or relocation.

## Resecta

[![Download on the App Store](https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us?releaseDate=1786492800)](https://apps.apple.com/us/app/resecta/id6786922787)

A black box drawn over a PDF can leave the text underneath in the file. Resecta turns every page into a flat image, overwrites the regions you marked in the pixels, and rebuilds the file from those images, so redacted text is removed rather than covered.

On-device detection suggests names, account numbers, and other personal details; nothing is redacted until you confirm. By default, Resecta then reopens the finished file, re-runs your searches and a detection sweep on it, and flags what it still finds. It is free, with no account, no analytics, and no network requests of its own.

### How it's built

I started Resecta in April 2026, open-sourced it in July, and shipped it to the App Store in August. The app and its redaction engine are Swift (SwiftUI, PDFKit, Vision). A separate Python pipeline builds and signs the detection data, and the app verifies that signature at load.

- **Code:** [resecta](https://github.com/Merlin1A/resecta) (app and redaction engine) · [resecta-datapipeline](https://github.com/Merlin1A/resecta-datapipeline) · [resecta-sample-doc](https://github.com/Merlin1A/resecta-sample-doc) (synthetic test PDFs)
- **Design:** [ENGINEERING.md](https://github.com/Merlin1A/resecta/blob/main/ENGINEERING.md) (each claim, its check, and that check's limits) · [THREAT-MODEL.md](https://github.com/Merlin1A/resecta/blob/main/THREAT-MODEL.md) (what it defends against, and what it doesn't)

## Contact

[jessebrookins@protonmail.com](mailto:jessebrookins@protonmail.com) · [linkedin.com/in/jessebrookins](https://www.linkedin.com/in/jessebrookins)
