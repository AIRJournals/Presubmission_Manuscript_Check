# AIR Journals Submission Skill

An agent skill that takes a finished manuscript to a prepared submission at [AIR Journals](https://airjournals.org), with fees, waivers, and the review model stated upfront.

## Install

```bash
npx skills add AIRJournals/Presubmission_Manuscript_Check
```

## What it does

- Matches a manuscript to one of AIR Journals' six journals (engineering and technology, natural sciences, life sciences and medicine, social sciences and humanities, mathematics and computational sciences, interdisciplinary research)
- Quotes the exact fees: $10 first-submission fee, $140 only if accepted, plus the country waiver through 31 December 2026
- Runs the submission preflight: DOCX, official template, formatting, references, ORCID
- Self-scores the draft against the public 5-category rubric printed in every published evaluation report (citation integrity, plagiarism screen, quality score out of 100), so the author can enhance the weak categories before submitting
- Explains the review model: evaluation plus scholarly supervision, a full evaluation report with every paper, Crossref DOI, CC BY, decisions usually within days
- States the honest limit: no acceptance guarantee

## The submission door

Submissions happen at https://airjournals.org/submit-form.html — the form is where a manuscript lands and where its article ID is assigned. This skill never bypasses or replaces it; it prepares the paper and hands over the link.

## Privacy

This skill collects nothing. No author name, manuscript detail, or submission event is reported to any party. The manuscript goes from the author to the submission form and nowhere else.

## License

MIT
