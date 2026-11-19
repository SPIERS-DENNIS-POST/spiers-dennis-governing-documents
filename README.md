# Spiers–Dennis Post 24 — Governing Documents
**Status: private staging repository; historical transcriptions awaiting proofreading and formal verification.** This repository is intended for review by authorized collaborators. It has not been established as the Post’s official governing record solely by publication here.
## Constitution and Bylaws
- [Constitution](CONSTITUTION.md)
- [Bylaws](BYLAWS.md)
- [Original signed five-page scan](sources/2004-signed-constitution-and-bylaws.pdf)
- [View the five signed scan pages in GitHub](sources/scan-previews/README.md)
The Constitution and Bylaws are separate Markdown documents to enable line-by-line comparisons, commit statistics, and public amendment histories if the repository is eventually made public. They were transcribed from a scanned original and **have not been fully proofread**. The scan is the comparison source for transcription discrepancies. Neither the scan nor this repository proves there were no later amendments.
## Standard operating procedures (future)
The [SOP directory](sops/README.md) is reserved for future Post standard operating procedures. An SOP may explain implementation or ordinary operations; it does not amend, supersede, or override the Constitution, Bylaws, or governing rules of the Department or National American Legion. Each future SOP should state its approval authority, adoption or effective date, version, and applicable review procedure. No SOP has been adopted through this repository.
## Historical source and integrity
The Constitution occupies scan pages 1–2; the Bylaws occupy pages 3–5. Each signed document records amendments accepted January 22, 2002 and November 23, 2004. Signatures and handwritten dates are preserved in the scan, not replaced by digital attestations.
SHA-256 of current source PDF (structurally repaired; scan content unchanged): `2dcf36251d5437cee43acc9b2f3ebf523b200edbbeaca455a7eeadcf552f72ef`. Original uploaded scan SHA-256: `66b03738e55f2109ee5050d700c75ef1a586ff9ade9237b5f123c22ae7caa63f` (preserved in Git history).
## Guidance for amending

This repository keeps the original signed scan as historical evidence and uses Markdown for text that can be compared, reviewed, printed, and converted to other formats. A GitHub commit or pull request is **not** an act of the Post and does not itself amend a governing document. Only changes adopted under the applicable governing procedure may be presented as adopted amendments.

### First distinguish a transcription correction from an amendment

- **Transcription correction:** Makes Markdown accurately match the signed scan. Identify the document, scan page, clause, and exact mismatch in the issue or pull request; have the correction checked against the scan. A faithful correction is not a vote to change the underlying Constitution or Bylaws.
- **Substantive amendment:** Changes what a governing provision says or means. Even if it looks like a small wording edit, treat it as a proposed amendment whenever it changes the rule. Do not merge such a change into the adopted text until it has been properly approved.
- **SOP change:** Follow the procedure and authority applicable to that SOP. An SOP cannot override the Constitution, Bylaws, or higher governing rules.

The current Markdown is a **historical transcription awaiting full verification**. The 2004 scan does not establish that no later amendments exist. Before using a provision as the basis for an actual vote, confirm the currently applicable governing text and any relevant Department, National, or legal requirements.

### Propose an amendment with a pull request

1. Create a branch from `main` and open a pull request against `main`. The branch and pull request contain **proposed** language; `main` is not changed by opening them.
2. Identify the exact Constitution or Bylaws article and section; show the existing language, proposed language, reason for the change, and any related sections that must change together.
3. Make the proposed wording available for the Post's required notice and consideration. Record the proposal, relevant meeting dates, and review discussion in the pull request without publishing private member information.
4. **Leave the pull request unmerged while the proposal is pending.** A public repository makes public pull-request branches and diffs visible, but visibility is not adoption.

### Follow the Post's actual amendment procedure

The scanned 2004 Constitution, Article VIII, Section 2, and Bylaws, Article XII, Section 1, describe written proposals, reading at the preceding regular meeting, written notice to members at least ten days before the vote, and a two-thirds vote of members attending the regular meeting. The Bylaws text specifically describes notice postmarked and mailed to all members. These are **historical-source references, not a substitute for verifying which rules currently govern**. Check the authoritative documents and any superior requirements before proceeding; retain evidence of required notice, quorum, vote, and approvals.

### Record the result, then publish

- **If adopted:** Record the adopting meeting date, exact approved wording, vote outcome, effective date if different, and the identifying reference for the approved minutes or resolution in the pull request. Keep restricted minutes in their appropriate records location. If the approved wording differs from the proposal, update the pull request to match what was actually approved before merging.
- **Then merge:** Merge only the approved wording into `main`; produce the printable and other derived copies from that Markdown; identify the adopted edition with an appropriate Git tag or release and retain independent copies.
- **If not adopted:** Close the pull request without merging. Its discussion remains useful institutional history, but its text does not become an amendment.

Preserve the signed original, prior adopted versions, official meeting records, and backups. Git history provides a useful public diff and audit trail, **not** a replacement for proof of lawful adoption. Do not rewrite the original scan to match a later amendment.

## Repository privacy
**This repository must be created Private.** While Private, its issues, pull requests, commits, and diffs are not public. Before any later conversion to Public, review **all prior Git history and discussions** for information that should remain confidential. The publishing script refuses to upload to a repository reported by GitHub as public.
## Authenticity and retention
Git history supplies useful traceability, not definitive proof of legal adoption and not a tamper-proof archival system. Preserve the historical scan, signed records, adopted minutes, backups, and any records required by Colorado law and Legion rules. Formally adopted, applicable governing documents control—not the most recent draft commit.
