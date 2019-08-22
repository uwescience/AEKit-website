---
layout: page
title: Methods
---

**Data**

The toolkit comprises of three components: 1. A surveillance tool and automated decision making identification guide 2. a questionnaire and 3. a facial recognition web demo. While the identification guide and questionnaire did not require any data for analysis, the facial recognition interactive demo was designed using data from Labeled Faces in the Wild, an Open Source data set comprising labeled celebrity photos.

Labeled Faces in the Wild includes faces from more than 5,000 celebrities, so we selected a subset of faces which included 15 faces of women of color, 15 faces of men of color, 15 faces of white women, and 15 faces of white men.


**Tools (aka “component specification”)**

We used Open Face, free and Open Source facial recognition repository, as our model for the demo. We used a Docker container to run Open Face on our images. We used Dash to build our interactive web app.

**Processes**

Three processes guided our design of the toolkit:

A. Preliminary discussions with our key stakeholders, community organizations in Seattle impacted by the use of surveillance technologies in their communities. To understand the civil rights concerns and how the Algorithmic Equity Toolkit could be developed, we planned stakeholder meetings and interviews within the first weeks of the project.

Our stakeholders included:

The American Civil Liberties Union (ACLU) of Washington to discuss about their work in regards to algorithmic systems and potential harms of these technologies. The ACLU-WA through the Tech Fairness Coalition has been at the forefront in advocating for transparency and accountability from the Seattle government when adopting surveillance technologies.
Densho works to preserve and share the history of the WWII incarceration of Japanese Americans. We met with Densho to understand their role in tech fairness advocacy and how the AEKit would be beneficial for their community members. The concerns raised by Densho are finding ways to educate the non-tech experts in the community about algorithmic bias and systems.
The Council on American Islamic Relations’ (CAIR) mission is to enhance understanding of Islam, protect civil rights, promote justice, and empower American Muslims. We met with CAIR-WA to understand the effects of surveillance technologies on their communities, and the role of the organization within the tech fairness policy advocacy. CAIR has raised concerns about how surveillance technologies have been used to unfairly track their Muslim-American community members.
Our stakeholder meetings with the ACLU, Densho, and CAIR allowed us to refine the audience and objectives for the toolkit. Based on feedback from our first meeting with the ACLU, we narrowed our toolkit’s audience to community members. Our meetings with Densho and CAIR illuminated the interest in surveillance technology specifically, which subsequently affected the focus of our toolkit to be on algorithmic surveillance systems, including facial recognition software and smart meters. We used an audio-recorder and took notes at all of our stakeholder meetings. After our CAIR and ACLU meetings, we wrote personal reflection memos on the major points of the meeting. We then discussed as a group how the feedback from the meeting may shape our toolkit. We noted follow-up information and procedures at the conclusion of the meeting with each stakeholder.

B. Research and discussions of academic papers on algorithmic bias, fairness, and privacy ethics.

We read a diverse array of literature and discussed it as a group. We reviewed Accountability and Transparency journal articles regarding the definitions of artificial intelligence and the potential biases that they hold to inform the definitions and terminology used in the toolkit. We also drew inspiration on questions to ask and concepts to cover from other algorithmic equity toolkits such as the AI Now, AI Blindspot, and GovEx Toolkit. We found that many of these toolkits were more specifically catered for technical audiences. We also read literature on the issues  of specific technologies like facial recognition and smart metering.  We reviewed the bill language, bill reports, and amendments for Washington state legislation regarding automated decision systems like the Seattle Surveillance Ordinance, House Bill 1654, and House Bill 1655. The bill analysis and report for HB 1654 and 1655 provided background about how facial recognition and automated decision-making systems currently have no Washington state or federal legislation regulating government use of automated decision systems. It also provided information about the sponsors, committee activity, public testimony, and highlights of changes made in the substitute bills. Reading these documents provided us with background and context regarding facial recognition and automated decision-making systems in Washington state, and it also gave us insight into the politics surrounding these bills. We were able to use these government bills to also understand the positioning of different stakeholder groups and the framing of algorithmic equity issues by reading the raw bill language. We also noticed how the intent and scope of some of the washington state bills weakened over time- indicating a possible lack of awareness or concern from the public and decision makers about unregulated automated decision systems.

C. Prototyping and usability evaluations from stakeholders

Designing drafts and iterating:
In creating  the toolkit, we followed a weekly prototyping schedule. We submitted new prototypes by the end of the work day on Fridays, received feedback from our leadership early in the following work week, and then incorporated the feedback and new design ideas into the next prototype.

Evaluations with stakeholders + Diverse Voices, data scientists:
To test and evaluate the usefulness and clarity of the toolkit we collected feedback from civil rights organizations like the ACLU, CAIR, and Densho once again as well as civil rights activists during the development process.. We designed a survey that tested the baseline understanding of civil rights advocates on automated decision systems and surveillance technologies. We then asked them to complete a survey after reviewing our Algorithmic Equity Toolkit to test whether it improved their understanding of automated decision systems. We also asked them for additional feedback and identified specific pain points in the toolkit through the survey and through follow-up meetings.

We also tested and evaluated the accuracy of the algorithmic definitions and representations of how they work in the surveillance and automated decision system identification portion of the toolkit by meeting with data scientists. This feedback was received from data scientists by meeting with them in-person and discussing confusing or inaccurate concepts and also by receiving written feedback.

The toolkit was also evaluated by 3 panels of community stakeholders using
the Diverse Voices methods developed by UW Tech Policy Lab. Our diverse voices panels solicited experiential feedback from racial and social justice activists, immigrations experts, and advocates of justice-involved individuals.


**Analyses**

We initially planned on creating a flowchart that focused primarily on identifying automated decision systems. We determined that it was important for them to distinguish a surveillance tool from an automated decision system. We also determined that it was important for civil rights activists to not only identify an automated decision system but also understand how they work. Understanding how an automated decision works is essential to identification and also to ask the right questions to public officials. Using a  flowchart limited our ability to demonstrate how automated decision systems work, and after feedback from stakeholders we reframed the flowchart as an identification guide.

We initially planned on creating a checklist for policy makers and community civil rights activists, but our meetings with stakeholders further informed our use-case scenario. The ACLU and other stakeholders expressed a desire for the toolkit to be focused on empowering civil rights activists who knew very little about government technology. Thus, we could not expect civil rights activists to answer complex questions about surveillance or automated decision technologies, nor could we expect civil rights activists to ask all the questions that we had on our list. A checklist could also be used as a form of evaluation, but we could not expect civil rights activists who knew very little about government technologies to do that. As a result, we reframed our checklist as a questionnaire to more appropriately fit the use-case scenario informed by our discussions with community stakeholders.

We explored a variety of options for our interactive web demo. One approach we investigated that didn’t work was using Civic Scape, open source predictive policing technology, to build a demo that analyzes the assumptions that predictive policing technology relies upon and the places where those assumptions fall short. We encountered difficulties with Civic Scape’s data loading step, and determined we may not be able to use the Seattle Police Department beat data that we wished to run in the model.

We ended up committing to the facial recognition interactive demo plan to analyze the results of running our images through Open Face’s model. With this demo, we convey some of the problems with facial recognition technology, including bias against people of color, false positives, choosing an accuracy threshold, and image quality.


**Limitations**

This project faced several limitations. First, we found little consensus regarding the definition and structure of concepts like artificial intelligence, machine learning, and automated decision systems (Krafft et al. 2019). Second, meeting with many diverse stakeholders presented a challenge in building the toolkit. Such a diverse set of community members inevitably resulted in diverse and sometimes conflicting priorities, and it proved difficult to meet all expectations. Due to time constraints, we also could not possibly meet with all stakeholders in the community coalition; thus, we had to select some community organizations over others resulting in certain community voices being more dominant and influential in creating our toolkit.

While the facial recognition demo showcases inaccuracies in facial recognition, it runs the risk of communicating that if these inaccuracies were fixed, the associated problems with facial recognition would be solved. As a team, we believe that even without inaccuracies, we still have reason to distrust these surveillance and automated decision technologies. We included statements from stakeholders and case studies to convey this concern in our demo alongside the demonstration of inaccuracies.
