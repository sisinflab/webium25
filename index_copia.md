---
layout: default
---

**\[UPDATE\]** We kindly ask you to fill in this [anonymous form](https://docs.google.com/forms/d/1Am4LBsYtyOVzo3axIRqYOC7vHOB5BQ9aSMyvTsjjF7I/edit) regarding the overall quality of the tutorial. As we are planning to present it to other venues, your feedback might be extremely important for us 🙏🙂

## Abstract

Wearable Devices (WD s), encompassing a spectrum from smartwatches to fitness trackers, continuously furnish a wealth of physiological and activity-related data. This trove of information facilitates the creation of robust user models, offering a dynamic lens into users’daily lives, health patterns, and interaction behaviours. Furthermore, the integration of Brain-Computer Interfaces (BCIs), directly interfacing with neural signals, presents a distinctive vantage point into cognitive processes and emotional states. This integration enriches user models, providing a profound understanding of mental states and engagement levels. While BCIs cannot be strictly categorized as WD s, the latest hardware developments are reaching a size comparable to earphones, anticipating their wearable integration in the near future. However, the exploitation of data from these devices for user modelling and profiling, enhancing personalized activities such as music listening and movie watching, remains an area ripe for exploration.
This workshop proposes an in-depth exploration of the transformative impact that data from WDs and BCIs can exert on user
modelling. This initiative seeks to pave the way for a nuanced comprehension of individual preferences, cognitive states, and overall user experiences. The workshop invites researchers, practitioners, and enthusiasts to the convergence of wearable technology, BCIs, and user modelling. Through interactive sessions and discussions, participants will delve into the methodologies, challenges, and opportunities associated with harnessing data from these innovative sources. By fostering collaboration and facilitating knowledge exchange, the workshop aims to propel the current understanding of user modelling by exploiting WD s and BCIs. Attendees will acquire insights into cutting-edge research findings, practical applications, and potential future developments within this rapidly evolving field. Ultimately, the workshop aspires to inspire new research directions, catalyze interdisciplinary collaborations, and cultivate innovative solutions that leverage the synergy between wearable technologies and BCIs to elevate the field of user modelling to unprecedented heights.

## Tutorial schedule

Total tutorial duration: 180 minutes

<div class="button-container">
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/introduction/" class="button">Pt.0 Introduction</a>
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/reproducibility/" class="button">Pt.1 Reproducibility</a>
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/graph_topology/" class="button">Pt.2 Graph Topology</a>
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/node_representation/" class="button">Pt.3 Node Representation</a>
</div>

**[Introduction and background](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/Part0.pdf)** (_Tommaso Di Noia_): 20 minutes

+ Introduction and motivations of the tutorial: 5 minutes
+ Basics concepts of recommender systems & GNNs-based recommendation: 15 minutes

**[Reproducibility](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/Part1.pdf)** (_Claudio Pomo_): 60 minutes

+ **\[[Hands-on #1](https://colab.research.google.com/drive/1_li7RQ_Rj4JaAVpw1kvuOGhrDpfCL-UQ?usp=sharing)\]** Implementation and reproducibility of GNNs-based recsys in Elliot with PyG and reproducibility issues: 35 minutes
+ Performance comparison of GNNs-based approaches to traditional recommendation systems: 25 minutes

**Break and Q&A**: 15 minutes

**[Graph topology](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/Part2.pdf)**: 30 minutes

+ Concepts and formulations of graph topological properties of the user-item graph (_Tommaso Di Noia_): 15 minutes
+ Impact of topological graph properties on the performance of GNNs-based recommender systems (_Daniele Malitesta_): 15 minutes

**[Node representation](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/Part3.pdf)** (_Daniele Malitesta_): 45 minutes

+ Design choices to train node embeddings from scratch: 20 minutes
+ **\[[Hands-on #2](https://colab.research.google.com/drive/1socyjwzmYNAm3trlquAevq-R1d4zX3KH?usp=sharing)\]** Leveraging item's side-information (e.g., multimodal features) to represent node embeddings: 25 minutes

**Closing remarks and Q&A**: 10 minutes

## Additional useful material

| Title | Paper                                                                                     | Slides                                                                                    | Code                                                           | Venue     | Year |
|---|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|----------------------------------------------------------------|----------|------|
| How Neighborhood Exploration Influences Novelty and Diversity in Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/MORS.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/MORS.pdf)   | [link](https://github.com/sisinflab/Novelty-Diversity-Graph)   | MORS @ RecSys  | 2022 |
| Auditing Consumer- and Producer-Fairness in Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/ECIR.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/ECIR.pdf)   | [link](https://github.com/sisinflab/ECIR2023-Graph-CF)         | ECIR           | 2023 |
| An Out-of-the-Box Application for Reproducible Graph Collaborative Filtering extending the Elliot Framework | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/UMAP.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/UMAP.pdf)   | [link](https://github.com/sisinflab/Graph-Demo)                | UMAP/GLB @ KDD | 2023 |
| Challenging the Myth of Graph Collaborative Filtering: a Reasoned and Reproducibility-driven Analysis | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/RecSys.pdf) | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/RecSys.pdf) | [link](https://github.com/sisinflab/Graph-RSs-Reproducibility) | RecSys         | 2023 |
| A Topology-aware Analysis of Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/arXiv.pdf)  |                                                                                           | [link](https://github.com/sisinflab/Graph-Characteristics)     | arXiv          | 2023 |
| Disentangling the Performance Puzzle of Multimodal-aware Recommender Systems | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/KDD.pdf) | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/KDD.pdf) | [link](https://github.com/sisinflab/MultiModal-Eval) | EvalRS@KDD | 2023 |
| On Popularity Bias of Multimodal-aware Recommender Systems: a Modalities-driven Analysis | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/MM.pdf)     |  [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/MMIR.pdf)                                                                                          | [link](https://github.com/sisinflab/MultiMod-Popularity-Bias)  | MMIR @ MM      | 2023 |
| Formalizing Multimedia Recommendation through Multimodal Deep Learning | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/TORS.pdf)   |                                                                                           | [link](https://github.com/sisinflab/Formal-MultiMod-Rec)                                                       | arXiv          | 2023 |

## Tutorial speakers

### Daniele Malitesta

_Ph.D. Candidate at Polytechnic University of Bari (Italy)_

Email: [daniele.malitesta@poliba.it](mailto:daniele.malitesta@poliba.it)

Website: [https://danielemalitesta.github.io/](https://danielemalitesta.github.io/)

<img src="https://danielemalitesta.github.io/images/profilo_new.jpeg" alt="Daniele Malitesta"  width="200"/>

### Claudio Pomo

_Research Fellow at Polytechnic University of Bari (Italy)_

Email: [claudio.pomo@poliba.it](mailto:claudio.pomo@poliba.it)

Website: [https://sisinflab.poliba.it/people/claudio-pomo/](https://sisinflab.poliba.it/people/claudio-pomo/)

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/image2-1197215127-scaled.jpg" alt="Claudio Pomo"  width="200"/>

### Tommaso Di Noia

_Professor of Computer Science at Polytechnic University of Bari (Italy)_

Email: [tommaso.dinoia@poliba.it](mailto:tommaso.dinoia@poliba.it)

Website: [https://sisinflab.poliba.it/people/tommaso-di-noia/](https://sisinflab.poliba.it/people/tommaso-di-noia/)

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/t_dinoia-506699224-315x270.png" alt="Tommaso Di Noia"  width="200" />
