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

What does your workflow or pipeline look like?
What steps did you follow?

**Analyses**

We initially planned on creating a flowchart that focused primarily on identifying automated decision systems. We determined that it was important for them to distinguish a surveillance tool from an automated decision system. We also determined that it was important for civil rights activists to not only identify an automated decision system but also understand how they work. Understanding how an automated decision works is essential to identification and also to ask the right questions to public officials. Using a  flowchart limited our ability to demonstrate how automated decision systems work, and after feedback from stakeholders we reframed the flowchart as an identification guide.

We initially planned on creating a checklist for policy makers and community civil rights activists, but our meetings with stakeholders further informed our use-case scenario. The ACLU and other stakeholders expressed a desire for the toolkit to be focused on empowering civil rights activists who knew very little about government technology. Thus, we could not expect civil rights activists to answer complex questions about surveillance or automated decision technologies, nor could we expect civil rights activists to ask all the questions that we had on our list. A checklist could also be used as a form of evaluation, but we could not expect civil rights activists who knew very little about government technologies to do that. As a result, we reframed our checklist as a questionnaire to more appropriately fit the use-case scenario informed by our discussions with community stakeholders.

We explored a variety of options for our interactive web demo. One approach we investigated that didn’t work was using Civic Scape, open source predictive policing technology, to build a demo that analyzes the assumptions that predictive policing technology relies upon and the places where those assumptions fall short. We encountered difficulties with Civic Scape’s data loading step, and determined we may not be able to use the Seattle Police Department beat data that we wished to run in the model.

We ended up committing to the facial recognition interactive demo plan to analyze the results of running our images through Open Face’s model. With this demo, we convey some of the problems with facial recognition technology, including bias against people of color, false positives, choosing an accuracy threshold, and image quality.


**Limitations**

This project faced several limitations. First, we found little consensus regarding the definition and structure of concepts like artificial intelligence, machine learning, and automated decision systems (Krafft et al. 2019). Second, meeting with many diverse stakeholders presented a challenge in building the toolkit. Such a diverse set of community members inevitably resulted in diverse and sometimes conflicting priorities, and it proved difficult to meet all expectations. Due to time constraints, we also could not possibly meet with all stakeholders in the community coalition; thus, we had to select some community organizations over others resulting in certain community voices being more dominant and influential in creating our toolkit.

While the facial recognition demo showcases inaccuracies in facial recognition, it runs the risk of communicating that if these inaccuracies were fixed, the associated problems with facial recognition would be solved. As a team, we believe that even without inaccuracies, we still have reason to distrust these surveillance and automated decision technologies. We included statements from stakeholders and case studies to convey this concern in our demo alongside the demonstration of inaccuracies.
