# WISDOM x AIMOS Conference

AIMOS is a meta-science and open science community who hosted their fifth annual conference at QUT in November 2023. Cooper introduced OHM via a discussion group at the conference and invited participants to join in a new collaboration to review AIMOS contributions under WISDOM. After the conference, AIMOS attendees were sent a survey form inviting them to (a) nominate contributions, (b) consent to having their contributions reviewed, (c) nominate values to be reflected in the study, and (d) self-nominate as a reviewer or research team member.

### Prototype upgrades
We made several upgrades to the prototype, based on learnings from our OHM experiments at OHM. Most notably, we:
- removed sensitive info from backend and condensed multiple sheets into a single sheet
- developed a pre-review process to select a representative sample of diverse contributions
- selected dimensions of interest based on popular response from the community

## Methods & Results
### Materials
- [Contribution Survey form](https://forms.gle/nyAr8baUuQ23FdUK9)
- [WISDOM Prototype](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?usp=sharing), including tabs for [Contribution Record](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1156578512#gid=1156578512), [Reviews](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=7517777#gid=7517777), [Meta-reviews](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1777353795#gid=1777353795) and [Recognition metrics](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1929743917#gid=1929743917))
- [Project board](https://github.com/orgs/openheartmind/projects/1)

### Participants
22 people responded to our Contribution Survey form, including 5 who elected to join the research team and 10 who elected to become reviewers.

### Procedure
These methods will be presented in chronological order using the WISDOM framework stages of Embed values, Record, Review, Recognise, Reward, and Respect.

**0. Embed values.** Survey respondents nominated a range of values to be reflected in this research project. We visualised these responses as a [word cloud](https://drive.google.com/open?id=10N0Z2mfRE1JZ8SjMG4CnT_U2Xju_b9VQ&usp=drive_fs) and agreed to select the 5 most common words as dimensions in this study: _Generosity, Inclusivity, Transparency, Integrity,_  and _Creativity_. We also included _Gratitude_, as this was the only stable baseline dimension in our Tiny OHM Prototype and including it would enable comparison between datasets.

<word-cloud>

**1. Record.** Survey respondents nominated a diverse range of conference contributions, including both visible contributions (e.g., talks, workshops) and less visible contributions that would normally go unnoticed (e.g., administration tasks). One person was nominated who "Made a really big effort during discussion breakouts to attend the group which had the lowest turnout, regardless of their own interests", demonstrating the inclusive nature of WISDOM. 

The research team then completed a pre-review process to select contributions for review. CS estimated the vaue of each contribution in OHMnoms. CS & AF added tags to each contribution. CS & AF created histograms to show diversity of selected contributions. CS selected a range of contributions, aiming to create a normal distribution of OHMnom estimates and a diverse selection of contributors and tags ((see 'preprocessing' tab [here](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?usp=sharing)). 
 

**2. Review.** Ten survey respondents elected to become reviewers, completing a total of 936 pairwise comparison review sets between them. Reviewers completed between 10 and 215 reviews each. Reviewers voted between pairs of conference contributions on the following 6 questions:
- 1-5: "Select the contribution that demonstrates more... Generosity / Inclusivity / Transparency /	Integrity /	Creativity"
- 6: "Overall, which are you more grateful for?"

Meta-reviewers answered just one question when comparing event contributions to review contributions: "Overall, which are you more grateful for?"

**3. Recognise.** _Atomic Reviews_ were awarded one _Gratitude Unit_ each (blue dots) and meta-review votes were used to fit a function to convert votes into Gratitude Units. Gratitude units were then calculated for all other contributions by interpolating this function (red dots). 

<picture>

Scores in the Gratitude dimension were then used to normalise the other five dimensions (e.g., Gratitude Units * Generosity votes / Gratitude votes), generating a multi-dimensional representation of each contribution on the six dimensions of interest.

The Polar Plot below shows each contribution as a coloured line, with scores on each dimension represented as a point on the relevant axis. You can see that "Created website" scored the highest on all dimensions, followed closely by "Create AIMOS-WISDOM prototype" (yes, we recognized our own work in running this study!). Conversely, "Attempting to balance attendance at breakout groups", mentioned above, was one of the lowest scoring contributions, but that person might still appreciate being acknoweldged and recognized for their efforts (see the data in more detail [here](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1929743917#gid=1929743917)).

<picture>

**4. Reward.** TBD.
**5. Respect.** TBD

# Discussion

### Autonomous Valuation
The key point to note here is that no one person was in charge of generating these scores, everyone was invited to participate in an inclusive review protocol that required minimal expertise or time to complete, and all reviewers were _directly and immediately rewarded_ for their valuable review data. The review data and recognition scores are then a public good that could be utilised by users and the community in a myriad of ways.

### Incentivizing contributions
Already, we have the beginnings of an incentive mechanism. Future contributors could use this dataset to predict how their contributions will be received by the community. We also have the beginnings of a <i>replicable template</i>, whereby future conference organizers could use this data to plan and assign tasks to the organizing team, or let the crowd self-select tasks based on their own abilities.  

### An evolving experiment
The AIMOS prototype is a dynamically evolving experiment, much like the WISDOM framework in general. Future work will explore relationships between the dimensions and other [research questions](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1589203329#gid=1589203329), and generate Reward and Respect metrics for our contributors, reviewers and meta-reviewers. If there's any research questions you think we should explore, we'd love to hear from you! 


~~~
Credit: This document was created by copying portions of the [Tiny OHM report](https://github.com/openheartmind/WISDOM/blob/main/reports/v2-1_Tiny-OHM-post-review.md)

