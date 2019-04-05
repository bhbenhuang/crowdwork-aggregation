# crowdwork-aggregation
Implemented 3 quality-control aggregations of crowdwork 

Crowdworkers were asked to characterize whether 10 adjectives described a category, but how do we make sure their work is accurate?

We have gold-standard control labels with known answers. Crowdworkers are also asked to characterize these known labels. Using their responses to these answers, we're able to perform quality-control on each specific user.

We use three algorithms – 1) unweighted majority, 2) expectation-maximization, 3) weighted majority – to calculate each workers quality.

After running the Python program with hw7_data.csv, we obtain the results of the three algorithms in output2.csv, output3.csv and output6.csv respectively
