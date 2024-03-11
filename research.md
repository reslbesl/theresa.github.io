---
layout: page
title: Research
subtitle: Reasoning about Privacy in Large-Scale Data Processing Systems
use-site-title: true
# bigimg: /img/privacy.jpg
---

What does it mean to protect privacy in large-scale data processing systems?

This is the most basic question we need to answer when designing systems that, we claim, are mindful of individuals’ privacy.
A good privacy definition ideally should capture what privacy means to us but at the same time be precise enough so that it can be implemented and validated against.

On a very high level, the goal of my research is to find such a criterion, that strikes the right balance between interpretability and technical precision, is generalisable across data-processing systems but simultaneously adaptable to context-specific privacy concerns.


Design of Privacy Evaluation Frameworks
---
To achieve this goal we develop novel frameworks to reason about privacy in large-scale data processing systems and aim to improve existing approaches to evaluate privacy risk.

As an example, we developed a new [framework](https://github.com/spring-epfl/synthetic_data_release) to quantitatively assess claims about the privacy benefits of synthetic data publishing.
Using our framework, we demonstrated that many of the claims made about the "absolute privacy" ([NHS England](https://data.england.nhs.uk/dataset/a-e-synthetic-data)) synthetic data provides do not hold true.

This is one example that shows how important it is to carefully evaluate the privacy properties of data processing systems.


**Articles**

[Synthetic data – Anonymisation Groundhog Day](https://www.usenix.org/system/files/sec22-stadler.pdf). *Stadler, T.*, Oprisanu, B., & Troncoso, C., USENIX Security (2022)

[Why the search for a privacy-preserving data sharing mechanism is failing](https://www.nature.com/articles/s43588-022-00236-x). *Stadler, T.*, & Troncoso, C., Nature Computational Science (2022)


**Impact**

Our paper on evaluating synthetic data as a privacy mechanism has already had a significant impact. Upon request, I have presented it to practitioners (Financial Conduct Authority, UK), data protection bodies (EDPS, EU level; CNIL, FR),
and academics in diverse disciplines, (e.g, Harvard Privacy Tools Group, Microsoft Research Cambridge, the Alan Turing Institute, or the "Health Sciences and Technology" program at MIT).
Furthermore, the framework implmentation is in use by multiple industrial partners.
and is cited as a reference evaluation framework in high-profile guidelines such an European Commission [JRC Technical Report](https://publications.jrc.ec.europa.eu/repository/handle/JRC128595) or
the European Data Protection Supervision [TechSonar Report 2021/22](https://edps.europa.eu/system/files/2021-12/techsonar_2021-2022_report_en.pdf).


Analysis of Real-World Systems
---
A large part of my research is dedicated to the analysis of real-world systems. 
Examples of this are our comparative analysis of the privacy and security risks of digital proximity tracing systems (a [DP-3T](https://github.com/DP-3T/documents/blob/master/Security%20analysis/Privacy%20and%20Security%20Attacks%20on%20Digital%20Proximity%20Tracing%20Systems.pdf) contribution)
and our [analysis of the potential harms](https://arxiv.org/abs/2103.11958) of the LUCA tracing system.

Analysing the privacy properties of novel complex systems is a challenging task as there are no standardised ways to conduct such an analysis.
The analysis process itself is thus an important part of our research.
It helps us to understand how we reason about privacy in different types of systems and enables us to improve guidelines for practitioners.

Beyond informing our research, our work has had a considerable impact on the design of digital aids for pandemic containment. 


**Articles**

[Preliminary Analysis of Potential Harms in the Luca Tracing  System](https://arxiv.org/pdf/2103.11958.pdf). *Stadler, T.*, Lueks, W., Kohls, K., Troncoso, C., arXiv preprint (2021)

[Privacy and Security Risk Evaluation of Digital Proximity Tracing Systems](https://github.com/DP-3T/documents/blob/master/Security%20analysis/Privacy%20and%20Security%20Attacks%20on%20Digital%20Proximity%20Tracing%20Systems.pdf) - The DP-3T Project, DP-3T GitHub (2020) 


**Impact**

Our work on the LUCA tracing system has received a lot of attention by the German media. Upon request, I have given interviews on the national news of both German public broadcasting stations (tagesthemen, ARD and heute journal, ZDF) and a long-format podcast.

[Warum wollen plötzlich alle LUCA?](https://www.zeit.de/digital/datenschutz/2021-03/corona-app-luca-kontaktverfolgung-einsatz-umstritten-kontakte-politik-lobbyismus). Eva Wolfangel, Die Zeit (2021)

[Luca vs. Datenschutz](https://www.ndr.de/nachrichten/info/podcast4808.html). SheLikesTech, NDR Podcast (2021)


Design of Privacy-Enhancing Technologies
---
I was involved in the development and design of many real-world systems in which privacy played a key role.

As part of the DP-3T project, I helped to develop a protocol for privacy-preserving decentralised proximity tracing that was later adopted by many countries around the world.
At Privitar, I worked with a large number of organisations, across sectors and industries, to find general purpose technologies to enable the ethical and safe use of data. 


**Articles**

[Deploying decentralized, privacy-preserving proximity tracing](https://dl.acm.org/doi/abs/10.1145/3524107). Troncoso, C., Bogdanov, D., Bugnion, E., ... *Stadler, T.* et al., Communications of the ACM (2022)

[Decentralized privacy-preserving proximity tracing](https://arxiv.org/pdf/2005.12273). Troncoso, C., Payer, M., Hubaux, J.P., Salathé, M., Larus, J., Bugnion, E., Lueks, W., *Stadler, T.* et al., arXiv preprint (2020)


**Patents**

[Computer-implemented privacy engineering systens and method](https://patents.google.com/patent/US20200327252A1/en). McFall J.D., Cabot, C.C., ..., *Stadler, T.* et al., US Patent Application, Singapore Granted Patent (2017)

[Method or system for querying a sensitive dataset](https://patents.google.com/patent/US20220277097A1/en). Cabot, C.C., Guinamard, K.F.P, ... *Stadler, T.* et al., US Patent Application (2018)


**Impact**

The work of the DP3T consortium had an immense impact world-wide during the COVID19 pandemic.  

[EU privacy experts push a decentralised approach to COVID-19 contacts tracing](https://techcrunch.com/2020/04/06/eu-privacy-experts-push-a-decentralized-approach-to-covid-19-contacts-tracing/). TechCrunch (2020)

[Germany flips to Apple-Google approach on smartphone contact tracing](https://www.reuters.com/article/us-health-coronavirus-europe-tech-idUSKCN22807J). Reuters (2020)

[Coronavirus apps: the risk of slipping into a surveillance state](https://www.ft.com/content/d2609e26-8875-11ea-a01c-a28a3e3fbd33). Financial Times (2020)

[Keine App mehr, uns alle zu tracken](https://www.zeit.de/digital/datenschutz/2020-04/datenschutz-corona-app-bundesregierung-probleme). Die Zeit (2020)


*Photo by Pixabay from Pexels*