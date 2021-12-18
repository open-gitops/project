# Governance

This document defines the governance process for the GitOps Working Group and community and OpenGitOps project.

## Roles

### All Members

This is an open public working group welcoming anyone who would like to join and help.
There are no special requirements for membership apart from the responsibilities listed  below.
Members are not required to have any explicit roles or additional responsibilities, but they may also have formally assigned roles (see below).
See the Working Group [README](README.md) for information about volunteering for committees and projects.
Note that voting requires additional conditions (see [Elections](#elections)).

Responsibilities:

- Must follow the [Code of Conduct](https://github.com/open-gitops/.github/blob/main/CODE_OF_CONDUCT.md)
- May not create the impression that they have any authority or formal responsibilities within the GitOps WG other than their explicitly assigned roles

### Committees

Working Group [Members](#all-members) may volunteer to join WG Committees and help with specific projects according to their interest and ability.
Responsibilities vary per committee, but in general please remember everyone is a volunteer.
Committees follow processes to allow for progress so long as they maintain inclusiveness, transparency, and respect for all involved.

Current WG committees:

- Principles Committee
  - Responsible for drafting the revised [GitOps Principles](https://github.com/open-gitops/documents)
- Events Committee
  - Responsible for organizing events such as GitOpsCon, and supporting other events in the wider GitOps community (see [OpenGitOps events](https://opengitops.dev/events))
- Communications Committee
  - Reponsible for coordinating public communications on behalf of the working group

### Maintainers

Working Group and OpenGitOps project Maintainers are [Members](#all-members) who have shown significant and sustained contributions in the GitOps WG.
The initial set of Maintainers were drawn from the organizations that proposed the creation of the working group.
Current Maintainers are listed in a [MAINTAINERS](./MAINTAINERS) file at the root of this git repository.

Responsibilities:

- Enable and promote GitOps Working Group community values
- Engage with the wider GitOps community through appropriate [communication channels](https://github.com/cncf/tag-app-delivery/blob/main/gitops-wg/README.md#community)
- Maintain involvement and open collaboration with working group members and committees
- Review and approve pull requests
- Ask for help when unsure and step down considerately when appropriate

The GitHub `@gitops-working-group/maintainers` team will be kept up to date with current maintainers.

### Chairs

The GitOps WG and OpenGitOps project will be co-chaired by 3 [Maintainers](#maintainers).
A maximum of one person from any one entity may hold a chair role at any given moment in order to avoid undue influence, and maintain balanced representation.
Current chairs are listed in a [CHAIRS.md](https://github.com/cncf/tag-app-delivery/blob/main/gitops-wg/CHAIRS.md) file in the GitOps Working Group directory of the CNCF App Delivery TAG git repository.

Responsibilities:

- Primary role of Chairs is governance of the Working Group, who collectively care for the OpenGitOps project
- Ensure the promotion of continued open involvement for the working group
- Ensure that meetings and other activities are conducted and progress continues to be made against the project agenda, while also engaging other group members in leadership roles
- Ensure discussion is extended asynchronously to be inclusive of members who cannot attend a specific meeting time
- Schedule discussion of proposals that have been submitted
- Partner with Maintainers and other WG members to establish a roadmap and manage ongoing projects
- Ask for new proposals to be made to address an identified needs
- Have GitOps domain knowledge
- Engage deeply in the work being done by the working group - that is, the role is not purely administrative.
  Chairs are, however not responsible for performing all of the work - this is shared across the working group members and expected from those who have volunteered onto various workstreams.
- When necessary, handle human and technical coordination across different working group workstreams
- Handle Code of Conduct violations
- Resolve escalated decisions when Maintainers can not reach consensus

Ultimately the chairs - after consulting with the collective of Maintainers and their community - drive the direction, values and governance of the overall project.

The GitHub `@gitops-working-group/chairs` team will be kept up to date with current chairs.

## Elections

[Chairs](#chairs) will be elected for one year terms and may run for reelection.

The election process takes place on the CNCF SIG App Delivery mailing list <cncf-sig-app-delivery@lists.cncf.io>.

Before each election, there will be a call for nominations on the mailing list.
Nominations should be sent to the mailing list, and include a brief bio and personal statement describing the candidate's qualifications to serve in this capacity.
Self-nominations are welcome. Only existing maintainers are eligible for nomination.

The GitOps WG employs "organization voting" to ensure no single organization can dominate the election process or project.
Up to two individuals from organizations who are both active members of the CNCF and listed in the [interested parties](https://github.com/cncf/tag-app-delivery/blob/main/gitops-wg/interested-parties.md) may vote.
Interested parties must be added at least one week before any election to have a vote.
Chairs will be elected using Ranked Choice Voting.

Election results will be announced on the mailing list, and current chairs listed in this document will be updated accordingly.

### Special Elections

There are several cases where positions are put up for unscheduled, special elections.

- Stepping down: If an elected chair steps down (or, in rare cases, is removed), a special election will be necessary to fill vacancies
- Change of affiliation: When affiliations of current chairs change – through job changes, mergers, etc. – and entity becomes overrepresented for a specific role, members of that entity will first be asked if they wish to resign their roles in order to remain within the allotment.
  If insufficient members resign their roles, the positions held by members associated with that entity will all be put up for a special election

In these cases, positions will be open both to previous holders and to any new nominees.
The standard nomination and [election](#elections) process will be carried out.
Representatives elected though this process will serve the remaining part of the current term.

## Decision Making

### Decision Guidelines

- The GitOps Working Group believes that the best decisions are reached through Consensus <https://en.wikipedia.org/wiki/Consensus_decision-making>.
  This applies to all working communication by WG members (see [GitOps WG community info](https://github.com/cncf/tag-app-delivery/blob/main/gitops-wg/README.md#community)).
- Most decisions begin by seeking Lazy Consensus <https://communitymgt.wikia.com/wiki/Lazy_consensus>.
- If an objection is raised through the Lazy Consensus process, the group works together to seek an agreeable solution.
- If Consensus can not be reached, but a decision must be made, the next step is try to attempt to agree that a vote should be called.
  This is important, as it gives dissenting views a chance to request more information or raise further points.
- If Maintainers can't agree on calling a vote, they may escalate to the Chairs.
  This should only be done at this stage if:
  1. An important deadline is threatened by continuing the Consensus process; or
  2. A Decider feels there is unreasonable blocking of both reaching Consensus and agreeing to a vote.
      This should be rare, due to the social cost of discontinuing the Consensus process for this reason.
      Most decisions should wait for the above process to take its course.
- If maintainers agree to a vote, the default is a Simple Majority.
- However, there are cases that require stronger voting – Supermajority or Unanimity – specified below:

### Simple Majority Decisions

If a vote is called, the default is a Simple Majority Vote <https://en.wikipedia.org/wiki/Majority>.

### Supermajority Decisions

If a vote is called, the following decisions require a Supermajority Vote <https://en.wikipedia.org/wiki/Supermajority>.

- Maintainers: Adding additional maintainers.
- Chairs: Enforcing a Code of Conduct violation by a community member.
- Chairs: Licensing and intellectual property changes.
- Chairs: Material changes to the Governance document.
  - Note: editorial changes to governance may be made by lazy consensus, unless challenged.
    These are changes which fix spelling or grammar, update work affiliation or similar, update style or reflect an outside and obvious reality.
    They do not change the intention or meaning of anything in this document.
