# Lynn Smith

Researcher at the University of Tübingen (Physiology Institute II — Garaschuk Lab),
working on **in vivo two-photon calcium imaging** in the mouse V1 cortex and the
**pipelines** to analyze it.

### Current focus
- In vivo awake two-photon calcium imaging (mouse visual cortex)
- End-to-end analysis pipelines: motion correction → segmentation → dF/F →
  event detection → tuning & population analysis → interactive reports
- Signal processing for calcium traces

### Public work

| | |
|---|---|
| **[mesc-io](https://github.com/LynnYuSmith/mesc-io)** · [PyPI](https://pypi.org/project/mesc-io/) | Read Femtonics `.mesc` two-photon recordings in Python, in the units the native reader shows — every unit's metadata and stage position, export and write-back, and a browser viewer that draws ROIs and computes their dF/F. Tested on three platforms; `pip install mesc-io`. |
| **[bio-methods-gallery](https://github.com/LynnYuSmith/bio-methods-gallery)** | Small, self-contained bio-imaging and bioinformatics methods. Each tile stands alone, runs in a minute on a synthetic example it generates itself, and answers one question against the established method — with tests and a before/after figure. |
| **[stimulus-runner](https://github.com/LynnYuSmith/stimulus-runner)** | Browser (WebGL) grating presenter for visual physiology: seamless grey ↔ grating, queued protocols, a dual-screen operator panel, and corner pulse markers that write the played protocol into the recording. |
| **[stimulus-aligner](https://github.com/LynnYuSmith/stimulus-aligner)** | The other half of the loop: decodes those pulse markers back out of a recording and aligns the played protocol onto the frame-exact timeline. |

Together these close the loop of an experiment: the runner shows the stimulus and marks it into the recording, the aligner reads the marks back out, and mesc-io reads the recording itself.

### Education
- **M.Sc.** Molecular Physiology & Biophysics — Kyiv Academic University (2021–2023)
- **B.Sc.** Biology & Biotechnology — National University of Kyiv-Mohyla Academy (2017–2021)

### Languages
English (C1) · Українська (native) · Deutsch (B1) · Français (A2)
