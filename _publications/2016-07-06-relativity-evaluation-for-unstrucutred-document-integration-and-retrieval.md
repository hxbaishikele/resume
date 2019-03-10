---
title: "A Relativity Evaluation Approach to Unstructured Document Integration and Retrieval for Building Information Modeling"
lang: zh
ref: publication/2016-07-06-relativity-evaluation-for-unstrucutred-document-integration-and-retrieval
collection: publications
permalink: /publication/2016-07-06-relativity-evaluation-for-unstrucutred-document-integration-and-retrieval
excerpt: '本研究提出一种BIM与非结构化文档集成、提取的相关性计算方法。'
date: 2016-07-06
venue: '16th International Conference on Computing in Civil and Building Engineering'
paperurl: 'https://linjiarui.net/files/2016-07-06-relativity-evaluation-for-unstrucutred-document-integration-and-retrieval.pdf'
citation: 'Zhang, Y., Zhang, J.*, Liu, Q. and Lin, J. (2016). &quot;A Relativity Evaluation Approach to Unstructured Document Integration and Retrieval for Building Information Modeling&quot; <i>in Proceedings of the 16th International Conference on Computing in Civil and Building Engineering</i>. 936-942. Osaka, Japan.'

category: conference

tags: 
  - proceedings
  - ICCCBE
---


Abstract
====

A large amount of construction project data is stored in unstructured documents, which are difficult to handle with highly structured Building Information Models (BIMs). This paper aims at proposing a method for unstructured information integration and retrieval based on Industry Foundation Classes (IFC) standard, thus increasing the efficiency of information utilization.  

This research firstly concentrated on mechanisms for evaluating relativity between text and BIM objects by their features. Document features can be represented by key terms extracted from its content/title based on text mining. Similar features of BIM objects can be extracted from their name, type, description, and properties. The correlation indexes are calculated and ranked by establishing a vector space based on the TF-IDF method with features extracted above.  

When integrating documents and model entities, correlation methods based on title and content of documents are provided. Weights of the two indices are determined by fuzzy comprehensive evaluation method, capable of searching a recommended list of correlated entities according to selected documents. After users’ confirmation, the relation between documents and model entities can be established based on IFC standard.  

Furthermore, to improve document retrieval, related documents are analyzed and separated into subsections by subtitles, forming a semi-structured document. Once a model entity is selected, correlation indices of related subsections are calculated by the above-mentioned method, providing a ranked list of related subsections. It is flexible for the users to obtain required information effectively. Additional query information can be specified if needed.  

Finally, an illustrative application shows that the correlation between documents and model entities can be established with the above-mentioned approach, and well-named BIM entities and statements of the documents will improve the accuracy of the method. Hence, unstructured information can be well integrated and retrieved based on the proposed method, thus increasing the efficiency of project information utilization. 

[论文下载地址]({{ site.baseurl }}/files/2016-07-06-relativity-evaluation-for-unstrucutred-document-integration-and-retrieval.pdf)

引用方式: Zhang, Y., Zhang, J.*, Liu, Q. and Lin, J. (2016). &quot;A Relativity Evaluation Approach to Unstructured Document Integration and Retrieval for Building Information Modeling&quot; <i>in Proceedings of the 16th International Conference on Computing in Civil and Building Engineering</i>. 936-942. Osaka, Japan.