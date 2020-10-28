---
title: "OpenBridgeGraph: Integrating Open Government Data for Bridge Management"
lang: zh
ref: publications/2020-10-14-openbridgegraph-integrating-open-government-data-for-bridge-management
collection: publications
permalink: /publications/2020-10-14-openbridgegraph-integrating-open-government-data-for-bridge-management
excerpt: '本研究提出一种面向桥梁运维管理的开放数据集成模型及方法'
date: 2020-10-14
venue: '2020 Proceedings of the 37th ISARC'
paperurl: 'https://doi.org/10.22260/ISARC2020/0172'
citation: 'Lin, J.R.* (2020). &quot;OpenBridgeGraph: Integrating Open Government Data for Bridge Management&quot; <i>2020 Proceedings of the 37th ISARC</i>. 1255-1262. Kitakyshu, Japan. doi: 10.22260/ISARC2020/0172'

comment: true
category: conference

tags: 
  - data modeling
  - graph database
  - open government data
  - bridge management
  - data integration
  - data retrieval
  - construction
---


{{site.data.ui-text[page.lang].abstract}}
====

Due to limited funds, road authorities around the world are facing challenges related to bridge management and the escalating maintenance requirements of large infrastructure assets. Nowadays, many government organizations have published a variety of data to enable transparency, foster applications, and to satisfy legal obligations. Open governments data like bridge data, weather data would help to better assess the condition of bridges for maintenance purpose and allocation of funds. However, these data sets are fragmented in different systems or formats, and their value in bridge management are not fully explored. This paper proposes a graph-based bridge information modeling framework to integrate open government data for bridge management. The framework represents bridge inventory data as a labeled property graph model and extends the model with weather data. Implementation of the framework employs python scripts for data processing, and neo4j database for data management. The framework is demonstrated using data from national bridge inventory (NBI) and national oceanic and atmosphere administration (NOAA). The results show that the proposed framework can potentially facilitate the integration and retrieval of public government data, and effectively support and provide services to bridge management. Scripts and used data are also shared on GitHub to foster future explorations.

[{{site.data.ui-text[page.lang].download_paper}}](https://doi.org/10.22260/ISARC2020/0172)

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2020-10-14-openbridgegraph-integrating-open-government-data-for-bridge-management.pdf)

[有关代码下载](https://github.com/smartaec/OpenBridgeGraph)

{{site.data.ui-text[page.lang].rec_citation}}: {{page.citation}}

This research is supported by the Tsinghua University Initiative Scientific Research Program (No.2019Z02UOT), the Natural Science Foundation of China (No. 51908323), and the Beijing Natural Science Foundation (No. 8194067). The author also thanks Prof. Kincho Law (Stanford University) for his valuable comments.