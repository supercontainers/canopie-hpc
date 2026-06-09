---
hide:
  - navigation
---

## 8th workshop on Containers and new orchestration paradigms for isolated environments in HPC (CANOPIE-HPC) at Supercomputing 2026

### Program chairs:

* Alberto Madonna, ETH Zurich / Swiss National Supercomputing Centre
* Claudia Misale, CoreWeave, Inc.

* Shane Canon, Lawrence Berkeley National Lab
* Andrew Younge, Sandia National Labs

CANOPIE-HPC is a workshop focusing on containerization, virtualization, and
other methods to implement user-defined, bring-your-own, or isolated software
environments. Submissions will be peer-reviewed, and accepted papers will be
published by IEEE.


### Important Dates

* Submission opens:    June 10, 2026
* Submission closes (hard deadline - no extensions):    August 14th, 2026
* Papers decisions:    September 4th, 2026
* Lightning talks decisions:  September 11th, 2026
* Camera-ready papers deadline:    September 25th, 2026
* Workshop date:    November 16th, 2026

**Note: Items are due at 23:59 "anywhere on Earth" on the specified date. Specifically, this is 23:59 IDLW, i.e., UTC–12:00.**

### Overview

The ongoing revolution enabled via containerization, virtualization, and new 
orchestration models has dramatically changed how applications and services are 
delivered and managed across the computing industry.
This revolution has established a new ecosystem of tools and techniques with new,
flexible and agile approaches, and continues to gain traction in the HPC community. 
In addition to HPC-optimized container runtimes, emerging technologies like 
Kubernetes create a new set of opportunities and challenges. 
While adoption is growing, questions regarding best practices, foundational
concepts, tools, and standards remain.

Our goal is to promote the adoption of these tools and introspect the impact of this
new ecosystem on HPC use cases.
This workshop serves as a key venue for presenting late-breaking research, sharing
experiences and best practices, and fostering collaboration in this field.
Our seventh workshop iteration will continue to emphasize real-world experiences
and challenges in adopting and optimizing these new approaches for HPC.


### Scope

The scope of this workshop is to better understand and improve paradigms
around containerization, virtualization and orchestration for HPC and AI use cases.
The most well-known approaches are containers and virtualization, but anything
to further these goals is welcome.

Topics include but are not limited to:

* Container runtimes, virtual machine (VM) implementations, and other related technologies (e.g. unikernels, WebAssembly)
* Cloud-native approaches in HPC
* Container and VM image management and curation, including distribution and archiving
* Orchestration, scheduling, and/or resource management of jobs and microservices
* Workflows, including interaction between traditional HPC applications and containerized workflows or edge services
* AI model packaging, reproducibility, and distribution: containers, artifacts, environment portability, and sandboxing for models and agents.
* AI workloads at scale on cloud-native systems: training, inference, deployment, orchestration, scheduling, autoscaling, and resource management on Kubernetes and hybrid HPC/cloud platforms.
* Experience reports, perspectives from container framework users, developers, and system administrators
* Scientific reproducibility, including FAIR considerations
* GPUs, accelerators, proprietary interconnects, and other hardware considerations
* System and architecture portability
* Security considerations when adopting container technologies, including zero trust models
* Performance and scaling studies with containers and/or VMs
* Community standards, including OCI 
* Role of containerization in DevOps (ex: Gitlab CI/CD) 
* Perspectives on container outreach - convincing native application users/devs to make the jump


### Workshop format

We worked continuously to improve the CANOPIE-HPC program based on feedback 
from the community. We have made adjustments to the format for SC26 to include
more dynamic and engaging content, in addition to the traditional full paper
presentations. The content of technical sessions will be driven by the mix of
accepted submissions curated by the program chairs. We will offer two submission
tracks: one for full paper submissions, and one for lightning talks.
Like the previous edition, CANOPIE-HPC SC26 is going to be a full day workshop. 

Full paper submissions will receive at least 3 peer reviews in the SC26 
submission system on the basis of scientific validity, impact to the field,
reproducibility, and opportunity for interactive discussion at the workshop.
The program committee will discuss the submissions and their reviews over a
conference call moderated by the program chairs; final proceedings will be
selected by majority vote of the committee. Artifacts for reproducibility (digital archives of code, 
README instructions, images, etc.) will be a significant factor in paper 
acceptance into the workshop. Further details are available in the 
"Submission procedure" section below.
As in all previous years, accepted paper submissions will be published by
the SC proceedings publisher, which for SC26 is IEEE.

For lightning talks, participants can submit an abstract and an extended 
abstract that will be reviewed by the program committee. Our lightning talk 
track is meant to showcase demos, exploratory and late-breaking work, 
pain-points or shortcomings in current container/virtualization technologies, 
and projects that may not be fleshed-out enough to warrant a paper submission. 
We especially encourage lightning talk submissions from early career participants
and people who are relatively new to the world of containers/virtualization.

### Conference participation

SC26 is currently planned as an in-person event. At least one author per submission is
expected to present in-person in case of acceptance. SC26 workshops do not grant complimentary
registration to speakers, who should register as regular attendees. 
Remote presentations must be discussed with the SC Workshops chairs and be considered on a
case-by-case basis in the event of travel restrictions or health concerns, and will have to be explicitly approved.

### Diversity and inclusivity

Similarly to the broader field of HPC, the organizers recognize concerns with 
diversity and inclusion for CANOPIE-HPC. We continuously work to improve 
diversity and inclusion at leadership, program committee, and participation levels. 
We plan early and often targeted recruiting and advice-seeking with diversity 
organizations (e.g., WHPC). CANOPIE-HPC states explicit inclusion goals in the 
workshop CFP, includes an optional inclusion plan in paper submission system,
and specially considers any submitted inclusion plans during the Program 
Committee meeting.  To open CANOPIE-HPC to more early-career and non-expert participants, 
we plan to offer an expanded lightning talks session to lower the barrier to entry 
in the workshop. The workshop organizers will make any space considerations 
necessary to include those with accessibility requirements and ensure 
wheelchair-designated seating remains available to those in need. We also plan to 
include a 30 minute open discussion section to invite additional audience questions 
and participation. Furthermore, we will encourage attendees to join the Slack 
channel _hpc-containers_ to have an opportunity to continue to chat, ask questions 
and make professional connections.

### Reproducibility plan

In conjunction with the SC Reproducibility Initiative, paper submissions are required to provide
Artifact Descriptions as submission appendices, if applicable.
Artifacts such as reproduction instructions, source code, build recipes,
and/or container images would all be appropriate and considered during peer review.
For SC26, there is no page limit on Artifact Descriptions (AD). In case of acceptance,
authors are given the option to provide Artifact Evaluations (AE), if applicable.

### Use of AI-generated text

SC permits the use of AI tools (e.g., ChatGPT, Grammarly, or other AI assistants) to help improve the submission text.
The authors should verify whether the results are accurate before submission.
Authors are completely accountable for the contents of their papers, including content generated
by AI tools that could be interpreted as plagiarism or scientific misconduct (e.g., fabrication of facts).
AI tools are not eligible for authorship.

The use of any AI-generated text must be disclosed in the acknowledgments section.
The sections of the paper that use AI-generated text shall have a citation to the AI system used to generate the text.
If you use AI tools, you should include an acknowledgment section to disclose the AI assistance
with appropriate references to the sections in the paper.


### Submission procedure

Submissions must be in PDF format and use the IEEE proceedings template, with a two-column layout on U.S. 
letter-sized paper (8.5″ × 11″). LaTeX authors should select the `conference` mode.
Official IEEE templates for both LaTeX and Word are available [here](https://www.ieee.org/conferences/publishing/templates).
Manuscripts must be at least 4 pages in length, NOT including references. There is no maximum page limit.

All abstracts are limited to a maximum of 150 words.
Lightning talks can provide a 400-word extended abstract to better describe the submission.
We enthusiastically welcome original, high-quality submissions within the scope above.
These may describe complete studies; work-in-progress research; position papers on controversial,
emerging, or hot topics; state of the practice; or any other manuscript the authors believe
should be included in the CANOPIE-HPC program. We encourage submissions from academia,
industry, government, and/or any other type of institution.
Each manuscript will be assessed using peer review by program committee members (or outside reviewers, if needed)
on the basis of scientific validity, impact to the field, reproducibility, inclusivity, and opportunity
for useful and lively discussion at the workshop.
Review will be single-blind; i.e., reviewers will know authors’ identities, but not vice versa.
Authors should not anonymize their manuscripts. Each manuscript submission can expect to have at least 3
reviews and will be checked using anti-plagiarism software
(see [Plagiarism Guidelines](https://www.ieee.org/publications/rights/index.html#plagiarism-guidelines)).

In conjunction with the SC Reproducibility Initiative, submissions should be as 
transparent as possible regarding all methods. Submissions are also expected to
provide reproducibility artifacts such as reproduction instructions, source code, 
build recipes, and/or container images. These should be included as part of the 
submission in the form of [Artifact Description/Artifact Evaluation appendices](https://sc26.supercomputing.org/program/papers/reproducibility-appendices-badges/), 
which adhere to an established format adopted by SC26.

The program committee will discuss the submissions and their reviews and select
the program over a video conference meeting. Submissions will be assessed as-is, 
with no expectation of substantive revision after peer review, 
though some submissions may be accepted conditional on specified changes ("shepherded").

For any further details or inquiries, contact the workshop organizers at `sc-ws-canopie (at) info.supercomputing.org`

Submit your [SC26 CANOPIE-HPC paper](https://submissions.supercomputing.org/?page=Submit&id=SCWorkshopCANOPIEHPCSubmission&site=sc26)

Submit your [SC26 CANOPIE-HPC lightning talk](https://submissions.supercomputing.org/?page=Submit&id=SCWorkshopCANOPIEHPCLightningTalkSubmission&site=sc26)
