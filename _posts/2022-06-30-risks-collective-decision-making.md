---
layout: post
title:  "Algorithmic Risks to Collective Decision-Making"
author: luke
#categories: [ introduction ]
image: assets/images/gorge.jpg
featured: false
published: true
hidden: false
---

Political and ideological divisions appear to be deepening in some
countries[^1]. Many are concerned that this is increasing the risk of
both *intentional harms*---such as political violence, civil unrest,
doxxing etc.---and *incidental harms*, where society is unable to
respond effectively to external threats such as economic inequality,
climate change, or pandemics. These changes are often attributed to the
rise of recommender systems in online platforms, and other algorithms
that mediate human information flow with increasing ubiquity. In this
piece, I describe the mechanisms by which machine learning algorithms
may be eroding our capacity to collectively make decisions, and discuss
proposed regulatory responses.

# Mechanisms

The first broad class of mechanisms by which algorithms undermine
collective decision-making arise because the algorithms are not
"aligned" with our intentions or values.

This might be because the algorithm performs its task imperfectly. For
example, consider the use of automated classifiers to perform content
moderation on social media. Even if we were able to unambiguously
determine whether a given tweet or Facebook post was permitted under
platform speech policies, any algorithm trained to make such
determinations will always have some margin of error. This leads to a
fairly novel set of regulatory considerations. When laws or regulations
are enforced by algorithms, it becomes possible to be much more precise
about the rates of false positives and false negatives: occasions when
the rule was applied but should not have been, and vice versa. When
constructing regulations with automated enforcement, we should "take
into account the inevitability of error," "choose what kinds of error to
prefer," and "\[calibrate our\] rulemaking to the practical realities of
enforcement."[^2]

It might also be because the algorithm is performing the wrong task,
perhaps because the task is subjective or difficult to define. Again,
this is evident in the realm of automated content moderation. What
categories of online speech, if any, should be amplified or suppressed
in order to best promote long-term societal flourishing? The question
will always be contentious, and simply having the debate can further
fuel animosity and entrench divisions. Often, platforms will elect to
enforce governance policies for which there is lack of evidence. For
example, many of the major platforms have policies against scientific
misinformation relating to COVID-19 vaccines or climate change, despite
there being no evidence that such policies are helpful, and some
evidence they are harmful[^3]. Another prominent case in which societal
divisions may be exacerbated by algorithms performing "the wrong task"
is that of recommender systems in online platforms. Recommender systems
largely determine what information people are exposed to, and almost
without exception are designed to optimise for engagement. That is, they
position most saliently the content that is most likely to generate
observable behaviour such as clicks, reactions, comments, or reshares.
In doing so, they use human behaviour as a proxy for human
preferences[^4]. As a proxy, it is not very good. The most engaging
content is often that which is most outrageous or untrue, or most preys
on our imperfect self-control[^5]. Prioritising such content can lead
people to have distorted perspectives of reality and each other.

It might also be because the algorithm performs its task well enough,
but has side effects. A recommender system that uses reinforcement
learning or is designed with the help of A/B testing may satisfy
people's preferences not by simply giving them more of what they want,
but by altering their preferences so that they are more easily
satisfied[^6]. Increasing reliance on automation to perform tasks that
would traditionally require human reasoning[^7] may lead to an atrophy
of human critical thinking capabilities[^8]. And when algorithmic
gatekeepers to human communication are misaligned, this can create
perverse incentives for those who wish to profit off human attention.
For example, those in Veles, Macedonia who manage politically extremist
Facebook groups targeted at US audiences do so purely to direct users to
third party sites where they are able to collect advertising
revenue[^9]. They have no ideological agenda, but the incentives drive
them to produce content that deepens societal divisions.

The second broad class of mechanisms by which algorithms undermine
collective decision-making arise when the algorithms are "aligned" with
human intentions, but are employed by bad actors. This includes the use
of text and image generation models to generate synthetic media that
mislead audiences and contribute to an apathy with regard to the
question of what is and isn't true. Another example is the use of deep
learning algorithms as persuasion tools, as a means to improve the
targeting of political messaging, conduct information
gerrymandering[^10], or to generate arguments in support of a given
position, regardless of its merits[^11].

# Regulation

Public-interest regulation seems a natural response to concerns about
political division and the quality of civic discourse, which is arguably
a higher order concern than those discussed in the day-to-day news
cycle. But there are a number of challenges. The pervasiveness and
proprietary nature of many algorithmic systems means that it can be
difficult to conduct experiments and accumulate the causal evidence base
required to have a good understanding of how they are and are not
affecting societal division, and to inform and justify proposed
regulation. Attempts to regulate political discourse inevitably skirt
with issues of free expression, and risk violating human rights, or the
First Amendment in the US constitution. Regulatory efforts that are not
designed inclusively risk being politicised, as has been seen in the
case of the GDPR. For these reasons, I believe the most promising
regulatory models are those that do not address division directly but
instead promote trust and inclusive institutions in general.

Mandating certain transparency measures for online platforms is one such
approach. Better public understanding of how recommender systems
operate, for example, and the ability for academics to study their
macroscopic effects, is critical for building multilateral trust in both
platforms themselves and in efforts to regulate them. Currently there is
little scope for this, with platforms shuttering existing transparency
tools[^12] and pursuing legal action against academics doing
public-interest work[^13]. Governments could require that platforms
allow academics and other auditors to access data via physical research
data access centres, modelled on those used by government health
departments, or via APIs that implement privacy preserving features such
as differential privacy. The existence of such measures would
incentivise trustworthy behaviour on the part of online platforms, and
provide an evidence base on which to base future responses.

Another approach is greater experimentation with (and perhaps the
mandated use of) democratic oversight mechanisms for algorithmic
systems. Rahwan (2018)[^14] makes the case for 'algorithmic social
contracts' or 'society-in-the-loop AI'. In the context of mitigating
societal divisions, this might take the form of using sortition-based
citizens assemblies or mini-publics---groups of randomly selected
citizens---to deliberate and advise on algorithmic design decisions and
social media content moderation policies[^15]. Such bottom-up models of
governance have successfully made progress in many politically fraught
domains[^16] and have potential to build trust in the processes by which
algorithmic design decisions are made.

Done well, regulation of AI has benefits not just for the specific
issues being addressed, but for the broader level of social cohesion.
When regulations are written and imposed in ways that are not grounded
in evidence or are undemocratic, this (rightly) erodes trust in
expertise and fuels antipathy between political groups. By regulating
the processes via which algorithmic design decisions are made, we may be
able to mitigate the ways that artificially 'intelligent' systems can
exacerbate societal divisions.

[^1]: Levi Boxell, Matthew Gentzkow + Jesse Shapiro, [Cross-Country
    Trends in Affective
    Polarization](https://doi.org/10.3386/w26669), 2021.

[^2]: Evelyn Douek, [Governing Online Speech: From \'Posts-As-Trumps\'
    to Proportionality and
    Probability](http://dx.doi.org/10.2139/ssrn.3679607),
    2021.

[^3]: The Royal Society, [The Online Information
    Environment](https://royalsociety.org/-/media/policy/projects/online-information-environment/the-online-information-environment.pdf)
    2022.

[^4]: Luke Thorburn, Jonathan Stray + Priyanjana Bengani, [What Does it
    Mean to Give Someone What They Want? The Nature of Preferences in
    Recommender
    Systems](https://medium.com/understanding-recommenders/what-does-it-mean-to-give-someone-what-they-want-the-nature-of-preferences-in-recommender-systems-82b5a1559157),
    2022.

[^5]: Ulrik Lyngs, [Putting Self-Control at the Centre of Digital
    Wellbeing](https://ulriklyngs.com/pdfs/2019-02-08_Lyngs_workshop_digi_wellbeing.pdf),
    2019.

[^6]: Charles Evans + Atoosa Kasirzadeh, [User Tampering in
    Reinforcement Learning Recommender
    Systems](https://arxiv.org/pdf/2109.04083.pdf), 2021.

[^7]: Roxanne El Baff, Henning Wachsmuth, Khalid Al Khatib, Manfred
    Stede + Benno Stein, [Computational Argumentation Synthesis as a
    Language Modeling
    Task](http://dx.doi.org/10.18653/v1/W19-8607), 2019.

[^8]: Lisanne Bainbridge, [Ironies of
    Automation](https://doi.org/10.1016/S1474-6670(17)62897-0),
    1983.

[^9]: Heather Hughes + Israel Waismel-Manor, [The Macedonian Fake News
    Industry and the 2016 US
    Election](https://doi.org/10.1017/S1049096520000992),
    2020.

[^10]: Alexander Stewart, Mohsen Mosleh, Marina Diakonova, Antonio
    Arechar, David Rand + Joshua B. Plotkin, [Information
    gerrymandering and undemocratic
    decisions](https://www.nature.com/articles/s41586-019-1507-6),
    2019.

[^11]: Luke Thorburn + Ariel Kruger, Optimizing Language Models for
    Argumentative Reasoning, forthcoming.

[^12]: Kevin Roose, [Inside Facebook's Data
    Wars](https://www.nytimes.com/2021/07/14/technology/facebook-data.html),
    2021.

[^13]: Russell Brandom, [Facebook shut down German research on
    Instagram algorithm, researchers
    say](https://www.theverge.com/2021/8/13/22623354/facebook-instagram-algorithm-watch-research-legal-threat),
    2021.

[^14]: Iyad Rahwan, [Society-in-the-Loop: Programming the Algorithmic
    Social
    Contract](https://link.springer.com/article/10.1007/s10676-017-9430-8),
    2018.

[^15]: Aviv Ovadya, [Towards Platform Democracy: Policymaking Beyond
    Corporate CEOs and Partisan
    Pressure](https://www.belfercenter.org/publication/towards-platform-democracy-policymaking-beyond-corporate-ceos-and-partisan-pressure),
    2021.

[^16]: Juan Ugarriza + Didier Caluwaerts, [Democratic Deliberation in
    Deeply Divided Societies: From Conflict to Common
    Ground](https://link.springer.com/book/10.1057/9781137357816),
    2014.
