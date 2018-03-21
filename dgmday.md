---
layout: main
title: DGM day
menu: no
---

![logo](/img/events/dgmday/logo.png){: style="float: right; margin: 0px 20px; height: 180px" }
# Deep generative models in NLP


On March 22 2018 we are gathering to present and discuss work on deep generative models (DGMs) and their applications to natural language processing. 
Our schedule will include a tutorial on variational inference and DMGs, research talks, and posters.

**Registration**  we've reached maximum capacity for this event, but we do have a [waiting list](https://docs.google.com/forms/d/e/1FAIpQLSce683Ca4JCnC7Ae22lrMo2TQoTInwTrJlCprchENFBZ9PEcA/viewform?usp=sf_link)

**Location** Room REC E0.15 at Roetersstraat 11, 1018 WB Amsterdam

**Schedule** see below


<iframe src="https://calendar.google.com/calendar/embed?showTitle=0&amp;mode=AGENDA&amp;height=300&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=aci7h1ua23taamdbat5hu73h14%40group.calendar.google.com&amp;color=%23AB8B00&amp;ctz=Europe%2FAmsterdam" style="border-width:0" width="600" height="300" frameborder="0" scrolling="no"></iframe>


# Programme


**Tutorial**

[Variational Inference and Deep Generative Models](https://github.com/philschulz/VITutorial): We start with a tutorial on VI and DGMs which is also a dry-run for a tutorial to be presented at ACL2018. This is a 3h-long tutorial with a 30 minutes coffee break.

**Lunch and posters**

**Research talks I**

<details>
    <summary>
        Bryan Eikema: <i>A joint model for neural machine translation.</i>
    </summary>
    <font color="darkgray">
        Neural machine translation (NMT) relies heavily on the availability of large amounts of sentence aligned parallel data. Not always is sufficient parallel data available for the desired language pair or domain. Vast amounts of monolingual data, however, are almost always available. One effective approach to incorporating monolingual target data in the training of an NMT system is to complete the monolingual data by pairing it with an automatic back-translation as a pre-processing step. However, it is unclear how much of such noisy bilingual data can be added before breaking the translation system. We propose a generative modeling approach by modeling the source and target side of the data jointly using a variational auto-encoder. Hereby we can probabilistically complete the data during training time, while allowing the model to distinguish between actual and synthetic parallel data. We show that our model improves on a standard NMT model with several BLEU points, but does not outperform the automatic back-translation approach. We speculate several causes of this and propose improvements for future work.
    </font>
</details>
<details>
    <summary>
        Philip Schulz: <i>A Stochastic Decoder for Neural Machine Translation.</i>
    </summary>
    <font color="darkgray">
        Neural Machine Translation (NMT) is becoming the dominant paradigm in automatic translation. One of the basic assumptions that still restricts NMT architectures, however, is that there is only one output (a distribution over target sentences) per source sentence. This makes current NMT systems very brittle and indeed their performance deteriorates quickly when they are presented with noisy data. It is also unsatisfying from a statistical perspective: we know that there is lexical and syntactic variation in human-produced translations and not accounting for this variation in our models is a bad design decision.
    In this work, we present a stochastic decoder for NMT that contains a latent variable per target position. The latent variables are intended to capture the noise sources that underlie the observed variation in the produced translations. We use the latent variables as additional inputs when updating the decoder state. This has the following consequences: the decoder state itself is now stochastic and so is the attention mechanism which is a function of the decoder state. The model is implemented as a deep generative model, meaning that the latent distributions are computed by neural network regressors. We show empirically that our model improves translation quality and that it is indeed able to produce varied translations.
    </font>
</details>
<details>
    <summary>
        Ke Tran: <i>Inducing Grammars with and for Neural Machine Translation.</i>
</summary>
    <font color="darkgray">
    Machine translation systems require semantic knowledge and grammatical understanding. Neural machine translation (NMT) systems often assume this information is captured by an attention mechanism and a decoder that ensures fluency.  Recent work has shown that incorporating explicit syntax alleviates the burden of modeling both types of knowledge. However, requiring parses is expensive and does not explore the question of what syntax a model needs during translation. To address both of these issues we introduce a model that simultaneously translates while inducing dependency trees.  In this way, we leverage the benefits of structure while investigating what syntax NMT must induce to maximize performance. We show that our dependency trees are 1. language pair dependent and 2. improve translation quality.
    </font>
</details>

<br>

**Coffee break**

**Research talks II**

<details>
    <summary>
        Miguel Rios: <i>Learning word representations by marginalisation of latent alignments.</i>
    </summary>
    <font color="darkgray">
        This work exploits translation data as a semantically relevant signal for learning word representations. In particular, we exploit translation equivalence as a form of distributed context for jointly learning how to embed and align with a deep generative model, where the latent lexical alignments are marginalized out. Our EmbedAlign model embeds words as posterior probability densities, rather than point estimates, which allows us to compare words in context using a measure of overlap between distributions (e.g. KL divergence). We investigate our model's performance on a range of lexical semantics tasks achieving competitive results on several standard benchmarks including natural language inference, paraphrasing, and text similarity.
    </font>
</details>
<details>
    <summary>
        Wilker Aziz: <i>Implicit models.</i>
    </summary>
    <font color="darkgray">
        <strong>TBA</strong><i></i>
    </font>
</details>
<details>
    <summary>
        <i>TBA</i>
    </summary>
    <font color="darkgray">
        TBA
    </font>
</details>

<br>

**Poster sessions with snacks and drinks**

* Implicit language models
* Learning from monolingual data with REINFORCE
* Latent graphs and permutations for neural machine translation 
* Natural language inference for multiple domains
* TBA
* TBA
* TBA
* TBA

# Contact

The [SLPL lab](https://staff.fnwi.uva.nl/k.simaan/research_all.html) is hosting this event.

Organisers:

* Wilker Aziz
* Miguel Rios
* Philip Schulz
* Khalil Sima'an

Contact persons: [Wilker](mailto:w.aziz@uva.nl) and [Miguel](mailto:m.riosgaona@uva.nl)


This event is supported by the Dutch Organization for Scientific Research (NWO) VICI Grant nr. 277-89-002.

