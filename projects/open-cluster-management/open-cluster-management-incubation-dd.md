# Open Cluster Management (OCM) Incubation Due Diligence
**Status:** Complete — ready for public comment PR to [cncf/toc](https://github.com/cncf/toc).

Open Cluster Management (OCM) provides a Kubernetes-native control plane for managing many clusters through a hub-and-spoke model. The adopter interviews show OCM in production across organizations that need multi-cluster federation, manifest replication, add-on distribution, and centralized operational control across regions and cloud providers.

- **Project:** [Open Cluster Management](https://open-cluster-management.io/)
- **Project repository:** [open-cluster-management.io](https://open-cluster-management.io/)
- **Interview evidence:** four completed adopter interviews, with Spectro Cloud, Red Hat, AppsCode, and Groww
- **Missing note:** Guidewire was contacted but did not provide interview responses

## Incubation Evaluation Summary for OCM

### Criteria Evaluation

The completed adopter interviews indicate that OCM satisfies the practical expectations for CNCF Incubation:

- **Adoption is real and production-based.** Each completed interview describes OCM in active use, not as a proof of concept.
- **The project solves a persistent infrastructure problem.** The common use case is operating many Kubernetes clusters consistently.
- **The implementation model is understandable.** Adopters repeatedly cited the hub-and-spoke pattern, manifest replication, and add-on architecture as clear and useful.
- **Documentation and community support are strong.** Interviewees consistently described the docs as useful and maintainers as responsive.
- **The project appears sticky.** Several adopters said they would fork or continue maintaining OCM if the project were archived.

The following themes were considered especially noteworthy:

- **Multi-cluster management is the primary value proposition.** OCM is used to coordinate clusters across regions, cloud providers, and product environments.
- **Extensibility matters.** Add-ons, plugin architecture, and controller-style integration are key reasons adopters selected OCM.
- **Operational utility is proven.** OCM is not only adopted, but embedded into platform operations and customer-facing deployments.

## Adoption Evaluation

**Adoption Evaluation** is based on TOC member live adopter interviews.

**Four** adopter interviews were completed for this summary. The interviews were conducted across organizations in different operational contexts:

- **Spectro Cloud**: production use in a platform setting, with emphasis on docs, maturity, and fast onboarding
- **Red Hat**: long-term use from the project’s beginning, including very large-scale deployment experience
- **AppsCode**: OCM as a foundational building block for a database-as-a-service platform
- **Groww**: production use for multi-cluster management, including custom adjacent tooling for rollout and override behavior

### What adopters reported

#### Strengths adopters cited

1. **Multi-cluster control plane value**
   OCM is consistently described as a practical answer for managing many clusters from one control plane.

2. **Production readiness**
   Interviewees described stable use in real environments, including customer-facing deployments and large-scale internal platforms.

3. **Documentation quality**
   The docs were repeatedly called useful, accurate, and sufficient to get started quickly.

4. **Community responsiveness**
   Adopters had positive experiences with GitHub issues, Slack, maintainers, and public community channels.

5. **Architectural clarity**
   The hub-and-spoke model, manifest replication, and add-on architecture were easy to understand and fit Kubernetes-native workflows.

6. **Strategic fit for platform teams**
   OCM maps well to teams operating multiple clusters as part of a broader platform or infrastructure service.

#### Improvement themes adopters raised

1. **Release cadence**
   Some interviewees felt release cadence could be faster, especially when paired with CVE response expectations.

2. **Maintainer breadth**
   There is concern about maintainer concentration and the desirability of broader geographic and organizational distribution.

3. **Operator ergonomics**
   A few interviewees wanted a better UI and richer status/reporting.

4. **Advanced behavior and overrides**
   In at least one case, adopters built adjacent tooling to handle override behavior and rollout needs.

5. **Ecosystem continuity**
   Red Hat in particular emphasized the importance of OCM staying aligned with SIG multicluster direction and broader upstream ecosystem expectations.

### TOC synthesis of the adopter signal

The interviews point to a project that is:

- clearly adopted
- valuable in production
- easy to explain and integrate at a high level
- worth maintaining if upstream disappeared
- improving, but still with some operational and governance gaps to close before graduation

## Criteria-by-Criteria Notes

### Adoption

OCM is used in production by organizations operating multiple clusters at meaningful scale. The interviews support the conclusion that OCM is not niche experimental tooling; it is embedded in platform operations.

### Documentation

The documentation is a consistent strength. Adopters reported being able to get started from docs, understand the architecture, and find useful implementation detail without needing heavy maintainer intervention.

### Community

Community interaction is healthy. GitHub, Slack, and community meetings are used effectively, and maintainers were described as responsive and approachable.

### Resilience if archived

Several adopters said they would fork or maintain the project if it were archived. That is a strong signal of dependence and value retention, though it also implies some risk if maintainer breadth does not expand.

### Limitations

The main concerns are not about the project’s ability to solve the problem. They are about surrounding maturity:

- release cadence and CVE responsiveness
- maintainer concentration
- UI and reporting gaps
- the need for broader upstream alignment and continuity

## Overall Strengths

- multi-cluster management is a real and recurring need
- OCM is production-proven
- the architecture is clear and Kubernetes-native
- docs and maintainers are strong
- the project creates durable operational value
- adopters are sticky and willing to continue supporting it

## Overall Risks

- slower release cadence may frustrate operators who need more predictable upgrades
- maintainer concentration could create long-term sustainability risk
- some advanced workflows require custom tooling around OCM
- UI and observability/reporting are not yet as strong as core control-plane functionality

## Conclusion

The TOC interview evidence supports a favorable due-diligence conclusion for OCM at incubation level. The project solves a meaningful and persistent cloud-native problem, has clear production adoption, and demonstrates good documentation and community support.

The remaining work is largely around governance breadth, operational ergonomics, and long-term project sustainability, not core project viability.
