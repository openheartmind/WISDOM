# WISDOM/README

Hi and welcome to the WISDOM project :)

We’re working with open scientists, meta-researchers and developers to build an autonomous value accounting system for estimating the value of community contributions through open peer-review, so that we can empower, connect and celebrate contributors to the commons.  (-> read more)

### How it works
Contributions can be recorded and peer-reviewed by any member of the community. Reviews are completed as pairwise comparisons: voting between pairs of contributions on one or more dimensions of interest to the community. Open source algorithms then convert these data into standardised metrics, which serve to (a) recognise the unique qualities of each contribution, (b) reward contributors automatically, and (c) respect contributors for the value they provide. 

### How is WISDOM different?
The key innovation of WISDOM is the way in which pairwise comparisons are used to peg the value of all other contributions. WISDOM recognises pairwise comparisons as valuable contributions in their own right, assigns them a standard unit of value, and includes them in the contribution set to be reviewed. This gives rise to meta-reviews (reviews of reviews), where one of the two items being compared is itself some number of reviews. Meta-review votes are then used to ‘weight’ the value of regular contributions, producing multidimensional scores where every unit is equivalent to the value of a single pairwise comparison.  (-> read more). 

### Background
WISDOM began life as an Open Science publication model and evolved through real-world experiments at Open Heart + Mind (OHM) to become an adaptable and inclusive framework for use by diverse communities with a range of values and needs.  (-> read more)

### Use cases
WISDOM is designed to be simple yet flexible, so that it can be applied to diverse use cases. At OHM, we’ve explored WISDOM in the context of festivals (e.g., art, food, donations) and open science conferences (e.g., talks, workshops, registration fees), using it both prior to the event (e.g., selecting from a range of proposed musical offerings) and retrospectively (e.g., reviewing both scheduled and spontaneous contributions to a conference).  (-> read more).

### Dog-fooding
In addition to fixed-duration events, WISDOM could also be used to evaluate dynamic contributions to an ongoing project. We intend to prove this concept via the WISDOM project itself, using WISDOM to recognise the full range of project contributions, including but not limited to documents, code, donations, and administration tasks. We also intend to explore the concept of a decentralised autonomous funding system, using WISDOM metrics to distribute any financial contributions that we receive (e.g., donations or grants).

### Minimum Viable Product
We’re focusing our early efforts on a minimal viable product (MVP), which is designed to serve our most proven use case: recognising contributions to an academic conference. The WISDOM MVP will focus on the first three stages of the broader framework (Record, Review, Recognise) and contain the bare minimum of features required for multiple instances to be created and tested. The MVP will have the following core components:

- Well established data model we can use as a basis for any future data analysis.
- Front-end facing application that will engage users with a pairwise comparison voting system. 
- A ‘pairing algorithm’ for assigning contribution pairs to reviewers, and a ‘scoring algorithm’ for assigning values to contributions. These algorithms will be relatively simple for the MVP, but can evolve into more complex algorithms over time. 
- Back-end management server that will manage all collected data and participating users
- Security best practices as we would need to be cautious and mindful of possible cyber security breaches, protecting the data of both users and votes, while also considering the dangers of frauds in the algorithms (Might not make it to MVP but needs a discussion regardless).

Note that we’ve previously built a proof-of-concept MVP that focussed primarily on the Review stage, and will be leveraging this existing codebase for the newer, more comprehensive MVP.

