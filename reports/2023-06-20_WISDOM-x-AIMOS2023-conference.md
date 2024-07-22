## WISDOM x AIMOS 2023
[AIMOS2023](https://openheartmind.org/aimos-conference-and-collaboration/) was both the first conference we presented OHM at and our first opportunity to generalize WISDOM, by peer-reviewing contributions to the AIMOS conference itself. In the months that followed, AIMOS members formed a research team and met online to discuss various issues, prepare the prototype, and send it out for open review (see the [project board](https://github.com/orgs/openheartmind/projects/1) for details). The report below is a summary of this collaborative effort.

## Methods & Results
### Materials
- [Contribution Survey form](https://forms.gle/nyAr8baUuQ23FdUK9)
- [WISDOM Prototype](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?usp=sharing) (including tabs for [Contribution Record](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1156578512#gid=1156578512), [Reviews](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=7517777#gid=7517777), [Meta-reviews](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1777353795#gid=1777353795) and [Recognition metrics](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1929743917#gid=1929743917))
- [Project board](https://github.com/orgs/openheartmind/projects/1)

### Prototype upgrades
We made several upgrades to the prototype, based on learnings from our Tiny OHM prototype. Most notably, we:
- condensed individual surveys into a single spreadsheet so that all reviews and results can be seen together
- developed a pre-review process to select a representative sample of diverse contributions
- selected dimensions of interest based on popular response from the community
- added a dynamically-updating token count to reward reviewers as they completed reviews

### Participants
After the conference, attendees were sent a survey form inviting them to (a) nominate contributions to the conference, (b) consent to having their contributions reviewed, (c) nominate values to be reflected in the study, and (d) self-nominate as a reviewer or research team member. 22 people responded to our Contribution Survey form, including 5 who elected to join the research team and 10 who elected to become reviewers.

### Procedure
These methods will be presented in chronological order using the new WISDOM stages of Value, Record, Review, Recognise, Reward, and Respect.

##### 0. Choose Values
Survey respondents nominated a range of values to be reflected in this research project. We visualised these responses as a semantic word cloud and the research team agreed to use the 5 most popular words as dimensions in this study: _Generosity, Inclusivity, Transparency, Integrity,_  and _Creativity_. We also included _Gratitude_ as the baseline dimension, since this was the only stable baseline dimension in our Tiny OHM Prototype and including it would enable comparison between datasets.

[word-cloud]

##### 1. Record
Survey respondents nominated a diverse range of conference contributions, including both visible contributions (e.g., talks, workshops) and less visible contributions that would normally go unnoticed (e.g., administration tasks). One person was nominated who "Made a really big effort during discussion breakouts to attend the group which had the lowest turnout, regardless of their own interests", demonstrating the inclusive nature of WISDOM. 

The research team then completed a pre-review process to select a subset of contributions for review. CS predicted the vaue of each contribution in Gratitude Units. CS & AF added tags to each contribution. CS & AF created histograms to show diversity of selected contributions. CS then selected a range of contributions, aiming to create a normal distribution across Gratitude scores and a representative sample across contributors and tags (see ['preprocessing' tab](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1750896307#gid=1750896307)). 
 
##### 2. Review
Ten survey respondents elected to become reviewers, completing a total of 936 pairwise comparison review sets (X regular reviews, X metareviews. Reviewers completed between 10 and 215 reviews each. Regular reviewers voted between pairs of conference contributions on the following 6 questions:
- 1-5: "Select the contribution that demonstrates more... Generosity / Inclusivity / Transparency /	Integrity /	Creativity"
- 6: "Overall, which are you more grateful for?"

[review picture]

Meta-reviewers answered just one question when comparing event contributions to review contributions: "Overall, which are you more grateful for?"

[meta-review picture]

##### 3. Recognise
_Atomic Reviews_ were awarded one _Gratitude Unit_ each (blue dots) and meta-review votes were used to fit a function to convert votes into Gratitude Units. Gratitude units were then calculated for all other contributions by interpolating this function (red dots). 

[picture]

Scores in the Gratitude dimension were then used to normalise the other five dimensions (e.g., Gratitude Units * Generosity votes / Gratitude votes), generating a multi-dimensional representation of each contribution on the six dimensions of interest.

The Polar Plot below shows each contribution as a coloured line, with scores on each dimension represented as a point on the relevant axis. You can see that "Created website" scored the highest on all dimensions, followed closely by "Create AIMOS-WISDOM prototype" (yes, we recognized our own work in running this study!). Conversely, "Attempting to balance attendance at breakout groups", mentioned above, was one of the lowest scoring contributions, but that person might still appreciate being acknoweldged and recognized for their efforts (see the data in more detail [here](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1929743917#gid=1929743917)).

[picture]

##### 4. Reward (TBD)

##### 5. Respect (TBD)

## Discussion

### Autonomous Valuation
The key point to note here is that no one person was in charge of generating the ratings, everyone was invited to participate in an inclusive review protocol that required minimal expertise or time to complete, and all reviewers were _directly and immediately rewarded_ for their valuable review data. The review data and recognition scores become a public good that could be utilised by users and the community in a myriad of ways.

### Incentivizing contributions
Already, we have the beginnings of an incentive mechanism. Future contributors could use this dataset to predict how their contributions will be received by the community. We also have the beginnings of a _replicable template_, whereby future conference organizers could use this data to plan and assign tasks to the organizing team, or let the crowd self-select tasks based on their own abilities.  

### Limitations
As with the Tiny OHM prototype, we restricted the review to a subset of all contributions, since reviewing all contributions would result in a combinatorial explosion of pairings under the fully balanced pairwise design. 

## Conclusion
The AIMOS prototype marked the first generalization of WISDOM outside of OHM and proof-of-concept for use in academia. We validated interest in the framework and developed a proof-of-concept for rating diverse contributions to an academic conference. Future conference organisers might find this dataset useful for planning purposes or for recognizing contributors. Future efforts could expand on this prototype to explore other use cases, such as rating contributions to a paper, contributions to a research group, or contributions to an entire research field (e.g., papers, data, code). In all cases, it will be valuable to explore more advanced algorithms that can handle a larger set of contributions without an excessive burden of time on reviewers.

### Work in progress
The AIMOS prototype is a dynamically evolving experiment, much like the WISDOM framework in general. Ongoing work will explore relationships between the dimensions and other [research questions](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=1589203329#gid=1589203329), along with Reward and Respect metrics for contributors and reviewers. If there's any research questions you think we should explore, we'd love to hear from you! 


~~~
Credit: This document was created by copying portions of the [Tiny OHM report](https://github.com/openheartmind/WISDOM/blob/main/reports/v2-1_Tiny-OHM-post-review.md)

