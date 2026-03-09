## Overview

This folder contains the survey materials and exported metadata for the clip-based user study used in *Toward Minimalist HUDs in Action Games: Longitudinal Trends and Player Perception*. The study was implemented in SoSci Survey and asked participants to watch six gameplay clips (approximately 90 seconds each) and rate how the presented interface would affect their experience. The questionnaire included consent, eligibility screening, gaming background items, per-clip familiarity and post-clip ratings, and final general-attitude questions about HUD preferences and prior HUD customization behavior.

## Folder contents

- `Galley-proof base (hudstudy2025) 09.03.2026, 13_35.pdf`  
  Galley-proof export of the full questionnaire as implemented in SoSci Survey. This file documents the survey flow, instructions, item wording, response scales, and page order logic.

- `variables_hudstudy2025_2026-02-28_14-09.csv`  
  Variable-level export from SoSci Survey. This file maps variable names to labels, item types, input types, and the corresponding survey questions.

- `values_hudstudy2025_2026-02-28_14-09.csv`  
  Value-label export from SoSci Survey. This file documents the coded response options for categorical variables.

- `codebook_hudstudy2025_2026-02-28_14-09.xlsx`  
  Spreadsheet codebook export from SoSci Survey combining variable metadata in a human-readable format.

## Study structure

The survey was designed as a remote within-subject clip-rating study. After consent and screening, participants completed a short background questionnaire covering age, gender, weekly gaming time, years of gaming experience, platforms, player type, and interest in action/action-adventure and role-playing games. The six gameplay clips were then shown in randomized order, followed by repeated post-clip question blocks. Each clip page first asked about game familiarity and then presented rating items on expected immersion, clarity/information sufficiency, perceived HUD minimalism, HUD reduction intention, and interface preference. The survey ended with two general HUD-preference items and three prior-HUD-configuration behavior items.

## Core constructs used in the paper

The per-clip questionnaire was designed around the following constructs:

- **Familiarity**: self-reported familiarity with the game shown in the clip.
- **Expected immersion (IMM)**: four items on absorption, tuning out real-world surroundings, presence, and focus.
- **Clarity / information sufficiency (CLAR)**: three items on situational clarity, sufficiency of interface information, and concern that important information is missing.
- **Perceived minimalism (MIN)**: three items on whether the interface looks clean and minimal, whether too much information is shown at once, and whether the game world is visually dominant over interface elements.
- **HUD reduction intention**: one item on whether the participant would try to hide or reduce on-screen interface elements.
- **Interface preference**: one item on whether the participant would like to play a game with an interface like the one shown.
- **General HUD preference / behavior**: end-of-survey items on preference for minimal HUDs, choosing minimal HUD settings, reducing or increasing HUD information, and using mods or tools to hide UI.
