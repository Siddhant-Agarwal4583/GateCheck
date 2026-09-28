# GateCheck FSE 2027 annotation integration report

## Status

The anonymous manuscript, Overleaf source, and supplementary artifact now incorporate the two returned review files without claiming evidence they do not contain. The manuscript compiles in the required anonymous ACM review format and is 15 pages including references and the reproducibility appendix.

## Results incorporated

- Frozen screening pool: 35 public changes from seven projects.
- Reviewer agreement on defect status: 32/35 (91.4%; nominal Krippendorff alpha 0.363).
- Reviewer agreement on primary contract: 30/35 (85.7%; alpha 0.829).
- Reviewer agreement on corpus inclusion: 31/35 (88.6%; alpha 0.739).
- Reviewer agreement on relation-support strength: 19/35 (54.3%; alpha 0.341).
- Conservative unanimous set: nine candidates from five projects.
- All five already executed public-patch replays are in the unanimous set.
- Four additional unanimous candidates were not executed and are not reported as GateCheck detections.
- Four inclusion disagreements remain unresolved and are published in the artifact.

## Claim boundary

The returned sheets derive from a common machine-assisted preliminary coding draft. The paper therefore calls the exercise “retrospective reviewer verification,” not blinded independent annotation. The AI system is not counted as an annotator. This disclosure is present in Methods, threats to validity, ethics, and the artifact protocol.

Both original workbooks omit all per-case review-minute values, although they contain total-time fields. Their built-in completeness formulas therefore remain incomplete. Timing is not used as a study outcome, and the omission is disclosed in the artifact protocol. The original workbooks are not placed in the anonymous artifact because their document metadata identifies the author; de-identified CSV exports and reproducible analysis code are included instead.

## Submission condition

Use the annotation-enhanced paper only if both external engineers actually checked all 35 cases against the public evidence and their recorded consent/independence attestations are true. Keep their consent records and the name-to-code mapping privately. If either person did not conduct that review, remove the reviewer-audit claims before submission.

The annotation audit improves the evidence-selection story, but it does not remove the paper's main limitations: only five public defects have executable replays, none of the four newly unanimous candidates has a Phase 2 reproduction, no direct common-subset comparison with another testing tool is reported, and there is no practitioner study. These limitations are stated explicitly; acceptance cannot be guaranteed.

## Verification completed

- LaTeX compilation completed without undefined references, missing citations, or overfull boxes.
- The 15 rendered pages were visually inspected; the running title was shortened to prevent header overlap.
- Annotation calculations were rerun from de-identified CSV files and checked against expected counts.
- Archive integrity tests and SHA-256 verification passed.
- Anonymous archives contain no author name, private metadata file, Python bytecode, or original review workbook.
