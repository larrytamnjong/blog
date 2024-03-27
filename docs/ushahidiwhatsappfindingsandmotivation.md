# Ushahidi WhatsApp Integration Findings and Motivation

This past few weeks have been interesting for me getting to know about Ushahidi and joining the amazing Ushahidi community. Up until this Outreachy Internship round I have 
not heard about Ushahidi before. I got to discover about Ushahidi and it's mission is to strengthen marginalized communities by facilitating the crowd sourcing, management, analysis, and visualization of information. Ushahidi's mission is almost personal to me and I will share more of it later in this post.

## Key Findings about Ushahidi and WhatsApp integration
### Mission Alignment
Ushahidi's mission to empower marginalized communities through information crowd sourcing aligns seamlessly with the integration of WhatsApp for citizen reporting. WhatsApp's huge presence and ease of use offer a powerful tool for enabling citizen reporting especially in Africa and around the world. 
### Versatility and Reach
WhatsApp's extensive user base and widespread availability on smartphones make it an ideal platform for broadening the reach of citizen reporting. By leveraging WhatsApp as a data source, Ushahidi can tap into diverse communities, including those with limited technological literacy.
### Technical Considerations
 Exploring backend frameworks like Flask and Django revealed Django as the pragmatic choice, offering scalability and seamless integration with Ushahidi's existing infrastructure. Additionally, evaluating WhatsApp Business API options highlighted the importance of comprehensive documentation and ease of implementation, with 2Chat API emerging as a promising solution.

## Inspirations
My inspiration for joining the Ushahidi Community as an intern and an active community member comes from my deep desire to promote change within my own community. Since my university days in Bamenda Cameroon, I have actively sought to use technology as a way for amplifying the voices of those often not heard. 
While social media platforms like Facebook and Twitter provide spaces for dialogue, the challenge lies in consolidating diverse reports to effect tangible outcomes – this is a gap that Ushahidi bridges. I previously attempted to build a basic platform for student reporting, albeit unsuccessfully. Now, Ushahidi presents an invaluable opportunity to channel my passion into meaningful action and contribute to a cause I deeply believe in. Without any much talking I have two reasons why I want to be a part of Ushahidi as an intern in this WhatsApp project.

### Personal Story of Resilience
My journey into technology-driven social change began in my second year of university in Bamenda, where I developed an app called ```"Speakout Student"```. This platform aimed to empower victims of sexual assault perpetrated by university lecturers. However, despite its clear intent, ```"Speakout Student"``` encountered resistance from university authorities. When three students used the platform to report instances of sexual harassment by a lecturer, I was issued a warning and a threat. This incident highlighted the pervasive culture of fear and suppression of voices within academic institutions. My experience with ```"Speakout Student"``` ignited a  passion for amplifying the voices of the marginalized and advocating for transparency and accountability.
Joining Ushahidi as an intern I am motivated to learn and Contribute to Ushahidi and be able to launch an instance of Ushahidi in Cameroon which will be aimed at gathering reports and testimonies about sexual assault perpetrated by lecturers against students across universities in Cameroon.

### Democratic Elections in Cameroon
With the 2025 Cameroon presidential elections coming up, the integration of WhatsApp for real-time citizen reporting takes on added significance. Cameroon's history of authoritarian rule and limited press freedom shows the importance of platforms like Ushahidi in fostering democratic participation and holding authorities accountable. By enabling citizens to report electoral irregularities and amplify their voices, Ushahidi can contribute to a more transparent and inclusive electoral process in Cameroon come 2025.

Generally the reasons to why I want to Join this WhatsApp integration project and Ushahidi lies in my vision on how Ushahidi can bring change to Cameroon and how I can be a part of that change. My contribution is not only in the coding aspect but I aim at doing extensive community outreach sensitizing local rights and news organizations on how they can also utilize the platform with accessible data source mode such as WhatsApp to collect relevant reports.

## Limitations
Sending WhatsApp messages involves collecting the sender's phone number. In countries like Cameroon, with strict SIM card registration laws and government surveillance, the anonymity afforded by WhatsApp reporting may be perceived as insufficient protection. The fear that the government could obtain WhatsApp numbers and consequently track the senders of reports for retaliation could deter people from speaking out or reporting through WhatsApp, posing a significant barrier to effective citizen engagement.

However, this limitation is relatively minor, as the Ushahidi platform currently utilizes SMS as a data source, and it is functioning well. I believe that the anonymity concern with WhatsApp could be seen as merely a food for thought. Furthermore educating organizations that launch instances of Ushahidi on how Ushahidi secures reporters' data will also go a long way in ensuring a sense of anonymity.

## Areas for further exploration
### Chatbot Functionality and Dynamic WhatsApp Surveys
One innovative avenue for further exploration in the WhatsApp integration with the Ushahidi platform involves the development of the chatbot functionality and the creation of dynamic WhatsApp surveys through the dashboard. This enhancement would revolutionize user interaction, streamline data collection, and empower organizations to gather valuable insights efficiently.

#### Chatbot Functionality
The integration of the chatbot functionality within the Ushahidi platform opens up a world of possibilities for engaging with users on WhatsApp. A Chatbot can serve as virtual assistants, guiding users through the reporting process, providing relevant information, and answering common queries in real-time. By leveraging natural language processing (NLP) and machine learning algorithms, the Chatbot can understand user intents, adapt to conversational changes, and deliver personalized responses.
##### Key Features
###### Chatbot Customization
Organizations will be able to customize their own Chatbots based on their needs. The ability to customize chatbots will empower organizations to create intelligent, responsive, and user-centric conversational experiences that drive meaningful engagement, foster trust, and facilitate positive outcomes in citizen reporting and community engagement initiatives.
###### Interactive Reporting 
The Chatbot will be able to prompt users to submit reports by asking targeted questions related to specific incidents, such as location, category, and description.
###### Information Retrieval 
Users will be able to inquire about relevant resources, services, or updates related to ongoing incidents, receiving instant responses and guidance.
###### Feedback and Support
The Chatbot will be able to gather feedback from users regarding their experience with the platform, address common concerns, and escalate inquiries to human operators when necessary.
###### Educational Outreach 
The Chatbot will also be used by organizations to, raise awareness about key issues the particular organization is targeting, plus it can be used to provide instructions on how to utilize Ushahidi for reporting purposes.

#### Dynamic WhatsApp Surveys
The creation of dynamic WhatsApp surveys through the Ushahidi dashboard will empower organizations to conduct targeted data collection campaigns and gather structured feedback from a wide range of stakeholders. 
##### Key Features
###### Customizable Templates
Organizations can design custom Whatsapp survey templates within the Ushahidi dashboard, defining question formats, response options, and branching logic based on specific objectives.
###### Automated Distribution
Surveys can be distributed to targeted audience segments via WhatsApp broadcast lists or group chats, reaching participants directly on their mobile devices and maximizing reach and engagement.

By enabling chatbot functionality and the creation of dynamic WhatsApp surveys through the dashboard, Ushahidi can empower organizations to harness the full potential of WhatsApp as a powerful tool for citizen engagement, data collection, and decision-making. This enhancement not only streamlines the reporting process but also facilitates meaningful interactions between organizations and their communities, fostering transparency, trust, and collaboration for positive social impact.