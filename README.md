<img src="https://cached-fe.84000.co/imgs/logo.svg" alt="84000 logo" width="200"/>
Translating the Words of the Buddha

# 84000/data-translation-memory

# 84000 Translation Memory files

## Explanation of file versions “-v1”, “-v2”, etc.. :
The versions listed after the file names reflect the method for generating the TM:
- “-v1”, **creationtool="84000-translation-memory"** - these were created manually using an early 84000 app around 2018 that highlighted segments in the source and target. There may some gaps between segments a slightly messy data. Segments have ids according to Tibetan folio.  
- “-v2”, **creationtool="InterText"** - these were created manually using the InterText method documented [here](https://github.com/84000/translation-memory-resources/wiki/TM-Editor-Guidelines#1-instructions-for-aligning-tms-from-pre-segmented-text-files-using-intertext). Contains some tags from the original TEI. Source segments include tags for Tibetan folio references, and the target segments contain tags for milestones and notes with ids. Segments that were translated from an alternate source but still matched to the Tibetan Degé e-text are marked as type=”alternative-source”. The segmentation should be more consistent than v1 as we attempted to follow a standard as much as was pragmatically possible. Segments have ids according to Tibetan folio.  
- “-v3”, **creationtool="linguae-dharmae/84000"** - these were created with machine alignment using Mitra. These alignment should be approximately 90% accurate. All TMs created in 2023 onward will include tags from the original TEI including the Tibetan folio references in the source and tags for notes and milestones in the target; however, TMs created before 2023 do not include these tags. Segments have ids according to the milestones in English translation.  
- “-v4” **creationtool="monlam-ai/84000"** - these were created by manually post correcting the machine alignment from Mitra, and should be 99-100% accurate. They include all the tags from the original TEI mentioned above. Segments have ids according to the milestones in English translation. We intend to eventually update all the v3 TMs to v4. 

## Terms of Use
**Last revised on June 14, 2023**
84000 operates the data sharing, published translation and Reading Room source code service, which we hope you use.

The Terms of Service can change at any time. We’ll warn you 30 days in advance of any changes. We’ll try to warn you about major changes to the Terms of Service, but we make no guarantees.

That’s the basic idea, but you must read through the entire Terms of Service below and agree with all the details before you use any part of the service.
# Reuse of these terms
This document is an adaptation of the Heroku Terms of Service (http://legal.heroku.com/tos), which in turn is an adaptation of the Google App Engine Terms of Service (http://code.google.com/appengine/terms.html). The original work has been modified with permission under the Creative Commons Attribution 3.0 License (http://creativecommons.org/licenses/by/3.0/). Neither Heroku, Inc. nor Google, Inc. is connected with or sponsors or endorses 84000 or its use of the work.

You’re welcome to adapt and use this document for your own needs. If you make an improvement, we’d appreciate it if you would let us know so we can consider improving our own document.
# Your agreement with 84000
Your use of the 84000 service is governed by this agreement (the “Terms”). “84000” means 84000: Translating the Words of the Buddha. The “Service” means all the services 84000 makes available including:
1. Translation data 
    - a. Metadata in RDF on https://github.com/84000/data-rdf 
    - b. TEI on https://github.com/84000/data-tei 
    - c. Translation memory on https://github.com/84000/data-translation-memory 
    - d. Glossaries and other translation data at https://read.84000.co/glossary/downloads.html 
2. Published content   
    - a. Translations in the reading room in HTML, PDF and ePub on  https://read.84000.co/ 
    - b. Translation harvesting in multiple formats via multiple web-accessible endpoints
    - c. Website content on https://84000.co
3. Source code and scripts
    - a. https://github.com/84000/exist-apps 

Recognizing that future engagement with the Tibetan Kangyur and its commentaries (Tengyur)—the root from which all Himalayan Buddhist traditions originate—was in danger, the seed for 84000 was planted with the mandate to make one of the world’s largest archives of wisdom freely and easily accessible for this generation and the next. And so began a project of all Buddhists, for all Buddhists and beyond.

84000 accomplishes its mission through two programs: translation for preservation and engagement through open access.  With a strong editorial research team, we work collaboratively with translators around the world to ensure accurate and credible translations of classical Tibetan Buddhist texts will form a cohesive canon upon completion. We offer the world free access to this entire collection presented online and made intuitively navigable through the use of new publication and data sharing technologies such as interactive glossaries, embedded bilingual source text views, advanced filters, and intertextual linkages as well as application programming interfaces and linked open data. More about our [guiding principles](https://84000.co/about/guiding-principles).

The adoption and use of technology has fundamentally informed 84000’s mission. 84000 has carefully established a technical program that uses innovation to advance its program, including the development of text encoding standards, modern digital publication strategies and open data. The recent advent of artificial intelligence will revolutionize the field of translation and 84000 seeks to use these technical achievements in service of its mission.

In order to use the Service, You (the “Customer,” “You,” or “Your”) must first agree to the Terms. You understand and agree that 84000 will treat Your use of the Service as acceptance of the Terms from that point onwards.

84000 may make changes to the Terms from time to time. You may reject the changes. You understand and agree that if You use the Service after the date on which the Terms have changed, 84000 will treat Your use as acceptance of the updated Terms.

If you have any questions about the Terms, please contact us at info@84000.co.
## Use of the service
### General provisions
- You agree to attribute 84000 if any part of the service is used externally to 84000.
- You agree not to engage in any activity that interferes with or disrupts the service.
- 84000 reserves the right to enforce quotas and usage limits (to any resources) at its sole discretion, with or without notice, which may result in 84000 disabling or throttling your usage of the service for any amount of time.
- You may not allow multiple people to use the same account.

### Specific service provisions
- Translation data is made available to external partnerships for their own use according to the restrictions below. 84000 requires that each project create a supporting written agreement in consultation with 84000 to ensure that the values and intentions of the partnership are aligned with 84000’s mission. 84000 reserves the right to rescind data partnerships. Please contact us at info@84000.co to register a data partnership.
- Readers of published content in the reading room and the public website can download PDF and EPUB versions of the website, or read the translations in the reading room viewer, without charge and without creating an account according to the restrictions set forth in this agreement.
- Source code and scripts are made available to external users according to the restrictions set forth in these terms.
## Service policies and privacy
The service shall be subject to the privacy policy for the service available at https://84000.co/about/privacy-policy. You agree to the use of your data in accordance with 84000's privacy policies.
## Cancellation and termination
You agree that 84000, at its sole discretion and for any or no reason, may terminate or suspend the service. You agree that any termination of your access to the Service may be without prior notice, and you agree that 84000 will not be liable to you or any third party for such termination.
## Ideas and feedback
You may choose to or we may invite you to submit comments or ideas about the service, including but not limited to ideas about improving the service or our products (“Ideas”). By submitting any idea, You agree that your disclosure is unsolicited and without restriction and will not place 84000 under any fiduciary or other obligation, and that we are free to use the idea, and/or to disclose the idea on a non-confidential basis or otherwise to anyone.
## Modification of the Service
- You acknowledge and agree that the Service may change from time to time without prior notice to you.
- Changes include, without limitation, changes to security patches, added or removed functionality, and other enhancements or restrictions.
- 84000 shall not be liable to you or to any third party for any modification, suspension or discontinuance of the service.
## External resources
The services may include hyperlinks to other web sites or content or resources or email content. You acknowledge and agree that 84000 is not responsible for the availability of any such external sites or resources, and does not endorse any advertising, products or other materials on or available from such web sites or resources.  The 84000 Reading Room App is available on the [Apple App store](https://apps.apple.com/us/app/84000/id1589912853) and the terms of use for that application are listed there.
## License from 84000 and restrictions
84000 gives you a personal, worldwide, royalty-free, non-assignable and non-exclusive license to use the services provided to you by 84000. This license is for the sole purpose of enabling you to use and enjoy the benefit of the service as provided by 84000, in the manner permitted by the terms.

The following licenses apply to the service:

| Translation Data                                                 | License                          |
|------------------------------------------------------------------|----------------------------------|
| 1. Metadata in RDF on https://github.com/84000/data-rdf | Creative Commons License CC-BY  |
| 2. TEI on https://github.com/84000/data-tei            | Creative Commons License CC-BY-ND |
| 3. Translation memory on https://github.com/84000/data-translation-memory | Creative Commons License CC-BY |
| 4. Glossaries and other translation data at https://read.84000.co/glossary/downloads.html | Creative Commons License CC-BY |
|                                                                  |                                  |

| **Published Content**                                                | **License**                          |
|------------------------------------------------------------------|----------------------------------|
| 1. Translations in HTML, PDF and ePub on https://read.84000.co/ | Creative Commons License CC-BY-ND |
| 2. Translations in multiple formats, including TXT, JSON, and ATOM on https://read.84000.co/ | Creative Commons License CC-BY-ND |
| 3. Website content on https://84000.co               | Creative Commons License CC-BY-ND |
|                                                                  |                                  |

| Source code and scripts                                          | License                          |
|------------------------------------------------------------------|----------------------------------|
| 1. https://github.com/84000/exist-apps             | GNU Lesser General Public License v2.1 |

### Creative Commons License CC-BY
#### General
Translation metadata is made available to individuals and projects under the Creative Commons Attribution 4.0 Generic (CC BY 4.0) license. The CC-BY license is an open license designed to make data available in the public domain, but with the added requirement of attribution. Attribution is requested as this reinforces and references 84000’s authorship and accountability in the space of open data.  RDF documents that describe 84000’s translations, and 84000 translation memories, are made available for harvesting and usage and we request attribution for the use of these resources.

#### Guidelines and technical details
You are free to share, copy and redistribute the resources made available under CC-BY in any medium or format. You are free to adapt, remix, transform, and build upon the material for any purpose, even commercially.  

*Fair Use*
- By uniform resource identifier (URI) to a particular translation metadata document (deep link), e.g. https://github.com/84000/data-rdf/blob/master/toh1-1.rdf
- By uniform resource identifier (URI) to 84000, e.g. https://github.com/84000/
- By text, e.g. Published by 84000: Translating the Words of the Buddha

*Not Permitted*
- Harvesting an RDF document either whole or in part without referencing 84000
- Publishing an RDF document either whole or in part without referencing 84000

### Creative Commons License CC-BY-ND
#### General
All translations posted by 84000 in any format, including HTML, ePub, PDF, TEI, JSON and TXT formats, are made available under a Creative Commons License 4.0. In the spirit of Creative Commons, we ask that those who access 84000 translations, and these derivative formats, kindly cite 84000 as the source in their attributions. Additionally, we ask that the translations provided by 84000 are not used for any commercial purposes, nor modified or adapted without specific permission.  For individuals and groups who may reference and/or rely on 84000 English language translations of materials in their own non-English language translations, an acknowledgement would be appreciated. Please note that the usage of 84000’s translations as reference materials does not constitute an endorsement from 84000.
#### Guidelines and technical details
All 84000 translations are published under a Creative Commons License 3.0 attribution, non-commercial, no derivatives. Full Creative Commons guidelines can be found on their website.
- Attribution. You must attribute the work in the manner specified by the author or licensor (but not in any way that suggests that they endorse you or your use of the work).
- Non-commercial You may not use this work for commercial purposes.
- No Derivative Works You may not alter, transform or build upon this work.

#### Attribution
From the point of view of 84000, the primary goal of attribution is to ensure that translations that appear online, in print or in other mediums identify the source translation in context. The context for dharma texts is critical as it defines the literary, social and “religious” environment in which the text was produced. This is an essential means of preserving the meaning of the texts as time unfolds.

*Fair Use*

- By uniform resource identifier (URI) to a particular translation (deep link), e.g. https://read.84000.co/translation/UT22084-062-018.html Purification of Karmic Obscurations
- By uniform resource identifier (URI) to 84000, e.g. https://read.84000.co
- By text, e.g. Published by 84000: Translating the Words of the Buddha

*Not Permitted*

- Publishing a translation either whole or in part without referencing 84000
- Including attribution to the translator(s) or the translation group, but omitting 84000

#### Non-commercial
While non-commercial may seem a straightforward definition, in practice complying with this clause is not straightforward. When in doubt, please consult 84000.

*Fair Use*

- Printing for reading
- Posting for free download
- Printing and giving away

*Not Permitted*

- Any use by editors, advertisers or others to solicit money using the translations

#### No Derivative
No Derivative licenses allow users to distribute the translation as long as they do not alter the translation or create derivative translations. The ND license ensures that no matter how many times a work is copied and shared, the content of the copies will be the same as the original. The ND license does not permit remixing or adaptation.  The notable exception to no derivatives is using 84000 in a machine learning environment. In this case, after harvesting, and use as training data, there is no trace of the original translation. In this way, 84000 considers machine learning to be in fair use.

*Fair Use*

- Publishing the whole translation online with ancillary material and notes
- Publishing the whole translation in print with ancillary materials and notes
- Use as training data in machine learning environments.

*Not permitted*

* Publishing an excerpt without express permission
* Publishing the translation online without the footnotes
* Remixing the glossary into another glossary

#### GNU Lesser General Public License v2.1
Open source software licenses for components of the service released under an open source license constitute separate written agreements. To the limited extent that the open source software licenses expressly supersede these terms, the open source licenses govern your agreement with 84000 for the use of the components of the service released under an open source license.
## Exclusion of warranties
- You expressly understand and agree that your use of the service is at your sole risk and that the service is provided “as is” and “as available.”
- You agree that 84000 has no responsibility or liability for the deletion or failure to store any content and other communications maintained or transmitted through use of the service. 
- 84000 does not warrant to you that: (a) your use of the service will meet your requirements, (b) your use of the service will be uninterrupted, timely, secure or free from error, (c) the results or data provided by the service will be accurate, (d) the quality of the service will meet your expectations and (e) any errors in the service will be fixed.
## Limitation of liability
You expressly understand and agree that 84000, its subsidiaries and affiliates, and its licensors shall not be liable to you for any direct, indirect, incidental, special consequential or exemplary damages which may be incurred by you, however caused and under any theory of liability. This shall include, but not be limited to, any loss of profit (whether incurred directly or indirectly), any loss of goodwill or business reputation, any loss of data suffered, cost of procurement of substitute goods or services, or other intangible loss (whether or not 84000 has been advised of or should have been aware of the possibility of any such losses arising).
## Indemnification
You agree to hold harmless and indemnify 84000, and its subsidiaries, affiliates, officers, agents, employees, advertisers, licensors, suppliers or partners (collectively “84000 and Partners”) from and against any third party claim arising from or in any way related to (a) Your breach of the Terms, (b) Your use of the service, or (c) your violation of applicable laws, rules or regulations in connection with the service, including any liability or expense arising from all claims, losses, damages (actual and consequential), suits, judgments, litigation costs and attorneys' fees, of every kind and nature. In such a case, 84000 will provide you with written notice of such claim, suit or action.
## General legal terms
The Terms constitute the whole legal agreement between you and 84000 and govern your use of the service and completely replace any prior agreements between you and 84000 in relation to the Service.
You agree that if 84000 does not exercise or enforce any legal right or remedy which is contained in the terms (or which 84000 has the benefit of under any applicable law), this will not be taken to be a formal waiver of 84000's rights and that those rights or remedies will still be available to 84000.
84000 shall not be liable for failing or delaying performance of its obligations resulting from any condition beyond its reasonable control, including but not limited to, governmental action, acts of terrorism, earthquake, fire, flood or other acts of God, labor conditions, power failures, and Internet disturbances.
