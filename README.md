# Quality-Assurance-Inspection-Sampling

This project was about solving following question using decision tree:

Quality Assurance Inspection Sampling:

Consider the manufacturing process of commodity computer memory chips. In order to manage outgoing quality we need to design a strategy for inspecting and rejecting bad production lots. From historical information it is evident that shipped lots of 1,000 parts each are either 1% or 10% nonconforming, that is, good or bad, respectively. It is also known that that 90% of the lots are 1% nonconforming(good) and the other 10% are 10% nonconforming (bad). Sampling and testing costs $2.50 per sample. Note that there are good lots (with 99% good parts, 1% bad) and bad lots (which have 90% good parts, and 10% bad).


States of Nature

θ1: 1% non-c onforming, P(θ1) = .9 (Good lot) 
θ2: 10% non-c onforming, P(θ2) = .1 (Bad lot)

Decision alternatives

a1 : accept lot
a2 : reject lot

Costs

a1|θ1 = 100 (shipped a good lot, transportation costs)
a1|θ2 = 1000 (shipped a bad lot, cost of lost good will, replacement, damages, etc. 
a2|θ1 = 400 (scrapping a good lot, lost cost of production) 
a2|θ2 = 400 (scrapping a bad lot, lost cost of production)

a. Determine the optimal sampling plan given the information above where samples are taken simultaneously. The sampling plan will state the number (n) to sample and the strategy of whether to choose a1 or a2 based on the results of the sample(s). 


b. Determine EVPI, EVSI and Efficiency for the sampling plan. 


c. Repeat parts a, b assuming that sampling may be done sequentially (i.e., onet att at time, after first sample you may choose to accept, reject, or take the next sample, etc.) Since theoretically, this could be infinite, consider one additional sample at a time until you can establish that you will never need to pay for another sample.
