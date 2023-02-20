# Meetings

Created time: February 17, 2023 11:17 AM
Last edited time: February 20, 2023 9:19 AM
Tags: Meeting

# Meetings

Overview of all meeting notes for the thesis project.

[Meeting 1 - week 6](https://www.notion.so/Meeting-1-week-6-e2a56e1e0960498981059010139d02db) 

[Meeting 2 - week 8](https://www.notion.so/Meeting-2-week-8-fc9451d0b1f942969a5e973dbbc7d972) 

---

# Meeting 1 - week 6

**Purpose**: Brainstorm about thesis subjects.

**What have been done since last meeting?**

- Veronika send me the following papers for inspiration prior to the meeting:
    - [https://www.nature.com/articles/s41746-022-00592-y](https://www.nature.com/articles/s41746-022-00592-y)
    - [https://jamanetwork.com/journals/jamadermatology/article-abstract/2784295](https://jamanetwork.com/journals/jamadermatology/article-abstract/2784295)
    - [https://arxiv.org/pdf/2212.08568.pdf](https://arxiv.org/pdf/2212.08568.pdf)

**Questions?**

**Notes from the meeting:**

- Agreed on a subject: **Public chest x-ray (and maybe CT) datasets and who uses them and how.**
    - reproducibility, annotate about these data sets (”fields” in the data set.csv)
    - A la transparency: Cheast xray (and maybe cheat ct (3D dimensional)
        - which data set
        - what’sin them
        - who, how are they being used (citations, factors etc.)
    - Sources: e.g., Kaggle, Google Scholar, Grand Challenge ([https://grand-challenge.org/](https://grand-challenge.org/)), Open Alex
    - Reproducibility
        - unofficially google scholar API
        
- Useful links:
    - Upcoming webinar [https://purrlab.github.io/webinar/](https://purrlab.github.io/webinar/)
    - https://github.com/madprogramer/PublicDatasets (Inspiration for set up/structure etc.)
    - Tool to extract citations of papers, Harzing - publish or perish: [https://harzing.com/resources/publish-or-perish](https://harzing.com/resources/publish-or-perish)
    - Taguette:
    
    [Taguette, the free and open-source qualitative data analysis tool](https://www.taguette.org/)
    
    - [Guide for students](https://www.notion.so/Guide-for-students-c85f30c838f1447780773a456cf35fcd)
    - Paper for inspiration by When et al. (2022). “*Characteristics of publicly available skin cancer image datasets: a systematic review***”.**
    
    [Characteristics of publicly available skin cancer image datasets: a systematic review](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(21)00252-1/fulltext)
    

**To be done before next meeting:**

- Write a thesis proposal
- Make a schedule for the thesis process.

---

# Meeting 2 - week 8

**Purpose**: Adjust the proposal

**What have been done since last meeting?**

- Draft for proposal
- Plan for the thesis process.

## Draft for proposal:

- **Situation**
    
    Chest X-rays (CXR) are commonly used to determine abnormalities in the lungs but can also be used to detect abnormalities in the heart, aorta and bones of the thoracic area. Thereby, CXR can be used in the diagnosis of medical conditions such as pneumonia, tuberculosis, heart failure, emphysema, lung cancer and bone fractures. Detecting abnormalities and performing diagnosis based on CXRs can be a challenging task as it relies on the availability of expert radiologists. Therefore, with the digital health innovation, public available CXR datasets are increasingly used to develop deep learning algorithms seeking to detect diseases and perform diagnosis based on CXR with the same or even higher accuracy than expert radiologists.
    

- **Complication**
    
    Artificial intelligence (AI) algorithms have potential to improve the detection of diseases, though they depend on the clinical data on which they are trained and tested to be generalisable. Çallı et al. (2021) reviews all studies using deep learning algorithms on CXR published before March 2021 and classify them based on the type of task being addressed in the study. However, they only describe the public available data sets that the AI algorithms are build on in terms of e.g., study size, labelling and task being applied. Thereby, it lacks to identify and describe any available metadata that describes type of patients included in the study. This causes lack of transparency and potential bias the algorithms as the information about the data that these are build upon on is currently unclear. 
    

- **Proposal**
    
    Through a systematic review, this study seek to identify and evaluate all public available data sets on CXR used for detecting diseases by exploring their characteristics, data access requirements, metadata of the patients in the data etc. to identify potential sources of bias in these data sets. Following PRISMA guidelines (Page et al. 2021) - and registration in PROSPERO (Booth et al. 2012) if applicable - searches will be conducted using MEDLINE, Kaggle, Google Scholar and Grand Challenge and OpenAlex.
    

- **Deliverables**
    - A project report
    - A Github repository with code

**References/ relevant litterature.**

Booth, A. *et al.* (2012) ‘The nuts and bolts of PROSPERO: an international prospective register of systematic reviews’, *Systematic Reviews*, 1(1), p. 2. Available at: [https://doi.org/10.1186/2046-4053-1-2](https://doi.org/10.1186/2046-4053-1-2).

Çallı, E. *et al.* (2021) ‘Deep learning for chest X-ray analysis: A survey’, *Medical Image Analysis*, 72, p. 102125. Available at: [https://doi.org/10.1016/j.media.2021.102125](https://doi.org/10.1016/j.media.2021.102125).

Daneshjou, R. *et al.* (2021) ‘Lack of Transparency and Potential Bias in Artificial Intelligence Data Sets and Algorithms: A Scoping Review’, *JAMA Dermatology*, 157(11), p. 1362. Available at: [https://doi.org/10.1001/jamadermatol.2021.3129](https://doi.org/10.1001/jamadermatol.2021.3129).

Meedeniya, D. *et al.* (2022) ‘Chest X-ray analysis empowered with deep learning: A systematic review’, *Applied Soft Computing*, 126, p. 109319. Available at: [https://doi.org/10.1016/j.asoc.2022.109319](https://doi.org/10.1016/j.asoc.2022.109319).

Page, M.J. *et al.* (2021) ‘The PRISMA 2020 statement: an updated guideline for reporting systematic reviews’, *BMJ*, p. n71. Available at: [https://doi.org/10.1136/bmj.n71](https://doi.org/10.1136/bmj.n71).

**Questions?**

**Notes from the meeting:**

**To be done before next meeting:**

---