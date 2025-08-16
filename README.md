# metadata-classification
## 1. Business Understanding

### 1.1 Problem statement
Many articles published in UNZA journals have incomplete or inconsistent descriptive metadata (e.g., missing author names, publication dates, keywords, abstracts). This makes it difficult for researchers or librarians to correctly cite articles. We need a way to automatically classify the completeness of metadata associated with each article, so we can identify gaps and improve metadata quality.

#### 1.2 Business Objectives
1. Automate Metadata Completeness Classification

 2. Diagnose Metadata Gaps A cross UNZA journels

 3. improve Citation Accuracy and Research Discoverability

 4. Standaridise Metadata Practices

 5. Establish Sustainable Metadat Governance

##### 1.2.1 what success might look like in real life :
-Metadata Completeness where each article recieves a scored ranging from 0% to 100% based on the presence of key metadata.

-Reduction in Incomplete Records where number of articles with missing metadata drops by a good percentage like 70%

-Improved Citation Quality where there is a great reduction in citation errors by researchers and librarians 

- Metadata validation reduces manual correction workload by a great percentage.

-Metadata audits and contributor training are institutionalised in various departments

 ##### 1.3 Translating business objectives into data mining goals 
To achieve the above business objectives, our project will focus on developing a robust classification model capable of automatically evaluating the completeness of descriptive metadata for articles in UNZA journals. Specifically:
- Build a supervised classification model that categorizes articles into defined completeness levels — for example:

  -Complete (all required metadata fields present),

  -Partially Complete (some key fields missing),

  -Incomplete (major fields missing).
- Train and validate the model using historical article metadata records, where completeness has been manually assessed, ensuring the model can generalize to new, unseen records.
- Leverage appropriate features from metadata fields such as title, author(s), publication date, keywords, abstract, DOI, and journal name to determine the completeness score/class.
- Enable metadata quality insights by aggregating classification results to identify common gaps across journals, which will guide targeted improvements and policy enforcement.
- Set measurable model performance targets — e.g., at least 85% classification accuracy for predicting completeness categories on test data.

### 1.4 Initial Project Success Criteria
We’ll know our project is successful when we can clearly see improvements in both the quality of metadata and the ease of managing it. Specifically:

1. ### Accurate classifications
   Our model should correctly predict whether an article’s metadata is complete, partially complete, or incomplete at least 85% of the time. It should also be especially reliable in spotting incomplete records, with precision and recall above 80%.

2. ### Trustworthy completeness scores 
   When we compare the system’s completeness scores to manual librarian checks, the difference should be very small ideally less than 5%.

3. ### Noticeable improvement in records  
   Within six months of putting the system into use, the number of articles with missing or incomplete metadata should drop by at least half in the journals we focus on.

4. ### Smooth workflow integration  
   The tool should fit into the existing UNZA journal processes without slowing things down, allowing continuous checks without extra hassle.

5. ### Positive user feedback  
   Librarians, editors, and contributors should find the tool easy to use and report that it saves them time and reduces the amount of manual fixing they have to do.

### 1.5 Next Steps
To move forward, we will begin by collecting and preparing metadata samples from existing UNZA journal articles. This includes labelling records for completeness and identifying key metadata fields. We will then design and test initial classification models, refining them based on performance metrics. Parallel to model development, we’ll engage stakeholders (librarians, editors, contributors) to ensure the solution aligns with their workflows and needs. Once validated, the tool will be piloted on select journals before broader deployment.
