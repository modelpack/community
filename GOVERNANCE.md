# Project Governance

The ModelPack project is dedicated to creating a universal, vendor-neutral standard for packaging, versioning, and running AI/ML projects that aligns with the OCI specification. The ModelPack project is especially important for organizations who are self-hosting models (open source, or self-built) and want to be able to use the tools and processes they've proven with containers, to manage their AI/ML project lifecycle.

This governance document explains how the project is run.

- [Values](#values)
- [Maintainers](#maintainers)
- [Becoming a Maintainer](#becoming-a-maintainer)
- [Meetings](#meetings)
- [Code of Conduct](#code-of-conduct)
- [Modifications](#modifying-this-charter)

## Values

The ModelPack project leadership embraces the following values:

- **Openness**: Communication and decision-making happens in the open and is discoverable for future reference. As much as possible, all discussions and work take place in public forums and open repositories.

- **Fairness**: All stakeholders have the opportunity to provide feedback and submit contributions, which will be considered on their merits.

- **Community over Product or Company**: Sustaining and growing our community takes priority over shipping code or sponsors' organizational goals. Each contributor participates in the project as an individual.

- **Inclusivity**: We innovate through different perspectives and skill sets, which can only be accomplished in a welcoming and respectful environment.

- **Participation**: Responsibilities within the project are earned through participation, and there is a clear path up the contributor ladder into leadership positions.

## Membership and Contributor Ladders

The ModelPack project is a community-driven open source project. We welcome contributions from anyone who shares our values and wants to help us achieve our mission. Below we lay out the different contributor roles in the ModelPack project, detailing the responsibilities, qualifications, and perks that come with each one.

| Role            | Responsibilities                                                       | Qualifications                                                               | Privileges                                                               |
| --------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **Contributor** | Follow our Code of Conduct & Contribution Guide                        | Anyone who participates in the community                                     | Can be assigned issues and request reviews                               |
| **Reviewer**    | Review PRs in your area of expertise and maintain quality              | A Contributor with a solid track record of high-quality reviews              | Approve PRs in specific areas and recommend others for Reviewer status   |
| **Maintainer**  | Merge PRs, coordinate releases, and help shape the project's direction | Long-term contributions, leadership, and a deep understanding of the project | Merge code, represent the project publicly, and nominate new Maintainers |

### Contributor

A **Contributor** is anyone who adds value to the project. This can be through code, but it doesn't have to be! This role is often where new or occasional contributors start.

- **Responsibilities**:

  - Follow the project's [Code of Conduct](code-of-conduct.md).
  - Stick to the [Contribution Guide](CONTRIBUTING.md).

- **Qualifications**:

  - Open to anyone who wants to be part of the community.
  - Contributions can include things like:
    - Joining in on community discussions.
    - Reporting bugs or giving feedback.
    - Testing new releases and sharing your thoughts.
    - Helping out with documentation.
    - Attending or speaking at community events.
    - Submitting pull requests (PRs).
    - Helping other users or answering questions.
    - Spreading the word about the project.

- **Privileges**:
  - You can be assigned to issues and ask for reviews on your contributions.

### Reviewer

A **Reviewer** is a Contributor who takes ownership of a specific part of the project (like code, docs, or tests). They play a key role in keeping our quality high by reviewing and approving changes in their area.

- **Responsibilities**:

  - Regularly review PRs in your area of expertise.
  - Make sure changes meet our coding standards, don't introduce bugs, and are good for the project.
  - Help other contributors become Reviewers.
  - Help triage issues.

- **Qualifications**:

  - You must already be a Contributor.
  - Proven track record of high-quality reviews and contributions.
  - Deep understanding of your specific area.
  - Commitment to maintaining responsibility for your designated area.
  - Supportive of new and occasional contributors, helping refine PRs for merging.

- **Privileges**:

  - You'll have GitHub permissions to approve PRs and manage labels in your specific areas.
  - You can recommend and review other Contributors for the Reviewer role.

- **How to Become a Reviewer**:

  1. Submit an issue to the community repository to request for becoming a reviewer, with a list of your contribution and specific area of expertise.
  2. Get approval from at least two existing Maintainers.

## Maintainers

Maintainers have write access to the project repositories in [the ModelPack GitHub organization](https://github.com/modelpack/). They can merge patches and are expected to review large or critical patches personally. The current maintainers can be found in [MAINTAINERS.md](./MAINTAINERS.md). Maintainers collectively manage the project's resources and contributors. Additional supplementary repositories can include a separate list of maintainers (such as for tools etc) which are not part of the primary ModelPack project maintainers.

This privilege is granted with some expectation of responsibility: maintainers are people who care about the ModelPack project and want to help it grow and improve. A maintainer is not just someone who can make changes, but someone who has demonstrated good judgement and an ability to collaborate with the team, get the most knowledgeable people to review code and docs, contribute high-quality code, and follow through to fix issues (in code or tests).

A maintainer is a contributor to the project's success and a citizen helping the project succeed.

The collective team of all Maintainers is known as the **Maintainer Council**, which is the governing body for the project.

### Becoming a Maintainer

To become a Maintainer you need to demonstrate the following:

- **Commitment to the project**:
  - Participate actively and impactfully in discussions, contributions, code and documentation reviews
  - Perform useful reviews for a significant number of non-trivial pull requests
  - Contribute non-trivial pull requests and have them merged
- Ability to write quality code and/or documentation
- Ability to collaborate with the team
- Understanding of how the team works (policies, processes for testing and code review, etc)
- Understanding of the project's code base and coding and documentation style

A new Maintainer must be proposed by an existing maintainer by opening an issue with the title "New Maintainer Proposal". A 2/3 vote of existing Maintainers must approve any application. Maintainers nominations will be evaluated without prejudice to employer or demographics.

Maintainers who are selected will be granted the necessary GitHub rights.

### Removing a Maintainer

Maintainers may resign at any time if they feel that they will not be able to continue fulfilling their project duties.

Maintainers may also be removed after being inactive, failing to fulfill their Maintainer responsibilities, violating the [Code of Conduct](./code-of-conduct.md), or other reasons. Inactivity is defined as a period of very low or no activity in the project for a year or more, with no definite schedule to return to full Maintainer activity.

A Maintainer may be removed at any time by a 2/3 vote of the remaining maintainers.

Depending on the reason for removal, a Maintainer may be converted to **Emeritus** status. Emeritus Maintainers will still be consulted on some project matters and can be rapidly returned to Maintainer status if their availability changes.

## Meetings

Time zones permitting, Maintainers are expected to participate in the ModelPack community meeting, which occurs bi-weekly on Thursday at 14:00 UTC.

### ModelPack Public Office Hours (bi-weekly)

**Bi-weekly on Thursdays @ 14:00 - 15:00**
**Time zone**: UTC
**Video call link**: [Zoom](https://zoom.us/j/99127808948?pwd=CggVIWsBPt1jUSbLaWCTcgaHpDB2tl.1)
**Meeting ID**: 991 2780 8948
**Passcode**: 644187

Maintainers may also have closed meetings in order to discuss sensitive matters or Code of Conduct violations. Such meetings should be scheduled by any Maintainer on receipt of a CoC report. All current Maintainers must be invited to such closed meetings, except for any Maintainer who is accused of a CoC violation.

## Code of Conduct

Everything we do in the ModelPack community is governed by our [Code of Conduct](./code-of-conduct.md). Violations by community members will be discussed and resolved by the Maintainers in a private forum. If a Maintainer is directly involved in the report, the Maintainers will instead designate two Maintainers to resolve the issue.

## Modifying this Charter

Changes to this Governance and its supporting documents may be approved by a 2/3 vote of the Maintainers.
