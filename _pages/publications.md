---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- title: "Publications" -->
# 2022
---


<div>
<strong>CILex: An Investigation of Context Information for Lexical Substitution Methods.</strong> Seneviratne S, Daskalaki E, Lenskiy A, Suominen H. The  29th International Conference on Computational Linguistics (COLING-2022).
<details>
  <summary>Abstract <a href="https://aclanthology.org/2022.coling-1.362.pdf">Full paper</a></summary>
  
<blockquote><p>Lexical substitution, which aims to generate substitutes for a target word given a context, is an important natural language processing task useful in many applications. Due to the paucity of annotated data, existing methods for lexical substitution tend to rely on manually curated lexical resources and contextual word embedding models. Methods based on lexical resources are likely to miss relevant substitutes whereas relying only on contextual word embedding models fails to provide adequate information on the impact of a substitute in the entire context and the overall meaning of the input. We proposed CILex, which uses contextual sentence embeddings along with methods that capture additional \textit{C}ontext \textit{I}nformation complimenting contextual word embeddings for \textit{Lex}ical substitution. This ensured the semantic consistency of a substitute with the target word while maintaining the overall meaning of the sentence. Our experimental comparisons with previously proposed methods indicated that our solution is now the state-of-the-art on both the widely used LS07 and CoInCo datasets with P@1 scores of 55.96% and 57.25% for lexical substitution. The implementation of the proposed approach is available at https://github.com/sandaruSen/CILex under the MIT license.</p></blockquote>

</details>
</div>
<hr>
<div>
<strong>m-Networks: Adapting the Triplet Networks for Acronym Disambiguation.</strong> Seneviratne S, Daskalaki E, Lenskiy A, Suominen H. The 4th Clinical Natural Language Processing Workshop at the Annual Conference of the North American Chapter of the Association for Computational Linguistics (Clinical NLP at NAACL 2022).
<details>
  <summary>Abstract <a href="https://aclanthology.org/2022.clinicalnlp-1.3.pdf">Full paper</a></summary>
  
<blockquote><p>Acronym disambiguation (AD) is the process of identifying the correct expansion of the acronyms in text. AD is crucial in natural language understanding of scientific and medical documents due to the high prevalence of technical acronyms and the possible expansions. Given that natural language is often ambiguous with more than one meaning for words, identifying the correct expansion for acronyms requires learning of effective representations for words, phrases, acronyms, and abbreviations based on their context. In this paper, we proposed an approach to leverage the triplet networks and triplet loss which learns better representations of text through distance comparisons of embeddings. We tested both the triplet network-based method and the modified triplet network-based method with $m$ networks on the AD dataset from the SDU@AAAI-21 AD task, CASI dataset, and MeDAL dataset. F scores of 87.31%, 70.67%, and 75.75% were achieved by the $m$ network-based approach for SDU, CASI, and MeDAL datasets respectively indicating that triplet network-based methods have comparable performance but with only 12% of the number of parameters in the baseline method. This effective implementation is available at https://github.com/sandaruSen/m_networks under the MIT license. </p></blockquote>

</details>
</div>

**Improving Text Simplification with Factuality Error Detection.**. Ma Y, Seneviratne S, Daskalaki E.  Workshop on Text Simplification, Accessibility, and Readability (TSAR-2022 at EMNLP 2022) (Accepted).


# 2021
---
<hr>
<div>
<strong>Comparison of Word and Character Level Information for Medical Term Identification Using Convolutional Neural Networks and Transformers.</strong> Seneviratne S, Lenskiy A, Nolan C, Daskalaki E, Suominen H. Studies in Health Technology and Informatics 2021.
<details>
  

</details>
</div>
<hr>


<div>
<strong>TNNT: The Named Entity Recognition Toolkit.</strong> Seneviratne S, Rodríguez Méndez S, Zhang X, Omran P, Taylor K, Haller A. The 11th Knowledge Capture Conference (KCAP).
<details>
  <summary>Abstract <a href="https://dl.acm.org/doi/abs/10.1145/3460210.3493550">Full paper</a></summary>
  
<blockquote><p>Extraction of categorised named entities from text is a complex task given the availability of a variety of Named Entity Recognition (NER) models and the unstructured information encoded in different source document formats. Processing the documents to extract text, identifying suitable NER models for a task, and obtaining statistical information is important in data analysis to make informed decisions. This paper presents\footnoteThe manuscript follows guidelines to showcase a demonstration that introduces an overview of how the toolkit works: input document set, initial settings, processing, and output set. The input document set is artificial in order to show various toolkit capabilities. TNNT, a toolkit that automates the extraction of categorised named entities from unstructured information encoded in source documents, using diverse state-of-the-art (SOTA) Natural Language Processing (NLP) tools and NER models.TNNT integrates 21 different NER models as part of a Knowledge Graph Construction Pipeline (KGCP) that takes a document set as input and processes it based on the defined settings, applying the selected blocks of NER models to output the results. The toolkit generates all results with an integrated summary of the extracted entities, enabling enhanced data analysis to support the KGCP, and also, to aid further NLP tasks.</p></blockquote>
</details>
</div>
<hr>

# 2019
---

**Concept Discovery through Information Extraction in Restaurant Domain.**. Pathirana N, Seneviratne S, Samarawickrama R, Wolff S, Chitraranjan C, Thayasivam U, Ranasinghe T. 20th International Conference on Computational Linguistics and Intelligent Text Processing (CICLING 2019).


# 2018
---

**Knowledge Building via Optimally Clustered Word Embedding with Hierarchical Clustering. **. Pathirana N, Seneviratne S, Samarawickrama R, Wolff S, Chitraranjan C, Thayasivam U, Ranasinghe T. 15th International Conference on Natural Language Processing (ICON 2018). 



<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->