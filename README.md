# Assignment2

Data Exploration: The threshold that I am using to determine what comments are toxic is .45 or 45%. This is a little under the half way mark which indicates the comment is pretty much neutral. Anything greater than the neutral half way threshold should be considered "toxic". The labels I will be looking at to determine if comments are toxic are the "toxic" and "severe toxic" since that is what I will be testing the score for.

Hypothesis: The API tends to mark homosexual terms as more toxic than they actually are intended to be.


Analyze Data & Results:

I predicted that there would be biases in the system of how homosexual terms would be percieved by the API. This is due to the inherent stigma around homosexuality in society and how it is still not considered to be fully "normal". Though homosexuality is being more accepted amongst a lot of people, the API does not seem to follow the trends of society. Neutral terms such as gay, homo, and lesbian could be considered toxic by the API when used in normal ways such as queer awareness and education. These terms could also be used in a negative way but overall homosexual terms should not be considered toxic.

The toxicity scores of homosexual comments tend to be more false positive. There are many cases where the words gay, homo, lesbian etc., are used in a non-toxic way but they all still tend to get toxicity scores of around .5 or above .5 which is in my opinion highly skewed. Most of these scores are above .45 which is considered as toxic. Overall I disagree with how the API perceives how toxic homosexual terms are.

My theory about these results are the API is not up to date with how society views homosexuality today. There is still a lot of work done to fully accept homosexuality, but in general it is not something that should be deemed as toxic as the API regeisters these terms to be. The API is definitely biased against homosexual terms and marks these normal terms to be more toxic than they actually are. My hypothesis is proven true through this data analysis.
