---
aip: 1
title: AIP Purpose and Guidelines
status: RFC
type: Meta
author: "@v-stickykeys"
created: 2021-05-14
---
## What is an AIP?
AIP stands for AOL Improvement Proposal. It's a concise specification for something new to be added to the Apes Online community.

## Rationale
AIPs are the primary mechanism for proposing new features, for collecting community input, and for documenting design decisions.

## Types
There are 4 types of AIP:
- **Hack** AIPs are for proposals related to software engineering (d-apps, smart contracts, bots, etc).
- **Play** AIPs are for proposals related to how we interact in the community (events, games, etc).
- **Earn** AIPs are for proposals related to how funds in the treasury are spent.
- **Meta** AIPs is for proposals related to how we do AIPs.

## Process

When opening a pull request to submit your AIP, use an abbreviated 3-word title in the filename, `aip-draft_title_abbrev.md`.

Statues:

- **Idea** - Pre-merge. Still brain-storming and open for discussion.
- **Draft** - Initial brain-storming is done. Your PR is ready to be checked by an editor for formatting.
- **RFC** - Request for comments. Editor gave the LGTM and merged it in. Proposal is refined, and now you need feedback.
- **Ready** - Discussion during RFC phase helped refine your final draft. Set the proposal to this status when it is ready to be voted on.
- **RIP** - If the community voted to reject the proposal.
- **LFG** - If the community voted to accept the proposal.
- **Achievement Unlocked** - When the proposal has been acted upon/implemented.

## Format
Required

1. Header
```
---
aip: <leave blank until assigned by an editor>
title: <AIP title>
author: <a list of the author's or authors' name(s) and/or username(s)>
discussions-to: <URL>
status: Idea
type: <Standards Track, Meta, or Informational>
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
---
```

2. Title. 44 characters or less.

3. Abstract. Simple, terse, concise, human-readablem, layman terms 200 word description.

4. Motivation. What problem does this solve? What benefit does it provide?

5. Proposal. Details go here.

6. Rationale. What motivated the design decisions. What considerations did you make? Explain the tradeoffs.

Optional

7. Reference Implementation. Proof of concept.

## History
This document was derived heavily from Ethereum's EIP01 written by Martin Becze and Hudson Jameson which in turn was derived heavily by Bitcoin's BIP-0001 written by Amir Taaki which in turn was derived from Python's PEP-0001.
