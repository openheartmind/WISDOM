# Design Document

### What is WISDOM?
A generalisable open source framework that diverse communities can use to openly peer-review contributions and recognize contributors on multiple dimensions. 

### How does it work
See README: https://github.com/openheartmind/WISDOM/

### Existing Resources
- WisdOHM (our MVP version that we've been developing to review OHM festivals)
  - React front end
  - Node JS backend
  - Azure database
- [Prototype](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?gid=7517777#gid=7517777)

### Minimal Viable Implementation (preprint review version)
- Enter dimensions (e.g., clarity, rigour, positivity)
- Extract new preprint reviews from preprint API (Sciety? [Zenodo](https://developers.zenodo.org/)?) and apply priors to fresh reviews based on certain review characteristics (e.g., platform, discipline, etc)
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


