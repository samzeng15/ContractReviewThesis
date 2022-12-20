This thesis was written for the Honours requirement of my Bachelor of Advanced Computing. 

Some code has been adapted from the original paper of Hendrycks et. al. (2021) which this paper uses as the base to improve on. 

A copy of the original papers' datasets and all modified datasets tested in the thesis can be found in https://www.dropbox.com/scl/fo/vpwgjgpcdyxt7u2h6snms/h?dl=0&rlkey=44rhsxcqu9c6eklq4rpcvdxtr


An abstract of the thesis is presented below:

The Contract Understanding Atticus Dataset (CUAD) is a highly specialised contribution for deep learning within the legal domain (Hendrycks et al., 2021). While it is well annotated, there is room for improvement to its accuracy in contract review and related ML tasks. We argue that the relatively low performance of the QA models is caused by the data imbalance issue in the original data set. We propose two enhancement strategies to address this issue. We find that while steps have been taken to address imbalance within the dataset, there is high imbalance within the data of different categories. Additionally, as CUAD models the Stanford Question and Answer Dataset (SQuAD), we find that their adaption of fitting entire contracts as context paragraphs results in issues of excess false positives. Thus, we propose separating each question answer contract into smaller paragraphs to be more in line with the SQuAD data format and benefit more from unanswerable questions. We also propose splitting the label categories into different datasets grouped by label count to prevent particular categories from dominating the samples until further annotations for lower label-count categories can be introduced.