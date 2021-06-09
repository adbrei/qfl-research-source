---
title: "Literature Review: ''Federated Learning: Why, What and How''"
author: "Anneliese Brei"
tags: ["Federated Learning"] 
date: "2021-06-09" 
---
-----------------------------
*(Last updated: June 9, 2021)*

So far, the majority of my blog posts concentrate on aspects of Quantum Computing. Today I'd like to shift gears to the other side of my research: Federated Learning (FL). My goal is to glean a better intuitive understanding of the mathematical equations that represent the FL framework. I start with Saheed Tijani's article "Federated Learning: Why, What and How" that was posted on LinkedIn on 14 April 2020.[^1] While this piece does not go into any of the mathematical equations, it introduces the FL framework, thereby serving as a nice overview of the system.

### Summary

---------------
#### The Situation
Much quality data floats around the web. Social media sites harbor images and text with potential for training sophisticated algorithms, such as those leveraged by [AlphaGo](https://en.wikipedia.org/wiki/AlphaGo), a program that in 2015 successfully beat a human champion during a game of Go. Quality data is untapped potential that could train more algorithms to perform exciting tasks.

Strict data protection laws across many parts of the globe restrict programmers' access to this data. To use the data, programmers must ensure that no one's privacy is undermined.

#### Conceptual View of FL
FL is like a federation of states in which a group of partially self-governing states are joined by an overarching form of governance. It is a system of edge devices that individually collect data to train personalized algorithms that are periodically collected to refine an overarching algorithm which is then redistributed.

FL is a type of distributed learning but is different than High Performance Computing (HPC). The motivation behind HPC is to "spread out" a collection of data across multiple machines to reduce time required for learning. FL attempts to reach data from multiple machines, regardless of location, to train its algorithm. Since different types of machines have disjoint data, FL must account for non-IID data.

#### FL Architecture and Process
FL has a curator (the central server) that is in charge of the main training algorithm and coordinating activities with its network of (potentially millions of) edge devices.

1. Curator sends edge devices current global model weights (the learning algorithm);
2. Edge devices learn independently;
3. Edge devices return new individual algorithms to curator;
4. Individual algorithms are aggregated (the weights are averaged);
5. The main training algorithm is updated;
6. The above steps are repeated until an accuracy condition is met or a defined number of cycles is completed.

Notice that FL is best suited for deep learning rather than other types of machine learning. 

During the learning process, data is never transfered from edge devices: only model weights are shared. Hence FL is more secure privacy-wise than other learning frameworks. It is also communcation efficient by greatly reducing the amount of information that needs to be communicated.

#### In the Real World
FL is already being used for applications such as [GBoard](https://blog.google/products/search/gboard-now-on-android/), a next word prediction software that is available on android cellphones. In this case, the curator is the Android server, and the edge devices are all of the mobile devices running the Android operating system.

Potential uses of FL might include an anonymous Bureau of Meteorology, where multiple weather stations observing rainfall share their learned model weights. In this way, the amount of information communicated is greatly reduced, saving time and computational power.

Another use could be a hypothetical linked commercial bank and e-commerce economy. The learning algorithm would be tasked with predicting product purchases and would learn from data collected at both the bank and the economy. Both institutions would train their own (disjoint) models that would be later shared with the curator. No private or individual information is ever shared, so all customers maintain their privacy.

### References
[^1]: Tijani, S., &amp; Follow. (2020, April 14). Federated Learning: Why, What and How? LinkedIn. https://www.linkedin.com/pulse/federated-learning-why-what-how-saheed-tijani. 
