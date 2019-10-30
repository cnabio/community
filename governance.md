# CNAB Governance

The CNAB Foundation is a non-profit foundation under the [Joint Development Foundation](http://www.jointdevelopment.org/), which is the standards arm of the Linux Foundation.

The CNAB Foundation uses a working group model to create standards and reference implementations.

## Working Groups

Working groups are responsible for defining and approving important parts of the CNAB ecosystem. Each working group is responsible for its own timelines, roadmaps, goals, and deliverables. When a working group reaches a significant milestone, that group may announce a Working Group Approval. This indicates that the working group is ready to release a standard.

Currently, there are two working groups under the foundation:

- The CNAB Specification Working Group: This group works on the [CNAB specifications](https://github.com/deislabs/cnab-spec).
- The Duffle Working Group: This group works on [duffle](https://github.com/deislabs/duffle), which is the reference implementation of CNAB. The same group works on common libraries and other supporting reference implementations for CNAB.
### Working Group Creation

Working groups can be created by a supermajority of executive directors and are seeded with one or more [associates](#working-group-participants).

### Working Group Participants

Participants in working groups fall into two categories:

* Associate: A participant that contributes work and has voting rights
* Contributor: A participant that contributes work but *does not* have voting rights

Voting rights are applicable to working group processes and, when required, the selection of a new executive director.

Anyone can become a working group contributor but in order to become an associate, the person will need to be voted into the position by a supermajority of existing associates. There are no company restrictions on working groups.

## The Executive Directors

The executive directors have two sets of responsibilities:

1. Conduct the mundane business associated with the foundation.
2. Ratify _Working Group Approval_ documents, making them Approved Drafts, which are then published as complete artifacts.

The current executive directors of the CNAB Foundation are (in alphabetical order):

- Matt Butcher (Microsoft)
- Chris Crone (Docker)

Provisionally, new executive directors are nominated by existing executive directors by unanimous vote. In the event that executive directors cannot name new directors, the working groups may nominate and then vote on new executive directors, with a 2/3 supermajority of working group associates required for successful nomination. No one company may hold more than 50% of the voting power of the executive directorship.

The current term for an executive director is two years. Provisionally, the director may serve another term at will. (A future version of this governance document will provide a formal method.) An executive directory may step down from this position by formally announcing it to the other executive director(s), at which time the remaining executive directors may nominate and vote on a replacement director.

## The Working Group Lifecycle

This process governs the motion of a specification from rough draft through full standardization. While it does not necessarily follow the typical software lifecycle, we have approximately adapted it for reference implementations as well. A document is termed a _deliverable_ as it passes through various phases from _pre-draft deliverable_ to _accepted deliverable_, at which point it becomes a final specification.

### Versioning

Specifications shall each track their own versions. A specification will call out a target version (such as 1.0), and then also include its phase (such as Pre-Draft, see below) to indicate progress towards the target version.

For example, one of the specifications in this repository is the CNAB Core specification. The CNAB Core specification should be formally referenced as _Cloud Native Application Bundle Core 1.0.0_. The phase of the process MAY be appended as a stability marker: _Cloud Native Application Bundle Core 1.0.0-Draft_. It MAY be abbreviated to _CNAB1_ or _CNAB1-Draft_.

Other specifications must follow the same nomenclature.

### Development Process

The specification will proceed through the following phases:

- *Pre-Draft (PD):* Any working group associate or contributor may submit a proposed initial draft document as a candidate for this working group. The Working Group Chair may designate such a submission as a Pre-Draft Document.
- *Draft (Draft):* A Pre-Draft may be approved by the working group, in which case it becomes an official draft under the auspices of the CNAB specification working group. The working group will continue to revise the draft until it is in a state the group sees as fit for standardization.
- *Working Group Approval (GA):* When the working group believes a draft is fit for standardization, the group formally approves the draft and submits it for final approval.
- *Final Approval (AD):* The Executive Directors may grant Final Approval to a draft with Working Group Approval. This is by simple majority vote. At this point, the work is now designated an Approved Deliverable and is no longer a draft.
- *Publication:* When Final Approval is granted, the Approved Deliverable is made publicly available under the terms of the Open Web Foundation 1.0 license.
- *Submission to Other Standards Bodies:* With the approval of the Working Group, the Executive Director may submit an Approved Deliverable to another standards body in collaboration with the JDF.

Documents that have reached AD are considered complete. Errata may be captured in a separate section of the document, but the document itself is not changed except to correct typographical and formatting errors where necessary.

When the content of a document needs changes that cannot be captured as errata, a new _version_ of the specification must be created, and must proceed through the stages outlined above.
