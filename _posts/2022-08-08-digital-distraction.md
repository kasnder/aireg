---
layout: post
title: "The Self-Regulation Challenges of Computing Technology"
author: ulrik
categories: [ distraction ]
image: assets/images/posts/distraction.jpg
featured: false
hidden: false
published: false
---

Powerful, portable computing technologies like smartphones and laptops
challenge the ability to control our attention and behaviour. Amidst
constant notifications and AI-powered recommendation feeds that try to
optimise \'engagement\' with digital services, many people find it
difficult to use their devices in the way they want without being
distracted and wasting time[^1]. For example, our work might routinely
take much longer than it should, because we keep interrupting ourselves
to go to social media. Or we might fail to go to bed at the time we
intended, because we get \'sucked in\' by our devices.

There are two main reasons we can find it difficult to self-regulate
digital device use. First, digital services are often deliberately
designed to nudge us into behaving in ways that benefit the developer.
This can take the form of manipulative \'dark patterns\', such as
pre-ticked boxes on shopping sites with deliberately ambiguous wording.
It can also take the more ambivalent form of \'grey patterns\' like
infinitely scrolling feeds that, though they may surface genuinely
valuable content, can act as attention sinks and make us forget our
intentions for use.

Second, the sheer scale of instant access to information, connection, or
entertainment can cause self-regulation difficulties. Psychological
research shows that people who are better at self-regulating, are those
who arrange their environments such that they have fewer temptations
available[^2]. Therefore, if digital devices make everything always
available with minimal effort, this should *in itself* make it difficult
to self-regulate usage.

## Emerging design solutions

The good news is that in recent years, developers and researchers have
experimented with design patterns that support self-regulation. On
online stores for apps and browser extensions, hundreds of \'digital
self-control tools\' now provide interventions that help people stay in
control, for example by blocking apps or hiding distracting website
elements, tracking and visualise use, or providing rewards or
punishments for how devices are used.[^3] Researchers have done
controlled studies with such tools, and a wide range of interventions
have been shown to both change behaviour and make people feel that they
are better able to control their device use[^4].

Different strategies have different likelihoods of success, and depend
to a greater or lesser extent on individual differences in personality
and ecosystem of devices used[^5]. Similarly to the findings in
psychological research, our own accumulating research data from
workshops with hundreds of students at the University of Oxford, suggest
that the most generally useful strategies involve **empowering users to
control how much potentially distracting information they are exposed
to**. For example, being able to hide recommended videos on YouTube, or
use blocking tools to temporarily reduce the functionality of one's
devices to just those apps that are needed for a given task (Lyngs et
al. in prep).

### Platform conditions determine what solutions are available

The extent to which people are able to control the amount of information
in their digital environments differ widely between platforms. The
largest amount of freedom exists on the web, where internet browsers
allow people to customise the look and functionality of any website via
browser extensions. All major browsers now share the cross-browser [Web
Extensions
API](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API)
which allows users to, for example, tailor Facebook to their needs via
injected stylesheets or scripts.

The situation is very different for mobile apps, however, where most
people report self-regulation difficulties. No options currently exist
to change the look or functioning of mobile apps to fit individual user
needs beyond the options developers choose to provide.

Moreover, the tools available for blocking apps or tracking usage differ
dramatically between Android and iOS: On Android, a diverse ecosystem
exists for apps that provide customised app blocking and usage
visualisations, in addition to what Google provides in their \'Digital
Wellbeing\' app. On iOS, Apple takes a much more restrictive approach to
developer permissions, which makes Apple\'s Screen Time tool the only
option to properly block apps or track use.

## Is there a role for regulation?

How might regulation support the availability of design patterns that
support user self-regulation over digital device use? Let us consider
the levels of (i) specific design patterns, (ii) user control over
digital interfaces, and (iii) business models.

### Banning specific design patterns?

Some attempts are currently being made at banning use of specific design
patterns. For example, in relation to the GDPR, the design pattern of
pre-ticked checked boxes has been [ruled](https://curia.europa.eu/juris/document/document.jsf;jsessionid=8944BCAFE078CEF12B4950EA89590324?text=&docid=218462&pageIndex=0&doclang=EN&mode=req&dir=&occ=first&part=1&cid=101112) not to constitute valid consent. Similarly, EU\'s new [Digital Services Act](https://www.consilium.europa.eu/en/press/press-releases/2022/04/23/digital-services-act-council-and-european-parliament-reach-deal-on-a-safer-online-space/) intends to ban \"misleading interfaces known as \'dark patterns\' and
practices aimed at misleading users\".

Banning specific patterns may apply to a small number of obviously
manipulative practices. However, the much larger zone of \'grey
patterns\' commonly used to drive user engagement (e.g., infinitely
scrolling feeds, the selection algorithms that curate those feeds,
autoplay), cannot be addressed through bans. Whereas these patterns may
cause self-regulation difficulties as a side effect, they often do serve
important user needs.

### Mandating increased control over digital interfaces?

An alternative is to mandate greater user control. An example is
underway in the [EU\'s Digital Services Act](https://ec.europa.eu/info/sites/default/files/proposal_for_a_regulation_on_a_single_market_for_digital_services.pdf), which will require very large online platforms that use recommender systems to provide at least one option for algorithmic selection not based on personal profiling.

I wish to suggest a more far-reaching option: As mentioned, users
already have the power on the web to control the appearance and
functionality of websites via browser extensions. Mandating an analogue
of this mobile apps could have radically empower users and allow the
long tail of idiosyncratic \'online harms\' to be addressed in a
bottom-up fashion.

The research project 'GreaseVision' is imagining what this might look
like[^6]. GreaseVision is a technical system to allow end users to
customise interfaces of their mobile apps to suit their needs, including
around factors connected with self-regulation challenges. For example,
users can themselves limit the amount of content on recommender feeds,
change the colour of notification markers, add overlays to particular
types of unwanted content, and so on.

Providing end users a \'right to tinker\', via mandated provision of the
equivalent of browser extensions for mobile apps, could be a highly
impactful way to regulate.

### Making non-exploitative business model more viable

Regulators may also consider a more hands-off approach focused on
business models. Thus, rather than directly intervening on designs,
regulators might try to make it more likely that design patterns
supportive of self-regulation are viable on digital marketplaces.

The underlying issue here is that many of the design patterns that cause
self-regulation difficulties derive from business models that rely on
selling user attention to companies and others who pay to have ads
shown[^7]. Some have argued that digital platforms should be obliged to
provide subscription options that do not rely on targeted advertisement.
A gentler approach is to mandate disclosure of specific practices tied
to business models. For example, Apple recently began to require that
developers disclose on the App Store what user data apps collect. Such
disclosures might make consumers more likely to pay for apps that do not
rely on attention capture and targeted advertisement, analogous to how
organic farming has been supported by labelling that makes consumers
willing to pay a premium.

Finally, a more radical approach is regulation aimed at disrupting
current tech architectures. Sir Tim Berners Lee\'s has proposed
\'re-decentralising the web\' via interlinked \'Personal Online Data\'
(POD) stores kept securely on servers of the user\'s choice[^8]. People
would decide which apps could access the data, and social networks like
Facebook or Instagram be re-implemented as ways to interconnect
individual PODs. Users\' data would not live in data stores owned by the
companies, but in PODs under direct control of individual users who
simply allow specific entities to read and interlink their data into
specific services. A world where PODs were the basic nodes of the web,
might favour market competition around user interfaces and data
interlinkages that effectively support self-regulation. However, the
practical and regulatory obstacles involved in this transformation are
likely to be substantial.

## Conclusion

Digital devices like smartphones and laptops have revolutionised our
world, but the instant connectivity they provide can lead to
self-regulation failure rather than productivity and wellbeing. This is
especially true for individuals who are attentionally vulnerable, for
example children or adults with conditions like ADHD, making this an
important concern for AI regulation.

On the web, browser extensions allow people to customise websites to
their needs, and for example have YouTube without recommended videos. On
mobile platforms, however, users have little control. To support
self-regulation on mobile platforms, governmental regulation banning
specific design patterns is likely to be useful only for obvious cases
of manipulative dark patterns. Mandating greater user control over
digital interfaces, however, could hold great potential to support a
long tail of idiosyncratic user needs. This could take the form of a
\'right to tinker\' that provides users the same control over mobile
interfaces as that which browser extensions enable on the web. Finally,
regulators should require disclosure of data collection practices to
make business models that are not based on attention capture more
viable.

[^1]: Jonathan A. Tran et al., 'Modeling the Engagement-Disengagement     Cycle of Compulsive Phone Use', in *Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems*, CHI '19 (New York, NY, USA: ACM, 2019), 312:1-312:14, <https://doi.org/10.1145/3290605.3300542>

[^2]: Brian M. Galla and Angela L. Duckworth, 'More Than Resisting Temptation: Beneficial Habits Mediate the Relationship Between Self-Control and Positive Life Outcomes', *Journal of Personality and Social Psychology* 109, no. 3 (2015): No Pagination Specified, <https://doi.org/10.1037/pspp0000026>

[^3]: Ulrik Lyngs et al., 'Self-Control in Cyberspace: Applying Dual Systems Theory to a Review of Digital Self-Control Tools', in *CHIConference on Human Factors in Computing Systems Proceedings (CHI 2019)* (New York, NY, USA: ACM, 2019), <https://doi.org/10.1145/3290605.3300361>

[^4]: Ulrik Lyngs, 'Ulysses in Cyberspace: Examining the Effectiveness of Design Patterns for Digital Self-Control' (PhD dissertation, University of Oxford, 2021), ORA, <https://ora.ox.ac.uk/objects/uuid:8940aba0-6255-4244-a8c3-1a5e51a0b63f>

[^5]: Gloria Mark, Mary Czerwinski, and Shamsi T Iqbal, 'Effects of Individual Differences in Blocking Workplace Distractions', in *Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems*, CHI '18 (New York, NY, USA: ACM, 2018), 92:1----92:12, <https://doi.org/10.1145/3173574.3173666>

[^6]: Siddhartha Datta, Konrad Kollnig, and Nigel Shadbolt, 'GreaseVision: Rewriting the Rules of the Interface' (arXiv, 7 April 2022), <http://arxiv.org/abs/2204.03731>; 'Mind-Proofing Your Phone: Navigating the Digital Minefield with GreaseTerminator \| 27th International Conference on Intelligent User Interfaces', accessed 22 May 2022, <https://dl.acm.org/doi/10.1145/3490099.3511152>

[^7]: *Ideas Made to Matter, The Case for New Social Business Models*, Brown, Sara, June 16, 2021, MIT Management Sloan School, <https://mitsloan.mit.edu/ideas-made-to-matter/case-new-social-media-business-models>

[^8]: *Sir Tim Berners-Lee calls for re-decentralisation of web with 'Solid' platform*, Engineering & Technology, Oct 1, 2018, <https://eandt.theiet.org/content/articles/2018/10/sir-tim-berners-lee-calls-for-re-decentralisation-of-web-with-solid-platform/>
