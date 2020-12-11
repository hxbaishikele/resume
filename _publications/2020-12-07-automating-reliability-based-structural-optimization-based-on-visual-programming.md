---
title: "A Framework to Automate Reliability-based Structural Optimization based on Visual Programming and OpenSees"
lang: zh
ref: publications/2020-12-07-automating-reliability-based-structural-optimization-based-on-visual-programming
collection: publications
permalink: /publications/2020-12-07-automating-reliability-based-structural-optimization-based-on-visual-programming
excerpt: '以可视化编程和OpenSees为基础，本研究提出一种考虑可靠度的结构优化方法，可自动进行结构模型与荷载样本生成、结构仿真与可靠度计算，从而大幅节约建模、仿真时间，使得探索大规模参数空间成为可能'
date: 2020-12-07
venue: 'Proceedings of the 8th International Conference on Construction Engineering and Project Management (ICCEPM 2020)'
doi: '10.13140/RG.2.2.23831.73126'
paperurl: 'https://doi.org/10.13140/RG.2.2.23831.73126'
citation: 'Lin, J.R.*, Xiao, J., and Zhang, Y. (2020). &quot;A Framework to Automate Reliability-based Structural Optimization based on Visual Programming and OpenSees&quot; <i>Proceedings of the 8th International Conference on Construction Engineering and Project Management (ICCEPM 2020)</i>. 225-234. Hong Kong.'

comment: true
category: conference

tags: 
  - visual programming
  - generative design
  - structural optimization
  - OpenSees
  - reliability-based design
  - automatiion
  - smart design
  - dynamo

grants:
  - 8194067
  - 51908323
  - 2018YFD1100900
  - QNRC2016001
---


{{site.data.ui-text[page.lang].abstract}}
====

基于可靠性的结构优化往往需要设计人员或工程师手动对不同的设计进行建模，这个过程非常耗时且难以充分探索所有可能性。或者，设计师或工程师需要大量时间来学习数学建模和编程技能。因此，本研究提出了一个将生成设计、结构仿真和可靠性理论相结合的框架。利用所提出的框架，可通过可视化编程基于特定组规则和参数来生成各种设计，并通过OpenSees模拟其结构性能。然后，基于仿真结果评估每个设计的可靠性，并找到最佳设计。所提出的框架和原型在钢框架结构的优化中进行了测试，结果表明所提出的方法可集成Dynamo和OpenSees自动评估结构的可靠性，从而大幅节约建模、仿真时间，使得探索大规模参数空间成为可能。

Reliability-based structural optimization usually requires designers or engineers model different designs manually, which is considered very time consuming and all possibilities cannot be fully explored. Otherwise, a lot of time are needed for designers or engineers to learn mathematical modeling and programming skills. Therefore, a framework that integrates generative design, structural simulation and reliability theory is proposed. With the proposed framework, various designs are generated based on a set of rules and parameters defined based on visual programming, and their structural performance are simulated by OpenSees. Then, reliability of each design is evaluated based on the simulation results, and an optimal design can be found. The proposed framework and prototype are tested in the optimization of a steel frame structure, and results illustrate that generative design based on visual programming is user friendly and different design possibilities can be explored in an efficient way. It is also reported that structural reliability can be assessed in an automatic way by integrating Dynamo and OpenSees. This research contributes to the body of knowledge by providing a novel framework for automatic reliability evaluation and structural optimization. 


[{{site.data.ui-text[page.lang].download_preprint}}](https://doi.org/10.13140/RG.2.2.23831.73126)

[{{site.data.ui-text[page.lang].download_paper}}]({{ site.baseurl }}/files/2020-12-07-automating-reliability-based-structural-optimization-based-on-visual-programming.pdf)

{{site.data.ui-text[page.lang].rec_citation}}: {{page.citation}}

This research is supported by the Beijing Natural Science Foundation (No. 8194067), the National Science Foundation of China (No. 51908323), the National Key R&D Program of China (No. 2018YFD1100900), and the Young Elite Scientists Sponsorship Program by China Association for Science and Technology (No. QNRC2016001)

论文集全文[在这](http://www.iccepm2019.com/wp-content/uploads/2020/12/Proceedings-of-ICCEPM-2020.pdf), 本网站也有[备份]({{ site.baseurl }}/files/Proceedings-of-ICCEPM-2020.pdf).