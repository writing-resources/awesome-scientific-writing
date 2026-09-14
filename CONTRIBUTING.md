# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this
project you agree to abide by its terms.

---

## We welcome

- **Additions**: restricted to addition of one new entry per pull-request.
- **Removals**: restricted to removal of one obsolete entry per pull-request.
- **Edits**: you may correct the descriptions if it can be improved.

## Criteria for accepting a pull-request

*Contributors, make sure that*:

- a **short pitch** is included in the pull-request description,
- if the entry is a software:
  - the entry is **open-source** with appropriate **license**,
  - it should be **maintained** (at least a commit / a release in the past 3 years),
  - it should have a **cool-down period** of at least 1 month of non-trivial
    version control history (from first commit to last commit),
- the table of contents has been updated (if a section is added / removed).
- the contents are sorted **alphabetically**,

Thank you for your suggestions!

*Maintainers, make sure that*:

- the above criteria are followed,
- the tests pass on the CI,
- in case of addition or removal, make an assessment of
  awesomeness of the entry.

## Updating your PR

If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one.

## AI/LLM Usage Policy

This is a curated list that values human expertise and judgment. We distinguish
between two scenarios:

### 1. Use of LLMs to generate the PR itself
- AI can assist with drafting the PR description, formatting, or other metadata
- If AI/LLM tools were used, you must disclose the specific tools in the PR description (e.g., "Assisted-by: GitHub Copilot")
- Human contributors must verify and take responsibility for all content

### 2. Use of LLMs to generate code of the tool being listed
- AI assistance in the tool's development is acceptable only if the tool demonstrates sustained value
- Purely AI-generated tools without human judgment, usage, or maintenance will be rejected

## Explanation for the Maintained and Cool-down Period criteria
- For new entries: The tool must have at least 1 month of non-trivial version control history from first commit to last commit
- For the entry itself: At least one release or significant update in the past 3 years, with evidence of active community or usage
- Exception: Widely adopted tools with clear research impact may be considered even with shorter history, at maintainer discretion

## Appendix: running lint tests

To run tests locally:

    # using ruby
    gem install awesome_bot
    awesome_bot README.md
    # using node.js
    npm install -g awesome-lint
    awesome-lint README.md

