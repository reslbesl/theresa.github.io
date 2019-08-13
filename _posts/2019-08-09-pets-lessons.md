---
layout: post
title: Three Lessons about PETs
subtitle: What I have learned about privacy-enhancing technologies
image: /img/pets.jpg
tags: [data privacy]
---

15th August will mark 990 days at Privitar for me, and sadly also my last day as an employee there.
I took this as an occasion to write down everything that I have learned about privacy and privacy-enhancing technologies and present it to my colleagues.
Here's a summary of this talk.

Privacy is contextual and blurry
---
The first thing I got to learn after I started working for a software start-up focused on data privacy is all the ways in which privacy is different from security in the context of big data analytics. Of course there are many different approaches to answering this question. However, one of the defining aspects for me is the boundary we draw between valid information flow and a breach of security or privacy.

In security, this distiniction seems pretty clear-cut. There are people authorised to see some information, for example, the human resource department looking up an employees record, and there are malicious actors trying to access data in unintended ways, an ex-employee trying to retrieve data about his former manager, for instance. A system that provides data security will prevent this unintended information flow. Even though this notion of security is used in some privacy-preserving systems, such as anonymous communication systems, as well, it doesn’t extend easily to data privacy in the context of statistical computations.

The complexity in building privacy-preserving data procesing systems often lies in defining what is the information we want to hide versus what is the information we want to extract. This line, the line between valid inference and privacy breach, is blurry and often hard to define up-front. Take a scenario
It further depends on a whole host of contextual factors, such as the type of information shared, the context, the data environment, the person accessing the data, and the analytical goal for which the data is accessed.

It is hard, however, to design technologies that aim to protect what can't be expressed in a formal framework and is so highly contextual.

I quite often found myself saying thins like “Differential Privacy comes with a trade-off”, referring to the accuracy loss incured by differentially private noise addition to protect data releases from unintended disclosures. After a while, however, I realised that this phrase was misrepresenting the actual underlying problem quite substantially. Rather than introducing a new trade-off between accuracy and privacy, the use of the Differential Privacy framework made an existing trade-off visible and quantifiable. People got so used to this framing of the story because for a long time data was considered a free-of-cost resource that could be freely shared without any additional costs. Only after a while, and thanks to the great work of people like Latanya Sweeney and Cynthia Dwork, people started to understand that there was a cost, paid by loss of privacy. PETs alleviate the trade-off  


Privacy-enhancing technologies are very problem-specific
---

*Photo by Dominika Roseclay from Pexels*