---
layout: page
title: Maximilian Boether
permalink: /speakers/maximilian-boether/
nav: false
---

**Affiliation:** ETH Zurich and DatologyAI

**Talk Title:** Efficient data mixing and loading for foundation model training

**Abstract:** State-of-the-art large language and vision models are trained over trillions of tokens that are aggregated from a large variety of sources. As training data collections grow, manually managing the samples becomes time-consuming, tedious, and prone to errors. Yet recent research shows that the data mixture and the order in which samples are visited during training can significantly influence model accuracy. In this talk, I will present Mixtera, a data plane for foundation model training that enables users to declaratively express which data samples should be used in which proportion and in which order during training. Mixtera is a centralized, read-only layer that is deployed on top of existing training data collections and can be declaratively queried. I will also give an outlook onto Zephon, our work-in-progress data loader extending Mixtera's ideas. Zephon enables efficient online stateful n:m transformations, such as packing, while supporting checkpoints and elastically deterministic execution of input data pipelines.

**Bio:** Maximilian Boether is a Ph.D. student at ETH Zurich and a Member of Technical Staff at DatologyAI. At ETH, he is part of the Systems Group and the Efficient Architectures and Systems Lab (EASL), supervised by Ana Klimovic and Gustavo Alonso. His research interests lie at the intersection of systems and data-centric AI. He has published at venues such as SIGMOD, VLDB, MLSys, and ICLR, and contributed to Apertus, Switzerland's national LLM.

**Homepage:** <https://mboether.com/>
