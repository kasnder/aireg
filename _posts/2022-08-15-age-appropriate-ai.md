---
layout: post
title: "Age-Appropriate AI: Gaps, Challenges, and What May Future Look Like"
author: ge
categories: [ children, harms ]
image: assets/images/posts/kid.jpg
featured: false
hidden: false
published: false
---

AI algorithms are starting to play a variety of roles in the digital
ecosystems of children - being embedded in the connected toys, apps and
services they interact with on a daily basis[^1]. Such AI systems
provide children many advantages, such as personalised teaching and
learning from intelligent tutoring systems[^2], or online content
monitoring and filtering algorithms that proactively identify
potentially harmful content or contexts before they are experienced[^3].
AI systems in games and entertainment services provide personalised
content recommendations[^4], while social robots power the interactive
characters in ways that make them engaging and human-like[^5]. Going
forward, AI systems will, in all likelihood, become altogether even more
pervasive in children's applications simply due to their sheer
usefulness in creating compelling, adaptive, and personal user
experiences[^6].

Yet, understanding the ways that AI-systems are being used in systems
for children, and their harm and impact is still a new and emerging area
of investigation. On one hand, there exists a growing body of literature
(including research findings, codes of practice, and proposed
legislation) characterising such AI harms across many kinds of
applications (e.g. the White House's Guidance for the Regulation of
Artificial Intelligence[^7], and the EU's proposed Artificial
Intelligence Act[^8]); and on the other, there is a complementary body
of literature focusing on risks to children, which similarly includes
primary research, proposed policies, and codes of practice, such as the
UK ICO's Age Appropriate Design Codes[^9] and UNICEF\'s AI policy for
children[^10]. These diverse efforts have created a confusing outlook
for designers and practitioners to create concrete and safe designs for
children.

## Background

To establish the scope of our investigation we first aim to define what
we mean by "AI for children\'\'. Starting with "AI", the OECD's
Recommendation of the Council of Artificial Intelligence defines AI
systems as "machine-based systems that can, given a set of human defined
objectives, make predictions, recommendations, or decisions that
influence real or virtual environments"[^11]. This definition is cited
by the proposed EU Artificial Intelligence Act (EUAIA)[^12], as well as
the 2020 UNICEF Policy Guidance for AI for Children[^13] and offers a
convenient definition that remains independent of particular
implementation or application. With respect to "AI system", however
there is some divergence among common use; some papers use the term "AI
system" to mean the particular algorithm or subsystem that enables a
particular AI-associated capability (e.g. learning, inference, or
recommendation), while others consider a broader context, namely those
components that enable a specific application-specific capability (e.g.,
voice recognition, face recognition, video content recommendation). In
other contexts, an "AI system" refers to end-user systems that have such
capabilities embedded within them (e.g. intelligent tutoring
systems[^14]). Here, we adopt the latter two, considering both the
specific capabilities and entire end-user systems as AI systems.

## Towards a Code for Age-Appropriate AI Design

The AADC of the UK ICO requires all online services to be used by
children to appropriately safeguard children and support children's
rights[^15]. This is grounded by UNCRC's recognition that children's
rights in all aspects of their life should be guaranteed by appropriate
legal protections[^16]. Although the AADC codes provide strong guidance
for ensuring children's data to be used 'appropriate to their age', we
argue that the application of age-appropriateness may require new
thinking in the area of AI for children.

We believe that having a unified Age Appropriate AI framework, as a part
of existing Age Appropriate Design efforts[^17], could help standards
and regulatory bodies start to ensure that the complex,
multi-dimensional and often difficult-to-anticipate long-term safety
needs of children are met, as technology startups race to bring AI
technical innovations to market[^18]. Appropriately scoped, a regulatory
codes and duties of care that are specific for designing AI for children
could lower the barrier, and in some cases, incentivise innovators to
address a set of core principles, including safety, fairness, inclusion,
long-term impact/sustainability, and privacy.

What might we suggest about assembling a code for AgeAppropriate AI
Design then ? We feel that such a code should be strongly connected to,
and contextualised against both principles for safe and ethical AI, and
those for child-centred and age-appropriate design:

*Fairness, equality, inclusion and access* is derived as a combination
of the fairness & non-discrimination principles and that of universal
inclusion, relating not only to discovering the needs of diverse groups
but also ensuring that all children are treated fairly and equally.
Participatory methods involving children from a variety of backgrounds
and with different abilities have been applied in a variety of contexts
(e.g.[^19]), and should be an essential strategy in creating
human-centred AI for children. Theoretical work in AI and fairness has
focused on statistical approaches to ensure 'black-box' AI classifiers
do not yield allocative harms that disproportionately impact particular
groups[^20]. Work on fairness in a child-centred context, however, has
thus far been scarce. Unfortunately, discovering and mitigating
representative harms may be very difficult in practice due to their
being highly contextual \[67\].

*Transparency* and *accountability* are often brought up together in the
literature. Accountability requires identifying a chain of
responsibility for system (mis)-behaviours, and we believe that this
responsibility should include both algorithmic accountability that is
derived from designs and social accountability that can be contributed
to stakeholders, typically including the professionals or
parents/guardians. Transparency is of great importance within this chain
to make sure everything is easy to understand, and we believe
transparency should not only be about the system itself, but also the
accountability procedures, such as what to do if something went wrong.

Similarly, privacy and manipulation and exploitation are also closely
related. To protect children's privacy refers to two things - respecting
their interpersonal privacy, examples including not showing detailed
online activities of children to their parents[^21]; and implementing
systemic-level privacy, such as applying data minimisation and
privacy-preserving techniques to prevent children's data from being
collected by third parties [^22]. In fact, misuse of data is one of the
main mechanisms that manipulation and exploitation are built upon[^23],
and thus should be prevented appropriately to children's age. That said,
our findings also showed that the use of children's personal information
is sometimes essential for the functioning of many systems, medical
diagnosis systems in particular, and a recent study with developers also
suggested that while they want to respect children's privacy, they have
to make compromises due to limited monetisation options[^24].
Nevertheless, data collection should be strictly minimised for the
purpose needed. On the other hand, it is often considered hard to
determine and judge between 'good' nudging and 'detrimental'
manipulation and exploitation[^25], and although nudging practices can
be used positively for children in applications such as engaging and
motivating them in learning, transparency/accountability of such an
approach or data minimisation principles are not always well-considered
along.

The word 'harm' is centred to safety and safeguarding, that is to ensure
systems would not do harm to children, as well as protect children from
harm. On the other hand though, that has been a long debate on what
indeed counts towards 'harm to children'[^26], and that 'harmful
content' could be subjective and contextual, and thus individual to
identify alone[^27]. Achieving personalised and contextualised
assessment of system effectiveness would yield more informative
outcomes, however, this would often require access to vulnerable
children or specialised learning/medical environment, which can be a
barrier non-trivial to overcome.

Finally, we posit that sustainability in a child-specific context should
refer to supporting the long-term development of children, and in a way
that considers the important aspect of meeting developmental needs of
children. While such age-appropriateness consideration is vital not only
for sustainability, but also across multiple aspects including safety,
safeguarding, privacy, transparency; we argue that to anticipate/design
for developmental needs may be difficult outside learning and education,
where supporting theory and empirical evidence are less well-identified.
We also found that the current evaluation criteria tends to be vague in
terms of what counts as supporting children's long-term development.
Thus including children's voices is increasingly recognised in both
regulatory development[^28] and empirical explorations[^29].

[^1]: 2019\. Generation AI: Establishing Global Standards for Children and AI. <http://www3.weforum.org/docs/WEF_Generation_AI_%20May_2019_Workshop_Report.pdf>

[^2]: Ahmed Fadhil and Adolfo Villafiorita. 2017. An Adaptive Learning with Gamification and Conversational UIs: The Rise of CiboPoliBot. In Adjunct Publication of the 25th Conference on User Modeling, Adaptation and Personalization (Bratislava, Slovakia) (UMAP '17). Association for Computing Machinery, New York, NY, USA, 408--412. <https://doi.org/10.1145/3099023.3099112>

[^3]: N. Kumaresamoorthy and M.F.M. Firdhous. 2018. An APPROACH OF Filtering The Content Of Posts In Social Media. In 2018 3rd International Conference on Information Technology Research (ICITR). 1--6. <https://doi.org/10.1109/ICITR.2018.8736152>

[^4]: Mohamed Heni Frikha, Tarek Zlitni, and Nadia Bouassida. 2020. Towards a Recommendation System for Children's Animated Movies Based on Chromatic Features. In Proceedings of the 2nd International Conference on Digital Tools (Virtual Event, Tunisia) (DTUC '20). Association for Computing Machinery, New York, NY, USA, Article 22, 6 pages. <https://doi.org/10.1145/3423603.3424058>

[^5]: Ginevra Castellano, Iolanda Leite, André Pereira, Carlos Martinho, Ana Paiva, and Peter W. Mcowan. 2014. Context-Sensitive Affect Recognition for a Robotic Game Companion. ACM Trans. Interact. Intell. Syst. 4, 2, Article 10 (June 2014), 25 pages. <https://doi.org/10.1145/2622615>

[^6]: 2020\. The state of AI in 2020. <https://www.mckinsey.com/business-functions/mckinsey-analytics/our-insights/global-survey-the-state-of-ai-in-2020>

[^7]: 2020\. Guidance for Regulation of Artificial Intelligence Applications. <https://www.whitehouse.gov/wp-content/uploads/2020/11/M-21-06.pdf>

[^8]: 2021\. Proposal for a REGULATION OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL LAYING DOWN HARMONISED RULES ON ARTIFICIAL INTELLIGENCE (ARTIFICIAL INTELLIGENCE ACT) AND AMENDING CERTAIN UNION LEGISLATIVE ACTS. <https://eur-lex.europa.eu/legalcontent/EN/ALL/?uri=CELEX:52021PC0206>

[^9]: 2020\. Age appropriate design code. <https://ico.org.uk/media/fororganisations/guide-to-data-protection/key-data-protection-themes/ageappropriate-design-a-code-of-practice-for-online-services-2-1.pdf>

[^10]: UNICEF. 2020. Policy guidance on AI for children. (2020).

[^11]: Karen Yeung. 2020. Recommendation of the council on artificial intelligence (oecd). International Legal Materials 59, 1 (2020), 27--34

[^12]: 2021\. Proposal for a REGULATION OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL LAYING DOWN HARMONISED RULES ON ARTIFICIAL INTELLIGENCE (ARTIFICIAL INTELLIGENCE ACT) AND AMENDING CERTAIN UNION LEGISLATIVE ACTS. <https://eur-lex.europa.eu/legalcontent/EN/ALL/?uri=CELEX:52021PC0206>

[^13]: UNICEF. 2020. Policy guidance on AI for children. (2020).

[^14]: Arthur C Graesser, Xiangen Hu, and Robert Sottilare. 2018. Intelligent tutoring systems. In International handbook of the learning sciences. Routledge, 246--255.

[^15]: 2020\. Age appropriate design code. <https://ico.org.uk/media/fororganisations/guide-to-data-protection/key-data-protection-themes/ageappropriate-design-a-code-of-practice-for-online-services-2-1.pdf>

[^16]: 2020\. General comment No. 25 (2021) on children's rights in relation to the digital environment. <https://www.ohchr.org/EN/HRBodies/CRC/Pages/GCChildrensRightsRelationDigitalEnvironment.aspx>

[^17]: 2020\. Age appropriate design code. <https://ico.org.uk/media/fororganisations/guide-to-data-protection/key-data-protection-themes/ageappropriate-design-a-code-of-practice-for-online-services-2-1.pdf>

[^18]: 2021\. PwC's Global Artificial Intelligence Study: Exploiting the AI Revolution. <https://www.pwc.com/gx/en/issues/data-and-analytics/publications/artificial-intelligence-study.html>

[^19]: Ole Sejer Iversen, Rachel Charlotte Smith, and Christian Dindler. 2017. Child as protagonist: Expanding the role of children in participatory design. In Proceedings of the 2017 Conference on Interaction Design and Children. 27--37.

[^20]: 2020\. Explaining decisions made with AI. <https://ico.org.uk/for-organisations/guide-to-data-protection/key-data-protection-themes/explaining-decisionsmade-with-ai/>

[^21]: Arup Kumar Ghosh, Charles E. Hughes, and Pamela J. Wisniewski. 2020. Circle of Trust: A New Approach to Mobile Online Safety for Families. Association for Computing Machinery, New York, NY, USA,1--14. <https://doi.org/10.1145/3313831.3376747>

[^22]: Zach Jorgensen, Ting Yu, and Graham Cormode. 2015. Conservative or liberal? Personalized differential privacy. In 2015 IEEE 31St international conference on data engineering. IEEE, 1023--1034.

[^23]: M Worledge and M Bamford. 2019. Adtech: Market Research Report. <https://ico.org.uk/media/about-the-ico/documents/2614568/ico-ofcom-adtech-research-20190320.pdf>

[^24]: Anirudh Ekambaranathan, Jun Zhao, and Max Van Kleek. 2021. "Money Makes the World Go Around": Identifying Barriers to Better Privacy in Children's Apps From Developers' Perspectives. In Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems (Yokohama, Japan) (CHI '21). Association for Computing Machinery, New York, NY, USA, Article 46, 15 pages. <https://doi.org/10.1145/3411764.3445599>

[^25]: Jason Borenstein and Ronald C Arkin. 2017. Nudging for good: robots and the ethical appropriateness of nurturing empathy and charitable behavior. AI & Society 32, 4 (2017), 499--507.

[^26]: Heidi Hartikainen, Netta Iivari, and Marianne Kinnula. 2016. Should We Design for Control, Trust or Involvement? A Discourses Survey about Children's Online Safety. In Proceedings of the The 15th International Conference on Interaction Design and Children (Manchester, United Kingdom) (IDC '16). Association for Computing Machinery, New York, NY, USA, 367--378. <https://doi.org/10.1145/2930674.2930680>

[^27]: Teo Keipi, Atte Oksanen, James Hawdon, Matti Näsi, and Pekka Räsänen. 2017. Harm-advocating online content and subjective well-being: A cross-national study of new risks faced by youth. Journal of Risk Research 20, 5 (2017), 634--649.

[^28]: UNICEF. 2020. Policy guidance on AI for children. (2020).

[^29]: Christopher Frauenberger, Judith Good, Wendy Keay-Bright, and Helen Pain. 2012. Interpreting Input from Children: A Designerly Approach. Association for Computing Machinery, New York, NY, USA, 2377--2386. <https://doi.org/10.1145/2207676.2208399>
