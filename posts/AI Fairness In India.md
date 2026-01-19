# Re-imagining Algorithmic Fairness in India and Beyond
Nithya Sambasivan, Erin Arnesen, Ben Hutchinson, Tulsee Doshi, Vinodkumar Prabhakaran
### Introduction
Most AI fairness studies are conducted in the West particularly due to the presence of institutions that closely engage with biases and fairness in AI systems. The Freedom of Information Act, coupled with legacy of research quantifying markers of inequality among various social groups in the USA have allowed such research to flourish.
When applied to non-western contexts some of these factors may be absent  or differently aplicable. Therefore it becomes important that research in local contexts is carried out so that AI systems are able to identify and mitigate the biases that are unique to the local contexts.
Based on interviews with 36 researchers and activists the authors present their finding on fairness in AI landscape of India from the lens of feminism, decolonialization, and caste.

### Analysis
#### Axes of Western Fairness Studies
Race and Gender have dominated the fairness discourse in the USA, with secondary focus on disability, age and sexual orientation. Many studies try to develop metrics for analysing fairness based on the legal defintions in USA for example via the Civil Rights Act, which are a product of the hisotry of the region. Similarly the philosophical ideals that determine the fairness criterion can be different. Much of the philosophical backbone in the western cotnext derives from the ideas of the englightenment and post enlightenment, for example Rawl's Theory on Justice. While Rawl's work deals with fair allocation of goods and services under the assumptions of free and equal citizens, Ambedkar's philosophy is concerned with breaking the hierarchical structure of the society. The latter can be considered as an example of restorative justice which seeks to undo historic harms.

#### Emperical Considerations
Early datasets like Imagenet did not have representation from non western contexts, similarly many NLP systems have struggled with non-western names for instance. This points to an issue realted to lack of good quality data. These issues are compounded by the fact that many of these systems are built without clear fairness goals and can often have complicated owenership and liability issues.
The authors describe their methodology as an "exploratory study" where they interview experts from various facets of live to understand the landscape.

Respondent Distribution by Field*

```text
Computer Science        | ########### (11)
Activism                | #########   (9)
Law & Public Policy     | ######      (6)
Science & Technology    | #####       (5)
Studies (STS)           |
Development Economics   | ##          (2)
Sociology               | ##          (2)
Journalism              | #           (1)

Legend: # = 1 respondent
Total Respondents: 36
```

#### Findings
1. Data Issues:
The paper makes several observations which would be very familiar to most Indians would have come across. The most notable data collection challenges arise from people navingating their social situations to make the best of what they have and/or to preserve privacy or protect identity. These behavior patterns include shared usage of mobile phones in households which breaks the assumption of one data point(in this case phone number as proxy for identity) corresponds to only one person. Similar patterns are observed in other proxies such as location which for example changes with time in migrant worker communities. The authors further describe the problems due to disproportiante participation of people online or in surverys owing to scoietal divides like patriarchy and class that have crept as is in the digital space; thus they note that rural women are most under-represented groups online alongside tribal communties. Authors acknowlege that vast amount of data is collected by government agencies however there is little political will to digitize the data and make them available publicly.
This digital divide in online footprint means that some concerns and problems are more visible than others depending on the group, brigading and online trolling is further a factor which the authors have not considered but which affects the digital presence of several marginalized groups.
2. Model
Fair ML standards are rarely enforced in india for example credit applications can use all personal data on phone like call logs etc to model a person's likelihood of repayment. Many technologies that are imported from the west are used out of the box or with unscrupulous contenxtualization. It is also worth noting that most AI technologies are quickly rolled out in india without much consideration for fairness and has led the author to dub India as "Petri Dishes" of AI. This stems from the idea that most AI is deployed with the purpose of quickly collecting more data without regards to personal boundaries and to utilize the linguistic diversity to improve the models' robustness. This is aided by lack of regulatory framework to hold the entities accountable for violations of ethical codes. Another aspect of this is that due to centralization often redressal mechanisms are opaque not accessible.
Recent attitute in India towards technology has been one of optimism and is driven by the idea that technological innovation will solve social problems ushering a era of prosperity. Criticism of technology are not very acceptable and there is a risk of being labelled anti-development. This is partially driven by the (false) notion that algorithms are independent of humans and human interferrence and thus de factor fair.
Reflection:
In recent discourse the idea of India 1, India 2 and India 3 is quite similar to the analyisis in this section, most online services are targetted to india 1(>10LPA which can be considered as upper middle class).  
#### Remedies
The authors acknowledge that the problem is complex and a comrehensive solution would require significant shift in both the public perception of AI(and technology) which is seen as a magic band aid solution to social problems as well as adress the systemic incompetencies that incentivze the creation of AI services without regards for ethical concerns. In essence the proposed solution is to reduce the "distance" between those who build AI, those who generate the data and those who use the AI. Understanding the needs and concerns at grassroot level is important to discovering potential side effects of a system.

#### What the authors missed/developments since the pulication of paper
Authors barely touch upon questions of data ownership, while they agree that data is disproportiantely generated by different social groups which influences products and services, dataownership is barely adressed. One the other hand one can assume that the paper's criticcism of neoliberal economic order implies concerns about data ownersip.
Emergence of dark patterns in quick commerce is another development that the paper could not have forseen but many ideas can be applied directly to the analysis of the system. Algorithms are increasingly determining what and how gig workers do, in this light it is important to make sure that these algorithms are fair and not explotitative/manipulative.
While the paper acknowledges that representation of social groups in journalism reflects the broader social inequalities, they do not evaluate or consider the technical literarcy of mass media journalists with regards to AI given the fast pace developments in AI.
The authors do not engage with effects of online behavior such as astroturfing and trolling that significantly shapes public discourse and drives response from companies and state alike.

Another contemporary challenge is assessing the fairness of new systems like content recommendation systems. It has been anecdotally observed that content recommendation algorithms can reinforce biases or even drive vulnerable users like those in depression to perform self harm. Such systems are hard to fit in the current ML Fairness framework of selection rates and demographic parity. A related challenge is how content moderation systems work and do they have biases wrt what kind of content that is reported is likely to be banned. This is especially relevant in Indian context where online discourse can get uncivil. This is especially important given increasingly partisan nature of social media ownership(e.g X/Twitter)

The paper does not engage with intersectional vulnerabilities as much, while it does acknowledge the intersection of caste and gender it fails to look at other intersectionalities like language and class and occupation(blue vs white collar), religion and caste.

The paper scratches the surface of network effects in the context of credit worthiness, however it fails to note the effects of social-network(not to be confused with social media) leading to digital redlining. Examples include companies limiting CoD features based on risk for the entire pin codes or algorithms that look for Lookalike audiences.

*ASCII Art created by ChatGPT
