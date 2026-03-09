# Supplementary Materials for “Toward Minimalist HUDs in Action Games: Longitudinal Trends and Player Perception”

This repository contains the supplementary materials supporting the paper’s corpus construction, expert HUD coding, stimulus documentation, and survey implementation. It is intended to make the methodological basis of the project transparent and to provide enough documentation for readers to understand how the corpus was delimited, how the coding framework was applied, and how the clip-based user study was implemented.

## Repository structure

### Root-level materials

- `hud_minimalism_codebook.pdf`  
  Full coding manual for the expert analysis of HUD minimalism. The document defines the anchor-based coding framework used to derive the four reported dimensions: Diegetic Integration (DIEG), Persistence (PERS), Density (DENS), and Contextuality (CONT). It also specifies the observation rules, weighting logic, edge-case handling, and the mathematical rationale behind the scoring procedure.

- `exclusion_rationales.pdf`  
  Documentation of titles considered but excluded from the final corpus, together with the methodological reasoning for each exclusion. These rationales are included to make corpus construction explicit and reproducible.

- `stimulus_timestamps_links.pdf`  
  Documentation of the public gameplay sources used for the six clips in the user study, including source links and extraction timestamps for each selected segment.

- `README.md`  
  Overview of the repository and its contents.

### Survey materials

The folder `survey_data/` contains the survey documentation and data exports associated with the clip-based user study. Further documentation for the survey materials and exports are in the Folder-specific `README.md`  

## Scope of the supplementary materials

The materials in this repository support four parts of the project.

First, the coding manual documents how HUD minimalism was operationalized as a relative information-distribution strategy rather than as the mere absence of interface elements. Instead of counting raw widgets, the framework codes gameplay-relevant information anchors and evaluates how they are communicated across ordinary gameplay. This approach was used to derive the four expert-rated dimensions reported in the paper.

Second, the exclusion document records why certain prominent titles were not included in the final corpus. These decisions were made to preserve comparability within a bounded sample of real-time, character-centric 3D action-adventure and action-RPG games.

Third, the stimulus documentation records the origin of the six gameplay clips shown in the user study. For each clip, the repository specifies the publicly available source and the exact segment used for extraction.

Fourth, the survey folder documents the user study as implemented in SoSci Survey. It contains the questionnaire export and variable documentation needed to reconstruct the survey structure, item wording, and response coding.

## Coding scope and observation rules

The expert coding focused on the mature default HUD as ordinarily encountered once core systems were available in regular play. Tutorial-only states, menus, accessibility presets, and user-customized layouts were excluded. Coding was based on publicly available gameplay footage spanning the major UI-relevant contexts of play, including exploration, combat, traversal, dialogue, and other game-specific states in which interface demands changed.

## Intended use

This repository is meant as a documentation and transparency package for the paper. It is not intended as a full gameplay archive, but as a structured record of the materials and rules used to construct the corpus, score the HUD dimensions, select the study stimuli, and document the survey implementation.