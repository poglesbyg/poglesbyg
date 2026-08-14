# Hi there 👋

I'm Paul Greenwood: data scientist and developer working on document ingestion, retrieval systems, and agent tooling, with a background in biomedical informatics and federal geospatial data.

Most of what I build lately answers the same question: how do you get messy, unstructured documents into a form a model can actually reason over? Scanned PDFs, OOXML, lab forms, literature, road inventories. The repos below are where I work that out.

## 🔨 What I'm building

**Document ingestion & retrieval**
- [**lab_submission_rag**](https://github.com/poglesbyg/lab_submission_rag) — RAG system that extracts laboratory submission data from PDF/DOCX into seven structured categories with validated models and per-field confidence scoring. ChromaDB, domain-specific chunking, pluggable Ollama/OpenAI/Claude backends.
- [**pdf_slurper**](https://github.com/poglesbyg/pdf_slurper) — PDF table and metadata extraction (PyMuPDF + pdfplumber) with header normalization, numeric parsing, and content-hash idempotency into SQLite. CLI, FastAPI web UI, containerized.
- [**bb_rag**](https://github.com/poglesbyg/bb_rag) — a RAG engine in Rust with no vector database and no framework. Sentence-aware chunking with overlap, TF-IDF and dense cosine retrieval, three swappable providers. Written to understand the internals rather than import them.
- [**LitKG**](https://github.com/poglesbyg/LitKG) — integrating biomedical literature with structured knowledge graphs (CIVIC, TCGA, CPTAC) for hypothesis generation. Entity linking with ontology disambiguation, hybrid GNN + RAG.

**Agent tooling & Rust**
- [**capscan**](https://github.com/poglesbyg/capscan) — diff the capability surface of a crate between versions: unsafe, FFI, process/network/filesystem access, build scripts. On [crates.io](https://crates.io/crates/capscan).
- [**capscan-mcp**](https://github.com/poglesbyg/capscan-mcp) — MCP server exposing that scanning as agent-callable tools, so an agent can check what a dependency actually does before recommending a version bump. Ships with a Claude Code skill.
- [**decidex**](https://github.com/poglesbyg/decidex) — extracts engineering decisions from git history and surfaces them in `CLAUDE.md`, Cursor rules, and Copilot instructions, so AI tools remember what you already decided. On npm.
- [**tracelet**](https://github.com/poglesbyg/tracelet) — minimal embeddable Rust tracer: the `#[tracing::instrument]` you already use, without the OpenTelemetry dependency tree.

**Science & geospatial**
- [**ai-chipseq-mcp**](https://github.com/poglesbyg/ai-chipseq-mcp) — applying ChIP-seq peak-calling methodology to transformer attention patterns for model interpretability.
- [**usda-forest-viz**](https://github.com/poglesbyg/usda-forest-viz) — downloading and visualizing USDA Forest Service Enterprise Data Warehouse geospatial datasets.

## 💼 Work

**Data Scientist**, Leading Solutions LLC 
Supporting USDA Forest Service Hurricane Helene recovery for the National Forests in North Carolina. OCR ingestion pipelines for thousands of scanned survey documents, Python/ML analysis of forest road infrastructure across 1,900+ segments tied to billions in recovery funding, ArcGIS Online automation, and long-term strategic planning analysis.

**Product Manager & Developer**, UNC Chapel Hill School of Medicine
AI/ML research tooling, genomics pipelines (NCGenes), clinical NLP, and FHIR/HL7 integrations.

**Project Manager**, UNC Chapel Hill 
20+ concurrent research projects.

**Program Coordinator**, UNC Chapel Hill 
EHR and precision analytics initiatives.

## 🛠️ Tech

- **AI/ML** — RAG architecture, embeddings and retrieval evaluation, LangChain, ChromaDB, MCP servers, OCR (pytesseract), NLP, scikit-learn
- **Languages** — Python, Rust, TypeScript, SQL, R, Bash
- **Data & geospatial** — pandas, GeoPandas, ArcGIS Online/Pro, matplotlib, seaborn, Plotly
- **Health informatics** — FHIR, HL7, EHR systems, clinical data pipelines
- **Infrastructure** — Linux (Fedora, CachyOS), Docker, Slurm, Singularity, Conda, Git, CI/CD

## 🎓 Background

- **MPS, Biomedical Health Informatics** — UNC Chapel Hill
- **BA, English** — UNC Chapel Hill
- **Additional coursework** — Chemistry (UNCG), Computer Science (University of Bergen), Linguistics (University of Oslo)

## 📄 Publications

- Co-author, *Nature* — GENYSIS
- Wahl et al. (2021) — SARS-CoV-2 treatment research

## 🌍 Languages

English (native) • Norwegian • Swedish • Danish

## 🤝 Open to collaborating on

Retrieval and document-processing systems • agent tooling and MCP • biomedical informatics • open-source research tools

## 🏔️ Otherwise

Voracious reader • backcountry skiing • hiking • camping • cooking • acoustic guitar

## 📫 Connect

[LinkedIn](https://linkedin.com/in/poglesbyg) · [Portfolio](https://poglesbyg.github.io) · [Email](mailto:pogrant@alumni.unc.edu)
