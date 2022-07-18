---
layout: post
title: "Regulation of AI: New and Old"
author: konrad
categories: [ regulation, GDPR ]
image: assets/images/posts/new-old.jpg
featured: false
hidden: false
---

*Personalised ads* are one of the most widespread AI applications and
the core of the business models of the largest tech companies -- even
Apple increasingly monetises through advertising. These personalised
ads, in turn, rely on the collection of data about user behaviour at
large scale, so-called *tracking*. Such tracking is widespread on the
web and in apps, and usually takes place without users' awareness let
alone explicit choice.

The *harms* that arise from the ongoing mass-scale collection are varied
and sometimes highly individual. The underlying technologies cannot only
have significant effects on the rights to privacy and data protection,
but also on other fundamental rights, such as the right to
non-discrimination (e.g. when data from mobile tracking is used in AI
systems, such as targeted ads for job offers) or the right to fair and
free elections (e.g. when political microtargeting is used as in the
Brexit vote or the Trump election).

Our research group at Oxford has long been analysing tracking on the web
and in apps. In our 2018 paper "Third Party Tracking in the Mobile
Ecosystem" \[1\], we found in analysing 1 million Android apps that
about 90% of apps could send data to Google, and 40% to Facebook.

## The GDPR, an effective remedy?

Whether or not the GDPR requires consent to tracking (or whether
companies can instead rely on their legitimate interest) is subject to
ongoing debate. However, this debate might miss the point. In February
2022, the Belgian data protection authority found that the most widely
used framework to retrieve consent was in fact not compliant with the
GDPR. Instead, individuals had been bombarded in digital systems by
popups that were not actually ensuring compliance with GDPR ('compliance
theatre'). Data practices that do not protect the fundamental rights of
individuals are unlikely to be legal.

Our research found that the widespread presence of tracking within apps
has seen little change since the introduction of the GDPR in 2018 \[2\].
Nearly 90% of Android apps can share data with Google/Alphabet, around
40% with Facebook/Meta. Since the predominant business model of apps,
relying on ads and tracking, has not changed, neither have the
underlying data practices.

## Tracking, with or without user consent?

Besides the GDPR, another law -- the ePrivacy Directive -- currently
foresees consent to reading and storing information on a user's device
in the EU and UK (unless such is strictly necessary) \[3\]. This could
be seen as a general prohibition of tracking without consent. However,
the UK government is currently considering reforming this obligation to
reduce mindless 'box-ticking', and lower the barriers for tracking;
there is a risk that this reform might weaken the privacy protections
for individuals.

Analysing a random subset of 1,297 apps from the UK Google Play Store
\[3\], we found that 70% of apps send data to known tracking companies
-- at the first app store before the first user interactions. Less than
10% asked for *any* form of user agreement to data tracking. Those apps
that did ask for consent were found to share data with substantially
more companies. Few apps with consent allowed users to refuse consent
while continuing using the app. All of this points to widespread
infringements of the ePrivacy Directive.

In our paper, we also tried to understand some of the reasons for the
apparent lack of consent flows and resulting infringements of UK data
protection law. To achieve this, we examined the online documentation of
the most common third-party tracking libraries in detail. While most
acknowledge that they rely on app developers to obtain consent on their
behalf, they typically fail to put in place robust measures to ensure
this: disclosure of consent requirements is limited; default consent
implementations are lacking; and compliance guidance is difficult to
find, hard to read, and poorly maintained.

## What's next for regulation?

Our research suggests rather widespread infringements of current data
protection law, and that regulators have been struggling to keep up
(partly due to lack of resources) \[2\]. Recently, Apple stepped into
this void of privacy regulation by mandating new opt-in flows for apps
that want to track their users. Apps that would like to access the
Identifier for Advertisers (IDFA), which allows easy cross-app tracking
of users, must now seek prior user consent. Our most recent research
suggests that Apple's measure is effective at improving user privacy,
but is far from perfect and reinforces existing market power of certain
gatekeepers \[4\].

Our research efforts have faced enormous challenges, due to design
decisions of gatekeepers. For instance, Apple encrypts every app by
default on iOS with its FairPlay DRM. The circumvention of this
protection is rather straightforward, but in conflict with strict
copyright laws that apply worldwide. Few exemptions exist, and app
research usually requires the analysis of thousands of apps, leading
researchers to violate this law potentially many times -- or not do the
research at all. As a result, the last large-scale study of privacy in
iOS apps had been done in 2013, despite the fact that iOS remains the
largest mobile operating system in the UK and US. We've been able to
work around some of these barriers using a new method \[4, 5\]. However,
the use of IP and copyright law against researchers remains an enormous
challenge.

Policymakers are currently considering introducing a range of new
regulation of digital technologies. In the UK, there is the Online
Safety Bill; in the EU, the Digital Markets Act and the Digital Services
Act. Article 31 of the planned Digital Services Act is particularly
promising for researchers because it will enable them to analyse
problems with key digital technologies that pose 'systemic risk'.
However, there remain questions around whether these efforts might again
be hampered by understaffed regulators (as we've seen in privacy and
data protection), or clash with existing legislation (e.g. copyright and
IP law).

## Mobile App Extensions

At our research institute, we are trying to develop new ways to mitigate
some of the harms that are currently present in digital technologies
\[6, 7\]. This is rooted in the observations that harms in apps remain
widespread, and that individuals have limited agency in overcoming such
harms in apps that those individuals rely on for their daily lives.

Specifically, we have developed an Android app that allows end-users to
select an app that they find problematic, and then change or remove
problematic parts within this app \[6\]. Our method relies on the
availability of 'extensions' that describe how to alter the behaviour of
other Android apps to reduce harms. This is methodologically similar to
browser extensions on the web: software developers would write these
mobile app extensions and make them available for other individuals to
use.

It is important to note that, with our system, we do not aim to
eradicate all harms in apps from one day to the other. Moreover, we
neither aim nor advocate for a wide adoption of our concrete
implementation. Instead, we envisage that, at some point in the future,
Google and Apple might add explicit support for extension functionality
to their mobile devices, in the same way as desktop browsers already do.
The incentive to do so would be to enable end-users to face fewer harms
in their mobile devices. Apple already does this in its latest iOS 15
but restricts extension functionality so far to the Safari browser,
rather than extending the concept to arbitrary apps.

With mobile app extensions being a new, agency-enabling technology
against digital harms, we believe that our system aligns well with the
theme of the conference, trying to design the future of technology. As a
next step, we intend to conduct a user study with actual smartphone
users and investigate their concerns around problematic app features and
design practices. We would welcome input from the participants of the
conference on the design of our user study.

## References

1.  Binns, R., Lyngs, U., Van Kleek, M., Zhao, J., Libert, T., & Shadbolt, N. (2018). Third Party Tracking in the Mobile Ecosystem. *ACM WebSci 2018*. <https://doi.org/10.1145/3201064.3201089>

2.  Kollnig, K. & Binns, R. & Van Kleek, M. & Lyngs, U. & Zhao, J. & Tinsman, C. & Shadbolt, N. (2021). Before and after GDPR: tracking in mobile apps. *Internet Policy Review, 10*(4). <https://doi.org/10.14763/2021.4.1611>

3.  Kollnig, K., Binns, R., Dewitte, P., Kleek, M. V., Wang, G., Omeiza, D., Webb, H., & Shadbolt, N. (2021). A Fait Accompli? An Empirical Study into the Absence of Consent to Third-Party Tracking in Android Apps. *SOUPS 2021*. <https://www.usenix.org/system/files/soups2021-kollnig.pdf>

4.  Kollnig, K., Shuba, A., Van Kleek, M., Binns, R., & Shadbolt, N. (2022). Goodbye Tracking? Impact of iOS App Tracking Transparency and Privacy Labels. *ACM FAccT 2022*. <https://arxiv.org/abs/2204.03556>

5.  Kollnig, K., Shuba, A., Binns, R., Kleek, M. V., & Shadbolt, N. (2022). Are iPhones really better for privacy? A comparative study of iOS and Android apps. *Proceedings on Privacy Enhancing Technologies, 2022*(2), 6--24. <https://doi.org/10.2478/popets-2022-0033>

6.  Datta, S., Kollnig, K., Shadbolt, N. (2022). Mind-proofing Your Phone: Navigating the Digital Minefield with GreaseTerminator. *ACM IUI 2022*. <https://doi.org/10.1145/3490099.3511152>

7.  Kollnig, K., Datta, S. and Kleek, M. K. (2021). I Want My App That Way: Reclaiming Sovereignty Over Personal Devices. *Extended Abstracts of the 2021 CHI Conference on Human Factors in Computing Systems*. <https://dl.acm.org/doi/10.1145/3411763.3451632>
