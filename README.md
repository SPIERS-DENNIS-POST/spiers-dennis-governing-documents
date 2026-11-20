# Spiers–Dennis Post 24 — Governing Documents

**Transcription status: complete and checked against the signed historical source. Governing status: a 2004 baseline pending incorporation of known later amendments.**

This repository maintains a public-facing, version-controlled record of the Constitution, Bylaws, and Standard Operating Procedures of Spiers–Dennis Post #24, The American Legion, Department of Colorado. At this checkpoint, the Constitution and Bylaws files reproduce the signed historical documents reflecting amendments accepted January 22, 2002, and November 23, 2004. Later Post amendments are known to exist, but their adopted wording and supporting records have not yet been assembled and incorporated here. Consequently, the current files must **not** be treated as a complete statement of all governing provisions presently in force.

## Constitution and Bylaws

- [Constitution](CONSTITUTION.txt)
- [Bylaws](BYLAWS.txt)
- [Signed five-page historical scan](sources/2004-signed-constitution-and-bylaws.pdf)
- [Five scan pages for viewing in GitHub](sources/scan-previews/README.md)

The Constitution and Bylaws are maintained as separate UTF-8 plain-text (`.txt`) files so their wording remains readable and reproducible without Markdown or HTML. The transcriptions were reviewed against all five scanned pages, including wording, capitalization, punctuation, numbering, and reproducible spacing. Differences required by plain-text layout, such as line wrapping and centering, are not intended to reproduce the scanned page design.

The transcriptions of the signed 2004 documents are complete. The historical scan controls if the transcription of that baseline differs from its source. Later adopted amendments, once documented, will change the evolving TXT files without altering the historical scan. This README describes stable repository practices and the fixed historical source; evidence, source citations, and explanations for each subsequent amendment or transcription correction belong in that change's pull request and supporting official records, not in a running README history. Editorial commentary is not inserted into the governing TXT files.

## Standard Operating Procedures

The [SOP directory](sops/README.md) is reserved for the Post Executive's operational standards. SOPs may use Markdown (`.md`); they are not subject to the Constitution and Bylaws' historical plain-text transcription format. The Executive may revise SOPs within its authority, following any applicable approval requirements. SOPs cannot conflict with the Post Constitution, Bylaws, or applicable Department, National, or other higher governing requirements. Each SOP should identify its responsible role, approving authority, effective date, and revision history. No SOP has yet been adopted through this repository.

## Historical source and integrity

The Constitution occupies scan pages 1–2; the Bylaws occupy pages 3–5. Each signed document records amendments accepted January 22, 2002, and November 23, 2004. The 2004 scan preserves handwritten signatures identified as those of Hank Bentley (then Post Commander) and Philip Morton (then Post Adjutant), based on an identification reported by Post Adjutant Jimmy Davidson. The baseline TXT identifies these historical signers by name; typed names are not new signatures, new approval, or a certification of adoption. This is a permanent note about the 2004 scan, not a requirement that its signers or dates appear in future amended editions. Minor differences in handwritten date punctuation between the two historical documents are preserved in the baseline transcription rather than normalized.

SHA-256 of current source PDF (structurally repaired; scan content unchanged): `2dcf36251d5437cee43acc9b2f3ebf523b200edbbeaca455a7eeadcf552f72ef`. Original uploaded scan SHA-256: `66b03738e55f2109ee5050d700c75ef1a586ff9ade9237b5f123c22ae7caa63f` (preserved in Git history).

## Amendments and transcription corrections

**Amendments are made by the Post, not by GitHub.** Members introduce motions and the Post considers and votes on them under the applicable Constitution, Bylaws, Robert's Rules of Order, and higher governing requirements. Participation in Post governance does not require GitHub.

Changes to `CONSTITUTION.txt` and `BYLAWS.txt` going forward are to be proposed through pull requests. A pull request should distinguish:

- **Transcription correction:** Corrects a mismatch between the TXT wording and the historical source or adopted amendment record it is intended to reproduce. Identify the source document, relevant page or section, and exact discrepancy. Correcting transcription does not itself amend the underlying governing document.
- **Adopted amendment:** Incorporates wording actually approved through the applicable Post procedure. Cite the motion, official minutes or resolution, adopting meeting date, effective date where applicable, and exact adopted wording. Keep restricted personal information out of public pull-request discussions.
- **Pending proposal:** May be discussed or drafted in a pull request, but remains unmerged until the Post has adopted the change under the applicable procedure. Opening a pull request does not put a motion before the Post or approve it.

The maintainer reviews the source evidence and confirms that the proposed TXT change reproduces the actual correction or adopted amendment before merging into `main`. The pull-request diff and Git history preserve the change and its context. Earlier text remains available in the repository history. Significant checkpoints may be identified with Git tags or releases.

Because later amendments are already known to exist but not yet fully documented here, incorporating an amendment does not by itself establish that `main` contains every provision currently in force. The governing-status notice must remain clear until the amendment record has been reconciled.

SOP changes follow the approval authority applicable to each SOP; merely storing an SOP here does not subject it to the Constitution or Bylaws amendment procedure.

## Public record and retention

This repository is intended to make the Post's document history, including earlier transcription drafts, changes, and review discussions, observable. The `main` branch is the repository's published checkpoint; previous commits show how that checkpoint was developed, not separate acts of adoption. A GitHub commit, pull request, or merge is a record-keeping event, not an official Post vote.

Git history provides traceability, not definitive proof of adoption and not a tamper-proof archival system. Preserve signed source documents, adopted minutes, resolutions, backups, and records required by applicable law and Legion rules. Formally adopted, applicable governing documents control; repository publication alone does not establish which provisions are currently effective.
