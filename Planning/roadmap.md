# Implementation Roadmap

## Week 1 — Foundation and source ingestion
##### Milestone 1 — Source acquisition
###### Estimated effort: 7–9 hours

### Tasks
- [X] Install Python, llama.cpp and the initial model.
- [ ] Create the project structure.
- [ ] Establish project and source-file management.
- [ ] Implement TXT, JSON and YAML readers.
- [ ] Implement PDF text extraction.
- [ ] Implement basic Python code and docstring extraction.
- [ ] Define the unified source data structure.
- [ ] Introduce input validation and error reporting.

**Deliverable: A working application capable of accepting the principal input formats and displaying extracted information with source references.**

## Week 2 — Extended input processing
##### Milestone 2 — Multi-source support
###### Estimated effort: 7–9 hours

### Tasks
- [ ] Add CSV and Excel readers.
- [ ] Extend code parsing and comment extraction.
- [ ] Add basic Draw.io XML extraction.
- [ ] Implement image asset management.
- [ ] Preserve page numbers, file locations and other metadata.
- [ ] Test extraction completeness.

**Deliverable: The system can consolidate information from mixed technical sources.**

Note: Image interpretation beyond OCR and basic diagram-source extraction remains an optional extension.

## Week 3 — Document structure and AI generation
##### Milestone 3 — Documentation generation
###### Estimated effort: 8–10 hours

### Tasks
- [ ] Integrate Qwen3.
- [ ] Implement the structured document model.
- [ ] Implement JSON document definitions.
- [ ] Create technical documentation templates.
- [ ] Create operating procedure templates.
- [ ] Implement section-by-section generation.
- [ ] Add manual user instructions.
- [ ] Implement missing-information markers.
- [ ] Introduce evidence-aware prompts.

**Deliverable: Generate complete technical manuals and operating procedures in Markdown.**

## Week 4 — Validation and anti-hallucination
##### Milestone 4 — Reliable generation
###### Estimated effort: 8–10 hours

### Tasks
- [ ] Implement source-to-document traceability.
- [ ] Implement fact validation.
- [ ] Detect conflicting source information.
- [ ] Validate numerical values and configuration parameters.
- [ ] Check generated commands against source evidence.
- [ ] Detect unsupported claims.
- [ ] Add document completeness checks.
- [ ] Create automated test fixtures.
- [ ] Test generation with deliberately incomplete and contradictory sources.

**Deliverable: Documentation with verifiable source references and explicit handling of missing or conflicting information.**

## Week 5 — Editable output and interface
##### Milestone 5 — Document production
###### Estimated effort: 7–10 hours

### Tasks
- [ ] Complete Markdown export.
- [ ] Implement Pandoc-based LaTeX export.
- [ ] Create reusable LaTeX document templates.
- [ ] Implement diagram and image embedding.
- [ ] Add document preview.
- [ ] Add editing and regeneration capabilities.
- [ ] Add Streamlit interface for document generation.
- [ ] Implement output directory and version management.

**Deliverable: Editable Markdown and LaTeX documentation, generated through a usable local interface.**

## Week 6 — Testing, refinement and release
##### Milestone 6 — Version 1.0
###### Estimated effort: 8–12 hours

### Tasks
- [ ] Test with realistic technical projects.
- [ ] Test multiple input formats simultaneously.
- [ ] Test missing and contradictory information.
- [ ] Benchmark model generation time.
- [ ] Measure peak RAM consumption.
- [ ] Optimize context sizes and processing.
- [ ] Check Markdown and LaTeX rendering.
- [ ] Test PDF conversion using the exported LaTeX.
- [ ] Test fully offline operation.
- [ ] Document installation and usage.

**Deliverable: Version 1.0 of the local documentation generation platform.**
