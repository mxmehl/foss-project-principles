# Checklist for FOSS projects

Things to check when considering whether a FOSS project is managed in a healthy, good, sustainable, promising, fair, collaborative, open... way.

Very unsorted, based on various interpretations.

## Good

### Copyright distributed

- Copyright belongs to multiple entities, ideally many individual developers or organisations.
- Includes that there is no CLA
- Exception: Open Source Foundation that guarantees that code will remain Open Source (like Apache or FSF/GNU)

### Transparent governance processes

- The project documents
  - how decisions are made
  - who makes these decisions
  - and why these people have the power to make the decisions (e.g. by merit, elections, financiel investment, founder/tradition)

### Transparent roadmap

- It's documented or openly discussed how priorities for the next project releases are set
- It's transparent who's involved in these decisions

### Transparent maintainership

- Related to "transparent governance processes"
- It's documented who is considered to be maintainer
- Implementation: MAINTAINER.md or CODEOWNERS.md

### Documented contribution guidelines

- It's transparent how someone is expected to contribute: important documentation, setting up dev environment, making good issues and PRs, coding/formatting standards and other requirements
- Goal: make good contributions, and experience a friendly workflow without negative feedback regarding formalities that could have been avoided
- Implementation: CONTRIBUTING.md

### Contributor diversity

- There are multiple active contributors to the project
- Contributors come from more than one legal entity

### Documented (additional) discussion channels

- If there is more than the source code repository and hosting source forge to communicate within the project, this should be documented
- Especially if these channels are open to the public. Rationale: new contributors shall be enabled to listen/read first

## Bad

### CLA

"most vendors require that any potential contributor to the open-source software sign over the rights to their contribution to the vendor. The required type of contract is called a contributor license agreement (CLA). CLAs are used by an organization to centralize all needed rights to the software, for example to represent it in court. They were originally invented by the open source foundations, but like many legal tools are now used by vendors as well.

Not surprisingly, the practice of acquiring copyright to tightly control it is disenchanting to developers. Vendors typically don’t receive many contributions and therefore develop most if not all of their code themselves. They don’t do so in the open but keep their road-maps secret to hinder competition. In contrast to open source projects run under an open source foundation, the governance of projects run by a vendor is typically closed, not open."

Source: https://dirkriehle.com/publications/2023-selected/the-future-of-the-open-source-definition/


### Licenses not approved by OSI/FSF, or considered open source equivalent

Anything under a license not approved by OSI or FSF, or truly equivalent to those (e.g. Creative Commons without NC/ND clause).

This checklist does not go deeper in this rabbit hole as it extends the Open Source/Free Software principles.


### Does not accept outside contributions

- A project may decide to not accept contributions by anyone, or just a pre-defined group (e.g. employees)


### Un-maintained / no stable release

- The project hasn't seen activity since (?) 3 months, 1 year...
- There hasn't been a release since X months, but commits in a dev branch or so

## Unclear

### Trademarks

Who owns the trademarks? Are they held by a vendor-neutral organisation?

Is there an open trademark policy? Can users use the project's branding without large constraints?

Same goes for **domains**.


### Funding

If funds are raised (e.g. sponsorships, donations, paid projects), who owns them? An individual, a foundation, an organisation?


### Security best-practices

- Automated dependency updates, regular check for vulnerabilities
- SECURITY.md or other documented ways to report security flaws in the project

### Coding best practices

- Version Control System (not just tar dumps)
- CI
- Tests
- Documentation (usage, installation, examples, APIs etc)

### Licensing best practices

- Licensing and copyright very transpatent, e.g. REUSE compliance

### Code of Conduct

- There is a Code of Conduct, codifying social standards along the lines of "be kind to each other"


## Sources/tools

- https://github.com/opengovernance/opengovernance.dev
- https://dirkriehle.com/publications/2023-selected/the-future-of-the-open-source-definition/
- https://github.com/dbsystel/oss-red-flag-checker/
- https://github.com/todogroup/repolinter
