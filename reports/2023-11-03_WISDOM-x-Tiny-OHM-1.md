# WISDOM x Tiny OHM #1

Tiny OHM #1 was a gift-based gathering held in Orleigh Park, West End, on 25th June 2022. It was a public event attended by well over 100 people and co-created by our diverse cOHMunity, featuring art, music, science and wellbeing offerings (see [here](https://github.com/openheartmind/WISDOM/blob/main/reports/2022-06-25_Tiny-OHM-1.md) for more details).

### Open review model
In our pre-event 'headliner' review, we used the updated [WISDOM v2 model](https://github.com/openheartmind/WISDOM/blob/main/reports/WISDOM_v2.md) but left out the meta-review component, since we were only interested in generating a ranked list for scheduling purposes. After the event, we conducted another open review of the actual contributions to the event, including both scheduled and non-scheduled contributions (e.g., food and drink, production). This second dataset included the unique feature of our model, _meta-reviews_, and thus became the first proof-of-concept dataset for the complete WISDOM v2 model.

## Methods
### Materials
- [Post-Tiny OHM Survey TEMPLATE (open access)](https://docs.google.com/spreadsheets/d/1tkwqzx2RmbYZXYHtkanUfepgWaoiAusp5NAXUO5jKNc/edit?usp=sharing)
- [Post-Tiny OHM Survey Backend (restricted)](https://docs.google.com/spreadsheets/d/1Z4Y0bLmKW8koYfsDj0iMaQP9yS4P6-WhScdvgzu4-wE/edit?usp=sharing)

### Participants
16 reviewers from the OHM community. 

### Process
These methods will be presented in chronological order using the WISDOM stages of Record, Review, Recognise, Reward, and Respect 

#### 1. Record
Tiny OHM contributions were recorded in the OHM Clickup workspace. From these records, the research team selected a diverse range of contributions including both contributions to the event and review contributions. 29 contributions were selected, including 26 event contributions (e.g., talks, music) and 3 review contributions (completion of 1, 4 & 16 surveys, respectively). 

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
2. Benchmark. Reviewers awarded 1 OHMnom per pairwise comparison set, fitted and used to scale rankings
- 1 survey (25 pairs) = 25 OHMnom
- 4 surveys (100 pairs) = 100 OHMnom
- 16 surveys (400 pairs) = 400 OHMnom
3. Meta-review. Validated experts review rankings and assign weights to each dimension.
4. Amalgamate. OHMnoms = average across meta-reviewer weightings

#### 4. Reward
Contributors are given OHMnoms as a token of gratitude. Excess tokens can be paid forward.
- OHMnoms given to each contributor
- Subtract Tiny OHM ‘fee’ (average cost per ~111 participants = 77.68 OHMnom)
- Subtract equivalent costs for:
  - OHMniversal Basic Income scheme (3 recipients prior to Tiny OHM, 1 shown in results)
  - Headliner bonuses

#### 5. Respect
Experts and reliable reviewers are identified and acknowledged with numerical indicators.
- Expertise = % of total OHMnoms in field
- Reviewer reliability
  - Intra-rater reliability = % test-retest (within-subjects)
  - Inter-rater reliability = % test-retest (between-subjects)
  - Self-bias = % votes by self for own contribution / votes by others
  - Note that in the future, reviewer rewards might be moderated according to reliability, incentivising honesty

# Results
- [Post-Tiny OHM Results](https://docs.google.com/spreadsheets/d/1HS7HFa9y6PfF61_wTuCAbj9RTHe94VLXulS0pDYgtns/edit?usp=sharing)

### Learnings
1. Inclusive. The survey was rated as moderately easy (28%) or very easy (48%); and comfortable (46%) or neutral (50%), suggesting that the new pairwise comparison format was user-friendly and inclusive. 
2. Time-efficient. A single pairwise comparison took less than one minute to complete on average, meaning that reviewers can add a single datapoint in a modicum of time. 
3. Gratitude is a stable baseline dimension. We also tested Uniqueness, Diversity and Inclusion, and alignment with the OHM Vision, but each of these produced skewed results after baselining and were instead baselined against the Gratitude dimension. 

### Next steps
- Algorithm upgrades (ELO, priors, filter by exposure)
- Pre-vs post-event (‘super predictors’)
- Explore more dimensions (e.g., Necessity, Creativity, Difficulty, Generosity, Honesty, Clarity, Connection)
- Present at AIMOS conference 

### Conclusion
This experiment marked the first proof-of-concept for the complete WISDOM v2 model. In general it was a success, demonstrating an autonomous, inclusive, community-controlled system that can generate multidimensional ratings across diverse contributions. The reviewed contributions represent only a partial sample of all contributions, however, demonstrating a need to improve recording processes and develop more efficient algorithms that can handle more contributions without a full balancing of all contribution pairings. Nevertheless, the results mark our first step toward an autonomous gathering template, which might one day be used to organise similar gatherings in a decentralised, autonomous fashion. 

### EDIT
Additional contributions were added and meta-reviewed following the AIMOS presentation ([recording](https://youtu.be/NHgG599NoSk?si=CKAcxIM36oMvLlPc), [slides](https://docs.google.com/presentation/d/1PDAqqHFCZsq3-z8pjbRob9QhcJ7vnTFwHxqXcuwGs2s/edit?usp=sharing)), including two review contributions (2 & 8 surveys) and two financial contributions ($150 & $280). These can be seen in the results spreadsheet but are not reflected in the above text. 


~~~
Credit: This document was created by copying portions of previous documents:
- WISDOM 2.0 Summary in Clickup: https://app.clickup.com/t/2eb2xpn
- Google Slides presentation: https://docs.google.com/presentation/d/1PDAqqHFCZsq3-z8pjbRob9QhcJ7vnTFwHxqXcuwGs2s/edit?usp=sharing

