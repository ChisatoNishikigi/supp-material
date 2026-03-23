# Prompt Files

This directory contains the complete prompt files associated with the structured prompting pipeline described in the submission.

The files are organized by stage:

- style-aware analysis,
- within-window analysis,
- cross-window reasoning, and
- final decision.

These files are provided as supplementary materials for reference and are intended to complement the prompt descriptions included in the paper appendix.

## File List

- `style_glossary_prompt.txt`: prompt for coarse style classification
- `style_cue_glossary.md`: style-specific cue glossary used to guide subsequent analysis
- `within_w1_prompt.txt`: first-stage within-window irregularity discovery prompt
- `within_w2_prompt.txt`: second-stage within-window evidence collection prompt
- `within_w3_prompt.txt`: third-stage within-window evidence verification prompt
- `cross_c1_prompt.txt`: first-stage cross-window predictive continuity prompt
- `cross_c2_prompt.txt`: second-stage cross-window evidence collection prompt
- `cross_c3_prompt.txt`: third-stage cross-window evidence verification prompt
- `final_decision_prompt.txt`: final decision prompt based on structured within/cross summaries

## Note

These files are provided as prompt templates with placeholders where applicable. They are intended to document the prompting structure used in the supplementary pipeline, rather than to serve as a full inference code release.
