# Plus ça change, plus c'est la même chose": from Swiss-Prot to Cellosaurus, 40 years of biocuration

> Amos Bairoch will reflect on 40 years of biocuration, from Swiss-Prot to Cellosaurus, highlighting how core challenges and values have endured despite the many developments in computational biology over that time.

## Questions to ask

- Swiss-Prot began with a human-readable flat-file schema, whereas modern databases often use relational or graph models. What were the biggest gains and losses when moving from flat files to these newer formats, and how do those trade-offs affect query performance and curation flexibility today?
- Swiss-Prot's PE evidence codes give a graded sense of annotation reliability, but Cellosaurus uses binary contamination flags. Could you imagine a unified, quantitative confidence metric spanning both proteins and cell lines—and what kinds of data (e.g., publication counts, STR-profile scores, automated checks) would you include?”
- UniRule and HAMAP drive large-scale automated annotation in Swiss-Prot, while Cellosaurus leans on GitHub-driven issue tracking and community feedback. What design principles or limitations have you seen in each approach, and how might hybrid strategies combine their strengths?”
- Both proteoforms (e.g., splice variants, PTM states) and subclonal cell-line variants can be hard to tell apart. What are the most persistent challenges in name-normalization and ontology mapping (e.g. against CLO or disease ontologies), and where do heuristic rules still fall short?”
- Capturing dynamic passage history for cell lines—or context-specific PTMs for proteins—can vastly improve reproducibility. What lightweight provenance models could be layered on top of existing schemas without exploding curator workload?”
- Swiss-Prot benchmarks misannotation rates across enzyme families, while Cellosaurus tracks STR-authentication success. How could we develop unified QA metrics or benchmarks that let us compare data quality fairly between protein and cell-line resources?”
- When you integrate Swiss-Prot reference proteomes into mass-spec PTM mapping or link Cellosaurus RRIDs to CRISPR and single-cell workflows, what are the key interoperability bottlenecks—both technical and semantic—that must be solved for reproducible end-to-end pipelines?”
- Large language models and automated ontology-mapping tools promise to accelerate curation, but risk surface-level errors. What safeguards or human-in-the-loop designs would you recommend to maintain Swiss-Prot's depth and Cellosaurus's reliability at scale?”
- Crowdsourced platforms can vastly expand coverage to non-model organisms and rare cell lines, yet expert review is critical for consistency. What hybrid community curation models do you see as most promising to balance breadth and depth?”
- Looking ahead, how might biocuration frameworks evolve to natively represent temporal cell-state trajectories, dynamic proteoform ensembles, or even single-cell omics datasets within Swiss-Prot- or Cellosaurus-style infrastructures?
