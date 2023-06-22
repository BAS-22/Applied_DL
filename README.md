This paper evaluates the performance of a semi-supervised learning framework,
with a Mean Teacher algorithm, used for semantic segmentation of pet images
from Oxford-IIIT Pet dataset. In particular, we compare the framework results
with a baseline without unlabelled data, and we also compare it with an upperbound
with all labels being available. Furthermore, we tackle two research questions.
The first question relates to the impact of different noise levels, added to
the inputs, on the performance of the framework. The second question focuses
on the impact of different labelled data ratios on the framework’s performance.
Our experiments show that the framework performs better than the baseline by
achieving 78.5% test IoU accuracy which is significantly higher than the baseline
which gives 48.9%. The framework with an upper-bound performs the best as
it gives 91.2% accuracy. The result of our research on the noise level shows that
initially increasing the noise level improves test accuracy, but after a certain
level it causes the accuracy to decrease. Lastly, we observe that increasing the
labelled that ratio improves model accuracy only to a certain point, suggesting
that not having enough labelled data is not the only factor which limits model
accuracy, but other factors also play a part.
