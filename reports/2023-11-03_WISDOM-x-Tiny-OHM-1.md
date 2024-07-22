_Note this is a duplicate of the website post, please keep both updated together. This is simplest by editing here, then copy pasting the formatted text into the Elementor content editor window (white box on the left)_

## WISDOM x Tiny OHM #1

[Tiny OHM #1](https://openheartmind.org/tiny-ohm-1/?preview_id=1&preview_nonce=822c709527&preview=true) was our first opportunity to prototype our new pairwise comparison WISDOM model. Prior to the event, we used a partial version of the [WISDOM v2 model](https://github.com/openheartmind/WISDOM/blob/main/reports/WISDOM_v2.md) to review headline offerings, leaving out meta-reviews since they were not required to rank-order offerings. 

After the event, we conducted another review of actual event contributions, including both scheduled and non-scheduled contributions (e.g., food and drink, production and planning), and using the full WISDOM v2 model so that we could generate relative valuations of all contributions. This second review round is the subject of the below report. 


## Methods & Results

### Materials
- [Post-Tiny OHM Survey TEMPLATE (open access)](https://docs.google.com/spreadsheets/d/1tkwqzx2RmbYZXYHtkanUfepgWaoiAusp5NAXUO5jKNc/edit?usp=sharing)
- [Post-Tiny OHM Survey Backend (restricted)](https://docs.google.com/spreadsheets/d/1Z4Y0bLmKW8koYfsDj0iMaQP9yS4P6-WhScdvgzu4-wE/edit?usp=sharing)
- [Post-Tiny OHM Results](https://docs.google.com/spreadsheets/d/1HS7HFa9y6PfF61_wTuCAbj9RTHe94VLXulS0pDYgtns/edit?usp=sharing)

### Participants
16 members of the cOHMunity self-nominated as reviewers in response to social media posts and personal messages requesting reviewers. 

### Procedure
Methods will be presented in chronological order using the main stages of the OHM model (note that these stages have been [updated since](https://github.com/openheartmind/WISDOM/tree/main)). 

**0. Embed Values.** 
#### 1. Record 
Tiny OHM contributions were recorded in our transparent workspace, from which the research team selected a diverse sample of contributions to undergo review. 30 contributions were selected, including 27 event contributions (e.g., performances, volunteering) and 3 review contributions (completion of 1, 4 & 16 surveys, respectively). 

#### 2. Appreciate
Reviewers voted between pairs of contributions on four dimensions of interest. There were 35 surveys in total: 26 regular surveys containing only event contributions, and 9 meta-review surveys containing event _and_ review contributions. Each survey contained 25 random pairs and was assigned to a single reviewer. Pairings were fully balanced, with every pair combination represented twice ('A vs B', and 'B vs A'). CS nominated 4 questions (dimensions) to ask reviewers and meta-reviewers (same for all surveys), based on OHM values and discussions with the community:
- “Which contribution are you the most **grateful** for?”
- “Which contribution was the most **unique**?”
- “Which offering best supported the **OHM vision** and mission?”
- “Which offering best supported our principle of **Diversity and Inclusion**?”_

#### 3. Honour
Pairwise comparison votes were converted into multidimensional ratings via the following process:
- Votes tallied for each contribution & dimension
- Reviewers awarded _1 Gratitude Unit_ per set of pairwise comparisons (1 survey containing 25 pairs = 25 _Gratitude Units_)
- Meta-review votes for review contributions used to fit a linear function
- Values for all non-review contributions interpolated from function
  - Financial contributions were rated at 0.802 OHMnoms per Australian dollar
- Dimension ratings reviewed by meta-reviewers, who then assigned weights to each dimension (note that [flaws were detected in all but the gratitude dimension](https://docs.google.com/spreadsheets/d/1HS7HFa9y6PfF61_wTuCAbj9RTHe94VLXulS0pDYgtns/edit?gid=2015988523#gid=2015988523).

#### 4. Reward
OHMnoms were calculated as an average across weighted dimension ratings and summed for each contributor. The average 'cost' per participant was estimated (77.68 OHMnoms) and subtracted from each contributors score, serving as a proof-of-concept for an OHMnom-neutral event. Note that this is only an estimate, since we only used a subsample of contributions and contributors. 

#### 5. Respect
Experts and reliable reviewers were identified and acknowledged with numerical indicators. Expertise was calculated as the percentage of total OHMnoms in the category of interest, serving as a proof-of-concept for contributor reputations. Reviewer reliability was calculated across several metrics:
- Intra-rater reliability = % test-retest (within-subjects)
- Inter-rater reliability = % test-retest (between-subjects)
- Self-bias = % votes by self for own contribution / votes by others
Note that in the future, reviewer rewards might be moderated according to reliability, incentivising high-quality, honest reviews.

#### 6. Receive
Financial costs were also subtracted from balances, serving as a proof-of-concept for a pay-it-forward gratitude scheme. Subtracted costs included payments to organisers under the [OHMniversal Basic Income scheme](https://github.com/openheartmind/WISDOM/blob/main/reports/OHMniversal-basic-income-scheme.md) (3 recipients, 1 shown in results) and payments to headline acts. 

## Discussion

### Major Learnings
1. **Inclusive**. The survey was rated as moderately easy (28%) or very easy (48%); and comfortable (46%) or neutral (50%), suggesting that the new pairwise comparison format was user-friendly and inclusive. 
2. **Time-efficient**. A single pairwise comparison took less than one minute to complete on average, meaning that reviewers can add a single datapoint in a modicum of time. 
3. **Gratitude** is a stable baseline dimension. We also tested Uniqueness, Diversity and Inclusion, and alignment with the OHM Vision, but each of these produced skewed results after baselining and were instead baselined against the Gratitude dimension. 

### Next steps
- Algorithm upgrades (ELO, priors, filter by exposure)
- Compare pre-vs post-event (‘super predictors’)
- Present at AIMOS conference 

### Conclusion
This experiment marked the first proof-of-concept for the complete WISDOM v2 model. In general it was a success, demonstrating an autonomous, inclusive, community-controlled system that can generate multidimensional ratings across diverse contributions. We generated estimates for each contribution category, including an OHMnom/$ rate for financial donations. The reviewed contributions represent only a partial sample of all contributions, however, demonstrating a need to improve recording processes and develop more efficient algorithms that can handle more contributions without a full balancing of all contribution pairings. Nevertheless, the results mark our first step toward an autonomous gathering template, which might one day be used to organise similar gatherings in a decentralised, autonomous fashion. 

### EDITS
Additional contributions were added and meta-reviewed following the AIMOS presentation ([recording](https://youtu.be/NHgG599NoSk?si=CKAcxIM36oMvLlPc), [slides](https://docs.google.com/presentation/d/1PDAqqHFCZsq3-z8pjbRob9QhcJ7vnTFwHxqXcuwGs2s/edit?usp=sharing)), including two review contributions (2 & 8 surveys) and another financial contribution ($150). These can be seen in the results spreadsheet but are not reflected in the above text (see report [here](https://github.com/openheartmind/WISDOM/blob/main/reports/WISDOM-x-Tiny-OHM-upgrades.md)).


~~~
Credit: This document was created by copying portions of previous documents:
- WISDOM 2.0 Summary in Clickup: https://app.clickup.com/t/2eb2xpn
- Google Slides presentation: https://docs.google.com/presentation/d/1PDAqqHFCZsq3-z8pjbRob9QhcJ7vnTFwHxqXcuwGs2s/edit?usp=sharing

