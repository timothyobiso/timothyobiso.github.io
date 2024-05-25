---
title: "GLAMR: Augmenting AMR with GL-VerbNet Event Structure"
collection: publications
permalink: /publication/glamr
excerpt: 'This paper proposes GLAMR, an extension of AMR.'
date: 2024-05-20
venue: 'LREC-COLING'
paperurl: 'https://aclanthology.org/2024.lrec-main.685.pdf'
citation: 'Tu J., <b>Obiso, T.</b>, et. al. (2024). &quot;GLAMR: Augmenting AMR with GL-VerbNet Event Structure.&quot; <i>Proceedings of LREC-COLING 2024</i>.'
---

This paper introduces GLAMR, an Abstract Meaning Representation (AMR) interpretation of Generative Lexicon (GL)
semantic components. It includes a structured subeventual interpretation of linguistic predicates, and encoding of
the opposition structure of property changes of event arguments. Both of these features are recently encoded in
VerbNet (VN), and form the scaffolding for the semantic form associated with VN frame files. We develop a new
syntax, concepts, and roles for subevent structure based on VN for connecting subevents to atomic predicates. Our
proposed extension is compatible with current AMR specification. We also present an approach to automatically
augment AMR graphs by inserting subevent structure of the predicates and identifying the subevent arguments from
the semantic roles. A pilot annotation of GLAMR graphs of 65 documents (486 sentences), based on procedural texts
as a source, is presented as a public dataset. The annotation includes subevents, argument property change, and
document-level anaphoric links. Finally, we provide baseline models for converting text to GLAMR and vice versa,
along with the application of GLAMR for generating enriched paraphrases with details on subevent transformation
and arguments that are not present in the surface form of the texts.
