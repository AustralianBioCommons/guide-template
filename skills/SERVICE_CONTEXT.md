# Service Documentation Authoring Context Template

Use this file to set up an AI-assisted guide writing session. Fill in as many fields as you
can before starting, the more context you provide upfront, the less the AI will need to ask,
and the closer the first draft will be to the BioCommons template conventions.

---

## 1. Documentation identity

### Service / platform title
<!-- A working title is fine — it can change. -->
<!-- Example: "Australian BioCommons Leadership Share (ABLeS)" -->


### Main / target computational infrastructure for the service
<!-- Check all that apply -->

- [ ] Galaxy Australia
- [ ] NCI Gadi (PBS Pro)
- [ ] Pawsey Setonix (Slurm)
- [ ] Nectar Research Cloud
- [ ] Australian Nextflow Seqera Service
- [ ] Bioplatforms Australia Data Portal
- [ ] Other: _______________


---

## 2. Audience

**Who is this documentation for?**
<!-- Describe the intended reader. Be specific — this affects tone, assumed knowledge, and
     how much background explanation is needed. -->
<!-- Example: "Researchers new to HPC who have some command-line experience but have
     never used a job scheduler before" -->


**What can the reader be assumed to already know?**
<!-- List skills/tools the documentation can reference without explaining -->
<!-- Example: basic Linux commands, what FASTA format is, how to log in to an HPC -->


**What should the documentation NOT assume the reader knows?**
<!-- List things that need to be explained from scratch -->
<!-- Example: what Nextflow is, what a container is, what a samplesheet is -->

---


## 3. Scope

**What this documentation covers:**
<!-- Bullet list of the main tasks the usage guide (i.e. usage-guide.md) for the documentation will walk through -->
<!--
- Task 1
- Task 2
- Task 3
-->


**What this documentation explicitly does NOT cover:**

<!-- Bullet list of the main tasks the usage guide (i.e. usage-guide.md) for the documentation will **NOT** walk through -->
<!-- Important for keeping the documentation focused. Helps the AI avoid scope creep. -->
<!-- Example: "This documentation does not cover how to interpret AlphaFold2 output structures.
     See the best-practices guide for that." -->


**Approximate size:**
- [ ] Short (1–2 sections, single page)
- [ ] Medium (3–5 sections, single page)
- [ ] Long (6+ sections, consider multi-page)

---


## 4. Registry metadata

Fill in what you have. For anything not yet available, write `Not yet known` — the AI will
insert a clearly labelled placeholder and remind you to supply the real value before publishing.

**Any WorkflowHub entry URLs, DOIs, or collections:**
<!-- WorkflowHub entry example: https://workflowhub.eu/workflows/221 -->
<!-- WorkflowHub DOI example: https://doi.org/10.48546/WORKFLOWHUB.WORKFLOW.221.3 -->
<!-- WorkflowHub collection example: https://workflowhub.eu/collections/5 -->

**Any relevant bio.tools entry URLs:**
<!-- Example: https://bio.tools/alphafold_2 -->

**Any relevant TeSS training search links:**
<!-- Example: https://tess.elixir-europe.org/search?q=genome+assembly -->
<!-- Generate one by searching for your topic at tess.elixir-europe.org -->

**Zenodo DOI (if a previous version of this documentation has been published):**
<!-- Example: https://doi.org/10.5281/zenodo.8210268 -->
<!-- If new guide: "Not yet minted" -->

---


## 5. People

**Authors:**
<!-- Add a row for each contributing author. GitHub handle and ORCID are used in CONTRIBUTORS.yml -->

| Name | GitHub handle | ORCID | Institution |
|------|--------------|-------|-------------|
|      |              |       |             |
|      |              |       |             |


**BioCommons program, project, or activity this documentation is connected to:**
<!-- Example: Threatened Species Initiative, ABLeS, Australian Nextflow Seqera Service -->
<!-- If none: leave blank -->


**Funding acknowledgement — any additional funders beyond NCRIS/BioCommons?**
<!-- Example: "Bioplatforms Australia", "ARC grant DP123456" -->
<!-- The standard NCRIS/BioCommons acknowledgement will always be included -->

---


## 6. Related resources

**Related documentation:**
<!-- Links to existing documentation the reader might need before or after this one -->
<!-- Links to existing BioCommons documentation that could be used to help draft this documentation -->
<!-- Example: https://australianbiocommons.github.io/how-to-guides/genome_assembly/assembly_qc -->


**Upstream documentation the AI should reference for technical accuracy:**
<!-- Links to relevant docs, nf-core pages, platform user guides, etc. -->
<!-- The AI cannot fetch these automatically — paste key details into the session if needed -->
<!--
- Tool docs: 
- Platform docs:
- nf-core page:
-->


**Any existing draft content to incorporate:**
<!-- If you have notes, a Google Doc, a previous documentation version, or any other draft,
     describe it here. Paste the content into the session after this context file.
     Note: always convert existing content to markdown before asking the AI to work with it. -->

---


## 7. Known constraints or special requirements

**Are there any known technical gotchas for this service / platform?**
<!-- Example: "AlphaFold2 databases are very large and must be pre-staged on Gadi before
     running — this is not obvious from the nf-core docs" -->


**Are there access or eligibility requirements the reader needs to meet first?**
<!-- Example: "Users must have an active ABLeS allocation before following this documentation" -->

---


## 8. Session goals

**What do you want to have produced by the end of this session?**
<!-- Check all that apply -->
- [ ] Full draft of the complete documentation
- [ ] One specific section: _______________
- [ ] Convert existing draft to BioCommons template format
- [ ] Review and fix an existing documentation site, so that it aligns with the template checklist


**Any sections you already have content for and don't need the AI to generate?**
<!-- List them so the AI doesn't regenerate content you're happy with -->

---

*This file is part of the Australian BioCommons guide-template repository.
See `llms.txt` for full documentation template conventions and the closing review checklist.*
