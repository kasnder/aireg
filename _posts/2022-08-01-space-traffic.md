---
layout: post
title:  "AI, Autonomous Systems and Space Traffic Management"
author: rachel
categories: [ space, traffic ]
image: assets/images/posts/space.jpg
featured: false
hidden: false
published: true
---

A niche, but growing use case for AI is in the space context. Recent
developments in the 'New Space' industry have seen increasing
investments into the space sector from state and private actors alike in
recent years, driving new and innovative ventures from both established
industry players and start-ups. From 2010 to 2020, the global space
economy grew by 55% to a value of \$447 billion, of which the commercial
space economy represented nearly 80%[^1]. This dynamic and growing
environment is fertile ground for the development of innovative
technologies and simultaneously demands new solutions for faster,
larger-scale decision-making processes. It is within this environment
that autonomous and artificial intelligence (AI) systems are attracting
a new and increased focus.

As a highly technological field with fundamentally remote operations,
there is a precedent for the use of AI solutions in space technologies,
such as diagnostic parameter monitoring for complex spacecraft and
intelligent object detection for path navigation[^2]. These existing
precedents are all cases where AI is used to enhance existing human
decision-making capability, while still subsidiary to a final,
human-made decision with wider contextual inputs. However, the growing
'New Space' initiatives in the space industry are also driving an
entirely new use case for AI in the contexts of space situational
awareness (SSA) and space traffic management (STM). In a paradigm shift
from historic launch patterns, operators including SpaceX and OneWeb
have now begun to launch 'mega constellations' of up to tens of
thousands of satellites each for commercial telecommunications, with
plans to increase the number of active objects in low-Earth orbit from
around 2,000 to up to 100,000 by the end of the century[^3]. As the
number of objects in orbit grows, it no longer becomes economically or
practically feasible to exclusively control satellites through direct
human tracking and intervention. The successful operation of these
constellations - without collision with either other satellites or
untracked 'space debris' - therefore drives an industry-wide motivation
for operational autonomy for space traffic management.

In this case, AI and machine learning (ML) techniques are applied to
detecting, recognising and avoiding space objects automatically in an
increasingly congested orbital environment[^4][^5]. The fundamental
objective is collision avoidance, but approaches vary for the extent of
autonomy to be used in this process; while some plans would use AI only
for detection and assessment of risk and collision likelihood, deferring
the ultimate manoeuvres to human intervention[^6], other major players
(notably SpaceX) claim to already be performing regular collision
avoidance manoeuvres with no human input at all[^7].The present or
prospective use AI for STM is not limited to commercial enterprises or
mega-constellation projects; the European Space Agency has now launched
its own cornerstone programme for the development of automated manoeuvre
decision-making on board future ESA spacecraft[^8]. However, a lack of
transparency over the proprietary technologies involved complicates any
investigation into the claims and actual extent of the role of AI in
private use cases.

So, with the prospect of machine intelligence integration into many
parts of the space chain[^9] and ongoing research into applications for
SSA and STM, we may anticipate a highly autonomous future for space,
necessitated itself by the scale of ambition for future space
developments[^10]. These increasing use cases of new technologies raise
questions for the application of existing regulations which have no
reference to AI. It will be necessary to clarify the application of
existing space law in the context of autonomous systems, particularly
for cases involving liability, and in some cases to implement new policy
and regulation to address these new capabilities.

## Space law, liability, and the regulation of Artificial Intelligence

The current regulation of space, much like the regulation of the
internet, is the outcome of a long history of efforts beyond national
borders responding reactively to new technologies. Reaching new
agreements in space law is complicated by the need for international
consensus, and consequently no new international space treaties have
entered into force since the Moon Treaty of 1979, or even arguably since
the Registration Convention of 1974, given the limited international
acceptance of the Moon treaty[^11]. This leads to a modern regulatory
framework for space comprised of six treaties, of which for our case
should be taken into consideration the 1967 *Treaty on Principles
Governing the Activities of States in the Exploration and Use of Outer
Space* or 'Outer Space Treaty'[^12], the 1972 *Convention on
International Liability for Damage Caused by Space Objects* or
'Liability Convention'[^13] and the 1975 *Convention on Registration of
Objects Launched into Outer Space* or 'Registration Convention'[^14]. As
there is no set of laws or guidelines applying to autonomy in space in
particular, the use of AI in space will first and foremost be subject to
this existing international space regulation.

Clarification on the 'rules of the road' for autonomous space navigation
is necessitated by the high-stakes nature of satellite operations.
Collisions between satellites may cause damage ranging from instrument
loss, to loss of critical service (e.g. GPS/weather forecasting), to
exponential debris damage to further satellites. Satellites may be
commercial, scientific, or military assets and are considered the
responsibility of the launching nation under the Outer Space Treaty.
Ambiguity over the role and behaviour of AI in any satellite's
operations may therefore lead to strategic and even diplomatic
difficulties in resolution.

In one example, we may imagine a 'closed future' scenario where a
satellite detects, identifies, and avoids another approaching satellite
entirely autonomously, with no human intervention on the part of either
satellite. Under current practice, the identifying operator would
usually contact the other party directly in advance of any manoeuvre and
negotiate a mutual solution[^15]. In this entirely autonomous scenario,
under current space regulations, there is no guarantee that either party
would

a)  notify the other party of a planned manoeuvre (and indeed, with no guarantee of any means of mutual identification/communication)

b)  notify the other party of the planned *direction and manner* of the avoidance manoeuvre

c)  share the same 'collision risk threshold' on deciding whether any manoeuvre is necessary at all

It is easy to see how in this scenario, two satellites with no
information on the other's collision avoidance AI systems may attempt to
avoid a collision and end up colliding anyway via their own manoeuvring
decisions.

And so, the first problem to be addressed for regulation of AI in space
traffic management is the question of transparency and open data.
Openness is of critical importance when it comes to any proper
understanding of a highly autonomous orbital environment.

In her publication "*The Advent of Artificial Intelligence in Space
Activities: New Legal Challenges*"[^16]Anne-Sophie Martin proposes an
addendum to existing registration regulations as a policy solution for
this problem. It is already required under the Registration Convention
that each launching state should report the basic orbital parameters and
function of a space object to the United Nations upon launch of a space
object. Martin proposes the development of an additional 'special'
registry specifying the features of spacecraft with on board AI
capabilities. However, any changes will need to be sensitive to
potential national private interests, e.g. in military technology, and
to the interests of innovating stakeholder companies developing new
in-house technologies.

In practice, the current international law situation means that hard
regulation will be most easily developed on the national or regional
scale, as new space treaties are highly unlikely to emerge and soft
recommendations are limited in power. Some progress is already being
made on this scale; the E.U. is considering a legislative proposal for
space traffic management by the end of 2024, on the basis that the rules
"should also guarantee that the EU operators do not suffer from
distortion of competition by operators established outside the EU
benefiting from less stringent standards, ... by imposing equal
treatment to EU operators and to any satellite operator intending to
provide services within the EU"[^17].

In advance of any new space law, policy makers and industry leaders can
also seek to encourage good practice and openness in commercial
operators through incentives. For example, as part of its Space Safety
Programme, the European Space Agency plans to incentivise industrial
contributions to its new Collision Risk and Automated Mitigation system,
potentially with the objective of then incentivising these industrial
players to unite in using one same, interoperable system[^18].

Satellites and space operations can also lead to large liability issues
in the event of an incident. We have noted that the current use of
autonomous systems in space is limited to 'informing' operators of
collision risks and is still subsidiary to human decisions in most
cases. However, when we consider the 'closed future' case of fully
autonomous space systems, important questions are raised for liability
issues when human judgement is removed from the equation. Under current
space law, the Liability Convention provides a regime for attributing
absolute and fault-based liability to launching states in the case of
damage caused by the launching state's space object. Some literature has
analysed the applicability of this convention to the case of autonomous
space objects. In "*Artificial Intelligence in Space"*[^19], George
Anthony Gal et al note that fault liability under Article III of the
Liability Convention is premised on the "fault of persons" and is
therefore unlikely to apply to artificial intelligences. In *"Autonomous
Space Objects and International Space Law: Navigating the Liability
Gap"*[^20], Ioana Bratu et al raise that historical approaches to the
legal personhood of AI have concluded that it is redundant to give a
legal personality to AI, as harms from fully autonomous technologies can
still be more effectively addressed by attributing responsibility to
existing categories of legal person[^21]. In these cases, it is likely
that a liability gap may arise in space law when attempting to attribute
fault to an entirely autonomous space system.

As liability issues will become relevant in the case of any near-future
scenario collisions, it is important that these liability gaps are
considered appropriately and addressed before these issues become live.
To begin with, it is necessary to map all relevant legal frameworks in
advance of any issue and share a common understanding about how to move
forward in the case of a liability gap. An optimal outcome would see the
Liability Convention revisited and amended for the intersection of
modern technology with all fault-bearing scenarios. However, the current
international situation means that the consensus necessary for such a
revisit is highly unlikely.

## Summary and future considerations

A lack of clarity, legal liability gaps and outdated regulatory
frameworks risk miscommunication and misunderstandings between
autonomously enabled space actors, with potentially large financial and
geopolitical consequences. Potential solutions, whether through updates
to space law, incentives to commercial actors, or through soft
recommendations, should make a priority the development of acceptable
norms and standards of behaviour for autonomous systems in outer space.
The promotion of transparency and due diligence for on-board AI systems
should encourage that there are no wholly 'black box' systems involved
when the assets of other actors are at risk from the decisions of these
systems. Existing guidelines, including the Registration Convention and
the ITU guidelines for the registration of satellite systems[^22] give
some regulatory precedent for assessment of potential launches in this
way. Automated collision scenarios, meanwhile, and their associated
liability gaps can be most easily avoided by maintaining a scope for
human intervention in any satellite manoeuvres and encouraging open
communication with any intention to move.

It is therefore critical to initiate a discussion on the regulation of
autonomous systems in space while still in advance of the widespread
deployment of these systems. Discussions should seek to promote
harmonisation and standardisation of the space law at the international
level for AI liability, 'rules of the road' and quality standards, in
balance with the interests and innovative ambitions of all space object
stakeholders.

[^1]: Space Foundation (2021), <https://www.spacefoundation.org/2021/07/15/global-space-economy-rose-to-447b-in-2020-continuing-five-year-growth/>

[^2]: Forbes, "How Is AI Helping to Commercialize Space?" (2020), <https://www.forbes.com/sites/cognitiveworld/2020/03/21/how-is-ai-helping-to-commercialize-space/?sh=7b2161907c9f>

[^3]: Royal Astronomical Society. "Dark Skies Policy Consultation: response from the Royal Astronomical Society" (2020).

[^4]: Enrico Lagona et al, "Autonomous Trajectory Optimisation for Intelligent Satellite Systems and Space Traffic Management", Acta Astronautica, 194 (2022), pp. 185-201 <https://doi.org/10.1016/j.actaastro.2022.01.027>

[^5]: Sreeja Nag et al, "Prototyping operational autonomy for Space Traffic Management", Acta Astronautica, 180 (2021), pp. 489-506, <https://doi.org/10.1016/j.actaastro.2020.11.056>

[^6]: ESA, "Automating collidion avoidance" (2019), <https://www.esa.int/Safety_Security/Space_Debris/Automating_collision_avoidance>

[^7]: Quartz, "SpaceX's new satellites will dodge collision autonomously" (2019), <https://qz.com/1627570/how-autonomous-are-spacexs-starlink-satellites/>

[^8]: Tim Flohrer et al, "Update on ESA's Space Safety Programme and its Cornerstone on Collision Avoidance" (2020), <https://amostech.com/TechnicalPapers/2020/SSA-SDA/Flohrer.pdf>

[^9]: Hogan Lovells, "Artificial Intelligence and your space business" (2018), <https://www.hoganlovells.com/%7E/media/ai-article-space-09nl.pdf>

[^10]: Anne-Sophie Martin et al, "The Advent of Artificial Intelligence in Space Activities: New Legal Challenges", Space Policy, 55 (2021) 101408 <https://doi.org/10.1016/j.spacepol.2020.101408>

[^11]: UNOOSA, "Space Law" (2022), <https://www.unoosa.org/oosa/en/ourwork/spacelaw/index.html>

[^12]: Treaty on Principles Governing the Activities of States in the Exploration and Use of Outer Space, Including the Moon and Other Celestial Bodies (Jan. 27, 1967) 18 U.S.T. 2410, 610 U.N.T.S. 205

[^13]: Convention on International Liability for Damage Caused by Space Objects (Mar. 29, 1972) 24 U.S.T. 2389, 961 U.N.T.S. 187

[^14]: Convention on Registration of Objects Launched into Outer Space (Nov. 12, 1975) 28 U.S.T. 695, 1023 U.N.T.S. 15

[^15]: K. Merz et al, "Current Collision Avoidance service by ESA's Space Debris Office", (2017) <http://spacedebris2017.sdo.esoc.esa.int>

[^16]: Anne-Sophie Martin et al, "The Advent of Artificial Intelligence in Space Activities: New Legal Challenges", Space Policy, 55 (2021) 101408 <https://doi.org/10.1016/j.spacepol.2020.101408>

[^17]: SpaceNews, "EU lays out plan to bolster space traffic management capabilities" (2022), <https://spacenews.com/european-union-lays-out-plan-to-bolster-space-traffic-management-capabilities/>

[^18]: Tim Flohrer et al, "Update on ESA's Space Safety Programme and its Cornerstone on Collision Avoidance" (2020), <https://amostech.com/TechnicalPapers/2020/SSA-SDA/Flohrer.pdf>

[^19]: George Anthony Gal et al., "Artificial Intelligence in Space."

[^20]: Ioana Bratu et al, "Autonomous Space Objects and International Space Law: Navigating the Liability Gap", Indonesian Journal of International Law (2021), Vol. 18 No. 3 pp. 423-446, Available at SSRN: <https://ssrn.com/abstract=3880911>

[^21]: Publications Office of the European Union, "Liability for Artificial Intelligence and other Emerging Digital Technologies." (Publications Office of the European Union, November 27, 2019), <http://op.europa.eu/en/publication-detail/-/publication/1c5e30be-1197-11ea-8c1f-01aa75ed71a1/language-en/format-PDF>

[^22]: ITU, "Regulation of satellite systems" (2022), <https://www.itu.int/en/mediacentre/backgrounders/Pages/Regulation-of-Satellite-Systems.aspx>
