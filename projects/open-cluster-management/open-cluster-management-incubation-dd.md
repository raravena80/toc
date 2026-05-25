# Open Cluster Management (OCM) Incubation Due Diligence

- Link to [Incubation application issue](https://github.com/cncf/toc/issues/1884)

> **Status: DRAFT** - Filed by [@raravena80](https://github.com/raravena80) as TOC sponsor.
> Adopter interviews in progress. This due diligence is in draft until interviews are complete.

---

## Incubation Evaluation Summary for Open Cluster Management (OCM)

### Criteria Evaluation

*Ricardo Aravena (@raravena80) conducted the due diligence of Open Cluster Management (OCM) who applied for Incubation. The project [has/has not] completed the criteria that show its maturity at Incubation. The following criteria implementations are noteworthy to call out... $NOTABLES. The following actions were provided to the project that were considered blocking but since resolved... $BLOCKERS. The following recommendations were provided to the project that are non-blocking in the TOC's assessment but should be completed by the project to ensure continued viability of the project... $RECOMMENDATIONS.*

> **TODO:** Complete this summary after criteria evaluation and adopter interviews are finished.

### Adoption Evaluation

*The adopter interviews reflect a project [in use/too early] for the level which the project applied. They show ... $INTERVIEWSUMMARY.*

> **TODO:** Complete after adopter interviews.

### Final Assessment

*[The TOC has found the project to have satisfied the criteria for Incubation / The TOC's evaluation of the project shows a needed focus to complete the outstanding blockers and reapply when the following conditions are met ... $CONDITIONS].*

> **TODO:** Complete after full evaluation.

---

## Application Process Principles

### Suggested

- [x] **Engage with domain-specific TAG(s) to present the technical architecture of the project.**
  * TAG-Runtime presentation occurred on 06-MAR-2025, recording available at https://www.youtube.com/watch?v=ex3vdlCDPXw. A General Technical Review (GTR) was also completed and is available at https://github.com/open-cluster-management-io/community/blob/main/cncf/GTR.md.

### Required

- [x] **Complete a [General Technical Review (GTR)](https://github.com/cncf/toc/blob/main/operations/toc_subprojects/project-reviews-subproject/general-technical-questions.md).**
  * GTR completed and available at https://github.com/open-cluster-management-io/community/blob/main/cncf/GTR.md.

- [ ] **Complete a [Governance Review](https://github.com/cncf/toc/blob/main/operations/toc_subprojects/project-reviews-subproject/governance-review-template.md).**
  * No Governance Review on file at time of DD. Not blocking per process - depends on TAG Contributor Strategy availability.

- [x] **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**
  * Project asserts vendor-neutrality. OCM uses APIs not tied to any cloud provider or proprietary platform. Governance and contribution paths are open and based on community involvement, not company affiliation. OCM contributes to and aligns with SIG-Multicluster APIs. Verified via governance and contribution documentation.

- [x] **Review and acknowledgement of expectations for [Sandbox](https://sandbox.cncf.io) projects and requirements for moving forward through the CNCF Maturity levels.**
  * Met during project's sandbox application on 28-SEP-2023. Onboarding issue: https://github.com/cncf/sandbox/issues/227.

- [ ] **Due Diligence Review.**
  * Completion of this due diligence document, resolution of concerns raised, and presented for public comment satisfies the Due Diligence Review criteria.

- [x] **Additional documentation as appropriate for project type.**
  * OCM documentation covers installation, user guide, developer guides, and user scenarios: https://open-cluster-management.io/docs/. Blog posts available at https://open-cluster-management.io/blog/.

---

## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from the Project Reviews subproject.

### Suggested

- [x] **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**
  * Governance document: https://github.com/open-cluster-management-io/community/blob/main/GOVERNANCE.md. Documented iterations include updating the contributor ladder ([PR #187](https://github.com/open-cluster-management-io/community/pull/187)) and community meeting times ([PR #188](https://github.com/open-cluster-management-io/community/pull/188)).
  * > **TODO:** Independently verify governance history via git log and PR history.

- [x] **Clear and discoverable project governance documentation.**
  * Governance document is publicly available and linked from the project README and community repo: https://github.com/open-cluster-management-io/community/blob/main/GOVERNANCE.md.

- [x] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**
  * Governance was recently updated. Meeting schedule and community processes are reflected at https://open-cluster-management.io/community/.
  * > **TODO:** Verify last commit date on GOVERNANCE.md and cross-check with actual meeting cadence.

- [x] **Governance clearly documents [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) project direction.**
  * Governance explicitly describes paths to maintainership based on community involvement, not company affiliation.

- [x] **Document how the project makes decisions on leadership, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**
  * Documented in GOVERNANCE.md.

- [x] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams.**
  * Documented in GOVERNANCE.md and maintained via active Slack channel.

- [x] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**
  * Defined in the contributor ladder: https://github.com/open-cluster-management-io/community/blob/main/CONTRIBUTOR_LADDER.md.

- [x] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**
  * Examples: [PR #210](https://github.com/open-cluster-management-io/community/pull/210), [PR #214](https://github.com/open-cluster-management-io/community/pull/214) (additions); [PR #209](https://github.com/open-cluster-management-io/community/pull/209) (emeritus). Recent maintainer additions also announced on Slack.

- [x] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**
  * Documented in [GOVERNANCE.md](https://github.com/open-cluster-management-io/community/blob/main/GOVERNANCE.md#default-subproject-governance) and the [addon-contrib governance section](https://github.com/open-cluster-management-io/addon-contrib?tab=readme-ov-file#governance).

### Required

- [x] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**
  * MAINTAINERS.md: https://github.com/open-cluster-management-io/community/blob/main/MAINTAINERS.md.
  * > **TODO:** Verify file is current and includes all required fields (contact info, domain, affiliation).

- [x] **A number of active maintainers which is appropriate to the size and scope of the project.**
  * Project claims 22 maintainers from multiple organizations. Devstats: https://openclustermanagement.devstats.cncf.io.
  * > **TODO:** Independently verify maintainer count and org diversity via MAINTAINERS.md and devstats.

- [x] **Code and Doc ownership in GitHub and elsewhere matches documented governance roles.**
  * OWNERS file: https://github.com/open-cluster-management-io/ocm/blob/main/OWNERS. Cross-referenced with MAINTAINERS.md and GOVERNANCE.md.
  * > **TODO:** Spot-check OWNERS files across key sub-repos against MAINTAINERS.md.

- [x] **Document adoption and adherence to the CNCF Code of Conduct.**
  * CoC adopted during sandbox onboarding: https://github.com/open-cluster-management-io/community/blob/main/CODE_OF_CONDUCT.md.

- [x] **CNCF Code of Conduct is cross-linked from other governance documents.**
  * Linked directly from GOVERNANCE.md: https://github.com/open-cluster-management-io/community/blob/main/GOVERNANCE.md#code-of-conduct.

- [x] **All subprojects, if any, are listed.**
  * Full sub-project list in GOVERNANCE.md: https://github.com/open-cluster-management-io/community/blob/main/GOVERNANCE.md#subprojects.

---

## Contributors and Community

Note: this section may be augmented by the completion of a Governance Review from the Project Reviews subproject.

### Suggested

- [x] **Contributor ladder with multiple roles for contributors.**
  * Defined at https://github.com/open-cluster-management-io/community/blob/main/CONTRIBUTOR_LADDER.md.

### Required

- [x] **Clearly defined and discoverable process to submit issues or changes.**
  * Documented in community [CONTRIBUTING](https://github.com/open-cluster-management-io/community/blob/main/CONTRIBUTING.md) and OCM [CONTRIBUTING](https://github.com/open-cluster-management-io/ocm/blob/main/CONTRIBUTING.md).

- [x] **Project must have, and document, at least one public communications channel for users and/or contributors.**
  * Slack: https://kubernetes.slack.com/channels/open-cluster-mgmt. Linked from README and project website.

- [x] **List and document all project communication channels, including subprojects.**
  * Channels (Slack, GitHub, weekly community meetings, office hours) documented at https://open-cluster-management.io/community/.

- [x] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**
  * OCM Calendar: https://calendar.google.com/calendar/u/0/embed?src=openclustermanagement@gmail.com. Two recurring meetings (bi-weekly NA/EU lunch chat; bi-weekly APAC community meeting).
  * > **TODO:** Verify calendar is current and meetings are being held as documented.

- [x] **Documentation of how to contribute, with increasing detail as the project matures.**
  * See CONTRIBUTING.md links above.

- [x] **Demonstrate contributor activity and recruitment.**
  * Project reports 28 contributors in the last year, average of 758 contributions and 30 contributors/month, ~85 PRs merged/month. Devstats: https://openclustermanagement.devstats.cncf.io. Active KubeCon/KCD participation documented in application.
  * > **TODO:** Independently verify via devstats and GitHub contributor graphs.

---

## Engineering Principles

### Suggested

- [x] **Roadmap change process is documented.**
  * Roadmap maintained at https://github.com/orgs/open-cluster-management-io/projects/2/views/9 and https://open-cluster-management.io/docs/roadmap/.

- [x] **History of regular, quality releases.**
  * Release history documented at https://open-cluster-management.io/docs/release/ and GitHub project dashboard.
  * > **TODO:** Review release cadence and changelog quality.

### Required

- [x] **Document project goals and objectives that illustrate the project's differentiation in the Cloud Native landscape.**
  * Covered in the GTR: https://github.com/open-cluster-management-io/community/blob/main/cncf/GTR.md.

- [x] **Document what the project does, and why it does it - including viable cloud native use cases.**
  * Covered in GTR and website: https://open-cluster-management.io/docs/concepts/ and https://open-cluster-management.io/docs/scenarios/.

- [x] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**
  * GitHub Project board: https://github.com/orgs/open-cluster-management-io/projects/2/views/9.

- [x] **Document overview of project architecture and software design that demonstrates viable cloud native use cases.**
  * Covered in GTR and project concepts documentation: https://open-cluster-management.io/docs/concepts/.

- [x] **Document the project's release process.**
  * Release runbook: https://github.com/open-cluster-management-io/community/blob/main/RELEASE.md.

---

## Security

### Suggested

N/A

### Required

Note: this section may be augmented by a joint-assessment performed by TAG Security and Compliance.

- [x] **Clearly defined and discoverable process to report security issues.**
  * SECURITY.md: https://github.com/open-cluster-management-io/community/blob/main/SECURITY.md. Also documented at https://open-cluster-management.io/docs/security/.

- [x] **Enforcing Access Control Rules to secure the code base against attacks.**
  * GitHub 2FA enforced by default. Merge/commit access managed via OWNERS files and Prow CI/CD.
  * > **TODO:** Check OpenSSF Scorecard results for branch protection, token permissions, SAST, and CI best practices.

- [x] **Document assignment of security response roles and how reports are handled.**
  * Documented in SECURITY.md and at https://open-cluster-management.io/docs/security/.

- [x] **Document Security Self-Assessment.**
  * Self-assessment filed: https://github.com/open-cluster-management-io/ocm/blob/main/SELF_ASSESSMENT.md.
  * > **TODO:** Review self-assessment content for completeness and accuracy.

- [x] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**
  * Badge achieved (passing): https://www.bestpractices.dev/en/projects/5376.
  * > **TODO:** Verify badge is current and at 100%.

---

## Ecosystem

### Suggested

N/A

### Required

- [x] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**
  * ADOPTERS.md: https://github.com/open-cluster-management-io/ocm/blob/main/ADOPTERS.md. Includes use cases and adoption level details.

- [x] **Used in appropriate capacity by at least 3 independent + indirect/direct adopters.**
  * Public adopters include Appscode, eBay, SpectroCloud, Alibaba, Red Hat. At least 2 additional non-public adopters noted by the project.

- [ ] **TOC verification of adopters.**
  * Refer to the Adoption section below. Interviews in progress.

- [x] **Clearly documented integrations and/or compatibility with other CNCF projects as well as non-CNCF projects.**
  * Documented at https://open-cluster-management.io/ and https://github.com/open-cluster-management-io/ocm/tree/main/solutions. Integrations include: Kubernetes, Argo CD, KubeVela, KubeStellar, Kueue.

### Adoption

> **TODO:** Complete with interview summaries once adopter interviews are conducted and approved for publication.

#### Adopter 1 - $COMPANY/$INDUSTRY

*If the adopting organization needs to remain anonymous, stating the industry vertical is sufficient.* MONTH YEAR

#### Adopter 2 - $COMPANY/$INDUSTRY

*If the adopting organization needs to remain anonymous, stating the industry vertical is sufficient.* MONTH YEAR

#### Adopter 3 - $COMPANY/$INDUSTRY

*If the adopting organization needs to remain anonymous, stating the industry vertical is sufficient.* MONTH YEAR
