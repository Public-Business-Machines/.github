# Public Business Machines

**Public Business Machines** is an open software organization focused on building accessible, developer-friendly tools for document authoring, scripting, and print-production workflows.

---

## Projects

### Billetscript Editor v1

The **Billetscript Editor** is a document scripting and layout editor designed for composing structured documents — including billets, notices, certificates, and formal correspondence — with precision formatting and print-ready output.

Key capabilities of the Billetscript Editor include:

- **Script-based document authoring** — Define document content and layout through a concise scripting syntax, enabling repeatable and version-controlled document production.
- **Rich text and layout control** — Fine-grained control over typography, margins, and page geometry to meet formal document standards.
- **Print-production workflows** — Export documents directly to print-ready formats suitable for professional and commercial production.
- **Blue Electroplate integration** — Built-in support for the Blue Electroplate rendering pipeline (see below).

---

## Blue Electroplate

**Blue Electroplate** (`Blue Electroplate v1.cs`) is the core rendering and output component of the Billetscript Editor. Inspired by the historical electroplate printing process — where a high-fidelity metal plate is formed from a composed document to enable precise, repeatable reproduction — Blue Electroplate translates a Billetscript document into a finalized, print-quality output.

### Features

- **Document rendering engine** — Converts Billetscript source documents into structured, fully laid-out output representations ready for display or export.
- **High-fidelity reproduction** — Preserves precise typographic and spatial properties of the original composition during rendering, ensuring output matches the authored intent.
- **Electroplate pass pipeline** — Executes a multi-stage processing pipeline (the "electroplate pass") that resolves references, applies styles, calculates layout geometry, and produces the final document plate.
- **Format export** — Supports exporting the rendered plate to multiple output formats, including print-ready PDFs and structured data representations.
- **Error and validation reporting** — Provides detailed validation feedback during the electroplate pass, highlighting document structure issues before output is committed.
- **Extensible rendering hooks** — Exposes hooks at each stage of the pipeline, allowing downstream tools and integrations to inspect or modify the document plate during rendering.

### Purpose

Blue Electroplate serves as the bridge between human-authored Billetscript documents and their final physical or digital output. It encapsulates all logic required to take a raw script and produce a verified, reproducible document, making it the foundation of the Billetscript Editor's print-production capability.

---

## Getting Started

Visit the [Billetscript Editor v1 repository](https://github.com/Public-Business-Machines/Billetscript-Editor-v1) to explore the source code, report issues, or contribute.

---

## Contributing

We welcome contributions from the community. Please open an issue or pull request in the relevant repository. For organization-wide questions or documentation improvements, use this repository.

---

## License

See individual repositories for license information.
