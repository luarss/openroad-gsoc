## Why does your org want to participate in GSoC?

OpenROAD is a fully autonomous, open-source RTL-to-GDSII flow that makes chip design accessible to researchers, startups, and universities worldwide. We're breaking down the proprietary walls in Electronic Design Automation (EDA), and GSoC helps us build a community that can actually sustain that vision.

Here's why we participate:

1. **Develop real EDA expertise**: Contributors don't just write code—they work with production-grade algorithms for floorplanning, placement, clock tree synthesis, routing, and timing optimization.

2. **Get fresh perspectives on hard problems**: Physical design optimization is tough. Multi-objective placement algorithms, parasitic extraction, ML integration—these aren't solved problems. Contributors bring new approaches that genuinely strengthen our toolchain.

3. **Make chip design more accessible**: Every improvement we make means someone else can build custom silicon who couldn't before. We've enabled 600+ tapeouts through Google-sponsored programs (chipIgnite, OpenMPW). That's 600+ real chips, not just demos.

4. **Grow the community long-term**: We've seen GSoC contributors become maintainers, academic collaborators, and industry practitioners who continue championing open-source EDA in their careers.

OpenROAD started as a DARPA project and has ongoing industrial collaborations. We're committed to participating in GSoC to nurture the next generation of EDA developers, and advancing chip design tools which should be accessible to all.

## What would your organization consider to be a successful GSoC for your org?

We measure success in three ways: does the code actually work, do contributors stick around, and did they learn real software skills?

**Technical Impact:**
- Production-ready code that gets merged and used in real flows
- Measurable metric improvements: shorter wirelength, better timing closure, improved power-performance-area (PPA), or cleaner design rule compliance
- Real algorithmic contributions to core engines—global placement, detailed routing, static timing analysis, parasitic extraction
- Good regression test coverage: across different designs and tech nodes
- Documentation that actually helps people use the new features

**Community Sustainability:**
- More than half of contributors remain active 6 months later (GitHub, Slack)
- Alumni who come back to mentor, review code, or help triage issues
- Growing knowledge base—tutorials, design examples, docs that explain how things work

**EDA Expertise Development:**
- Contributors who genuinely understand physical design algorithms, chip flows, and optimization techniques they can take to industry or research
- Career progression into grad programs, EDA companies, or chip design roles

A successful summer means both immediate contributions and people who'll keep advancing open-source hardware design for years.

## How will you keep mentors engaged with their GSoC contributors?

Mentors stay engaged when the work matters to them and they're not left hanging. Here's our approach:

**Structured Coordination:**
- Weekly mentor syncs to track progress, solve problems, and share what's working
- Dedicated Slack channels so mentors can coordinate in real-time or async

**Clear Expectations & Backup:**
- Mentor handbook that spells out responsibilities, time commitment (5-10 hours/week), code review process, and when to escalate issues
- Backup mentors assigned upfront so there's coverage across time zones and no single points of failure
- Project leadership handles conflict resolution, schedule adjustments, and getting people what they need

**Recognition & Career Development:**
- Co-authorship on conference papers and publications that come out of GSoC work
- Public acknowledgment in release notes, announcements, and technical reports

**Strategic Alignment:**
- Mentors propose and scope projects in their areas (physical design, timing, ML, infrastructure)
- Projects align with the OpenROAD roadmap, so mentor effort advances tools they actually depend on for research and tapeouts
- Contributor wins translate to real improvements in design flow quality

**Ecosystem Connections:**
- Collaboration with industry partners (Google, Qualcomm, Arm, Intel, Precision Innovations, SkyWater, GlobalFoundries, IHP, Efabless, Samsung, Abacus Semiconductor) and universities (UCSD, UCSC, UMich, UIUC, UTD, UMN, Brown, ASU, NYU, UFRGS)
- Networking with EDA researchers building the future of open-source chip design

## How will you help your GSoC contributors stay on schedule to complete their projects?

We borrow project management practices from the semiconductor industry—if there's one thing chip design teaches you, it's hitting deadlines:

**Milestone-Driven Planning:**
- Projects broken into 2-week sprints with concrete deliverables (algorithm prototype, test suite, docs, integration)
- Community bonding period creates detailed specs: API designs, test cases, performance targets, regression test plans
- Mid-program evaluations with code review and technical assessment—we'll adjust timelines if complexities emerge

**Communication Cadence:**
- Weekly 1-hour video meetings with mentors for deep technical discussions, design reviews, and solving blockers
- Daily async updates via GitHub or Slack documenting progress, challenges, and what's blocking you

**Proactive Risk Management:**
- Backup mentors activate when someone's stuck on algorithm complexity, toolchain integration, or architectural questions
- Weekly at-risk project reviews where senior maintainers provide guidance and resources

**Technical Support:**
- Developer docs covering build systems, coding standards, test frameworks, and architecture
- Active Slack (#general, #development, #gsoc-2026) with 100+ people who can help fast
- CI infrastructure (Jenkins/GH Actions) that gives you build verification, test results, and code quality metrics in minutes

**Adaptive Scope:**
- Projects scoped with core functionality plus optional stretch goals—so if you're behind, we can adjust gracefully
- Monthly scope checkpoints to reality-check against EDA complexity (routing convergence problems, timing closure headaches, etc.)
- Architectural pivots allowed when investigation shows a better approach

## How will you keep your GSoC contributors involved in your community during and after GSoC?

**During GSoC:**

*Deep Integration into EDA Community:*
- Full Slack access including specialized channels where you can connect with domain experts
- Code reviews with core maintainers and academic collaborators—you'll build relationships beyond just your assigned mentors

*Documentation & Visibility:*
- **Three blog posts** published on our website: (1) introduction post before starting, (2) mid-term progress update, and (3) final project summary—documenting your journey and technical contributions
- Featured posts cross-promoted on theopenroadproject.org
- Social media highlights (@OpenROAD_EDA on Twitter/X and LinkedIn) showcasing your work to 5,000+ EDA community members
- Acknowledgment in release notes, technical docs, and GitHub credits

**After GSoC:**

*Advanced Contribution Pathways:*
- Extended project opportunities for alumni: hierarchical placement, advanced routing algorithms, ML-driven optimization engines
- Invitations to specialized working groups developing next-gen capabilities (cloud-native EDA, distributed optimization, GPU acceleration)
- Research collaborations that extend GSoC work into conference papers (DAC, ICCAD, ISPD) or journal publications

*Career & Academic Development:*
- Letters of recommendation from OpenROAD faculty mentors and industry partners for grad school or EDA industry positions
- Direct introductions to hiring managers at partner organizations (Google, Precision Innovations, SkyWater) and academic research groups
- Portfolio showcasing: your projects featured in OpenROAD technical presentations at industry conferences

*Technical Leadership:*
- Maintainer invitations with commit privileges for sustained high-quality contributors—you get architectural influence over open-source EDA tools
- Mentorship roles: alumni guide future contributors, review code, and provide domain expertise
- Project definition: alumni propose and scope future GSoC projects based on roadmap priorities

*Sustained Community Engagement:*
- OpenROAD Alumni Network for ongoing collaboration, career networking, and knowledge sharing among 20+ former contributors
- Annual reunions at major EDA conferences (DAC, ICCAD, ISPD) for in-person collaboration and industry networking
- Continued access to Slack, GitHub org membership, technical resources, and mentorship

**What Our Alumni Have Done:**
Since 2022, OpenROAD GSoC alumni have:
- Become maintainers contributing to placement engines, routing algorithms, and infrastructure
- Published peer-reviewed papers at top EDA venues featuring OpenROAD innovations
- Gone to grad programs in VLSI design, EDA research, and computer architecture
- Come back as GSoC mentors themselves

We don't measure success by summer deliverables alone—it's about multi-year engagement advancing open-source chip design.

## Has your org been accepted as a mentor org in GSoC?

Yes. We've participated as a GSoC mentor organization since 2022, with well-documented contributions from 2023-2025, through partnership with UC Santa Cruz Open Source Program Office (UCSC OSPO).

## If so, when and how many GSoC contributors are still actively involved in your community today?

**Participation Timeline:**

- **2023**:
  - **Jack Luar** (Masters student, NUS): Updated OpenROAD documentation and tutorials, enabling multi-OS support for 9 major operating systems, improving 20+ tool-specific docs, and reducing installation-related GitHub issues by 10%. Jack later became a mentor for 2024-2025 projects.

- **2024**:
  - **Aviral Kaintura** (B.Tech-M.Tech CSE, NFSU Delhi + B.S. Data Science, IIT Madras): LLM Assistant for OpenROAD—data engineering and testing
  - **Palaniappan R** (Undergraduate, BITS Pilani): LLM Assistant for OpenROAD—model architecture and prototype. Developed ORAssistant chatbot with hybrid-search combining keyword and vector search. Palaniappan later became a mentor for 2025 projects.

- **2025**: Currently active
  - **Gambali Seshasai Chaitanya**: Implementing rectilinear (polygonal) die shapes in OpenROAD's floorplanning flow, extending beyond rectangular floorplans to support complex shapes

**Alumni Engagement:**

Since 2023, we've maintained strong connections with our GSoC contributors:

- **Active Technical Contributors**: Jack Luar, Aviral Kaintura, and Palaniappan R continue contributing through GitHub PRs, code reviews, and technical discussions. Their work on documentation, LLM integration, and infrastructure remains in active use.

- **Community Leadership**: Jack Luar (2023) and Palaniappan R (2024) and Aviral Kaintura (2024) progressed from contributors to mentors, now guiding 2025 GSoC participants—demonstrating our contributor-to-leader pipeline.

**Retention Success:**
- **High retention rate**: Out of 3 alumni from 2023-2024, all 3 remain engaged—2 progressed to mentorship roles (Jack Luar, Palaniappan R) and 1 continues contributing (Aviral Kaintura)
- **Career advancement**: Our alumni have advanced to graduate programs and industry positions while maintaining community involvement
- **Sustained technical impact**: Contributions from 2023-2024 (multi-OS support, documentation improvements, ORAssistant) remain in active production use across hundreds of tapeouts
- **2025 contributor**: Gambali Seshasai Chaitanya is mid-way through the project with strong progress

Our track record shows genuine contributor retention and progression, not just summer project completion.

## Where does your source code live?

Everything's on GitHub under The-OpenROAD-Project organization:

**Primary Repository:**
- https://github.com/The-OpenROAD-Project/OpenROAD — Unified RTL-to-GDSII application with floorplanning, placement, clock tree synthesis, routing, parasitic extraction, and timing analysis

**Related Repositories:**
- https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts — Reference design flow scripts for various tech nodes
- https://github.com/The-OpenROAD-Project — Organization with 50+ repos including individual tool components, PDK configs, design examples, and utilities

**Documentation & Resources:**
- https://openroad.readthedocs.io/ — Technical docs covering tool APIs, algorithms, tutorials, and developer guides
- https://theopenroadproject.org/ — Project website with news, tapeout showcases, publications, and getting-started info

## Link to your Ideas List (this is the most important part of the application!)

- **Primary location**: https://the-openroad-project.github.io/[ideas-repo]

**Project Categories:**

TBC

# References
- https://google.github.io/gsocguides/mentor/org-application.html#whats-on-the-application