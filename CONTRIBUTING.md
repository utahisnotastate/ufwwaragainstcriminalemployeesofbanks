# How to Review

This project needs people who can prove it wrong. Experience in law, bank examination, forensic accounting, compliance, market structure or derivatives is especially useful. You don't need credentials to report an error, though.

## What to review

| Review type | Question to ask | Where to look |
| --- | --- | --- |
| Factual | Is this statement about a case, rule or market true? | [Documents](documents/) and [petition](petition/the-case-for-nobel-recognition.md) |
| Rating | Is this scheme rated correctly? | [Scheme tracker](review/scheme-tracker.md) |
| Legal | Does the conduct meet the elements of an actual offense? | Each scheme's "Future Verdict" |
| Formula | Are the units, logic and threshold sound? | Section 5 of each batch |
| Practical | Could an investigator actually get this data? | Section 5 of each batch |

The thresholds need the most scrutiny. None has been back-tested, so a test that flags ordinary firms or misses known cases is a useful finding.

## How to send a review

1. Find the scheme ID, such as `B07.2`, in the document or the tracker.
2. Open an issue using the right template:
    - [Factual correction](https://github.com/utahisnotastate/ufwwaragainstcriminalemployeesofbanks/issues/new?template=factual-correction.yml)
    - [Rating challenge](https://github.com/utahisnotastate/ufwwaragainstcriminalemployeesofbanks/issues/new?template=rating-challenge.yml)
    - [Formula or threshold problem](https://github.com/utahisnotastate/ufwwaragainstcriminalemployeesofbanks/issues/new?template=formula-problem.yml)
3. Quote the exact words you are challenging, and link your source.

If you are comfortable with Git, you can also open a pull request against the Markdown in `documents/`. Change one issue per pull request, and leave `archive/` and `documents/word/` alone. The Word copies are a snapshot of the October 31, 2026 edition.

## What counts as evidence

Use the strongest source you can find, in this order:

1. Statutes, regulations, court opinions and regulator orders
2. Official data, filings and regulator or central bank research
3. Peer-reviewed research
4. Reputable journalism, labeled as such

Please give the date of any source, because cases and rules change. A settlement without an admission is not a finding of guilt, and an indictment is only an allegation.

## How ratings change

A rating changes when a linked source supports the change:

- **To Documented:** a court, regulator or official record shows essentially this conduct.
- **To Plausible lead:** the mechanism is shown to be real, with a specific way it could break the law.
- **To Lawful or policy:** the practice is shown to be permitted, and no deception is involved.
- **To Unsupported:** the record contradicts the claim, or no record can be found after a real search.

## Ground rules

- **Name no suspects.** Discuss private individuals or firms only as they appear in public court or regulator records. Do not accuse anyone of an unproven crime.
- **Post nothing confidential.** That includes non-public bank data, client information, suspicious activity reports, and anything covered by a duty of confidentiality.
- **Protect yourself.** If you are a whistleblower, do not use a public issue. Use the official channels listed in the [README](README.md#if-you-know-about-a-real-crime) and consider speaking to a lawyer first.
- **Argue with evidence.** Be civil, and critique the claim rather than the person.

This repository is not legal advice, investment advice or a reporting channel for crimes.
