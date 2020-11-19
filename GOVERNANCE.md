<!-- see https://github.com/yzhang-gh/vscode-markdown/blob/master/README.md#table-of-contents -->
<!-- omit in toc -->
# Flux Governance

This document <https://github.com/fluxcd/community/blob/main/GOVERNANCE.md> defines the governance process for the Flux project and community.

- [Values](#values)
  - [Code of Conduct](#code-of-conduct)
- [Roles in the Flux Community](#roles-in-the-flux-community)
  - [Users](#users)
  - [Contributors](#contributors)
  - [Maintainers](#maintainers)
  - [Oversight Committee](#oversight-committee)
- [Decision Making](#decision-making)
  - [Deciders](#deciders)
  - [Decision Guidelines](#decision-guidelines)
  - [Simple Majority Decisions](#simple-majority-decisions)
  - [Supermajority Decisions](#supermajority-decisions)
  - [Unanimity Decisions](#unanimity-decisions)
- [Proposal Process](#proposal-process)
- [Licenses and Copyright](#licenses-and-copyright)

## Values

- **Open:**
The Flux community strives to be open, accessible and welcoming to everyone.
Anyone may contribute, and contributions are available to all users according to open source values and licenses.
- **Transparent:**
Flux strives for transparency in all discussions, announcements, disclosures and decision making.
- **Unbiased:**
Flux strives to operate independently of specific partisan interests, and for decision making to fairly balance the wider community interests of its end users and contributors.

### Code of Conduct

The Flux community adheres to the CNCF Code of Conduct <https://github.com/cncf/foundation/blob/master/code-of-conduct.md>.

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting a _Flux_ Oversight Committee member.

If no conclusion can be reached in meditation, such issues can be escalated to the CNCF mediator, Mishi Choudhary <mishi@linux.com>, in which case CNCF may choose to intervene.

## Roles in the Flux Community

The Flux community comprises the following roles:

### Users

Flux end users are the most important aspect of the community, without whom the project would have no purpose. Users are anyone who has a need for the project.
Apart from following the Code of Conduct, there are no special requirements.

### Contributors

Flux welcomes all kinds of contributions, including code, issues, documentation, external tools, advocacy and community work.
As a contributor we want to invite you to join the discussions in a variety of forums laid out in <https://github.com/fluxcd/community>.

### Maintainers

Maintainers are elected Contributors who showed significant and sustained contributions in a git repository.
Current Maintainers are listed in a `MAINTAINERS` file at the root of the git repository.

Maintainers are expected to:

- Enable and promote Flux community values
- Engage with end Users through appropriate communication channels
- Serve as a point of conflict resolution between Contributors to their git repository
- Maintain open collaboration with Contributors and other Maintainers
- Ask for help when unsure and step down considerately

Maintainers will be invited to the `@fluxcd/maintainers` <https://github.com/orgs/fluxcd/teams/maintainers> team, and are members of this team for as long as they are involved with the project.

### Oversight Committee

This committee is responsible for the overall project, and anything not easily managed by the Maintainers of each git repository. Including:

- Overseeing the project health and growth
- Maintaining the brand, mission, vision, values, and scope of the overall project
- Changes to licensing and intellectual property
- Administering access to all project assets
- Administering git repositories as needed
- Handling Code of Conduct violations
- Managing financial decisions
- Defining the scope of each git repository
- Resolving escalated decisions when Maintainers responsible are blocked

Ultimately the committee - after consulting with the collective of Maintainers and their community - drive the direction, values and governance of the overall project.

This committee will initially be comprised of Flux Maintainers who have steered the project prior to this initial Governance document.
The aspiration is no one company or organization should have oversight of the overall project, however that is not yet realistic at this stage. The goal is to broaden maintainership to include a wider range of organizations during CNCF incubation.

Oversight Committee members are publicly listed in the `@fluxcd/oversight-committee` <https://github.com/orgs/fluxcd/teams/oversight-committee> GitHub team.

## Decision Making

### Deciders

- Repository Maintainers: Decisions that affect only one git repository.
- Oversight Committee: Decisions that are outside the scope of a single git repository.

### Decision Guidelines

- Decisions that warrant wider input should be made public by using the below guidelines in combination with the Proposal Process below.
- Whether or not wider input is required, the Flux community believes that the best decisions are reached through Consensus <https://en.wikipedia.org/wiki/Consensus_decision-making>.
- Most decisions start by seeking Lazy Consensus <https://communitymgt.wikia.com/wiki/Lazy_consensus>.
- If an objection is raised through the Lazy Consensus process, Deciders work together to seek an agreeable solution.
- If Consensus can not be reached, but a decision must be made, the next step is try to attempt to agree that a vote should be called.
  This is important, as it gives dissenting views a chance to request more information or raise further points.
  If Deciders are the Oversight Committee, part of that responsibility is the final point of escalation, so agreeing to a vote is assumed if timeline doesn't allow the consensus process to continue.
- If Deciders are Repository Maintainers, and they can't agree on calling a vote, they may escalate to the Oversight Committee.
  This should only be done at this stage if:
  1. An unmovable deadline is threatened by continuing the Consensus process; or
  2. A Decider feels there is unreasonable blocking of both reaching Consensus and agreeing to a vote.
      This should be rare, due to the social cost of discontinuing the Consensus process for this reason.
      Most decisions should wait for the above process to take its course.
- If Deciders agree to a vote, the default is a Simple Majority.
- However, there are cases that require stronger voting – Supermajority or Unanimity – specified below:

### Simple Majority Decisions

If a vote is called, the default is a Simple Majority Vote <https://en.wikipedia.org/wiki/Majority>.

### Supermajority Decisions

If a vote is called, the following decisions require a Supermajority Vote <https://en.wikipedia.org/wiki/Supermajority>.

- Oversight Committee: Enforcing a Code of Conduct violation by a community member.
- Oversight Committee: Licensing and intellectual property changes.
- Oversight Committee: Material changes to the Governance document.
  - Note: editorial changes to governance may be made by lazy consensus, unless challenged.
    These are changes which fix spelling or grammar, update work affiliation or similar, update style or reflect an outside and obvious reality.
    They do not change the intention or meaning of anything in this document.

### Unanimity Decisions

If a vote is called, the following decisison require Unanimity <https://en.wikipedia.org/wiki/Unanimity>.

- Repository Maintainers: Electing new Maintainers of the same repository.
- Oversight Committee: Electing new Committee members.
- Oversight Committee: Removing a Repository Maintainer or Committee member for any reason other than inactivity.

## Proposal Process

- Code changes should go through the pull request process, where the idea and implementation details can be publicly discussed with Maintainers, other contributors, and end users.
  Pull requests should only be merged after receiving GitHub approval from at least one Maintainer who is not the pull request author.
  Note that Flux v2 uses GitHub discussions for proposals in the `fluxcd/toolkit` git repository <https://github.com/fluxcd/toolkit/discussions?discussions_q=category%3AProposals>.
- Non-code changes should be proposed as GitHub issues.
  If unclear which git repository to create the issue in, default to the community repository <https://github.com/fluxcd/community>.
- All proposals should be discussed publicly in an appropriate GitHub issue or pull request.
- If a Maintainer of an affected git repository feels feedback from specific people is warranted they will @mention those users or teams to request feedback.
- Proposals may also be added to the Flux Dev weekly meetings agenda, as a good avenue for making progress on a decision <https://lists.cncf.io/g/cncf-flux-dev/calendar>.

## Licenses and Copyright

- Apache 2.0 is required for all git repositories.
- Developer Certificate of Origin (DCO) commit signoff is required for all new code contributions.

Links to relevant CNCF documentation:

- <https://github.com/cncf/foundation/blob/master/charter.md#11-ip-policy>
- <https://github.com/cncf/foundation/blob/master/allowed-third-party-license-policy.md#approved-licenses-for-allowlist>
- <https://github.com/cncf/foundation/blob/master/copyright-notices.md#copyright-notices>
