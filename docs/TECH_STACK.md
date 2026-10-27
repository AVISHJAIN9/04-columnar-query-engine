# Technology Stack Specification: Columnar Vectorized Query Engine

| Layer | Component | Selection | Rationale |
| :--- | :--- | :--- | :--- |
| **Core Kernel** | Execution Engine | Rust, Apache Arrow memory layout, Python, React / TypeScript | High performance, memory predictability, and zero-cost abstractions |
| **Governance** | Version Control & CI | GitHub Actions | Automated validation, linting, and dependency monitoring |
| **Documentation** | Technical Specifications | Markdown & Mermaid | Scannable, versioned technical design and system contracts |
