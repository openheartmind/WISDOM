# WISDOM x Tiny OHM #1

Tiny OHM #1 was a gift-based gathering held in Orleigh Park, West End, on 25th June 2022. It was a public event attended by well over 100 people and co-created by our diverse cOHMunity. We tracked and recorded contributions in our transparent workspace, including both the public-facing (e.g., art, music, science and wellbeing offerings) and background tasks that went into the event. 

### Open review model
Prior to the event we conducted a public review of 'headliner' offerings using [WISDOM v2](https://github.com/openheartmind/WISDOM/blob/main/reports/WISDOM_v2.md), leaving out the meta-review component since we only needed to generate a ranked list of the offerings. 

After the event, we conducted another open review of the actual contributions to the event, which included both scheduled and non-scheduled contributions (e.g., food and drink, production). This second dataset included the unique feature of our model, _meta-reviews_, and thus became the first proof-of-concept dataset for the complete WISDOM v2 model.

## Methods
### Materials
- [Post-Tiny OHM Survey TEMPLATE (open access))](https://docs.google.com/spreadsheets/d/1tkwqzx2RmbYZXYHtkanUfepgWaoiAusp5NAXUO5jKNc/edit?usp=sharing)
- [Post-Tiny OHM Survey Backend (restricted)](https://docs.google.com/spreadsheets/d/1Z4Y0bLmKW8koYfsDj0iMaQP9yS4P6-WhScdvgzu4-wE/edit?usp=sharing)


### Participants
16 reviewers from the OHM community. 

### Process
These methods will be presented in chronological order using the WISDOM stages of Record, Review, Recognise, Reward, and Respect 

#### 1. Record
Tiny OHM contributions were recorded in the OHM Clickup workspace. From these records, the research team selected a diverse range of contributions including both contributions to the event and review contributions. 30 contributions were selected, including 27 event contributions (e.g., talks, music, donations) and 3 review contributions (completion of 1, 4 & 16 surveys, respectively). 

#### 2. Review
Reviewers vote between pairs of contributions on multiple dimensions of interest (see Materials above for survey links)

- 35 surveys (26 regular surveys with event contributions only, 9 ’expert’ surveys with event AND review contributions)
- Each survey contains 25 pairs (randomised)
- 4 dimensions per pair (2AFC):
_“Which contribution are you the most grateful for?”
“Which contribution was the most unique?”
“Which offering best supported the OHM vision and mission?”
“Which offering best supported our principle of Diversity and Inclusion?”_

#### 3. Recognise
Algorithms rank and benchmark contributions against pairwise comparisons. Meta-reviewers evaluate dimensions
1. Rank. Votes tallied for each contribution & dimension
2. Benchmark. Surveys awarded 1 OHMnom per pairwise comparison, fitted and used to scale rankings
- 1 survey (25 pairs) = 25 OHMnom
- 4 surveys (100 pairs) = 100 OHMnom
- 16 surveys (400 pairs) = 400 OHMnom
3. Meta-review. Validated experts review rankings and assign weights to each dimension.
4. Amalgamate. OHMnoms = average across meta-reviewer weightings

#### 4. Reward
Contributors are given OHMnoms as a token of gratitude. Excess tokens can be paid forward.
- OHMnoms given to each contributor (_Future: Divide collaborations using secondary review_)
- Subtract Tiny OHM ‘fee’ (average cost per ~111 participants = 77.68 OHMnom)
- Pay it forward use cases (say thanks to someone, gift to community, trade for project funding, etc.)
- Subtract equivalent costs for:
  - OHMniversal Basic Income scheme (3 recipients prior to Tiny OHM, 1 shown in results)
  - Headliner bonuses

#### 5. Respect
Experts and reliable reviewers are identified and acknowledged with numerical indicators.
- Expertise = % of total OHMnoms in field
- Intra-rater reliability = % test-retest (within-subj)
- Inter-rater reliability = % test-retest (between-subj)
- Self-bias = % votes for own contribution / likelihood others vote for own contribution
- _Future: Reliable reviewers earn more OHMnoms for their reviews. Reputation scores as a function of token burns and expertise._

### Results
- [Post-Tiny OHM Results](https://docs.google.com/spreadsheets/d/1HS7HFa9y6PfF61_wTuCAbj9RTHe94VLXulS0pDYgtns/edit?usp=sharing)
- [Video recording](https://youtu.be/NHgG599NoSk?si=CKAcxIM36oMvLlPc) and [slides](https://docs.google.com/presentation/d/1PDAqqHFCZsq3-z8pjbRob9QhcJ7vnTFwHxqXcuwGs2s/edit?usp=sharing) from our presentation at AIMOS 2023 conference
- TBC

- Successes:
  - Autonomous, community-controlled system
  - Transparent, replicable, inclusive, diverse
  - First step toward an autonomous gathering template
- Limitations:
  - Did not identify all participants or contributions 
  - Skewed benchmarking for Uniqueness and Diversity
  - Could be improved with more meta-reviews (e.g., 2 & 8 surveys) or smarter ranking algorithm (e.g., ELO)

### Learnings
1. Inclusive. The survey was rated as moderately easy (28%) or very easy (48%); and comfortable (46%) or neutral (50%), suggesting that the new pairwise comparison format was user-friendly and inclusive. 
2. Time-efficient. A single pairwise comparison took less than one minute to complete on average, meaning that reviewers can add a single datapoint in a modicum of time. 
3. Gratitude is a stable baseline dimension. We also tested Uniqueness, Diversity and Inclusion, and alignment with the OHM Vision, but each of these exhibited instabilities during baselining and were instead baselined against the Gratitude dimension. 

### Next steps
- Algorithm upgrades (ELO, priors)
  - Filter by explosure (cf. pairing algorithm)
  - Pre-vs post-event (‘super predictors’)
  - Reward regulation (e.g., with reliability)
- New dimensions (e.g., Necessity, Creativity, Difficulty, Generosity, Honesty, Clarity, Connection)
- AIMOS prototype


~~~
Credit: This document was created by copying portions of previous documents:
- WISDOM 2.0 Summary in Clickup: https://app.clickup.com/t/2eb2xpn
- Google Slides presentation: https://docs.google.com/presentation/d/1PDAqqHFCZsq3-z8pjbRob9QhcJ7vnTFwHxqXcuwGs2s/edit?usp=sharing

