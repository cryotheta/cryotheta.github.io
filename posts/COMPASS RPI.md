## Fair prediction with disparate impact: A study of bias in recidivism prediction instruments
Alexandra Chouldechova
#### Introduction
In this discussion we will focus on section III of the paper, armed with the knowledge that there are various fairness criteria including Calibration, Predictive Parity and Balanced Error Rates and that Calibration and Balanced Error Rates are not achievable simultaneously. We will focus on analyzing which criteria is better applicable and why. To do so we must look at who bears the cost of an error in the prediction and what if any are the impacts on society as a whole. 

The paper discusses COMPASS a predictive tool for assigning risk scores to undertrail persons, which was the subject of the now famous expose by ProPublica. The primary acusation on compass was that it had non uniform error rates for black and white individuals. COMPASS countered this by arguing that their system was calibrated and hence fair. The tool as well as the pro publica piece have been throughly discussed in academic circles. Another important aspect of this debate is that the tool is legal to use in several jurisdictions is beign used with increasing popularity. 
A recent research has shown that such softwares could  "decrease rate of confinement across demographic groups, but that the use of the algorithm exacerbated differences in confinement between racial groups, thereby deepening racial disparity". If we were to use Rawl's viel of ignorance this kind of inqeuality is acceptable since it results in better absolute outcomes for all groups. How valid this assertion is we leave for the reader as an exercise.
##### Analysis
###### Result 1
Difference in error rates(FPRs) between groups results in person of the more recidivising group to be more likely to be wrongly penalized than the other group. Therefore one can argue that algorithm unfairly assumes the worse based on group attribute. Naturally it raises the question: What happens if we look inside the groups?
###### Result 2
Authors look at subgroups based on priors, looking at only people who had misdemeanour as the prior, same patterns of FPR can be seen, which suggests that even for similar priors, members of different social groups are treated differently across social groups.
###### Result 3
Authors simulate average prison time and 
