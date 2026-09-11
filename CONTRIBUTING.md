# Contributing to Selah commentary renderings

Thank you for helping preserve and clarify these classical voices. The task is
to correct Selah's rendering faithfully, not to modernize, harmonize, or repair
the commentator without saying so.

## Choose an issue or a pull request

- Open an **issue** when the Hebrew source, intended sense, or English wording
  needs discussion.
- Open a **pull request** when the exact correction is clear.
- Send application bugs and private security, account, or personal-data matters
  through [Selah support](https://selahproject.com/support).

## What to include

Identify the commentator, book, chapter, verse, current wording, proposed
wording, and reason. Quote only the source text needed to establish the
correction, and name the edition or source consulted when possible.

## Editing a record

Rendered comments live at
`<voice>/en-selah/<book>/<chapter>/<verse>.edn`.

- Edit only the affected string in `:comments` or a clearly related textual
  note.
- Preserve `:voice`, `:lang`, reference coordinates, Hebrew quotations,
  source-witness fields, and provenance metadata unless the issue specifically
  concerns them.
- Preserve HTML used for source headings and emphasis.
- Do not silently alter a difficult, offensive, archaic, or theologically
  unfamiliar statement merely to make it agree with a modern reader.
- If the source itself appears corrupt or mistaken, open an issue and preserve
  the distinction between source, translation, and editorial note.
- Keep unrelated commentators and corrections in separate pull requests where
  practical.

Where a `chalkboard/` record exists, preserve its Hebrew quotation exactly
unless the source witness establishes a transcription error.

## AI-assisted work

Disclose material use of a language model or automated translation tool and
describe the human review. Do not submit unreviewed bulk-generated commentary.

## License and attribution

Contribute only material you have the right to submit. By submitting, you agree
that accepted material will be distributed under this repository's
[CC BY-SA 4.0 license](LICENSE.md). Git history preserves the correction record
and contributor attribution.

## Review

Maintainers compare proposals with the Hebrew source, the named commentator's
voice, repository conventions, and supplied evidence. A correction may be
accepted, revised, held for further evidence, or declined with an explanation.
Please be patient, precise, and respectful of both contributors and the
traditions represented here.

## Conduct

Be honest, be kind, show your evidence. Distinguish certainty from
suggestion. The maintainers weigh and decide.
