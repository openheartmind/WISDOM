# WISDOM

Hi and welcome to the WISDOM revolution :)

We're developing a universally applicable, standardised framework for recognising and rewarding contributions to any community, so that we can empower contributors, connect communities, and transition to a collaborative gift-based society. 

WISDOM stands for 
**W**eighted
**I**nformation 
**S**chema for 
**D**iverse / Distributed 
**O**rganisations and 
**M**etascience (or something like that... it's more the sentiment that counts).

### The challenge of cultural change
As our world grows increasingly interconnected, the need to learn from one another's experiences has never been greater. Yet, despite the wealth of knowledge all around us, most people remain resistant to actively sharing their insights and feedback. Entrenched cultural norms and technological inertia make it difficult to incentivize the behaviors needed to harness this collective wisdom.

### The WISDOM Solution
WISDOM is a flexible framework designed to crack the code of cultural change. By providing an adaptable model for understanding individual and collective motivations and directly rewarding engagement, WISDOM empowers diverse communities to foster knowledge-sharing and collective growth. By directly rewarding contributors using transparent data and processes, WISDOM empowers contributors to decide how to deliver the best value for their community. 

At the heart of WISDOM is an inclusive review protocol that incentivises high-quality feedback about contributions, and generates a rich representation of the diverse qualities of every single contribution. Contributors are then rewarded with tokens reflecting the collective gratitude of the community, which can be paid forward to other people. Reliable reviewers and experts can also be respected via evidence-based metrics, providing a platform for those people we should be listening to. 

WISDOM aims to become a complete operating system for any community, integrating the key functions of _information sharing_, [_economics_](https://github.com/openheartmind/WISDOM/tree/main/documents) and [_governance_](https://github.com/openheartmind/WISDOM/blob/main/documents/governance.md). By connecting diverse communities under a common framework, WISDOM creates a universal language for sharing gratitude and collaborating more effectively toward common goals. 

### Minimal Viable Model (MVM)
_0. Embed Values._ Every community has the opportunity to decide which dimensions their reviewers will vote on, meaning that they can directly embed their values into the code. We suggest communities adopt the common dimension of "Gratitude" to facilitate cross-comparison between communities. Beyond this, each community is free to choose any number of dimensions, and dimensions can also evolve over time in response to evidence and feedback. 

_1. Record._ Contributions are recorded in a transparent register of the community's choice. The scale and scope of records depends on the community, and members are incentivised to keep the register current, complete and accurate. 

_2. Review._ WISDOM uses pairwise comparisons to generate ratings at the crowd-level. Pairwise comparisons are a quick, simple and user-friendly review protocol, ensuring that diverse people can contribute data, regardless of expertise or technical prowess. Anyone in the community can complete a pairwise comparison by voting between two contributions on each dimension of interest (e.g., "Which of these two contributions are you most grateful for?"). Reliable reviewers might also earn the status of '_meta-reviewer_', which entitles them to vote on the relative value of reviews themselves (termed a '_meta-review_') on the primary dimension of Gratitude. 

_3. Recognise._ Pairwise comparisons are relatively uniform, meaning that we can treat them as a 'standard unit' of contribution and use them to peg the value/s of all other contributions. This is achieved by including a range of review contributions (e.g., 32, 64, and 128 pairwise comparisons) in the meta-review, fitting a function to the resulting votes, and interpolating values for all regular contributions (see 'algorithm' tab in our [pilot dataset](http://tiny.cc/tinyOHMresults)). The result is a rich information matrix spanning multiple dimensions that recognises the unique qualities of every single contribution, and can be filtered in an infinite number of ways.

_4. Reward._ Contributors are rewarded with tokens representing the collective gratitude for their contributions. Reviews are rewarded at the rate of 1 token per pairwise comparison (including all dimensions), and regular contributions are rewarded commensurate to the number of units on the Gratitude dimension (more complicated transfer functions could be explored in the future). Communities may agree to subtract common costs (e.g., the average cost of an event), leaving a balance that reflects each contributor’s total energetic exchange with the community (see 'Summary' tab, 'Reward' column, in our [pilot dataset](http://tiny.cc/tinyOHMresults)). Excess tokens can be paid forward to other people who the contributor wishes to thank in turn, forming the basis of an evidence-based gifting economy.

_5. Respect._ By measuring contributions over time, we can generate metrics reflecting each persons unique strengths and value proposition to the community. Reviewer reliability can be measured using a range of measures (e.g., test-retest reliability, internal consistency), and trustworthy reviewers can be elevated to the status of _meta-reviewer_. Experts in particular fields and topics can be identified by tracking the value they add to that field over time (see 'Summary' tab, 'Reward' column, in our [pilot dataset](http://tiny.cc/tinyOHMresults)). Collectively, these metrics could form the basis of a merit-based participatory democracy algorithm, in which votes are weighted according to each person's validated expertise in the topic of interest. 

_6. Replicate and Repeat._ All of the above processes should be conducted transparently and shared with the community, so that everyone can learn and grow together. The final stage is therefore to replicate the previous materials, embed any learnings, and repeat the process again. 

### Principles and Features
- _Transparent_. Contributions and reviews are shared publicly, so you know what's going on behind the scenes.
- _Inclusive_. Everyone is rewarded for their unique contributions, including reviews, meaning that everyone can contribute in the way that works for them.
- _Replicable_. Open source and forkable, so you can stand on the shoulders of giants.
- _Accessible_. Our review protocol is user-friendly and cognitively simple, so that anyone can contribute meaningful data no matter their circumstances.
- _Collaborative_. Our crowd-based reward mechanism incentivises collaboration over competition.
- _Diverse_. Our framework is flexible, scaleable and can be customised to the needs of different communities.
- _Honest_. Transparent reviews and reliability metrics encourage honesty and guard against cheats. 

### A Universal Framework
WISDOM is designed to be maximally inclusive to all communities. The MVM above is the simplest model possible for capturing quantitative meta-information -- information about the relative value of information. There are of course more nuanced ways to conduct reviews, but all of these can be considered derivatives of the universal MVM we outline here. Each community could develop additional modules that plug into this core model (e.g., a qualitative review module), using the pairwise comparison method to determine the relative value of contributions to those layers (e.g., the value of a qualitative review could be given in terms of an equivalent number of pairwise comparisons). 

Communities are also free to develop their own terms, standards, processes and algorithms. For example, at OHM, we call our tokens OHMnoms, but other communities might want to name their own tokens accordingly. Each community could then decide what other communities to cooperate and trade with, by assessing their transparent processes and data and deciding (if necessary) a relative weighting for the respective tokens. Providing that all communities adopt the MVM we present here, it would create a fundamental communication layer both within and between communities that directly encodes gratitude and facilitates cooperation toward common goals.

### Usage Examples
1. Gatherings. See [data and results](https://docs.google.com/spreadsheets/d/1HS7HFa9y6PfF61_wTuCAbj9RTHe94VLXulS0pDYgtns/edit?usp=sharing) from a [Open Heart + Mind (OHM)](https://github.com/openheartmind) gathering called Tiny OHM (see also [/reports](https://github.com/openheartmind/WISDOM/tree/main/reports)). We're also prototyping with [Vibe Camp](https://github.com/vibecamp) to review [contributions to Vibeclipse](https://docs.google.com/spreadsheets/d/1t1mzPUlnKUeTf_lUKJySg1yiL5AxLkMORp6L5ZHOTww/edit?usp=sharing).
2. Conferences. See our [working prototype](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?usp=sharing) to evaluate contributions to the 2023 AIMOS open/meta-science conference.
4. Scholarly communication. Our model was originally designed to solve cultural inertia in the transition to open science platforms. If you work in the scholarly communication / evaluation space, we'd love to hear from you! 
5. Literally any contribution to _any_ community. We think of WISDOM as a _minimal viable model_, meaning that it is both flexible and adaptable to different community needs. We're collecting a list of organisations interested in exploring the framework, please add your name [here](https://docs.google.com/spreadsheets/d/1XF9CagLX1WUXaPy-HDYlY4kZv8HZngEGu7lM6EQnvy4/edit?usp=sharing) if interested so we can get in touch.

### Development History
- 2019-2021: WISDOM designed as a solution for cultural inertia in academia
- Nov 2021: Hosted Heart + Mind Festival, used to prototype WISDOM v0 (token allocation)
- Jan 2022: [Open Heart + Mind (OHM)](https://github.com/openheartmind) founded to prototype the model in the safer context of gift-based gatherings
- Feb 2022: Applications to OHM Gathering open, used to prototype WISDOM v1 (structured rubric)
- Mar 2022: Pairwise comparison model proposed to community (WISDOM v2)
- May 2022: Development of WisdOHM app begins (note this app will be open sourced as soon as we can resolve some sensitive data issues in the codebase)
- June 2022: Hosted Tiny OHM, used to prototype WISDOM v2.0 / v2.1 and collect first complete dataset
- June 2023: Hosted OHM Gathering (data collection waiting on app)
- Nov 2023: Presented framework and data at AIMOS conference; AIMOS collaboration begins
- Apr 2024: Presented framework at Vibeclipse; Vibecamp collaboration begins

Note that our first two years of documentation and development were recorded in our transparent Clickup workspace (contact Cooper Smout for access). In March 2024 we began migrating to Github and Github Projects (work in progress).

### Roadmap (work in progress)
- Apr 2024: Networking tour of North America and Colombia
- June 2024: Presenting at SIPS conference (Kenya)
- Sept 2024: OHM Gathering 2024

### About the Founder
Cooper Smout is a designer, data scientist and lifelong student of human behavior. During his PhD (cognitive neuroscience) he became fascinated with the problem of incentivising open science practices and founded the [worlds first collective action platform for researchers](https://freeourknowledge.org/), aiming to overcome cultural inertia through conditional pledges. Drawing on insights from this work, he then designed a novel model for scholarly communication that would aim to incentivise participation by generating prestige through AI-powered open evaluation. Realising that this model was likely too radical for risk-averse academics, and inspired by the creativity of Burning man-style events, he left academia to prototype in the safer, more dynamic and inclusive environment of [gift-based gatherings](https://doc.clickup.com/36615879/d/h/12xdp7-722/0579897aba652af), where he has been dancing and collaborating with amazing humans since. 
