---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.14.1
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

% !!!
%
% Don't edit this page directly!
% It has been automatically generated.
% Instead, edit the project's README.md file which gets inserted here,
% or the templates in /analysis/book_helpers/templates/
%
% !!!


# tracking_open_datasets

You can see the full contents of this project [on GitHub](https://github.com/neurodatascience/labelbuddy-annotations/tree/main/projects/tracking_open_datasets/).

## `<Project Name>`

`<1-2 sentences describing the project>`

## Papers

### How the papers were obtained
Typically with [pubget](https://neuroquery.github.io/pubget/pubget.html).
We recommend invoking `pubget` with the `--query_file` option, and storing a copy of the query file in the project's directory, or including a copy in the `README.md`.

`<description>`

### Where the full papers are stored

Typically on [OSF](https://osf.io/).
Please also add a `documents/datasets.json` file containing the URL where the full `pubget` dataset can be downloaded, that looks like:
`​`​`
[
    {
    "url": "https://osf.io/download/<...>/"
    }
]
`​`​`

`<description>`


## Annotations
### File(s) being annotated: 
- `/projects/<project_name>/documents/<documents_file1_name>.jsonl`
  - corresponding file in the pubget output: 
    - `<pubget_folder_name>/subset_allArticles_labelbuddyData/<documents_file1_name>.jsonl`
- `/projects/<project_name>/documents/<documents_file2_name>.jsonl`
  - corresponding file in the pubget output: 
    - `<pubget_folder_name>/subset_allArticles_labelbuddyData/<documents_file2_name>.jsonl`
  
### Annotation labels:
- `<label1>: <description of label1>`
- `<label2>: <description of label2>` 

### Labels found in other projects as well:
- `<label2>`

### Instructions for annotators
`<description>`




## Labels in this project



```{code-cell}
:tags: [remove-input]

from labelrepo import displays
text = """
<div class="detailed-label-set">
    
    <details style="--label-color: #f66151;">
        <summary class="label-display">did not use large open dataset (61 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …r rfMRI scans from 10 participants and concluded that this intraVar also reflected functionally specialized and flexible configuration across the human brain cerebral cortex [ ]. A recent work on the <mark class="annotated-text">MyConnectome</mark> project [ ] by Poldrack and colleagues has yielded the most detailed depiction of an individual brain’s function across one year (almost daily scanned) [ ], together with the work from Choe and colle…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4694646/"
                                       >PMC4694646</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …als were analyzed. This dataset is published publicly in compliance with Brain Imaging Data Structure (BIDS) specification  . All participants recruited in this study previously participated in   the <mark class="annotated-text">studyforrest</mark> project   ( ,  ,  . The T1, T2, SWI structural images and the fMRI dataset for retinotopic mapping, which are available from  , have also been utilized in this study. This section provides informatio…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5459569/"
                                       >PMC5459569</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …pecific genes affecting healthy resting-state connectivity must await large datasets with coincident resting-state functional imaging and genotyping. (Genetic data will soon be available both for the <mark class="annotated-text">HCP</mark> and for the UK Biobank imaging data.) 

Taken together, our results provide strong additional evidence for a neural basis of the heritability of functional connectivity in the human brain. We identif…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5621837/"
                                       >PMC5621837</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …fecting healthy resting-state connectivity must await large datasets with coincident resting-state functional imaging and genotyping. (Genetic data will soon be available both for the HCP and for the <mark class="annotated-text">UK Biobank</mark> imaging data.) 

Taken together, our results provide strong additional evidence for a neural basis of the heritability of functional connectivity in the human brain. We identify genetic influences bo…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5621837/"
                                       >PMC5621837</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …“good” values of DVARS varies over sites and protocols which makes it difficult to create comparable summaries of data quality across data sets. The emergence of the large scale data sets such as the <mark class="annotated-text">Human Connectome Project </mark>(HCP) ( 1k subjects) and the UK Biobank ( 10k subjects) further motivates the need for automated, yet reliable, quantitative techniques to control and improve the data quality. 

The purpose of this w…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5915574/"
                                       >PMC5915574</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … which makes it difficult to create comparable summaries of data quality across data sets. The emergence of the large scale data sets such as the Human Connectome Project (HCP) ( 1k subjects) and the <mark class="annotated-text">UK Biobank</mark> ( 10k subjects) further motivates the need for automated, yet reliable, quantitative techniques to control and improve the data quality. 

The purpose of this work is to provide a formal description …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5915574/"
                                       >PMC5915574</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …different datasets, including task, rest, MEG and fMRI, with potentially thousands of subjects. We anticipate that the generation of large and publicly available datasets from initiatives such as the <mark class="annotated-text">Human Connectome Project</mark> and UK Biobank, in combination with computational methods that can work at this scale, will bring a breakthrough in our understanding of brain function in both health and disease. 
 

# Body
 
## Int…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6138951/"
                                       >PMC6138951</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ts of neuroimaging data have recently become critical for bridging the gap between basic neuroscience research and clinical applications, such as the diagnosis and treatment of psychiatric disorders (<mark class="annotated-text">Human Connectome Project </mark>[HCP] [ ] [ ]; Human Brain Project [ ]; UK Biobank [ ]; and Strategic Research Program for Brain Sciences [SRPBS] [ ] [ ]) [ – ]. When collecting large amounts of data associated with psychiatric diso…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6472734/"
                                       >PMC6472734</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g the gap between basic neuroscience research and clinical applications, such as the diagnosis and treatment of psychiatric disorders (Human Connectome Project [HCP] [ ] [ ]; Human Brain Project [ ]; <mark class="annotated-text">UK Biobank</mark> [ ]; and Strategic Research Program for Brain Sciences [SRPBS] [ ] [ ]) [ – ]. When collecting large amounts of data associated with psychiatric disorders, it is necessary to acquire images from mult…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6472734/"
                                       >PMC6472734</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ing access to population neuroimaging studies, where thousands of fMRI subject data are available, a future study could test for nonzero software‐related variation by splitting a large dataset (e.g., <mark class="annotated-text">UK Biobank</mark> [Alfaro‐Almagro et al.,  ],   N   &gt; 10,000) into smaller subsets to generate an extensive collection of replication analyses across the three packages. This may allow for the creation of a null‐distr…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6618324/"
                                       >PMC6618324</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - human connectome project (24 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …d with each other in space and time, a property which we believe is neuroscientifically desirable. 

We assess the performance of our model on both simulated data and high quality rfMRI data from the <mark class="annotated-text">Human Connectome Project</mark>, and contrast its properties with those of both spatial and temporal independent component analysis (ICA). We show that our method is able to stably infer sets of modes with complex spatio-temporal i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4349633/"
                                       >PMC4349633</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …state. For both observation models, we simulated state time courses for 200 subjects, with 500 samples per subject. 


### fMRI data 
  
We used resting-state fMRI data from N = 820 subjects from the <mark class="annotated-text">HCP</mark>, all healthy adults (ages 22–35 years, 453 females) scanned on a 3 T Siemens connectome-Skyra. For each subject, four 15-min runs of fMRI time series data with temporal resolution 0.73 s and spatial …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6138951/"
                                       >PMC6138951</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …m   (ds000224) 
  
‘Kirby Weekly’: Downloaded from  
  
‘Day2day’: For availability, see  ; section ‘Availability of data and materials’ (available upon request). 
  

The 900 subjects release of the <mark class="annotated-text">Human Connectome Project</mark> was used for the cross-sectional dataset. They are downloadable from  . For more information on the specific release, see  . 

 

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7014820/"
                                       >PMC7014820</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …f the findings. In this study, we adopted a method capable of identifying reliable ICNs that can be compared across datasets . The group template of ICNs was identified from two independent datasets (<mark class="annotated-text">Human Connectome Project</mark> [HCP] and Genomics Superstruct Project [GSP]) with large sample sizes (  N   = 1005 for GSP and   N   = 823 for HCP) and different temporal resolutions (see details in Supplementary Note  ), and was …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7414843/"
                                       >PMC7414843</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …andon, Jakki and Arichi, Tomoki and Rueckert, Daniel and Hajnal, Joseph V. and Edwards, A. David and Smith, Stephen M. and Duff, Eugene and Andersson, Jesper
Neuroimage, 2020

# Title

The developing <mark class="annotated-text">Human Connectome Project</mark> (dHCP) automated resting-state functional processing framework for newborn infants

# Keywords

Developing Human Connectome Project
Functional MRI
Pipeline
Quality control
Connectome
Neonate


# Abst…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7762845/"
                                       >PMC7762845</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …the cumulative biases of pipelines in order to distinguish biological effects from methodological variance. 


## Methods 
  
Here we use an open structural MRI dataset (ABIDE), supplemented with the <mark class="annotated-text">Human Connectome Project</mark>, to highlight the impact of pipeline selection on cortical thickness measures. Specifically, we investigate the effect of (i) software tool (e.g., ANTS, CIVET, FreeSurfer), (ii) cortical parcellation…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7821710/"
                                       >PMC7821710</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ation ( ;  ). 


## Methods 
  
### Data 
  
All analyses in the present work were carried out using publicly available datasets selected based on the inclusion of extensive test-retests fMRI. 

#### <mark class="annotated-text">Human connectome project </mark>(HCP) 
  
We made use of the HCP S1200 release dataset ( ;  ). The unrelated healthy young adult participants who completed all fMRI scans (i.e. rest and task) were considered in our study. We selecte…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7983579/"
                                       >PMC7983579</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …omplementary to rsfMRI and tfMRI. 

In this study, functional subdivisions of the cerebellum were parcellated   via   a dual-regression-like framework based on sparse representation of nfMRI from the <mark class="annotated-text">Human Connectome Project</mark> (HCP). The parcellations were quantitatively evaluated and validated by functional homogeneity and boundary confidence, and quantitatively by comparison between cerebellum–cerebrum functional connect…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8719453/"
                                       >PMC8719453</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …emplate of replicable independent components (ICs) was constructed after spatially matching correlated group-level ICs between two healthy control fMRI datasets—genomics superstruct project (GSP) and <mark class="annotated-text">human connectome project</mark> (HCP). The estimated network template was then used as a prior for a spatially constrained ICA algorithm applied to each UK Biobank subject individually. This identified 53 functionally relevant rest…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8782493/"
                                       >PMC8782493</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ls while maximally optimizing the unique network property for each subject. The unbiased spatial network templates were estimated using two large independent groups of HCs, that is, 1005 HCs from the <mark class="annotated-text">Human Connectome Project </mark>(HCP) and 823 HCs from the Genomics Superstruct Project (GSP), with the number of independent components (ICs) in ICA set to 100, followed by the selection of 53 reliable, reproducible, and meaningful…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9294304/"
                                       >PMC9294304</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #aaff7f;">
        <summary class="label-display">new dataset (20 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …come critical for bridging the gap between basic neuroscience research and clinical applications, such as the diagnosis and treatment of psychiatric disorders (Human Connectome Project [HCP] [ ] [ ]; <mark class="annotated-text">Human Brain Project</mark> [ ]; UK Biobank [ ]; and Strategic Research Program for Brain Sciences [SRPBS] [ ] [ ]) [ – ]. When collecting large amounts of data associated with psychiatric disorders, it is necessary to acquire …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6472734/"
                                       >PMC6472734</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …sic neuroscience research and clinical applications, such as the diagnosis and treatment of psychiatric disorders (Human Connectome Project [HCP] [ ] [ ]; Human Brain Project [ ]; UK Biobank [ ]; and <mark class="annotated-text">Strategic Research Program for Brain Sciences </mark>[SRPBS] [ ] [ ]) [ – ]. When collecting large amounts of data associated with psychiatric disorders, it is necessary to acquire images from multiple sites because it is nearly impossible for a single …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6472734/"
                                       >PMC6472734</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n particular will also require larger samples. 

Increasing sample size and testing sensitivity and specificity across disorders will be greatly facilitated by data-sharing initiatives, including the <mark class="annotated-text">Pain and Interoception Imaging Network</mark> (PAIN) repository,  OpenPain (principal investigator: A. Vania Apkarian), UK Biobank,  and OpenfMRI.  Open data platforms will also aid in the problem of overfitting, making reproducibility, validati…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6727991/"
                                       >PMC6727991</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … sample size and testing sensitivity and specificity across disorders will be greatly facilitated by data-sharing initiatives, including the Pain and Interoception Imaging Network (PAIN) repository,  <mark class="annotated-text">OpenPain</mark> (principal investigator: A. Vania Apkarian), UK Biobank,  and OpenfMRI.  Open data platforms will also aid in the problem of overfitting, making reproducibility, validation, and generalization easier…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6727991/"
                                       >PMC6727991</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ray–white matter contrast in MR images, our data suggest that it results in apparent cortical thinning. Our findings have broad implications for large-scale studies of brain development including the <mark class="annotated-text">Pediatric Imaging Neurocognition and Genetics Data Repository</mark> ( ), the Adolescent Brain Cognitive Development study ( ), and the HCP data ( ) that use algorithms based on the intensity of MR images to estimate CT. Importantly, since these high-impact and large-…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6789966/"
                                       >PMC6789966</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ability 
  
The following longitudinal datasets were used (and are accessible through):   
‘Myconnectome’: Downloaded from   (ds000031) 
  
‘The Midnight Scan Club’: Downloaded from   (ds000224) 
  
‘<mark class="annotated-text">Kirby Weekly</mark>’: Downloaded from  
  
‘Day2day’: For availability, see  ; section ‘Availability of data and materials’ (available upon request). 
  

The 900 subjects release of the Human Connectome Project was use…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7014820/"
                                       >PMC7014820</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …al datasets were used (and are accessible through):   
‘Myconnectome’: Downloaded from   (ds000031) 
  
‘The Midnight Scan Club’: Downloaded from   (ds000224) 
  
‘Kirby Weekly’: Downloaded from  
  
<mark class="annotated-text">‘Day2day’</mark>: For availability, see  ; section ‘Availability of data and materials’ (available upon request). 
  

The 900 subjects release of the Human Connectome Project was used for the cross-sectional dataset…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7014820/"
                                       >PMC7014820</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …a, which is the Cambridge Buckner subset of the 1000 functional connectomes project ( ), and two smaller samples more well suited for test-retest reliability studies. The first small sample being the <mark class="annotated-text">intrinsic brain activity test retest</mark> (IBATRT) dataset ( ), and the second being the midnight scan club (MSC) dataset ( ). 

For the Cambridge Buckner data sample there were a total of 198 subjects (123 female), ages 18–30 (M = 21.03, SD…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7029189/"
                                       >PMC7029189</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ved, for fMRI studies that contain large‐scale images of participants and in which sample size is not a considerable concern, like the UK Biobank (Alfaro‐Almagro et al.,  ) or German National Cohort (<mark class="annotated-text">German National Cohort</mark>,  ), the greatest‐motion participants, which account for the greatest effect on FC, can be removed from the group. We suggest that if a group data set is large enough, participants with large motion …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7814752/"
                                       >PMC7814752</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ne measurement that helps us to bridge the space between biology and behavioral outcomes. Several large-scale studies have employed fMRI to map brain activity in the general population, including the <mark class="annotated-text">Rotterdam Study</mark> (Hofman et al.,  ), UK Biobank (Miller et al.,  ), and the Rhineland Study (Breteler et al.,  ). These large-scale population studies are usually not designed to answer one specific hypothesis. Rathe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7859438/"
                                       >PMC7859438</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - ukbb (15 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … components = 820 × 4 x 1200 × 50), were standardised so that, for each scan, subject and ICA component, the data have mean 0 and standard deviation 1. 

We also used resting-state fMRI data from the <mark class="annotated-text">UK Biobank</mark>, a large-scale prospective epidemiological study aiming to allow the identification of risk factors and early biomarkers relating to many diseases ( ,  ,  ). We used the first public release containi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6138951/"
                                       >PMC6138951</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … 


### Brain Functional Parcelation 
  
We tested four different parcelation maps in order to identify how the number of parcels affects the classification process. Two parcelations were part of the <mark class="annotated-text">UK Biobank</mark> Imaging Study , where about five thousands resting-state functional MRI data points were collected from different participants. Both parcelations were the result of a group independent components ana…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6929667/"
                                       >PMC6929667</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Cole, James H.
Neurobiol Aging, 2020

# Title

Multimodality neuroimaging brain-age in <mark class="annotated-text">UK biobank</mark>: relationship to biomedical, lifestyle, and cognitive factors

# Keywords

Brain aging
Neuroimaging
Multimodality MRI
UK Biobank
Biomedical measures


# Abstract
 
The brain-age paradigm is proving i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7280786/"
                                       >PMC7280786</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …le size GWAS summary data on chronic pain and sleep disturbance were used to explore their genetic correlations. The GWAS summary data of chronic pain was from a multisite GWAS of chronic pain in the <mark class="annotated-text">UK Biobank</mark>, which included ~380,000 participants . The PSQI is a widely used measure of sleep quality with high sensitivity (98.7%) and specificity (84.4%)  for identifying primary insomnia . Because there were…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7381677/"
                                       >PMC7381677</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Leming, Matthew and Suckling, John
Neuroimage, 2021

# Title

Deep learning for sex classification in resting-state and task functional brain networks from the <mark class="annotated-text">UK Biobank</mark>

# Keywords



# Abstract
  Highlights  
  
Applied deep learning to sex classification in UK BioBank fMRI connectomes. 
  
Deep learning classifies sex better in resting-state than in task fMRI. 
  …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8456752/"
                                       >PMC8456752</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ional brain networks from big data. 
  
sPROFUMO hierarchically estimates fMRI networks for the population and every individual. 
  
We characterised high dimensional resting state fMRI networks from <mark class="annotated-text">UK Biobank</mark>. 
  
Model outperforms ICA and dual regression for estimation of individual-specific network topography. 
  
We demonstrate the model&#39;s utility for predicting cognitive traits, and capturing subject …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8526871/"
                                       >PMC8526871</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ng a Gaussian kernel with FWHM = 6mm. 


### 2.3. Group independent component analysis 
  
We applied fully automated spatially constrained ICA using the NeuroMark approach [ ] on the 4D preprocessed <mark class="annotated-text">UK Biobank</mark> rs-fMRI data from Section 2.2. In the Neuromark approach, a template of replicable independent components (ICs) was constructed after spatially matching correlated group-level ICs between two healthy…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8782493/"
                                       >PMC8782493</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ghted MRI, T2-FLAIR, diffusion MRI (dMRI), resting-state functional MRI (fMRI), susceptibility-weighted imaging (swMRI), and arterial spin labelling (ASL), was defined in close approximation to prior <mark class="annotated-text">UK Biobank</mark> (UKB) and C-MORE protocols for Siemens 3T systems. We iteratively defined a comparable set of sequences for General Electric (GE) 3T systems. To assess multi-site feasibility and between-site variabi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9522299/"
                                       >PMC9522299</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ivided by the corresponding percentage in the background. 

The PheWeb database includes genome-wide associations for 1403 EHR-derived ICD billing codes from 408,908 White British participants of the <mark class="annotated-text">UK Biobank</mark> ( ). According to the repository   “All individuals were imputed using the Haplotype Reference Consortium panel, resulting in &gt;20 million variants. Analyses on binary outcomes were conducted using SA…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9842700/"
                                       >PMC9842700</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … al.,  ). 


### Network connectivity estimation 
  
In constructing functional connectomes, a data‐driven parcellation was obtained from a group‐level ICA in 4000 healthy older participants from the <mark class="annotated-text">UK Biobank</mark>. The original ICA analysis was set at 25 ICs, four of which were considered noise. The 21 signal ICs yielded 210 (i.e., ([21*21] − 21)/2) unique pairwise connections, each of which was examined separ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9875925/"
                                       >PMC9875925</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - adolescent brain cognitive development (14 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …nd children’s BMI. Methods: For this cross-sectional study, we used functional magnetic resonance imaging (fMRI) data of 6473 9–10-year-old Non-Hispanic Black and Non-Hispanic White children from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> (ABCD) study. The primary independent variable was putamen functional connectivity to the salience network, measured by fMRI. The primary outcome was the children’s BMI. Age, sex, neighborhood income…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8006001/"
                                       >PMC8006001</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es in children with lower levels of PAE with those of well-matched controls with no PAE. 


## Design, Setting, and Participants 
  
In this cross-sectional study, participants were selected from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> study. Children with PAE were compared with controls matched for age, sex, family income, maternal educational level, and caregiver status. Neither group had prenatal exposure to other adverse substa…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8984786/"
                                       >PMC8984786</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ed mortality. Early intervention in the initial stages of major depressive disorder and bipolar disorder can significantly improve personal health. 


## Methods 
  
We collected 309 samples from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> study, including 116 adolescents with bipolar disorder, 64 adolescents with major depressive disorder, and 129 healthy adolescents, and employed a support vector machine to develop classification mod…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9452797/"
                                       >PMC9452797</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s have been divided with respect to video gaming’s association with cognitive skills. 


## Objective 
  
To examine the association between video gaming and cognition in children using data from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> (ABCD) study. 


## Design, Setting, and Participants 
  
In this case-control study, cognitive performance and blood oxygen level–dependent (BOLD) signal were compared in video gamers (VGs) and non–…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9593235/"
                                       >PMC9593235</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ount for the relationships between cognitive abilities and socio‐demographic, psychological and genetic factors. For this, we leveraged the unique power of the large‐scale, longitudinal data from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> (ABCD) study (  n   ~ 11 k) and combined MRI data across modalities (task‐fMRI from three tasks: resting‐state fMRI, structural MRI and DTI) using machine‐learning. Our brain‐based, predictive models…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9704790/"
                                       >PMC9704790</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ciation with cognitive performance in US children. 


## Design, Setting, and Participants 
  
This cross-sectional study analyzed behavioral and imaging data from 9- to 11-year-old children from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> (ABCD) study between August 2017 and November 2018. The ABCD study is an open-science, multisite study following up more than 11 800 youths into early adulthood for 10 years with annual laboratory-ba…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9945095/"
                                       >PMC9945095</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …with diagnosis, treatment monitoring, and response prediction. 


## Data availability statement 
  
Publicly available datasets were analyzed in this study. This data can be found here: the datasets <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> Study:  . 


## Ethics statement 
  
The studies involving human participants were reviewed and approved by the Ethics Committee of ABCD. Written informed consent to participate in this study was pro…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9992191/"
                                       >PMC9992191</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … prediction of cognitive traits from structural and resting state functional MRI, which seems to account for little behavioral variability. We leverage baseline data from thousands of children in the <mark class="annotated-text">Adolescent Brain Cognitive Development  </mark>(ABCD ) Study to inform the replication sample size required with both univariate and multivariate methods across different imaging modalities to detect reproducible brain-behavior associations. We de…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10312746/"
                                       >PMC10312746</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …9 ms, 176 Slices, FOV: 256×256, Voxel Size: 1.0 mm, Bandwidth: 240 Hz/px) image was collected. 


#### ABCD dataset 
  
A large-scale group averaged resting-state functional connectivity map from the <mark class="annotated-text">Adolescent Brain Cognitive Development</mark> (ABCD) study was used to compare individual functional connectivity to averaged group data. This group average map used strict denoising (N = 3,928; &gt;8 min; RSFC data post frame censoring at a filter…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10705259/"
                                       >PMC10705259</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …all studies, as well as large-scale collection efforts with thousands of participants, given competing interests among multiple investigators and limited participant availability. 

Here, we used the <mark class="annotated-text">Adolescent Brain and Cognitive Development</mark> (ABCD) study and the Human Connectome Project (HCP) to systematically characterize the effects of sample size and scan duration of resting-state fMRI on BWAS prediction accuracy and reliability. We c…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10889017/"
                                       >PMC10889017</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - genomics superstruct project (14 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …rfMRI time series (not normalized), a dual regression (DR) procedure was employed [ ]. Specifically, spatial confidence maps   of the seven networks derived from 1,000 healthy adults [ ] of the Brain <mark class="annotated-text">Genomics Superstruct Project</mark> [ ] were employed in the first regression on individual rfMRI images to construct the characteristic time series   of the seven networks at individual level in  . These characteristic time series wer…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4694646/"
                                       >PMC4694646</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …t al.,  ). We retrospectively evaluated published video frames showing “lag threads” computed from real BOLD resting state rs-fMRI data in a group of 688 subjects, obtained from the Harvard-MGH Brain <mark class="annotated-text">Genomics Superstruct Project</mark>. We assessed 4 sets of coronal sections (including a total of 54 Images) from the published videos (Threads 1, 2, 3, and 4):  
  
We also analyzed 10 well-matched published pairs of networks, from th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5285359/"
                                       >PMC5285359</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …an inflated form, which facilitates data visualization. We used the fsaverage template from FreeSurfer version 4.5.0. 


### Data and FreeSurfer processing 
  
Data from 1,490 subjects from the Brain <mark class="annotated-text">Genomics Superstruct Project</mark> (GSP) were considered (Holmes et al.,  ). All imaging data were collected on matched 3T Tim Trio scanners using the vendor‐supplied 12‐channel phase‐array head coil. Subjects were clinically normal, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6239990/"
                                       >PMC6239990</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …dopted a method capable of identifying reliable ICNs that can be compared across datasets . The group template of ICNs was identified from two independent datasets (Human Connectome Project [HCP] and <mark class="annotated-text">Genomics Superstruct Project</mark> [GSP]) with large sample sizes (  N   = 1005 for GSP and   N   = 823 for HCP) and different temporal resolutions (see details in Supplementary Note  ), and was used as a reference within a spatially …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7414843/"
                                       >PMC7414843</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ated the effect of two denoising pipelines and different whole‐brain network constructions on reproducibility of subject‐specific graph measures. We used the multi‐session fMRI dataset from the Brain <mark class="annotated-text">Genomics Superstruct Project</mark> consisting of 69 healthy young adults. 


## Results 
  
In binary networks, the test–retest variability for global measures was large at low density irrespective of the denoising strategy or the typ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7428495/"
                                       >PMC7428495</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ion 2.2. In the Neuromark approach, a template of replicable independent components (ICs) was constructed after spatially matching correlated group-level ICs between two healthy control fMRI datasets—<mark class="annotated-text">genomics superstruct project</mark> (GSP) and human connectome project (HCP). The estimated network template was then used as a prior for a spatially constrained ICA algorithm applied to each UK Biobank subject individually. This ident…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8782493/"
                                       >PMC8782493</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s for each seed (each DBS target) were calculated using a high-quality normative 3 T resting state fMRI data set derived from 1000 healthy subjects (age range: 18–35 years; 57.6% female) of the Brain <mark class="annotated-text">Genomics Superstruct Project</mark> (BGSP,  ), as previously described.  The MRI acquisition and pre-processing parameters for the BGSP normative connectome are described in detail in the original publication.  In short, the data were …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9123846/"
                                       >PMC9123846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …perty for each subject. The unbiased spatial network templates were estimated using two large independent groups of HCs, that is, 1005 HCs from the Human Connectome Project (HCP) and 823 HCs from the <mark class="annotated-text">Genomics Superstruct Project</mark> (GSP), with the number of independent components (ICs) in ICA set to 100, followed by the selection of 53 reliable, reproducible, and meaningful networks as templates. The network templates can be do…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9294304/"
                                       >PMC9294304</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …nts for the data. These component templates were created via a unified ICA pipeline. They were constructed using an independent resting-state fMRI data with large samples of healthy subjects from the <mark class="annotated-text">genomics superstruct project</mark> (GSP). The GSP data include 1005 subjects’ scans that passed the data QC. High model order (order = 100) group ICA was performed on the GSP data, and then the independent components (ICs) from the GS…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9844250/"
                                       >PMC9844250</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … human RS-fMRI data (  N   = 2,010) were obtained from the control arms of primary studies designed, conducted, and analyzed external to the derivative study described herein. These include the Brain <mark class="annotated-text">Genomics Superstruct Project</mark> ( ) (GSP) and ongoing studies at Washington University in St. Louis, including healthy control data from the Alzheimer&#39;s Disease Research Center and Neurodegeneration studies ( ). All participants we…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9878609/"
                                       >PMC9878609</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - camcan (12 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …healthy MEG participants completed the task (23 males, mean age 33.7, range 21–41, 4 left-handed) as part of the population-based sample collected by the Cambridge Centre for Ageing and Neuroscience (<mark class="annotated-text">Cam-CAN</mark>,  ). Full protocols and exclusion criteria for this cohort are described by  . Participants gave written informed consent and ethical approval for the Cam-CAN study was obtained from the Cambridgeshi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4981429/"
                                       >PMC4981429</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … ). 


#### Participants 
  
##### Cam-CAN. 
  
We used the 253 adults (131 female) who were aged 18–47 (mean age 34.8, SD = 7.9) from the healthy, population-derived cohort tested in Stage II of the <mark class="annotated-text">Cam-CAN </mark>project ( ;  ). The majority of participants (  n   = 228) were definitively right-handed defined as a handedness measure of ≥50 on a scale of −100 (left) to 100 (right); definitively left-handed were…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6246887/"
                                       >PMC6246887</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ained Functional connectivity Analysis (DAFA), to deeply mine the important functional connectivity changes in fMRI during brain aging. First, using resting-state fMRI data from 421 subjects from the <mark class="annotated-text">CamCAN</mark> dataset, functional connectivities were calculated using sliding window method, and the complex functional patterns were mined by an AE. Then, to increase the statistical power and reliability of the…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6978665/"
                                       >PMC6978665</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tworks derived from resting-state fMRI scans of participants from the Cam-CAN project, a study on healthy ageing ( ). 


## Methods 
  
### Data 
  
The data were collected as part of Phase II of the <mark class="annotated-text">CamCAN</mark> project ( ;  ). The MRI data were acquired on a 3T Siemens TIM Trio at the MRC Cognition &amp; Brain Sciences Unit, with a 32 channel head-coil. Structural images were acquired using a 1mm  isotropic, T1…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7613122/"
                                       >PMC7613122</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …odel optimization is made with reference to (log)-model evidence, which accounts for both model accuracy and model complexity. 

We applied DCM to resting-state data from 635 adults aged 18–88 in the <mark class="annotated-text">CamCAN</mark> dataset [ ]. A notable finding was that neural and haemodynamic parameters were independent predictors of age, supporting the hypothesis of separable mechanisms leading to age alterations in neural a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7741031/"
                                       >PMC7741031</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ucibility of RSNs in three large independent cohorts comprising a total of 563 older healthy adults (age range: 55–95 years); accordingly, we analyzed data from the Center for Aging and Neuroscience (<mark class="annotated-text">CamCAN</mark>) project ( ;  ), the Southwest University Adult Lifespan Dataset (SALD) ( ) and the Alzheimer’s Disease Neuroimaging Initiative (ADNI) database ( ;  ); (2) to identify differences in the anatomical c…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7869083/"
                                       >PMC7869083</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, we applied the same MVB logic to test HAROLD in the context of motor activity related to simple finger presses across two motor fMRI experiments in the Cambridge Center for Ageing and Neuroscience (<mark class="annotated-text">Cam-CAN</mark>) population-derived adult life span sample ( ;  ). In experiment 1, participants (  N   = 586) pressed a button with their right index finger when they saw/heard a visual/auditory stimulus. In experi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8580140/"
                                       >PMC8580140</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ovided an opportunity for the problem we want to study. In this study, we used the resting-state functional magnetic resonance imaging (rs-fMRI) data from Cambridge Center for Aging and Neuroscience (<mark class="annotated-text">Cam-CAN</mark>) database with large sample and long lifespan, and computed the functional connectivity (FC) values for each individual. Based on these values, the hemispheric similarity of functional connectivity (…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9548650/"
                                       >PMC9548650</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …of our study were to: 1) identify the functional gradients of the LC and reproduce them across different cohorts and image resolutions, using a 3T (the Cambridge Centre for Ageing and Neuroscience or <mark class="annotated-text">CamCAN</mark> cohort) and a 7T (the Human Brain Connectome or HCP 7T cohort) datasets; 2) characterize how the functional gradients of the LC change over the course of aging in the CamCAN dataset, a large cohort o…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10274957/"
                                       >PMC10274957</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …hanges in ER accuracy and its association with magnetic resonance imaging (MRI) measures (both structural and functional), on data collected for the ‘The Cambridge Centre for Ageing and Neuroscience (<mark class="annotated-text">Cam-CAN</mark>)’ project ( ;  ), with two specific aims. First, to identify when differences in ER performance start to consistently appear along the lifespan. Secondly, across the age groups showing the first sign…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10612567/"
                                       >PMC10612567</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - midnight scan club (9 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …s; TE = 4.77 ms; TI = 1100 ms; voxel size = 1.0 mm × 1.0 mm × 1.0 m; flip angle = 7°). Only the T1-weighted image acquired during the first scan session was used. 

 Dataset 4.   The fourth dataset (‘<mark class="annotated-text">midnight scan club</mark>’) contained data from ten subjects (5 females; age range 24–35 years; see,  ). Participants were scanned at midnight on twelve consecutive days with a 3T Siemens Trio MRI scanner (Siemens, Erlangen, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6215332/"
                                       >PMC6215332</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …sults and figures is available at:  . 



## Data availability 
  
The following longitudinal datasets were used (and are accessible through):   
‘Myconnectome’: Downloaded from   (ds000031) 
  
‘The <mark class="annotated-text">Midnight Scan Club</mark>’: Downloaded from   (ds000224) 
  
‘Kirby Weekly’: Downloaded from  
  
‘Day2day’: For availability, see  ; section ‘Availability of data and materials’ (available upon request). 
  

The 900 subject…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7014820/"
                                       >PMC7014820</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …( ), and two smaller samples more well suited for test-retest reliability studies. The first small sample being the intrinsic brain activity test retest (IBATRT) dataset ( ), and the second being the <mark class="annotated-text">midnight scan club</mark> (MSC) dataset ( ). 

For the Cambridge Buckner data sample there were a total of 198 subjects (123 female), ages 18–30 (M = 21.03, SD = 2.31), with all subjects included in the final analysis. For th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7029189/"
                                       >PMC7029189</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ta, even when using limited amounts of per-subject data, compared to parallel analysis of SE data from the same participants and 14 densely sampled individuals from three SE datasets (n = 10 from the <mark class="annotated-text">Midnight Scan Club</mark> [MSC] [ ]; n = 3 from the Cast-induced Plasticity [CAST] study [ ]; n = 1 from the MyConnectome [MC] project [ ;  ]). This effect was linked to at least three biophysical signal mechanisms with spati…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7792478/"
                                       >PMC7792478</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s relatively low (mean framewise displacement [mean-FD]   &lt;   0.2 mm for each of 300 scans, less than 1% [   n   = 3] of time points within each scan has FD   &gt;   0.2 mm). 


#### MSC dataset 
  
The <mark class="annotated-text">Midnight Scan Club</mark> (MSC) dataset consists of 10 participants, who each participated in 10 fMRI sessions over ten days beginning at midnight ( ) ( ). Each session included 30 mins of resting fMRI using a gradient-echo E…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7983579/"
                                       >PMC7983579</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …oximately 200,000 validation samples (~15,000 per network) were generated from the held out scans. 


### 2.6. Testing data 
  
After training, model outputs were compared using RS-fMRI data from the <mark class="annotated-text">Midnight Scan Club</mark> ( ) (MSC) collected at Washington University. The MSC contains high quality data collected from 10 participants, each scanned for 30 min in 10 separate sessions. The MSC data are freely avaliable ( )…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9878609/"
                                       >PMC9878609</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …her the coupling nor input signals are directly observable. 


### FC Is Related to Shared and Unshared Input Variance in Real fMRI Data 
  
To compare communication and FC in empirical data, we used <mark class="annotated-text">Midnight Scan Club</mark> (MSC) dataset ( ), a precision fMRI dataset with 10 sessions of fMRI rest and task data from nine participants. See   for BOLD data acquisition, preprocessing, FC, and variance calculation for restin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10312287/"
                                       >PMC10312287</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …k. As tasks impact signal in a region‐wise fashion, they likely impact FC reliability differently across the brain, making task an important decision in study design. Here, we use the densely sampled <mark class="annotated-text">Midnight Scan Club</mark> (MSC) dataset, comprising 5 h of rest and 6 h of task fMRI data in 10 healthy adults, to investigate regional effects of tasks on FC reliability. We further considered how BOLD signal properties cont…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10884875/"
                                       >PMC10884875</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mics, two sets of ROIs, and two data sets. Code for computing dynamics of discrete states and their test–retest reliability used in the present paper is available on GitHub [ ]. 


## Methods 
  
### <mark class="annotated-text">Midnight Scan Club</mark> data 
  
We use the resting-state fMRI data provided by the Midnight Scan Club (MSC) project [ ]. The MSC’s resting-state fMRI data consist of recording from ten healthy human adults [age:   (average…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10913599/"
                                       >PMC10913599</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - natural scenes dataset (5 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …unrelated to the experiment. Third, to improve the stability of beta estimates for closely spaced trials, betas are regularized on a voxel-wise basis using ridge regression. Applying GLMsingle to the <mark class="annotated-text">Natural Scenes Dataset</mark> and BOLD5000, we find that GLMsingle substantially improves the reliability of beta estimates across visually-responsive cortex in all subjects. Comparable improvements in reliability are also observ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9708069/"
                                       >PMC9708069</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … encoding and create personalized synthetic images designed to achieve a targeted pattern of brain activity within a specific individual. 


## Materials and methods 
  
### Data description 
  
#### <mark class="annotated-text">Natural Scenes Dataset</mark> 
  
The individual encoding models were created using the Natural Scenes Dataset (NSD) . The informed consent for all subjects was obtained by NSD. Our data usage was approved by NSD, and complies wi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9759560/"
                                       >PMC9759560</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Leveraging the improved sensitivity of modern designs and statistical analyses, we identify two food-selective regions in the ventral visual cortex. Our results are robust across 8 subjects from the <mark class="annotated-text">Natural Scenes Dataset</mark> (NSD), multiple independent image sets and multiple analysis methods. We then test our findings of food selectivity in an fMRI “localizer” using grayscale food images. These independent results confi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9932019/"
                                       >PMC9932019</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …brain activity; only the free parameters of the read-out heads were optimized to predict brain activity (Fig.  c). 

To optimize the parameters of each type of encoding model (Fig.  c, d) we used the <mark class="annotated-text">Natural Scenes Dataset</mark> , a massive sampling of blood-oxygenation-level-depedendent (BOLD) activity in eight subjects using ultra-high field fMRI (7T, 1.8-mm resolution). Subjects each viewed 9000–10,000 natural scenes (sam…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10247700/"
                                       >PMC10247700</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …atterns for viewpoint and depth may differ between static and moving bodies, especially given the complexities of natural image input. 



## Materials and Methods 
  
### Stimulus Selection. 
  
The <mark class="annotated-text">Natural Scenes Dataset</mark> ( ) contains 73,000 cropped color natural scene images from the MS COCO dataset ( ). We aimed to select a subset of images that contain only single persons and cover a broad range of legitimate human…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11181088/"
                                       >PMC11181088</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - myconnectome (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …s for each subject. Altogether, the datasets contained 653 rsfMRI sessions. A summary of the datasets is shown in  .   
Subject information. 
  Table 1             

 Dataset 1.   The first dataset (‘<mark class="annotated-text">myconnectome</mark>’) was part of the MyConnectome project (see,  ). During this project, resting state fMRI scans were acquired from a single person (male, 45 years at the start of study) on 89 occasions over the perio…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6215332/"
                                       >PMC6215332</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ftware availability 
  
Code to reproduce analyses, results and figures is available at:  . 



## Data availability 
  
The following longitudinal datasets were used (and are accessible through):   
<mark class="annotated-text">‘Myconnectome’</mark>: Downloaded from   (ds000031) 
  
‘The Midnight Scan Club’: Downloaded from   (ds000224) 
  
‘Kirby Weekly’: Downloaded from  
  
‘Day2day’: For availability, see  ; section ‘Availability of data and…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7014820/"
                                       >PMC7014820</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … the same participants and 14 densely sampled individuals from three SE datasets (n = 10 from the Midnight Scan Club [MSC] [ ]; n = 3 from the Cast-induced Plasticity [CAST] study [ ]; n = 1 from the <mark class="annotated-text">MyConnectome</mark> [MC] project [ ;  ]). This effect was linked to at least three biophysical signal mechanisms with spatially distinct influences and replicated in two other less densely sampled participants. 


## RE…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7792478/"
                                       >PMC7792478</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - open access series imaging studies (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … in this study are collected from FBIRN (Function Biomedical Informatics Research Network )   project, from release 1.0 of ABIDE (Autism Brain Imaging Data Exchange )   and from release 3.0 of OASIS (<mark class="annotated-text">Open Access Series of Imaging Studies</mark> )  . Healthy controls from the HCP (Human Connectome Project) ( ) are used for gender prediction. Refer to   for details of the datasets. 

#### Preprocessing 
  
We use two typical brain parcellatio…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9844250/"
                                       >PMC9844250</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ciated with the same network subsystems that mediate the association between Aβ and episodic memory. 


## METHODS 
  
### Data 
  
Data used in the preparation of this article were obtained from the <mark class="annotated-text">Open Access Series of Imaging Studies</mark> (OASIS) database ( ; accessed: April 4, 2020), collected by the Washington University Knight Alzheimer Disease Research Center over the course of 15 years. Beyond OASIS inclusion criteria, the curren…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9875925/"
                                       >PMC9875925</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ity non-uniformity (INU) using N4BiasFieldCorrection, ( ) and used as T1w-reference throughout the workflow. The T1w-reference was then skull-stripped using antsBrainExtraction.sh (ANTs 2.2.0), using <mark class="annotated-text">Open Access Series of Imaging Studies</mark> (OASIS) as target template. Brain surfaces were reconstructed using recon-all [FreeSurfer 6.0.1,  , ( )], and the brain mask estimated previously was refined with a custom variation of the method to …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9933514/"
                                       >PMC9933514</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - southwest university longitudinal imaging multimodal (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …to validate our results in an independent sample to confirm the reliability and repeatability of our study  .   We tested and validated the main findings in dataset 1 by using an open access dataset [<mark class="annotated-text">Southwest University Longitudinal Imaging Multimodal </mark>(SLIM) Dataset (International Neuroimaging Data-Sharing Initiative (INDI),  )] (Liu   et al.  ,  ) that also contains rs-fMRI data and SWB measurement in a format identical to that of the behavioral a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6123521/"
                                       >PMC6123521</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … MRI scans were acquired at baseline and week 12 [ ,  ]. 

REST-meta-MDD study consists of resting state fMRI data in medication-naïve first episode and recurrent MDD from 17 sites in China [ ,  ]. 

<mark class="annotated-text">Southwest University</mark> (SWU) cohort consists of a community-based recruitment which includes first episode and recurrent MDD and healthy control participants [ – ]. 

Stanford University cohort consists of MRI data in firs…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9869598/"
                                       >PMC9869598</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ample of 120 undergraduate students. Then, we unpacked the neuro-cognitive association between insular connectivity and cognitive performance during an Iowa gambling fMRI task. Lastly, an independent <mark class="annotated-text">Open Southwest University Longitudinal Imaging Multimodal</mark> dataset was used to validate the results. Findings suggested that the dAI was predominantly connected to the prefrontal regions; the vAI was primarily connected to the AMG–ventral–striatum system; an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9977390/"
                                       >PMC9977390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - studyforrest (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …th fMRI scanning of participants viewing films—Stage II of the   Cambridge Centre for Aging and Neuroscience   (Cam-CAN,  ) project (for details, see  ) and the 3 T audiovisual movie dataset of the   <mark class="annotated-text">studyforrest</mark>   ( ) project (for details, see  ). 


#### Participants 
  
##### Cam-CAN. 
  
We used the 253 adults (131 female) who were aged 18–47 (mean age 34.8, SD = 7.9) from the healthy, population-derived …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6246887/"
                                       >PMC6246887</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …lly improves the reliability of beta estimates across visually-responsive cortex in all subjects. Comparable improvements in reliability are also observed in a smaller-scale auditory dataset from the <mark class="annotated-text">StudyForrest</mark> experiment. These improvements translate into tangible benefits for higher-level analyses relevant to systems and cognitive neuroscience. We demonstrate that GLMsingle: (i) helps decorrelate response…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9708069/"
                                       >PMC9708069</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … should be noted that the dynamics of the voxel cluster researched in this paper represent the dominant cognitive state dynamics. 


### Localizer for higher-visual areas 
  
We use the data from the <mark class="annotated-text">StudyForrest</mark> dataset  to test whether the locations of VRE-selected voxels are consistent with known functional anatomy, and explore the representation and operations, involved in higher-visual object-selective c…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10163018/"
                                       >PMC10163018</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - baby connectome project (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …box is  ). 

In our analysis, fifty three reproducible spatial references, denoted as  , were identified by analyzing two distinct fMRI datasets, namely the Genomics Superstruct Project (GSP) and the <mark class="annotated-text">Human Connectome Project</mark> (HCP). The GSP dataset comprises 1005 subjects while the HCP dataset has 823 subjects [ ]. These spatial references were derived using group ICA and are collectively referred to as the Neuromark fMRI…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10802620/"
                                       >PMC10802620</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …subtle, this distinction is worth considering and its implications are worth exploring in future studies. 



## METHODS 
  
### Materials. 
  
Our subjects were selected from 4 imaging datasets: the <mark class="annotated-text">Baby Connectome Project</mark> (BCP) , and the development, young-adult, and aging cohorts of the Human Connectome Project (HCP-D, HCP-YA, HCP-A) . Subjects in the BCP ranged from 16 days to 6 years old, with 276 subjects (126 mal…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11195193/"
                                       >PMC11195193</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffaa00;">
        <summary class="label-display">used hcp pipeline (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …lin maps, performs precise within-individual cross-modal registrations, and carries out volume-based registrations to standard spaces. The one-step resampling procedure is a small portion of the full <mark class="annotated-text">Human Connectome Project (HCP) processing pipeline</mark>, which subsequently uses a surface-based approach with numerous further advantages ( ;  ;  ;  ). However, volumetric approaches continue to enjoy widespread popularity as lower resolution fMRI data r…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10541115/"
                                       >PMC10541115</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ing directions were performed (TR = 7560 ms, TE = 64 ms, FOV = 192 × 192 mm , FA = 90°/180°, matrix size = 96 × 96, 60 slices, slice thickness = 2 mm, and phase partial Fourier = 6/8). 

To apply the <mark class="annotated-text">Human Connectome Project</mark> (HCP) pipelines to our data, a series of structural images from all subjects were obtained on a day other than the testing day. Two separate sets of T1- and T2-weighted images were acquired using a 3…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10690858/"
                                       >PMC10690858</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - bold5000 (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …. Third, to improve the stability of beta estimates for closely spaced trials, betas are regularized on a voxel-wise basis using ridge regression. Applying GLMsingle to the Natural Scenes Dataset and <mark class="annotated-text">BOLD5000</mark>, we find that GLMsingle substantially improves the reliability of beta estimates across visually-responsive cortex in all subjects. Comparable improvements in reliability are also observed in a small…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9708069/"
                                       >PMC9708069</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - individual brain charting (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …elcher, David and Pessiglione, Mathias and van Wassenhove, Virginie and Eger, Evelyn and Varoquaux, Gaël and Dehaene, Stanislas and Hertz-Pannier, Lucie and Thirion, Bertrand
Sci Data, 2020

# Title

<mark class="annotated-text">Individual Brain Charting</mark> dataset extension, second release of high-resolution fMRI data for cognitive mapping

# Keywords

Brain imaging
Cognitive neuroscience
Human behaviour
Functional magnetic resonance imaging


# Abstra…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7567863/"
                                       >PMC7567863</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">stopped here (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - amsterdam open mri collection (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - human brain charting (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - narratives data (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #f9f06b;">
        <summary class="label-display">ds - neuromod (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #aec7e8;">
        <summary class="label-display">not sure (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
</div>
"""
displays.HTMLDisplay(text)
```