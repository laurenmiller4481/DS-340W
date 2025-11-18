# Connected Lies: Using Network-Informed Ensembles to Identify Sellers that Buy Fake Reviews
## By: Maya Nagiub and Lauren Miller

This project focuses on using supervised machine learning to identify sellers that buy fake reviews by utilizing ensemble models of network features, product level metadata features, and review text features on reviews from Amazon's home and kitchen section.

Sellers that buy fake reviews are defined as the sellers of products who buy favorable reviews in order to artificially boost their reputation on Amazon. This can be accomplished by posting a review request in one of the many fake review writing groups on platforms like Instagram and Facebook.

This project is based on the parent paper "Detecting Fake Review Buyers Using Network Structure: Direct Evidence from Amazon" (2022) by Sherry He, Brett Hollenbeck, Gijs Overgoor, Davide Proserpio, and Ali Tosyali.

The citation of the paper is below.

S. He, B. Hollenbeck, G. Overgoor, D. Proserpio, & A. Tosyali, Detecting fake-review buyers using network structure: Direct evidence from Amazon, Proc. Natl. Acad. Sci. U.S.A. 119 (47) e2211932119, https://doi.org/10.1073/pnas.2211932119 (2022).

The github link to the parent paper code and data is below.

https://github.com/dadepro/fake_review_detection/tree/main

This github is organized into folders denoting the different parts of our project. 

In the folder entitled "parent_paper", we have the two subfolders of "parent_paper_code" and "parent_paper_data". Under "parent_paper_code", we have put the original, unmodified parent paper code that we took directly from the parent paper's github. Under "parent_paper_data", we have put all of the data necessary to run the code in "parent_paper_code", again taken directly from the parent paper's github. 

In the folder entitled "parent_paper_fixed", we have the two subfolders of "parent_paper_fixed_code" and "parent_paper_fixed_data". Under "parent_paper_fixed_code", we have put the code that we modified to recreate the original parent paper as closely as possible without the data leakages that we identified. Under "parent_paper_fixed_data", we have put all of the data necessary to run the code in "parent_paper_fixed_code".

In the folder entitled "parent_paper_innovation", we have the two subfolders of "parent_paper_innovation_code" and "parent_paper_innovation_data". Under "parent_paper_innovation_code", we have the code in which we modified the "parent_paper_fixed_code" in order to marginally improve performance. Under "parent_paper_innovation_data", we have put all of the data necessary to run the code in "parent_paper_innovation_code".

In the folder entitled "parent_paper_innovation_supplementary", we have the two subfolders of "parent_paper_supplementary_code" and "parent_paper_supplementary_data". Under "parent_paper_supplementary_code", we have the code which utilized the same methodology as "parent_paper_innovation_code" but with a dataset of electronic reviews from Amazon. Under "parent_paper_supplementary_data", we have put all of the data necessary to run the code in "parent_paper_supplementary_code". 


