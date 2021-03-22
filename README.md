# PagerankSoftware
PageRank (PR) is an algorithm used by Google Search to rank web pages in their search engine results. PageRank is a way of measuring the importance of website pages. According to Google: PageRank works by counting the number and quality of links to a page to determine a rough estimate of how important the website is. The underlying assumption is that more important websites are likely to receive more links from other websites.[1]  Currently, PageRank is not the only algorithm used by Google to order search results, but it is the first algorithm that was used by the company, and it is the best known.[2][3] As of September 24, 2019, PageRank and all associated patents are expired.

Mathematical PageRanks for a simple network are expressed as percentages. (Google uses a logarithmic scale.) Page C has a higher PageRank than Page E, even though there are fewer links to C; the one link to C comes from an important page and hence is of high value. If web surfers who start on a random page have an 85% likelihood of choosing a random link from the page they are currently visiting, and a 15% likelihood of jumping to a page chosen at random from the entire web, they will reach Page E 8.1% of the time. (The 15% likelihood of jumping to an arbitrary page corresponds to a damping factor of 85%.) Without damping, all web surfers would eventually end up on Pages A, B, or C, and all other pages would have PageRank zero. In the presence of damping, Page A effectively links to all pages in the web, even though it has no outgoing links of its own.

PageRank is a link analysis algorithm and it assigns a numerical weighting to each element of a hyperlinked set of documents, such as the World Wide Web, with the purpose of "measuring" its relative importance within the set. The algorithm may be applied to any collection of entities with reciprocal quotations and references. The numerical weight that it assigns to any given element E is referred to as the PageRank of E and denoted by {\displaystyle PR(E).}PR(E).

Concepts
Unconditional probability: degree of belief in a proposition in the absence of any other evidence.
Conditional probability: degree of belief in a proposition given some evidence that has already been revealed.
Random variable: a variable in probability theory with a domain of possible values it can take on.
Independence: the knowledge that one event occurs does not affect the probability of the other event.
Bayes' Rule: P(a) P(b|a) = P(b) P(a|b)
Bayesian network: data structure that represents the dependencies among random variables.
Markov assumption: the assumption that the current state depends on only a finite fixed number of previous states.
Markov chain: a sequence of random variables where the distribution of each variable follows the Markov assumption.
Hidden Markov Model: a Markov model for a system with hidden states that generate some observed event.
Algorithms
Inference by enumeration
Sampling
Likelihood weighting
