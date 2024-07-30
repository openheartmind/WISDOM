# Preprint Meta-Review MVP Scope

### What is WISDOM?
A generalisable open source framework that diverse communities can use to openly peer-review contributions and recognize contributors on multiple dimensions. 

### How does it work
See README: https://github.com/openheartmind/WISDOM/

### Existing Resources
- [WisdOHM](https://github.com/openheartmind/wisdohm) (our MVP version that we've been developing to review OHM festivals)
  - React front end
  - Node JS backend
  - Azure database
- [Prototype](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=7517777#gid=7517777)

### What implementation are we talking about here?
This MVP would be for the implementation pitched in [Cooper's Astera Fellowship application](https://docs.google.com/document/d/1qujEyf75QqM0xms2TX9cbaaEQllkZwjrxhVZ1zAOaME/edit?usp=sharing), where WISDOM is used to meta-review preprint reviews on existing platforms (e.g., PREreview)

### Minimal Viable Implementation
- Enter dimensions (e.g., clarity, rigour, positivity)
- Extract new preprint reviews from preprint API (Sciety? [Zenodo](https://developers.zenodo.org/)?), apply prior values based on preprint review characteristics (e.g., platform, discipline, etc)
- Load priors for existing reviews (mean and standard deviation)
- Select two reviews using pairing algorithm (goal: maximise informational gain)
- Present two reviews side-by-side on screen
- Allow user to select which review best represents a particular dimension
- Record user selection in review comparison matrix
- Generate posterior probabilities for all reviews using [bayesian update algorithm](https://en.wikipedia.org/wiki/Posterior_probability)

### Future features (not implemented in MVI)
- Posterior precision triggers rewards for review (when estimate reaches threshold of precision)
- Dynamically updating Priors for user traits (e.g., reliability, expertise)


### Considerations
- can reviews change? if so need to consider version control


