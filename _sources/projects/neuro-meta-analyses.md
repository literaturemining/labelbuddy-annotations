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


# neuro-meta-analyses

You can see the full contents of this project [on GitHub](https://github.com/neurodatascience/labelbuddy-annotations/tree/main/projects/neuro-meta-analyses/).

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
    
    <details style="--label-color: #babdb6;">
        <summary class="label-display">DONE (but did not look into full paper) (677 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Dugré</mark>, Jules Roger and Potvin, Stéphane
Psychol Med, 2021

# Title

Impaired attentional and socio-affective networks in subjects with antisocial behaviors: a meta-analysis of resting-state functional conn…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Houenou</mark>, Josselin and Frommberger, Juliane and Carde, Soufiane and Glasbrenner, Manuela and Diener, Carsten and Leboyer, Marion and Wessa, Michèle
J Affect Disord, 2011

# Title

Neuroimaging-based markers o…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Teghil</mark>, Alice and Boccia, Maddalena and D&#39;Antonio, Fabrizia and Di Vita, Antonella and de Lena, Carlo and Guariglia, Cecilia
Neurosci Biobehav Rev, 2019

# Title

Neural substrates of internally-based and e…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Yang</mark>, Jie and Andric, Michael and Mathew, Mili M
Neurosci Biobehav Rev, 2015

# Title

The neural basis of hand gesture comprehension: A meta-analysis of functional magnetic resonance imaging studies.

# …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Kim</mark>, Jeffrey J and Cunnington, Ross and Kirby, James N
Neurosci Biobehav Rev, 2020

# Title

The neurophysiological basis of compassion: An fMRI meta-analysis of compassion and its related neural process…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Picó</mark>-Pérez, Maria and Moreira, Pedro Silva and de Melo Ferreira, Vanessa and Radua, Joaquim and Mataix-Cols, David and Sousa, Nuno and Soriano-Mas, Carles and Morgado, Pedro
Neurosci Biobehav Rev, 2020

#…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Nilsson</mark>, Martin and Kalckert, Andreas
Eur J Neurosci, 2021

# Title

Region-of-interest analysis approaches in neuroimaging studies of body ownership: An activation likelihood estimation meta-analysis.

# Ke…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Müller</mark>, Veronika I and Cieslik, Edna C and Laird, Angela R and Fox, Peter T and Radua, Joaquim and Mataix-Cols, David and Tench, Christopher R and Yarkoni, Tal and Nichols, Thomas E and Turkeltaub, Peter E …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Goutte</mark>, C and Hansen, L K and Liptrot, M G and Rostrup, E
Hum Brain Mapp, 2001

# Title

Feature-space clustering for fMRI meta-analysis.

# Keywords



# Abstract
Clustering functional magnetic resonance i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Eyler</mark>, Lisa T and Elman, Jeremy A and Hatton, Sean N and Gough, Sarah and Mischel, Anna K and Hagler, Donald J and Franz, Carol E and Docherty, Anna and Fennema-Notestine, Christine and Gillespie, Nathan a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">N studies included (545 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Kim, Hongkeun
Neuroimage, 2011

# Title

Neural activity that predicts subsequent memory and forgetting: a meta-analysis of <mark class="annotated-text">74</mark> fMRI studies.

# Keywords



# Abstract
The present study performed a quantitative meta-analysis of functional MRI studies that used a subsequent memory approach. The meta-analysis considered both su…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Postuma, Ronald B and Dagher, Alain
Cereb Cortex, 2006

# Title

Basal ganglia functional connectivity based on a meta-analysis of <mark class="annotated-text">126</mark> positron emission tomography and functional magnetic resonance imaging publications.

# Keywords



# Abstract
The striatum receives projections from the entire cerebral cortex. Different, but not mu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Hoffman, Paul and Morcom, Alexa M
Neurosci Biobehav Rev, 2018

# Title

Age-related changes in the neural networks supporting semantic cognition: A meta-analysis of <mark class="annotated-text">47</mark> functional neuroimaging studies.

# Keywords

Default mode network
Multiple demand network
Semantic memory
fMRI

# Abstract
Semantic cognition is central to understanding of language and the world an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Martin, Anna and Kronbichler, Martin and Richlan, Fabio
Hum Brain Mapp, 2016

# Title

Dyslexic brain activation abnormalities in deep and shallow orthographies: A meta-analysis of <mark class="annotated-text">28</mark> functional neuroimaging studies.

# Keywords

PET
dyslexia
fMRI
language
orthographic depth
reading

# Abstract
We used coordinate-based meta-analysis to objectively quantify commonalities and differ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Wager, Tor D and Smith, Edward E
Cogn Affect Behav Neurosci, 2003

# Title

Neuroimaging studies of working memory: a meta-analysis.

# Keywords



# Abstract
We performed meta-analyses on <mark class="annotated-text">60</mark> neuroimaging (PET and fMRI) studies of working memory (WM), considering three types of storage material (spatial, verbal, and object), three types of executive function (continuous updating of WM, me…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Sergi G and Brammer, Michael J and David, Anthony S and Fu, Cynthia H Y
Brain Res Rev, 2008

# Title

Predictors of amygdala activation during the processing of emotional stimuli: a meta-analysis of <mark class="annotated-text">385</mark> PET and fMRI studies.

# Keywords



# Abstract
Although amygdala activity has been purported to be modulated by affective and non-affective factors, considerable controversy remains on its precise f…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ui and Liu, Han-Hui and Yue, Chun-Lin and Lu, Guang-Ming and Zuo, Xi-Nian
Neurosci Biobehav Rev, 2015

# Title

Putting age-related task activation into large-scale brain networks: A meta-analysis of <mark class="annotated-text">114</mark> fMRI studies on healthy aging.

# Keywords

Aging
Cognitive control
Connectomics
Default mode
Neural network

# Abstract
Normal aging is associated with cognitive decline and underlying brain dysfunc…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ui and Liu, Han-Hui and Yue, Chun-Lin and He, Yong and Zuo, Xi-Nian
Hum Brain Mapp, 2015

# Title

Toward systems neuroscience in mild cognitive impairment and Alzheimer&#39;s disease: a meta-analysis of <mark class="annotated-text">75</mark> fMRI studies.

# Keywords

Alzheimer&#39;s disease
default mode
fMRI
mild cognitive impairment
neuronal network

# Abstract
Most of the previous task functional magnetic resonance imaging (fMRI) studies …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Jinhui and Jia, Chuchu and Liao, Jiajun and Chen, Kemeng and Qiu, Lixin and Yuan, Zhen and Huang, Ruiwang
Neuroimage, 2022

# Title

Neural correlates of transitive inference: An SDM meta-analysis on <mark class="annotated-text">32</mark> fMRI studies.

# Keywords

Cognitive map
Decision making
Flexible learning
Memory integration
Transitive inference

# Abstract
Transitive inference (TI) is a critical capacity involving the integrati…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …i, 2014

# Title

Patterns of cortico-limbic activations during visual processing of sad faces in depression patients: a coordinate-based meta-analysis.

# Keywords



# Abstract
The author retrieved <mark class="annotated-text">10</mark> functional magnetic resonance imaging studies about visual tasks for emotional faces in subjects with depression. The activation foci were then summarized and entered into a coordinate-based meta-ana…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-ALE (427 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Kirby, Lauren A J and Robinson, Jennifer L
Brain Cogn, 2017

# Title

Affective mapping: An <mark class="annotated-text">activation likelihood estimation</mark> (ALE) meta-analysis.

# Keywords

Activation likelihood estimation
Affect programs
Brainmap
Emotion
Neuroimaging
fMRI

# Abstract
Functional neuroimaging has the spatial resolution to explain the neu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Huang, Yujing and Su, Li and Ma, Qingguo
Neurosci Lett, 2020

# Title

The Stroop effect: An <mark class="annotated-text">activation likelihood estimation</mark> meta-analysis in healthy young adults.

# Keywords

ALE meta-analysis
Frontal network
Interference effect
Stroop
Young

# Abstract
Age plays a significant role in executive control processes in the S…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Turesky, Ted K and Turkeltaub, Peter E and Eden, Guinevere F
Front Aging Neurosci, 2016

# Title

An <mark class="annotated-text">Activation Likelihood Estimation</mark> Meta-Analysis Study of Simple Motor Movements in Older and Young Adults.

# Keywords

PET
aging
fMRI
finger
meta-analysis
motor
movement
neuroimaging

# Abstract
The functional neuroanatomy of finger…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Ran, Guangming and Cao, Xiaojun and Chen, Xu
Conscious Cogn, 2018

# Title

Emotional prediction: An <mark class="annotated-text">ALE</mark> meta-analysis and MACM analysis.

# Keywords

ALE
Dorsolateral prefrontal cortex
Emotional prediction
MACM
Orbitofrontal cortex
Ventrolateral prefrontal cortex

# Abstract
The prediction of emotion h…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Mothersill, O and Donohoe, G
Psychol Med, 2016

# Title

Neural effects of social environmental stress - an <mark class="annotated-text">activation likelihood estimation</mark> meta-analysis.

# Keywords

Functional magnetic resonance imaging
meta-analyses
social stress

# Abstract
Social environmental stress, including childhood abuse and deprivation, is associated with in…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Kim, Hongkeun
Hum Brain Mapp, 2013

# Title

Differential neural activity in the recognition of old versus new events: an <mark class="annotated-text">activation likelihood estimation</mark> meta-analysis.

# Keywords



# Abstract
This study presents a meta-analysis comparing hit and correct rejection (CR) conditions across 48 fMRI studies. Old/new (hit &gt; CR) effects associated most con…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Mauchand, Maël and Zhang, Shuyi
Cogn Affect Behav Neurosci, 2023

# Title

Disentangling emotional signals in the brain: an <mark class="annotated-text">ALE</mark> meta-analysis of vocal affect perception.

# Keywords

Brain
Emotion
Neuroimaging
Prosody
fMRI

# Abstract
Recent advances in neuroimaging research on vocal emotion perception have revealed voice-sen…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Rehme, Anne K and Eickhoff, Simon B and Rottschy, Claudia and Fink, Gereon R and Grefkes, Christian
Neuroimage, 2012

# Title

<mark class="annotated-text">Activation likelihood estimation</mark> meta-analysis of motor-related neural activity after stroke.

# Keywords



# Abstract
Over the past two decades, several functional neuroimaging experiments demonstrated changes in neural activity i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Amanzio, Martina and Benedetti, Fabrizio and Porro, Carlo A and Palermo, Sara and Cauda, Franco
Hum Brain Mapp, 2013

# Title

<mark class="annotated-text">Activation likelihood estimation</mark> meta-analysis of brain correlates of placebo analgesia in human experimental pain.

# Keywords



# Abstract
Placebo analgesia (PA) is one of the most studied placebo effects. Brain imaging studies p…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Bernstein, Lori J and Edelstein, Kim and Sharma, Alisha and Alain, Claude
Neurosci Biobehav Rev, 2021

# Title

Chemo-brain: An <mark class="annotated-text">activation likelihood estimation</mark> meta-analysis of functional magnetic resonance imaging studies.

# Keywords

Activation likelihood estimation
Cancer
Cancer-related cognitive dysfunction
Chemo-brain
Chemotherapy-Related cognitive im…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA1 (293 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …visual

# Abstract
This meta-analysis compares the brain structures and mechanisms involved in facial and vocal emotion recognition. Neuroimaging studies contrasting emotional with neutral (face: N = <mark class="annotated-text">76</mark>, voice: N = 34) and explicit with implicit emotion processing (face: N = 27, voice: N = 20) were collected to shed light on stimulus and goal-driven mechanisms, respectively. Activation likelihood es…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …view
Traumatic brain injury
Working memory

# Abstract
The aim of this review is to systematically examine the literature concerning multicomponent working memory (WM)-comprising a central executive (<mark class="annotated-text">CE</mark>), two storage components (phonological loop, PL and visuo-spatial sketchpad, VSSP), and episodic buffer (EB)-in pediatric traumatic brain injury (TBI). Electronic searches were conducted of MEDLINE, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …analysis is to identify brain regions that are commonly activated in functional magnetic resonance imaging studies (fMRI) investigating number processing and calculation in children. Here, we include <mark class="annotated-text">19</mark> developmental fMRI papers, five of which also examine children diagnosed with developmental dyscalculia and/or mathematical disability. Results reveal that children produce consistent fronto-parietal…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e regarding greater neural responses to a deviant stimulus in a stream of repeated, standard stimuli, termed here oddball effects. The meta-analysis of 75 independent studies included a comparison of <mark class="annotated-text">auditory</mark> and visual oddball effects and task-relevant and task-irrelevant oddball effects. The results were interpreted with reference to the model in which a large-scale dorsal frontoparietal network embodie…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …xperiments of inhibition or reasoning were selected. First level analysis consisted of Analysis of Likelihood Estimation (ALE) studies performed in two pooled data groups: (a) brain areas involved in <mark class="annotated-text">reasoning</mark> and (b) brain areas involved in inhibition. Second level analysis consisted of two contrasts: (i) brain areas involved in reasoning but not in inhibition and (ii) brain areas involved in inhibition b…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s, several neuroimaging studies have investigated the neural correlates of guilt, but no meta-analyses have yet identified the most robust activation patterns. A systematic review of literature found <mark class="annotated-text">16</mark> functional magnetic resonance imaging studies with whole-brain analyses meeting the inclusion criteria, for a total of 325 participants and 135 foci of activation. A meta-analysis was then conducted …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ract
This meta-analysis evaluated the extent to which executive function can be understood with structural and functional magnetic resonance imaging. Studies included structural in schizophrenia (k = <mark class="annotated-text">8</mark>; n = 241) and healthy controls (k = 12; n = 1660), and functional in schizophrenia (k = 4; n = 104) and healthy controls (k = 12; n = 712). Results revealed a positive association in the brain behavi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … years, which raises the need for an integrative framework. This study proposes a taxonomy of episodic memory formation to address this need. At the broadest level, the taxonomy distinguishes between <mark class="annotated-text">attention</mark>-driven vs. significance-driven memory formation. The three subtypes of attention-driven memory formation are selection-, fluctuation-, and level-related. The three subtypes of significance-driven mem…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …abnormalities between alphabetic languages differing in orthographic depth. Specifically, we compared foci of under- and overactivation in dyslexic readers relative to nonimpaired readers reported in <mark class="annotated-text">14</mark> studies in deep orthographies (DO: English) and in 14 studies in shallow orthographies (SO: Dutch, German, Italian, Swedish). The separate meta-analyses of the two sets of studies showed universal re…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …r, the neural mechanisms underlying abnormal EF in ASD remain unclear. This meta-analysis investigated the construct, abnormalities, and age-related changes of EF in ASD. Thirty-three fMRI studies of <mark class="annotated-text">inhibition</mark>, updating, and switching in individuals with high-functioning ASD were included (n = 1114; age range 7-57 years). The results revealed that the EF construct in ASD could be unitary (i.e., common EF) …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA2 (261 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …act
This meta-analysis compares the brain structures and mechanisms involved in facial and vocal emotion recognition. Neuroimaging studies contrasting emotional with neutral (face: N = 76, voice: N = <mark class="annotated-text">34</mark>) and explicit with implicit emotion processing (face: N = 27, voice: N = 20) were collected to shed light on stimulus and goal-driven mechanisms, respectively. Activation likelihood estimations were …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …regions that are commonly activated in functional magnetic resonance imaging studies (fMRI) investigating number processing and calculation in children. Here, we include 19 developmental fMRI papers, <mark class="annotated-text">five</mark> of which also examine children diagnosed with developmental dyscalculia and/or mathematical disability. Results reveal that children produce consistent fronto-parietal activation patterns in response…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …reater neural responses to a deviant stimulus in a stream of repeated, standard stimuli, termed here oddball effects. The meta-analysis of 75 independent studies included a comparison of auditory and <mark class="annotated-text">visual</mark> oddball effects and task-relevant and task-irrelevant oddball effects. The results were interpreted with reference to the model in which a large-scale dorsal frontoparietal network embodies a mechani…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ral substrates remains unclear. To address this issue, this study provides a direct, meta-analytic comparison of functional neuroimaging studies involving EM and IM tasks. The meta-analysis comprised <mark class="annotated-text">two</mark> separate meta-analytic comparisons. First, to compare EM and IM in terms of encoding activity, subsequent memory effects (remembered &gt; forgotten) and repetition suppression effects (first &gt; repeated)…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … selected. First level analysis consisted of Analysis of Likelihood Estimation (ALE) studies performed in two pooled data groups: (a) brain areas involved in reasoning and (b) brain areas involved in <mark class="annotated-text">inhibition</mark>. Second level analysis consisted of two contrasts: (i) brain areas involved in reasoning but not in inhibition and (ii) brain areas involved in inhibition but not in reasoning. Lateralization Indexes…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …he literature concerning multicomponent working memory (WM)-comprising a central executive (CE), two storage components (phonological loop, PL and visuo-spatial sketchpad, VSSP), and episodic buffer (<mark class="annotated-text">EB</mark>)-in pediatric traumatic brain injury (TBI). Electronic searches were conducted of MEDLINE, PsychINFO and EMBASE up to October 2014 with the inclusion criteria of children and adolescents with TBI, an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …l mechanisms underlying abnormal EF in ASD remain unclear. This meta-analysis investigated the construct, abnormalities, and age-related changes of EF in ASD. Thirty-three fMRI studies of inhibition, <mark class="annotated-text">updating</mark>, and switching in individuals with high-functioning ASD were included (n = 1114; age range 7-57 years). The results revealed that the EF construct in ASD could be unitary (i.e., common EF) in childre…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g a variety of stimuli and tasks instructions. By using activation likelihood estimation (ALE) meta-analysis we tested whether different MR networks can be modulated by the type of stimulus (body vs. <mark class="annotated-text">non-body </mark>parts) or by the type of tasks instructions (motor imagery-based vs. non-motor imagery-based MR instructions). Testing for the bodily and non-bodily stimulus axis revealed a bilateral sensorimotor act…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …the need for an integrative framework. This study proposes a taxonomy of episodic memory formation to address this need. At the broadest level, the taxonomy distinguishes between attention-driven vs. <mark class="annotated-text">significance</mark>-driven memory formation. The three subtypes of attention-driven memory formation are selection-, fluctuation-, and level-related. The three subtypes of significance-driven memory formation are novelt…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …extent to which executive function can be understood with structural and functional magnetic resonance imaging. Studies included structural in schizophrenia (k = 8; n = 241) and healthy controls (k = <mark class="annotated-text">12</mark>; n = 1660), and functional in schizophrenia (k = 4; n = 104) and healthy controls (k = 12; n = 712). Results revealed a positive association in the brain behavior relationship when pooled across schi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">DONE (222 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Peiffer, <mark class="annotated-text">Ann</mark> M. and Maldjian, Joseph A. and Laurienti, Paul J.
Int J Biomed Imaging, 2007

# Title

Resurrecting Brinley Plots for a Novel Use: Meta-Analyses of Functional Brain Imaging Data in Older Adults

# Ke…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2233772/"
                                       >PMC2233772</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Costafreda, Sergi G.
nan, 2009

# Title

<mark class="annotated-text">Pooling fMRI Data: Meta-Analysis, Mega-Analysis and Multi-Center Studies
</mark>
# Keywords

fMRI
meta-analysis
mega-analysis
multi-center studies
power
false positive results
random effects analysis
study design


# Abstract
 
The quantitative analysis of pooled data from relate…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2759345/"
                                       >PMC2759345</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Sugranyes</mark>, Gisela and Kyriakopoulos, Marinos and Corrigall, Richard and Taylor, Eric and Frangou, Sophia
PLoS ONE, 2011

# Title

Autism Spectrum Disorders and Schizophrenia: Meta-Analysis of the Neural Correl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3187762/"
                                       >PMC3187762</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Huang</mark>, Wenjing and Pach, Daniel and Napadow, Vitaly and Park, Kyungmo and Long, Xiangyu and Neumann, Jane and Maeda, Yumi and Nierhaus, Till and Liang, Fanrong and Witt, Claudia M.
PLoS ONE, 2012

# Title
…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3322129/"
                                       >PMC3322129</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Hayes</mark>, Jasmeet P and Hayes, Scott M and Mikedis, Amanda M
Biol Mood Anxiety Disord, 2012

# Title

Quantitative meta-analysis of neural activity in posttraumatic stress disorder

# Keywords

Activation lik…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3430553/"
                                       >PMC3430553</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Hattingh</mark>, Coenraad J. and Ipser, J. and Tromp, S. A. and Syal, S. and Lochner, C. and Brooks, S. J. and Stein, D. J.
Front Hum Neurosci, 2012

# Title

Functional magnetic resonance imaging during emotion rec…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3547329/"
                                       >PMC3547329</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Von</mark> Der Heide, Rebecca J. and Skipper, Laura M. and Olson, Ingrid R.
Front Hum Neurosci, 2013

# Title

Anterior temporal face patches: a meta-analysis and empirical study

# Keywords

social networks
an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3561664/"
                                       >PMC3561664</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Bernard</mark>, Jessica A. and Seidler, Rachael D.
Front Hum Neurosci, 2013

# Title

Cerebellar contributions to visuomotor adaptation and motor sequence learning: an ALE meta-analysis

# Keywords

cerebellum
sequ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Crepaldi</mark>, Davide and Berlingeri, Manuela and Cattinelli, Isabella and Borghese, Nunzio A. and Luzzatti, Claudio and Paulesu, Eraldo
Front Hum Neurosci, 2013

# Title

Clustering the lexicon in the brain: a me…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3695563/"
                                       >PMC3695563</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Jamadar</mark>, Sharna D. and Fielding, Joanne and Egan, Gary F.
Front Psychol, 2013

# Title

Quantitative meta-analysis of fMRI and PET studies reveals consistent activation in fronto-striatal-parietal regions an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3797465/"
                                       >PMC3797465</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-gingerale (147 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Kurkela, Kyle A and Dennis, Nancy A
Neuropsychologia, 2016

# Title

Event-related fMRI studies of false memory: An Activation Likelihood Estimation meta-analysis.

# Keywords

Encoding
False memory
<mark class="annotated-text">GingerALE</mark>
Meta-analysis
Retrieval
fMRI

# Abstract
Over the last two decades, a wealth of research in the domain of episodic memory has focused on understanding the neural correlates mediating false memories, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …chio, Nicola and Fedeli, Davide and Abutalebi, Jubin
Neurosci Biobehav Rev, 2020

# Title

Bilingual language processing: A meta-analysis of functional neuroimaging studies.

# Keywords

Bilingualism
<mark class="annotated-text">GingerALE</mark>
Language
Meta-analysis
PET
fMRI

# Abstract
Notwithstanding rising interest, a coherent picture of the brain&#39;s representation of two languages has not yet been achieved. In the present meta-analysis …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ra and Fabbro, Franco
Front Hum Neurosci, 2021

# Title

Effects of Linguistic Distance on Second Language Brain Activations in Bilinguals: An Exploratory Coordinate-Based Meta-Analysis.

# Keywords

<mark class="annotated-text">Ginger-ALE </mark>meta-analysis
age of appropriation (AoA)
bilingualism
fMRI
language families
linguistic distance

# Abstract
In this quantitative meta-analysis, we used the activation likelihood estimation (ALE) appr…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …

# Title

Neural correlates of aversive anticipation: An activation likelihood estimate meta-analysis across multiple sensory modalities.

# Keywords

ALE meta-analysis
Anxiety
Aversive anticipation
<mark class="annotated-text">GingerALE</mark>
fMRI

# Abstract
Anticipation is a universal preparatory response essential to the survival of an organism. Although meta-analytic synthesis of the literature exists for the anticipation of reward, a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …iewed the literature and performed a meta-analysis of functional magnetic resonance imaging (fMRI) studies in HIV-infected individuals using a well validated tool recently developed for use in fMRI, &#39;<mark class="annotated-text">GingerALE</mark>&#39;. Twenty-one studies (468 HIV+, 270 HIV- controls) were qualitatively reviewed, of which six (105 HIV+, 102 controls) utilized fMRI paradigms engaging the fronto-striatal-parietal network, making a q…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …related brain regions in patients with mild traumatic brain injury (mTBI). The databases PubMed, Ovid, Cochrane Library, Google Scholar, CNKI, WFSD, and VIP were systematically searched. The software <mark class="annotated-text">Ginger-ALE</mark> 3.0.2 was used for coordinate unification and meta-analysis. Seven studies with a total of 314 subjects were included. Meta-analysis results indicated that compared with healthy subjects, mTBI patien…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g cerebellar damage. To improve the characterization of emotion processing and investigate how attention allocation impacts this processing, we conducted a meta-analysis on task activation foci using <mark class="annotated-text">GingerALE</mark> software. Eighty human neuroimaging studies of emotion including 2761 participants identified through Web of Science and ProQuest databases were analyzed collectively and then divided into two catego…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … regions are altered along with anomalies in the attentional systems during cognitive deployment in bipolar disorder. An activation likelihood estimation meta-analysis of attentional activities using <mark class="annotated-text">GingerALE</mark> software was completed for adult and pediatric bipolar disorder populations in all published studies till December 2017. The meta-analysis of all fMRI studies included a total of ten pediatric studie…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …TSD to develop a robust mechanistic understanding of the related brain dysfunction. We identified primary studies through a comprehensive literature search of the MEDLINE and PsychINFO databases. The <mark class="annotated-text">GingerALE</mark> software (version 2.3.6) from the BrainMap Project was used to conduct activation likelihood estimation meta-analyses of the eligible studies for cognition, emotion and interface of both. Relative to…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tabases, yielded 116 functional magnetic resonance imaging and positron emission tomography studies that met the criteria. Coordinates that directly compared TD with either RD or MD were entered into <mark class="annotated-text">GingerALE</mark> (Brainmap.org). An activation likelihood estimate (ALE) meta-analysis was conducted to examine common and unique brain regions for RD and MD. Overall, more studies examined RD (n = 96) than MD (n = 2…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">exclude (146 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Lange, N
Hum Brain Mapp, 1997

# Title

<mark class="annotated-text">Empirical and substantive models, the Bayesian paradigm, and meta-analysis in functional brain imaging.
</mark>
# Keywords



# Abstract
Functional neuroimaging research is currently rediscovering and adapting established statistical methods for its use, including design of experiments, the general linear mode…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Miyahara, Motohide
Front Integr Neurosci, 2013

# Title

<mark class="annotated-text">Meta review of systematic and meta analytic reviews on movement differences, effect of movement based interventions, and the underlying neural mechanisms in autism spectrum disorder.
</mark>
# Keywords

MRI and fMRI
autism
developmental coordination disorder
motor development
movement

# Abstract
To identify and appraise evidence from published systematic and meta analytic reviews on (1)…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Han, Hyemin and Park, Joonsuk
Cogn Neurosci, 2019

# Title

<mark class="annotated-text">Bayesian meta-analysis of fMRI image data.
</mark>
# Keywords

-value
Bayes factors
Bayesian inference
Bayesian random-effect meta-analysis
fMRI
meta-analysis

# Abstract
We composed an R-based script for Image-based Bayesian random-effect meta-analy…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Kwee, Robert M and Kwee, Thomas C
Eur Radiol, 2022

# Title

<mark class="annotated-text">Diagnostic performance of MRI in detecting locally recurrent soft tissue sarcoma: systematic review and meta-analysis.
</mark>
# Keywords

Magnetic resonance imaging
Meta-analysis
Recurrence
Sarcoma
Systematic review

# Abstract
To systematically review the diagnostic criteria and performance of MRI in detecting locally recu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Suzuki, Keita and Yamashita, Okito
Neuroimage, 2021

# Title

<mark class="annotated-text">MEG current source reconstruction using a meta-analysis fMRI prior.
</mark>
# Keywords

Hierarchical Bayesian method
MEG inverse problem
Meta-analysis
Source reconstruction
fMRI

# Abstract
Magnetoencephalography (MEG) offers a unique way to noninvasively investigate millise…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Dugré, Jules Roger and Potvin, Stéphane
Psychol Med, 2021

# Title

<mark class="annotated-text">Impaired attentional and socio-affective networks in subjects with antisocial behaviors: a meta-analysis of resting-state functional connectivity studies.
</mark>
# Keywords

Functional connectivity
antisocial behaviors
conduct disorder
default mode network
dorsal attention network
ventral attention network

# Abstract
In the past decade, there has been a grow…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Ramsey, J D and Spirtes, P and Glymour, C
Neuroimage, 2011

# Title

<mark class="annotated-text">On meta-analyses of imaging data and the mixture of records.
</mark>
# Keywords



# Abstract
Neumann et al. (2010) aim to find directed graphical representations of the independence and dependence relations among activities in brain regions by applying a search proce…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Smith, David V and Delgado, Mauricio R
Hum Brain Mapp, 2017

# Title

<mark class="annotated-text">Meta-analysis of psychophysiological interactions: Revisiting cluster-level thresholding and sample sizes.
</mark>
# Keywords

CBMA
PPI
fMRI
meta-analysis
open science
psychophysiological interaction

# Abstract
Within the neuroimaging community, coordinate based meta-analyses (CBMAs) are essential for aggregatin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Dudek, Emily and Dodell-Feder, David
Neurosci Biobehav Rev, 2021

# Title

<mark class="annotated-text">The efficacy of real-time functional magnetic resonance imaging neurofeedback for psychiatric illness: A meta-analysis of brain and behavioral outcomes.
</mark>
# Keywords

Functional magnetic resonance imaging
Intervention
Meta-analysis
Neurofeedback
Neuromodulation
Psychiatric illness
Psychopathology
Real-time fMRI

# Abstract
Real-time functional magnetic…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Stevens, Jennifer S and Jovanovic, Tanja
Genes Brain Behav, 2019

# Title

<mark class="annotated-text">Role of social cognition in post-traumatic stress disorder: A review and meta-analysis.
</mark>
# Keywords

G × SE
PTSD
fMRI
face stimuli
genetic risk
meta-analysis
neuroimaging
social brain
social cognition
trauma exposure

# Abstract
Social functioning is a key component of recovery after a p…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA3 (141 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Martin, Anna and Kronbichler, Martin and Richlan, Fabio
Hum Brain Mapp, 2016

# Title

Dyslexic brain activation abnormalities in deep and shallow orthographies: A meta-analysis of <mark class="annotated-text">28</mark> functional neuroimaging studies.

# Keywords

PET
dyslexia
fMRI
language
orthographic depth
reading

# Abstract
We used coordinate-based meta-analysis to objectively quantify commonalities and differ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …anisms involved in facial and vocal emotion recognition. Neuroimaging studies contrasting emotional with neutral (face: N = 76, voice: N = 34) and explicit with implicit emotion processing (face: N = <mark class="annotated-text">27</mark>, voice: N = 20) were collected to shed light on stimulus and goal-driven mechanisms, respectively. Activation likelihood estimations were conducted on the full data sets for the separate modalities a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …stract
The aim of this review is to systematically examine the literature concerning multicomponent working memory (WM)-comprising a central executive (CE), two storage components (phonological loop, <mark class="annotated-text">PL</mark> and visuo-spatial sketchpad, VSSP), and episodic buffer (EB)-in pediatric traumatic brain injury (TBI). Electronic searches were conducted of MEDLINE, PsychINFO and EMBASE up to October 2014 with the…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …f modern neuroscience. We performed the first meta-analysis of functional magnetic resonance imaging (fMRI) data obtained over the past decade (1999-2008) on more than 800 children and adolescents in <mark class="annotated-text">three</mark> core systems of cognitive development and school learning: numerical abilities, reading, and executive functions (i.e. cognitive control). We ran Activation Likelihood Estimation (ALE) meta-analyses …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …a deviant stimulus in a stream of repeated, standard stimuli, termed here oddball effects. The meta-analysis of 75 independent studies included a comparison of auditory and visual oddball effects and <mark class="annotated-text">task-relevant</mark> and task-irrelevant oddball effects. The results were interpreted with reference to the model in which a large-scale dorsal frontoparietal network embodies a mechanism for orienting attention to the …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ropose a tripartite crosstalk among interoceptive signaling, emotional regulation, and low-level social cognition. Here we examined the neurocognitive convergence of such domains. First, we performed <mark class="annotated-text">three</mark> meta-analyses of functional magnetic resonance imaging studies to identify which areas are consistently coactivated by these three systems. Multi-level Kernel Density Analysis (MKDA) revealed major o…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …nderlying abnormal EF in ASD remain unclear. This meta-analysis investigated the construct, abnormalities, and age-related changes of EF in ASD. Thirty-three fMRI studies of inhibition, updating, and <mark class="annotated-text">switching</mark> in individuals with high-functioning ASD were included (n = 1114; age range 7-57 years). The results revealed that the EF construct in ASD could be unitary (i.e., common EF) in children/adolescents, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … with structural and functional magnetic resonance imaging. Studies included structural in schizophrenia (k = 8; n = 241) and healthy controls (k = 12; n = 1660), and functional in schizophrenia (k = <mark class="annotated-text">4</mark>; n = 104) and healthy controls (k = 12; n = 712). Results revealed a positive association in the brain behavior relationship when pooled across schizophrenia and control samples for structural (pr = …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g activation likelihood estimation (ALE) meta-analysis we tested whether different MR networks can be modulated by the type of stimulus (body vs. non-body parts) or by the type of tasks instructions (<mark class="annotated-text">motor</mark> imagery-based vs. non-motor imagery-based MR instructions). Testing for the bodily and non-bodily stimulus axis revealed a bilateral sensorimotor activation for bodily-related as compared to non-bodi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …he degree to which drug and natural rewards share neural substrates is not known. The objective of this study is to conduct a comprehensive meta-analysis of neuroimaging studies on drug, gambling and <mark class="annotated-text">natural</mark> stimuli (food and sex) to identify the common and distinct neural substrates of cue reactivity to drug and natural rewards. Neural cue reactivity studies were selected for the meta-analysis by means …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">N contrasts included (131 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Kim, Hongkeun
Hum Brain Mapp, 2017

# Title

Brain regions that show repetition suppression and enhancement: A meta-analysis of <mark class="annotated-text">137</mark> neuroimaging experiments.

# Keywords

fMRI
memory
meta-analysis
neural networks
repetition priming

# Abstract
Repetition suppression and enhancement refer to the reduction and increase in the neura…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s with human adults. To complement this work from a developmental perspective, we conducted a meta-analysis of fMRI studies of auditory language comprehension in human children. Our analysis included <mark class="annotated-text">27</mark> independent experiments involving n ​= ​625 children (49% girls) with a mean age of 8.9 years. Activation likelihood estimation and seed-based effect size mapping revealed activation peaks in the par…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …arch, especially upon reaching the discussion about brain functions. This large scale meta-analysis was performed on functional MRI studies. It included more than 700 active brain foci from more than <mark class="annotated-text">70</mark> different experiments to study gender related similarities and differences in brain activation strategies for three of the main brain functions: Visual-spatial cognition, memory, and emotion. Areas t…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …riate responses and the inhibition of others. Such effortful inhibition is achieved by a number of interference resolution and global inhibition processes. This meta-analysis including 57 studies and <mark class="annotated-text">73</mark> contrasts revisits the overlap and differences in brain areas supporting interference resolution and global inhibition in cortical and subcortical brain areas. Activation likelihood estimation was us…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …orld. However, the neural underpinnings of audiovisual integration continue to be a topic of debate. Using strict inclusion criteria, we performed an activation likelihood estimation meta-analysis on <mark class="annotated-text">121</mark> neuroimaging experiments with a total of 2,092 participants. We found that audiovisual integration is linked with the coexistence of multiple integration sites, including early cortical, subcortical,…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …despite decades of research, understanding of their neural correlates has been limited. A systematic coordinate-based meta-analysis of functional magnetic resonance imaging (fMRI) studies (altogether <mark class="annotated-text">87</mark> original datasets, n = 2328) was conducted to investigate neural inter-group biases, i.e., responses toward in-group vs. out-group in different contexts. We found inter-group biases in some previousl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ors. To address this, we conducted a meta-analysis investigating cue-reactivity functional MRI studies for different addictions. We explored 8 different addiction-related brain regions in 27 studies (<mark class="annotated-text">29</mark> samples) using homogeneity tests of effect sizes. An initial qualitative review failed to identify consistent activations in any brain region. We subsequently explored possible moderators related to …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …al substrates of executive function (EF), we conducted an activation likelihood estimation meta-analysis of 408 functional magnetic resonance imaging studies (9639 participants, 7587 activation foci, <mark class="annotated-text">518</mark> experimental contrasts) covering three fundamental EF subcomponents: inhibition, switching, and working memory. Our results found that activation common to all three EF subcomponents converged in the…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e general aspect of visual aesthetic experience (VAE) and those more strictly correlated with the content of the artworks. We applied a general activation likelihood estimation (ALE) meta-analysis to <mark class="annotated-text">47</mark> fMRI experiments described in 14 published studies. We also performed four separate ALE analyses in order to identify the neural substrates of reactions to specific categories of artworks, namely por…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …on where different semantic features are processed in the adult brain, the development of these systems in children is poorly understood. Here we conducted an extensive database search and identified <mark class="annotated-text">50</mark> fMRI experiments investigating semantic world knowledge, semantic relatedness judgments, and the differentiation of visual semantic object categories in children (total N = 1,018, mean age = 10.1 yea…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">N studies found (100 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …-traumatic growth for adult trauma survivors. We utilized the following databases to conduct our systematic search: Boston College Libraries, PubMed, MEDLINE, and PsycINFO. Our initial search yielded <mark class="annotated-text">834</mark> studies for initial screening. We implemented seven eligibility criteria to vet articles for full-text review. Twenty-nine studies remained for full-text review after our systematic review process wa…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ducted separate comprehensive PUBMED (1990-May 2008) searches to find all functional magnetic resonance imaging studies using a variant of the emotional faces paradigm in healthy subjects. Out of the <mark class="annotated-text">551</mark> originally identified studies, 105 studies met inclusion criteria. The overall database consisted of 1785 brain coordinates which yield an overall sample of 1600 healthy subjects. We found no support…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ctivity and local indices such as volume, etc.), FC, or task-based magnetic resonance imaging data. Meta-analyses were conducted, as applicable, using AES-SDM software. The literature search produced <mark class="annotated-text">4,645</mark> total records, of which 85 met the inclusion criteria for the systematic review. Records included structural (n = 35), FC (n = 33), and task-based (n = 42) findings. Meta-analyses were conducted on v…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">4645</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …BD has not been performed yet. We systematically searched PubMed, Scopus, and Web of Science for structural and functional MRI studies investigating relatives and healthy control subjects. A total of <mark class="annotated-text">230</mark> eligible neuroimaging studies (6274 SCZ-RELs, 1900 BD-RELs, 10,789 healthy control subjects) were identified. We conducted coordinate-based activation likelihood estimation meta-analyses on 26 struct…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …of significant results separately for each modality and multimodally (&#34;all-effects&#34;). CBMAs were also performed for each direction and combining both directions of group contrasts. Out of the initial <mark class="annotated-text">1929</mark> studies, only eight involving 555 participants (189 patients with TRD, 156 with TSD, and 210 HC) were included. In all-effects CBMA, precentral/superior frontal gyrus showed a significant difference …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …patial consistency of brain activation in conscious facial expressions recognition was calculated using ALE. The robustness of the results was examined by Jackknife sensitivity analysis. We retrieved <mark class="annotated-text">11,365</mark> articles in total, 28 of which were included. In the overall analysis, we found increased activity in the middle temporal gyrus, superior temporal gyrus, parahippocampal gyrus, and cuneus, and decrea…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">11365</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …derstanding of the neurocircuitry of PTSD. 


## Methods 
  
We conducted a literature search for PET and fMRI studies of PTSD that were published before February 2011. The article search resulted in <mark class="annotated-text">79</mark> functional neuroimaging PTSD studies. Data from 26 PTSD peer-reviewed neuroimaging articles reporting results from 342 adult patients and 342 adult controls were included. Peak activation coordinates…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3430553/"
                                       >PMC3430553</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … all remaining articles was then assessed using with a data extraction template, constructed for the purpose of organizing and extracting information from included articles. Following this procedure, <mark class="annotated-text">244</mark> initial publications were found, which were reduced to 44 after examining the title and abstract. A total of 7 out of 44 studies fulfilled all inclusion criteria, resulting in a combined sample of 91…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3547329/"
                                       >PMC3547329</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … imaging,” “motor sequence learning AND imaging,” and “working memory AND imaging.” Additionally, the searches used the limits “Humans,” “English,” and “Adult 19-44 years.” These searches resulted in <mark class="annotated-text">45</mark>, 149, and 1997 papers, respectively. We also consulted a recent review of motor learning and included related work on sensorimotor adaptation not found in our PubMed search (Seidler,  ). We followed …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ging,” “motor sequence learning AND imaging,” and “working memory AND imaging.” Additionally, the searches used the limits “Humans,” “English,” and “Adult 19-44 years.” These searches resulted in 45, <mark class="annotated-text">149</mark>, and 1997 papers, respectively. We also consulted a recent review of motor learning and included related work on sensorimotor adaptation not found in our PubMed search (Seidler,  ). We followed the s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">guidelines - prisma (78 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …## Selection procedures 
  
The literature review and selection of manuscripts for the meta-analysis was conducted according to the preferred reporting items for systematic reviews and meta-analyses (<mark class="annotated-text">PRISMA) guidelines</mark> (Moher et al.,  ). These guidelines outline a structured methodology for the performance of a meta-analysis and/or systematic review, with the aim of improving the quality of published reviews. 

A s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3797465/"
                                       >PMC3797465</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …y consensus discussion with one senior author of the research team (OT). To achieve a high standard of reporting, we adhered to the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (<mark class="annotated-text">PRISMA) guidelines</mark> and the revised Quality Of Reporting Of Meta-analyses (QUOROM) statement [ ]. 


### Outcome measures 
  
All studies used a block design including alternating blocks of the verbal fluency tasks with…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3903437/"
                                       >PMC3903437</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …orated in the present review; see Fig.   for the flow diagram of included studies. The 29 studies selected for review included a total of 1278 individuals, including 713 patients and 565 controls.   
<mark class="annotated-text">PRISMA</mark> flow diagram showing the process of study selection 
  

In this review, we distinguished the following samples: (1) ODD/CD-only, including only individuals with ODD/CD without comorbid ADHD, (2) ODD…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …esthetics, or originality of generated visual solutions (Dietrich &amp; Kanso,  ; Gonen‐Yaacovi et al.,  ). 


## Methods 
  
### Search strategy 
  
This systematic review and ALE meta‐analysis followed <mark class="annotated-text">PRISMA guidelines</mark> (Liberati et al.,  ) and synthesized studies recording neural activity during active generation of visual‐based creative (i.e., novel and useful) ideas (Runco &amp; Jaeger,  ). Tasks involving only passi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5064346/"
                                       >PMC5064346</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, and also assessed their brain wide co-activation patterns to reveal networks that are (conjointly) connected to these obtained areas. 


## Methods 
  
### Search strategies and study selection 
  
<mark class="annotated-text">In accordance with the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) statement ( ), references</mark> for this meta-analysis were collected by a search of the PubMed database in April 2015, and by reference tracing of retrieved articles. Keywords for the search were as follows: (i) ((“Sleep Apnea Syn…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5103027/"
                                       >PMC5103027</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …usters, providing the coordinates of the weighted center-of-mass and peak locations, and anatomical labels were assigned by the Talairach Daemon [ ]. 

The results are reported in accordance with the <mark class="annotated-text">PRISMA guidelines</mark> on reporting of systematic reviews and meta-analyses [ ]. 


#### 2.2.4. Non-quantitative analysis 
  
The studies or results which could not be included in the quantitative statistical meta-analyses…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5127572/"
                                       >PMC5127572</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …as linked to the fully matured core WM network and a decrease in activation in ancillary brain regions, that might serve a less mature WM network. 



## Methods 
  
### Protocol and registration 
  
<mark class="annotated-text">We followed the Preferred Reporting Items for Systematic Reviews and Meta Analyses ( ) method. 
</mark>

### Information source and search 
  
We first searched peer-reviewed papers published in English through MEDLINE, PubMed, PsychINFO and Cochrane Library, including all potential articles from incep…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5153561/"
                                       >PMC5153561</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …from conferences, monographs, theses, or reference lists in identified studies were also regarded as potential sources to be included in the meta-analysis. 


### Inclusion and exclusion criteria 
  
<mark class="annotated-text">According to the Preferred Reporting Items for Systematic Reviews and Meta-Analyses guidelines,</mark>  the following criteria were used for inclusion in the meta-analysis: 1) whole-brain analysis was used in task-free rs-fMRI studies; 2) studies included a comparison of the localized connectivity bet…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5317331/"
                                       >PMC5317331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …rature on connectivity abnormalities in ADAD and the at-risk APOEε4 genotype. 


## Methods 
  
### Literature search 
  
We conducted a systematic review of PubMed articles up to December 3, 2015 in <mark class="annotated-text">accordance with the Preferred Reporting Items for Systematic Reviews and Meta-Analyses guidelines</mark>  . Search terms and combinations used are provided in  . Results were filtered for duplicates within each of the two main search categories, that is, AD dementia or MCI patients ( ). Unique search re…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5436069/"
                                       >PMC5436069</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ing modalities and different nociceptive systems (superficial vs. deep and visceral). 


## Methods 
  
### Study inclusion and data selection 
  
The literature search was performed according to the <mark class="annotated-text">PRISMA guidelines</mark> for reporting meta-analyses and systematic reviews ( ). Functional MRI studies of experimental cutaneous pain were searched both through standard literature databases (PubMed and Web of Knowledge) an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5554296/"
                                       >PMC5554296</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA4 (65 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … in facial and vocal emotion recognition. Neuroimaging studies contrasting emotional with neutral (face: N = 76, voice: N = 34) and explicit with implicit emotion processing (face: N = 27, voice: N = <mark class="annotated-text">20</mark>) were collected to shed light on stimulus and goal-driven mechanisms, respectively. Activation likelihood estimations were conducted on the full data sets for the separate modalities and on reduced, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … in a stream of repeated, standard stimuli, termed here oddball effects. The meta-analysis of 75 independent studies included a comparison of auditory and visual oddball effects and task-relevant and <mark class="annotated-text">task-irrelevant</mark> oddball effects. The results were interpreted with reference to the model in which a large-scale dorsal frontoparietal network embodies a mechanism for orienting attention to the environment, whereas…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ctly correlated with the content of the artworks. We applied a general activation likelihood estimation (ALE) meta-analysis to 47 fMRI experiments described in 14 published studies. We also performed <mark class="annotated-text">four</mark> separate ALE analyses in order to identify the neural substrates of reactions to specific categories of artworks, namely portraits, representation of real-world-visual-scenes, abstract paintings, and…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ic resonance imaging. Studies included structural in schizophrenia (k = 8; n = 241) and healthy controls (k = 12; n = 1660), and functional in schizophrenia (k = 4; n = 104) and healthy controls (k = <mark class="annotated-text">12</mark>; n = 712). Results revealed a positive association in the brain behavior relationship when pooled across schizophrenia and control samples for structural (pr = 0.27) and functional (pr = 0.29) modali…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …kelihood estimations to merge available fMRI data on non-literal language. A literature search identified 38 fMRI studies on non-literal language (24 metaphor studies, 14 non-salient stimuli studies, <mark class="annotated-text">7</mark> idiom studies, 8 irony studies, and 1 metonymy study). Twenty-eight studies with direct comparisons of non-literal and literal studies were included in the main meta-analysis. Sub-analyses for metaph…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …639 participants, 7587 activation foci, 518 experimental contrasts) covering three fundamental EF subcomponents: inhibition, switching, and working memory. Our results found that activation common to <mark class="annotated-text">all three</mark> EF subcomponents converged in the multiple-demand network across adolescence and adulthood. The function of EF with the multiple-demand network involved, especially for the prefrontal cortex and the …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …number processing, arithmetic, and mental rotation. We used Activation Likelihood Estimation (ALE) to construct quantitative meta-analytic maps synthesizing results from 83 neuroimaging papers (24-31 <mark class="annotated-text">studies</mark>/cognitive process). All three cognitive processes were found to activate bilateral parietal regions in and around the intraparietal sulcus (IPS); a finding consistent with shared processing accounts.…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e. This meta-analysis included 48 functional magnetic resonance imaging studies that reported pragmatic versus literal language contrasts. The pragmatic forms were speech acts, metaphors, idioms, and <mark class="annotated-text">irony</mark>. Effect Size-Signed Differential Mapping software was used to calculate the mean for all contrasts as well as for each pragmatic form, and make comparisons among all forms. Due to variations in pragm…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …i have been linked with several neuropsychiatric disorders. However, questions still remain about the exact neural substrates implicated in social reward and punishment processing. Here, we conducted <mark class="annotated-text">four</mark> Anisotropic Effect Size Signed Differential Mapping voxel-based meta-analyses of fMRI studies investigating the neural correlates of the anticipation and receipt of social rewards and punishments usi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …amygdala activity than neutral stimuli. Comparable effects were observed for most negative and positive emotions, however there was a higher probability of activation for fear and disgust relative to <mark class="annotated-text">happiness</mark>. The level of attentional processing affected amygdala activity, as passive processing was associated with a higher probability of activation than active task instructions. Gustatory-olfactory and vi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - pubmed (65 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …pert and Ghahramani,  ; Imamizu et al.,  ) which suggests a modular organization of representations in the cerebellum. 


## Methods 
  
### Literature review 
  
Papers were identified through three <mark class="annotated-text">PubMed</mark> ( ) searches. Searches for papers investigating visuomotor adaptation, motor sequence learning, and working memory were conducted separately using the following search terms: “sensorimotor adaptation…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … sensitivity are priorized over functional interpretability regarding exact disease mechanisms. 


## Materials and methods 
  
### Identification and selection of relevant studies 
  
We conducted a <mark class="annotated-text">PubMed</mark> ( ) search using the following query on August 20, 2013: (  “depression” OR “depressive”) AND (“fMRI” OR “functional MRI” OR “functional magnetic”) AND (“functional connectivity” OR “resting state” O…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4159995/"
                                       >PMC4159995</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …in Function 
  
A comprehensive literature search was conducted of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using <mark class="annotated-text">PubMed</mark>, ScienceDirect, Google Scholar, Web of Knowledge, and Scopus electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ain regions linked to implicit memory and arousal, such as the hippocampus, amygdala, striatum and primary visual cortex. 


## Methods 
  
### Searching 
  
#### Inclusion and exclusion criteria 
  
<mark class="annotated-text">PubMed</mark>, Medline, Ovid, Sciencedirect, Web of Science and Google Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included fMRI and MRI, with s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … to be involved in cognition and working memory. 


## Methods 
  
### Data sources and inclusion criteria 
  
A systematic search strategy was performed to identify the relevant studies. We searched <mark class="annotated-text">PubMed</mark>, MEDLINE, and EMBASE from 1993 to 2014 for all relevant published observational studies and clinical trials. The following key terms were employed: “HT,” “HRT,” “HT,” “ERT,” “functional MRI or fMRI,”…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …creative thinking in humans. 


## Materials and Methods 
  
### Inclusion Criteria for Papers 
  
A systematic method was adopted to review the literature. The search was carried out with the aid of <mark class="annotated-text">PubMed</mark>, using the following string: “creativity and fMRI.” A total of 56 studies were found. 

Our   a priori   inclusion criteria for papers were: (1) Inclusion of whole-brain analysis performed using func…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4531218/"
                                       >PMC4531218</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …comparing brain activity in patients with MND and in healthy controls (HCs) to identify common findings across studies. 


## Materials and Methods 
  
### Literature Search Methods 
  
Ovid Medline, <mark class="annotated-text">Pubmed</mark>, and Emabase databases were searched for studies published up to April 2015 that reported functional MRI data in patients with MND. Search terms included “motor neuron disease,” “MND,” “amyotrophic l…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …dy had to be published in a peer-reviewed English language journal. No limits were set on the ages of participants. All relevant studies published up till June 2015 were incorporated. 

The databases <mark class="annotated-text">PubMed</mark>, EMBASE, PsycInfo and Web of Science were searched, using the search terms ODD, CD, disruptive behavioural disorder, disruptive behaviour, externalising behavioural disorder, externalising behaviour,…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … studies to explore the effectiveness of different study methods. 


## M 
  
### Literature search and selection 
  
Computerized literature search was conducted through online scientific databases: <mark class="annotated-text">PubMed</mark>/Medline, EMBASE, Web of Science, and PsycINFO. The literature search was performed in March 2015, with no restrictions on the date of publication. Search terms included “cogniti*,” “rehabilitation,” …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …udy selection 
  
In accordance with the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) statement ( ), references for this meta-analysis were collected by a search of the <mark class="annotated-text">PubMed</mark> database in April 2015, and by reference tracing of retrieved articles. Keywords for the search were as follows: (i) ((“Sleep Apnea Syndromes”[Mesh] OR “Sleep Apnea; Central”[Mesh] OR “Sleep Apnea; O…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5103027/"
                                       >PMC5103027</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - traditional ma (60 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Kwee, Robert M and Kwee, Thomas C
Eur Radiol, 2022

# Title

<mark class="annotated-text">Diagnostic performance of MRI in detecting locally recurrent soft tissue sarcoma: systematic review and meta-analysis.
</mark>
# Keywords

Magnetic resonance imaging
Meta-analysis
Recurrence
Sarcoma
Systematic review

# Abstract
To systematically review the diagnostic criteria and performance of MRI in detecting locally recu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Dudek, Emily and Dodell-Feder, David
Neurosci Biobehav Rev, 2021

# Title

<mark class="annotated-text">The efficacy of real-time functional magnetic resonance imaging neurofeedback for psychiatric illness: A meta-analysis of brain and behavioral outcomes.
</mark>
# Keywords

Functional magnetic resonance imaging
Intervention
Meta-analysis
Neurofeedback
Neuromodulation
Psychiatric illness
Psychopathology
Real-time fMRI

# Abstract
Real-time functional magnetic…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Plichta, Michael M and Scheres, Anouk
Neurosci Biobehav Rev, 2014

# Title

<mark class="annotated-text">Ventral-striatal responsiveness during reward anticipation in ADHD and its relation to trait impulsivity in the healthy population: a meta-analytic review of the fMRI literature.
</mark>
# Keywords

ADHD
Hyporesponsiveness
Impulsivity
Reward
Ventral striatum
Ventral–striatal hypoactivation

# Abstract
A review of the existing functional magnetic resonance imaging (fMRI) studies on re…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Janowich, Jacqueline R and Cavanagh, James F
Psychon Bull Rev, 2018

# Title

<mark class="annotated-text">Delay knowledge and trial set count modulate use of proactive versus reactive control: A meta-analytic review.
</mark>
# Keywords

AX-CPT
Cognitive control and automaticity
DPX
Meta-analysis

# Abstract
The AX-continuous performance task (AX-CPT) and dot pattern expectancy (DPX) are the predominant cognitive paradigm…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zafarmand, Mahsa and Farahmand, Zahra and Otared, Nastaran
Neurocase, 2022

# Title

<mark class="annotated-text">A Systematic Literature Review and Meta-analysis on Effectiveness of Neurofeedback for Obsessive-Compulsive Disorder.
</mark>
# Keywords

Neurofeedback
brain waves
electroencephalography
functional magnetic resonance imaging
obsessive-compulsive disorder

# Abstract
To evaluate the evidences related to the effectiveness of …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Noble, Stephanie and Scheinost, Dustin and Constable, R Todd
Neuroimage, 2019

# Title

<mark class="annotated-text">A decade of test-retest reliability of functional connectivity: A systematic review and meta-analysis.
</mark>
# Keywords

Edge-level
Intraclass correlation coefficient
Systematic review
Validity
fMRI

# Abstract
Once considered mere noise, fMRI-based functional connectivity has become a major neuroscience to…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Voon, Noor Shatirah and Manan, Hanani Abdul and Yahya, Noorazrul
Strahlenther Onkol, 2023

# Title

<mark class="annotated-text">Role of resting-state functional MRI in detecting brain functional changes following radiotherapy for head and neck cancer: a systematic review and meta-analysis.
</mark>
# Keywords

Biomarkers
Brain plasticity
Diagnostic imaging
Early diagnosis
Nasopharyngeal carcinoma

# Abstract
Increasing evidence implicates changes in brain function following radiotherapy for hea…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhang, Fan and Liu, Chen-Lu and Chen, Qian and Shao, Sheng-Chao and Chen, Shuang-Qing
Br J Radiol, 2019

# Title

<mark class="annotated-text">Accuracy of multiparametric magnetic resonance imaging for detecting extracapsular extension in prostate cancer: a systematic review and meta-analysis.
</mark>
# Keywords



# Abstract
To evaluate the diagnostic accuracy of multiparametric MRI (mpMRI) for detecting extracapsular extension (ECE) in patients with prostate cancer (PCa). We searched MEDLINE, Pu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Bender, Andreas and Jox, Ralf J and Grill, Eva and Straube, Andreas and Lulé, Dorothée
Dtsch Arztebl Int, 2015

# Title

<mark class="annotated-text">Persistent vegetative state and minimally conscious state: a systematic review and meta-analysis of diagnostic procedures.
</mark>
# Keywords



# Abstract
Acute brain damage can cause major disturbances of consciousness, ranging all the way to the persistent vegetative state (PVS), which is also known as &#34;unresponsive wakefulne…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhou, Huan and Si, Yi and Sun, Jiantong and Deng, Jiaxin and Yang, Ling and Tang, Yi and Qin, Wei
Eur J Radiol, 2023

# Title

<mark class="annotated-text">Effectiveness of functional magnetic resonance imaging for early identification of chronic kidney disease: A systematic review and network meta-analysis.
</mark>
# Keywords

Chronic kidney disease
Early identification
Functional magnetic resonance imaging
Network meta-analysis
Systematic review

# Abstract
The commonly used clinical indicators are not sensiti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">exclusion - no min n (55 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Bernard, <mark class="annotated-text">Jessica</mark> A. and Seidler, Rachael D.
Front Hum Neurosci, 2013

# Title

Cerebellar contributions to visuomotor adaptation and motor sequence learning: an ALE meta-analysis

# Keywords

cerebellum
sequence lear…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Rubia, <mark class="annotated-text">Katya</mark> and Alegria, Analucia A. and Cubillo, Ana I. and Smith, Anna B. and Brammer, Michael J. and Radua, Joaquim
Biol Psychiatry, 2014

# Title

Effects of Stimulants on Brain Function in Attention-Deficit…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Meneguzzo, Paolo <mark class="annotated-text">and</mark> Tsakiris, Manos and Schioth, Helgi B and Stein, Dan J and Brooks, Samantha J
BMC Psychol, 2014

# Title

Subliminal versus supraliminal stimuli activate neural responses in anterior cingulate cortex,…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Li, <mark class="annotated-text">Ke</mark> and Huang, Xiaoyan and Han, Yingping and Zhang, Jun and Lai, Yuhan and Yuan, Li and Lu, Jiaojiao and Zeng, Dong
Front Hum Neurosci, 2015

# Title

Enhanced Neuroactivation during Working Memory Task …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Shen, <mark class="annotated-text">Dongchao</mark> and Cui, Liying and Cui, Bo and Fang, Jia and Li, Dawei and Ma, Junfang
Front Neurol, 2015

# Title

A Systematic Review and Meta-Analysis of the Functional MRI Investigation of Motor Neuron Disease
…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Noordermeer, <mark class="annotated-text">Siri</mark> D. S. and Luman, Marjolein and Oosterlaan, Jaap
Neuropsychol Rev, 2016

# Title

A Systematic Review and Meta-analysis of Neuroimaging in Oppositional Defiant Disorder (ODD) and Conduct Disorder (CD)…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Wei, <mark class="annotated-text">Yan</mark>-Yan and Wang, Ji-Jun and Yan, Chao and Li, Zi-Qiang and Pan, Xiao and Cui, Yi and Su, Tong and Liu, Tao-Sheng and Tang, Yun-Xiang
Chin. Med. J, 2016

# Title

Correlation Between Brain Activation Cha…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Lau, <mark class="annotated-text">W</mark> K W and Leung, M-K and Lee, T M C and Law, A C K
Transl Psychiatry, 2016

# Title

Resting-state abnormalities in amnestic mild cognitive impairment: a meta-analysis

# Keywords



# Abstract
 
Amnes…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4872413/"
                                       >PMC4872413</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Martin, Anna and <mark class="annotated-text">Schurz</mark>, Matthias and Kronbichler, Martin and Richlan, Fabio
Hum Brain Mapp, 2015

# Title

Reading in the brain of children and adults: A meta‐analysis of 40 functional magnetic resonance imaging studies

#…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4950303/"
                                       >PMC4950303</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Santos, <mark class="annotated-text">Sara</mark> and Almeida, Inês and Oliveiros, Bárbara and Castelo-Branco, Miguel
PLoS ONE, 2016

# Title

The Role of the Amygdala in Facial Trustworthiness Processing: A Systematic Review and Meta-Analyses of fM…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5127572/"
                                       >PMC5127572</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-SDM (51 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …d Qiu, Yidan and Li, Jinhui and Jia, Chuchu and Liao, Jiajun and Chen, Kemeng and Qiu, Lixin and Yuan, Zhen and Huang, Ruiwang
Neuroimage, 2022

# Title

Neural correlates of transitive inference: An <mark class="annotated-text">SDM</mark> meta-analysis on 32 fMRI studies.

# Keywords

Cognitive map
Decision making
Flexible learning
Memory integration
Transitive inference

# Abstract
Transitive inference (TI) is a critical capacity inv…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …
Abnormal neural activities in adults and youths with major depressive disorder during emotional processing: a meta-analysis.

# Keywords

Emotional processing
Major depressive disorder
Meta-analysis
<mark class="annotated-text">Signed differential mapping</mark>
fMRI

# Abstract
Abnormal neural activities during emotional processing have been found in both adults and youths with major depressive disorder. However, findings were inconsistent in each group and…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, 2022

# Title

Delay activity during visual working memory: A meta-analysis of 30 fMRI experiments.

# Keywords

Activation likelihood estimation
Content-specific storage
Delay period
Meta-analysis
<mark class="annotated-text">Seed-based d mapping
</mark>Visual working memory
fMRI

# Abstract
Visual working memory refers to the temporary maintenance and manipulation of task-related visual information. Recent debate on the underlying neural substrates …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …

Atypical local brain connectivity in pediatric autism spectrum disorder? A coordinate-based meta-analysis of regional homogeneity studies.

# Keywords

Default mode network
Neurosynth
Resting state
<mark class="annotated-text">Seed-based d mapping
</mark>Sensorimotor network
fMRI

# Abstract
Despite decades of massive neuroimaging research, the comprehensive characterization of short-range functional connectivity in autism spectrum disorder (ASD) rema…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …l markers of increased vulnerability to psychosis are needed to improve the predictive value of psychosis risk syndrome and inform preventive interventions. I performed a signed differential mapping (<mark class="annotated-text">SDM</mark>) voxel-wise meta-analysis of functional magnetic resonance imaging (fMRI) studies of patients at clinical high risk for psychosis. Ten studies were included in the analysis. Compared with controls, h…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ting-state fMRI studies.

# Keywords

Amnestic mild cognitive impairment
Amplitude of low-frequency fluctuations
Default mode network
Meta-analysis
Resting-state functional magnetic resonance imaging
<mark class="annotated-text">Seed-based d mapping</mark>

# Abstract
Recent resting-state functional magnetic resonance imaging (rs-fMRI) studies have provided strong evidence of abnormal spontaneous brain activity in amnestic mild cognitive impairment (aM…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n use the  All functional neuro-imaging studies using the MIDT in healthy controls were retrieved using PubMed, Google Scholar &amp; EMBASE databases. Functional neuro-imaging data was analyzed using the <mark class="annotated-text">Seed-based d Mapping</mark> Software. Thirty-five studies met the inclusion criteria, comprising 699 healthy adults. In both anticipation and loss outcome phases, participants showed large and robust activations in the bilatera…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …stening engages brain functional networks remains elusive due to inconsistent results from previous findings. A meta-analysis of functional magnetic resonance imaging data using seed-based d mapping (<mark class="annotated-text">SDM</mark>) with permutation of subject images was performed. Studies that presented music listening paradigms to healthy individuals were included. Subgroup analyses were performed to investigate the effects o…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … carried out to explore the cerebral functional changes in dysphagic stroke patients. The aim of this study was to analysis these imaging findings using a meta-analysis. We used seed-based d mapping (<mark class="annotated-text">SDM</mark>) to conduct a meta-analysis for dysphagic stroke patients prior to any kind of special treatment for dysphagia. A systematic search was conducted for the relevant studies. SDM meta-analysis method wa…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … in suicidal individuals. Databases were searched to perform a meta-analysis of whole-brain functional MRI studies of suicidal individuals through January 14, 2020. Meta-analyses were conducted using <mark class="annotated-text">Seed-based d Mapping</mark> software. Based on a meta-analysis of 17 studies comprising 381 suicidal individuals and 642 controls, we mainly found that increased activity in the bilateral superior temporal gyrus, left middle te…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">has flow chart (46 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … to obtain additional relevant studies. All identified articles were reviewed by at least two authors, and studies were included in the meta-analysis based on a consensus decision (see Figure  ). 
  
<mark class="annotated-text"> Diagram of studies included in the present meta-analysis  . 
</mark>  
To meet the inclusion criteria, the studies had to (a) report group comparisons between postmenopausal women who received HT and matched controls, (b) employ fMRI, (c) report their results in a sta…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …pplementary motor area; SMN, sensorimotor network; SRFC, seed region-based FC; TBBS, tract-based spatial statistics; VBM, voxel-based morphometry; VMHC, voxel-mirrored homotopic connectivity  . 
    
<mark class="annotated-text"> The flow chart of the literature search in the systematic review  . 
</mark>  

### Details of MND Patients 
  
In total, 1124 participants with MND were reported, including 1062 ALS, 18 PMA and 44 PLS, although there was considerable overlap between studies. The reported mea…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …orated in the present review; see Fig.   for the flow diagram of included studies. The 29 studies selected for review included a total of 1278 individuals, including 713 patients and 565 controls.   
<mark class="annotated-text">PRISMA flow diagram showing the process of study selection 
</mark>  

In this review, we distinguished the following samples: (1) ODD/CD-only, including only individuals with ODD/CD without comorbid ADHD, (2) ODD/CD-mixed, including both individuals with ODD/CD-only…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …the articles holding the most relevant information were provided in  .[ ] The procedure of selecting articles was listed in  . 
  
Summary of the selected studies in the present meta-analysis 
      
<mark class="annotated-text">The procedure of studies searching. CRT: Cognitive remediation therapy; fMRI: Functional magnetic resonance imaging; PET: Photon emission tomography; ALE: Activation likelihood estimation. 
</mark>  
In order to evaluate how methodological differences affect results, analysis of all studies reported coordinates in standard space and whole-brain studies only were conducted separately. Previous A…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Tahmasian, <mark class="annotated-text">Masoud</mark> and Rosenzweig, Ivana and Eickhoff, Simon B. and Sepehry, Amir A. and Laird, Angela R. and Fox, Peter T. and Morrell, Mary J. and Khazaie, Habibolah and Eickhoff, Claudia R.
Neurosci Biobehav Rev, 20…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5103027/"
                                       >PMC5103027</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Pan, <mark class="annotated-text">PingLei</mark> and Zhang, Yang and Liu, Yi and Zhang, He and Guan, DeNing and Xu, Yun
Sci Rep, 2017

# Title

Abnormalities of regional brain function in Parkinson’s disease: a meta-analysis of resting state functi…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">figure caption not found</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5228032/"
                                       >PMC5228032</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Xiao, Bo <mark class="annotated-text">and</mark> Wang, Shuai and Liu, Jianbo and Meng, Tiantian and He, Yuqiong and Luo, Xuerong
Neuropsychiatr Dis Treat, 2017

# Title

Abnormalities of localized connectivity in schizophrenia patients and their un…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">figure caption not found</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5317331/"
                                       >PMC5317331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …activate memory systems). Each of these could confound the brain activation attributable to chemosensory perception of taste and thus cause false positives. After this step, 101 records remained. 
  
<mark class="annotated-text">Flowchart of the review process. The number of publications (n) in each stage is labeled 
</mark>  
In the next step, the full text of the remaining 101 records was further evaluated based on an extra ordered set of five inclusion criteria listed below: 

  
Reported results from healthy (i.e., s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5390838/"
                                       >PMC5390838</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s were filtered for duplicates within each of the two main search categories, that is, AD dementia or MCI patients ( ). Unique search results underwent further screening as described subsequently.   
<mark class="annotated-text">Flowchart of the study selection process. Selection process for AD and MCI studies included in the meta-analyses. Studies using rsfMRI methods dissimilar to seed-based and ICA methods, such as degree centrality or graph theory, amplitude of low-frequency fluctuations, and regional homogeneity were not included. Abbreviations: AD, Alzheimer&#39;s disease; EEG, electroencephalogram; ICA, independent component analysis; MCI, mild cognitive impairment; MEG, magnetoencephalography; rsfMRI, resting-state functional magnetic resonance imaging. 
</mark>  


### Study selection 
  
Search results were subjected to two successive screenings with increasingly stringent criteria. The initial screen was performed on article abstracts. An article was incl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5436069/"
                                       >PMC5436069</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ally screened for the presence of Montreal Neurological Institute (MNI) or Talairach space and OT effects. All coordinates were entered by authors Y. Ma and D. Wang and double-checked by X. Yan.
 
  
<mark class="annotated-text">Flow diagram of the literature search. 
</mark>  
All relevant studies (414 included) were screened for the following inclusion/exclusion criteria: (1) we included papers reporting empirical studies with humans (188 studies were included) and excl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #aec7e8;">
        <summary class="label-display">thresholding (42 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …. ALE statistics calculated the probability that at least one of the foci lay within each voxel and, therefore, the likelihood that each voxel was activated across all studies included in the analysis<mark class="annotated-text">. The ALE statistic maps were compared with a null-distribution of random spatial associations between experiments (random-effects model) to assess for above chance clustering between experiments using a threshold at false discovery rate (FDR) corrected   P   &lt; 0.05 and a cluster-extent of 100 mm . 
</mark>
To explore the hypothesis that activity in the ventromedial prefrontal cortex and the amygdala was inversely related, we first identified whole-brain studies that reported increased ventromedial pref…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3430553/"
                                       >PMC3430553</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …els via measurement error, which bypasses reliance on publication-specific anatomical labeling (Laird et al.,  ). 

For this ALE, the latest version of the ALE software (Eickhoff et al.,  ) was used, <mark class="annotated-text">with correction using False Discovery Rate (FDR) at   p   = 0.05 and a minimum cluster threshold of 160 mm .</mark> Previous versions of GingerALE calculated the probability of voxel activation in the brain on the basis of all foci reported in studies, as if these 3D coordinates were independent of each other. Thi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3547329/"
                                       >PMC3547329</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    ….,  ; Turkeltaub et al.,  ). 


### Statistical analysis 
  
In order to guarantee sufficient statistical power to the analyses and to exclude clusters that were not clear sign of converging evidence,<mark class="annotated-text"> only those clusters that contained 10 or more activation peaks, coming from at least five different studies were considered further. </mark>Because it was impossible to determine   a priori   the exact cluster size that granted the statistical analysis the desired reliability, the 10-peaks and 5-studies thresholds were set   a posteriori …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3695563/"
                                       >PMC3695563</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …arate meta-analyses of selection and stopping, any studies reporting Talairach coordinates instead of MNI were converted to MNI space using the Talairach to MNI transform as implemented in GingerALE. <mark class="annotated-text">In the GingerALE analysis, we then applied the following options in addition to the default settings: non-additive ALE method ( ); output cluster minimum volume, 100 mm ; and FDR   p   &lt; 0.05. </mark>The resulting thresholded ALE map was viewed in MRIcroN ( ) and the anatomical labelling of foci facilitated by the Anatomy toolbox ( ) in SPM8 ( ). 

To perform a GingerALE conjunction (action select…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3898966/"
                                       >PMC3898966</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …iously generated selection and stopping ALE maps as inputs. The same options used in the previous selection and stopping ALEs were applied and permutations testing carried out with 10,000 iterations. <mark class="annotated-text">A threshold of FDR   p   &lt; 0.05 was applied to the conjunction image. </mark>


### Combined selection and stopping fMRI study 
  
#### Subjects and task 
  
21 healthy right-handed subjects were recruited from the MRC Cognition and Brain Sciences Unit volunteer panel. Four su…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3898966/"
                                       >PMC3898966</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ta-analysis used Ginger ALE ( ). All fMRI coordinates were converted into Talairach space. We used the default Ginger ALE parameters ( ), and additionally added the number of subjects per experiment. <mark class="annotated-text">We chose a false discovery rate threshold level of 0.05.</mark> We used all available fMRI publications of mTBI, most of which used working memory tasks, but the tasks also included resting state fMRI, an auditory odd-ball task, and a spatial navigation task ( ).…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4107372/"
                                       >PMC4107372</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …matically converted into MNI coordinates by GingerALE), according to   procedure. The Full-Width Half-Maximum (FWHM) value was automatically computed, as this parameter is empirically determined ( ). <mark class="annotated-text">The thresholded ALE map was corrected for multiple comparisons using False Discovery Rate (FDR), at a 0.05 level of significance. Moreover, a minimum cluster size of 200 mm  was chosen. </mark>The ALE results were registered on an MNI-normalized template using MRICRO. Hereafter the link to access MRICRO 


### Tasks and Contrasts Taken into Account 
  
Regarding the musical domain, particip…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4531218/"
                                       >PMC4531218</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …and a disagreement was ruled by a third party after discussions. The full width at half maximum (FWHM) was set at 20 mm, which had excellent control for false positives according to previous studies; <mark class="annotated-text">and the statistical threshold was set to be a   P  -value &lt;0.005 without correction for false discovery rate (FDR), which was found to be able to optimize the balance between sensitivity and specificity ( ).</mark> Mean analysis and Jackknife sensitivity analysis were carried out. The last analysis was a meta-regression of voxel values across the studies by the ALSFRS-R scores of the patients’ samples. 



## R…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …on maps of each experiment was created to form the ALE image that contains the combined probability distribution of finding an activation being located at that particular voxel (that is, ALE scores). <mark class="annotated-text">The ALE image was then thresholded using uncorrected   P  &lt;0.001 and a cluster-level inference threshold of   P  &lt;0.05 with 1000 permutations of simulated random data based on the characteristics of the imported data.  In the cluster-level inference, contiguous voxels (that is, clusters) that exceed the cluster-forming threshold were compared against the simulated random clusters. The cluster-inference threshold approach is considered optimal because it is more stringent than uncorrected voxel-level thresholds and less conservative than conventional false discovery rate and family-wise error rate corrections. Clusters contributed by a single study only were not reported even if they exceeded the cluster-inference threshold. </mark>A total of two ALE analyses were conducted for each contrast (healthy control&gt;aMCI or healthy control&lt;aMCI) in all aMCI patients. 


## Results 
  
aMCI patients showed decreases in resting-state acti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4872413/"
                                       >PMC4872413</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ter-study variance was larger than that resulting from sampling error alone [ ,  ]. Such analyses can reveal any false-positive brain regions due to significant unexplained between-study variability. <mark class="annotated-text">The default ES-SDM thresholds were set for the heterogeneous results based on a voxel-level threshold of   p   &lt; 0.005 and a cluster-level threshold of k = 10 voxels [ ]. </mark>

A subgroup analysis of adult samples was conducted to examine if potential confounding effects of age contributed to the heterogeneity of the findings [ ,  ]. To evaluate the replicability of meta-a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5891971/"
                                       >PMC5891971</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-MACM (40 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Ran, Guangming and Cao, Xiaojun and Chen, Xu
Conscious Cogn, 2018

# Title

Emotional prediction: An ALE meta-analysis and <mark class="annotated-text">MACM</mark> analysis.

# Keywords

ALE
Dorsolateral prefrontal cortex
Emotional prediction
MACM
Orbitofrontal cortex
Ventrolateral prefrontal cortex

# Abstract
The prediction of emotion has been explored in a v…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zald, David H and McHugo, Maureen and Ray, Kimberly L and Glahn, David C and Eickhoff, Simon B and Laird, Angela R
Cereb Cortex, 2014

# Title

<mark class="annotated-text">Meta-analytic connectivity modeling</mark> reveals differential functional connectivity of the medial and lateral orbitofrontal cortex.

# Keywords

fMRI
network
orbital frontal
ventrolateral prefrontal
ventromedial prefrontal

# Abstract
The…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Goodwill, Alicia M and Low, Li Tong and Fox, Peter T and Fox, P Mickle and Poon, Kenneth K and Bhowmick, Sourav S and Chen, S H Annabel
Brain Imaging Behav, 2023

# Title

<mark class="annotated-text">Meta-analytic connectivity modelling</mark> of functional magnetic resonance imaging studies in autism spectrum disorders.

# Keywords

Adult
Autism spectrum disorder
BrainMap
Meta-analysis
Meta-analytic connectivity modelling
fMRI

# Abstract…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Kohn, N and Eickhoff, S B and Scheller, M and Laird, A R and Fox, P T and Habel, U
Neuroimage, 2014

# Title

Neural network of cognitive emotion regulation--an ALE meta-analysis and <mark class="annotated-text">MACM</mark> analysis.

# Keywords

ALE
Angular gyrus
DLPFC
Emotion regulation
MACM
SMA
STG
VLPFC
aMCC

# Abstract
Cognitive regulation of emotions is a fundamental prerequisite for intact social functioning whic…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g and Northoff, Georg
Neuroimage, 2022

# Title

Spatial-topographic nestedness of interoceptive regions within the networks of decision making and emotion regulation: Combining ALE meta-analysis and <mark class="annotated-text">MACM</mark> analysis.

# Keywords

Interoception
decision making
emotion regulation
insula
meta-analysis
salience network

# Abstract
Prominent theories propose that interoception modulates our behavioral and em…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …D and Mattingley, Jason B
Neurosci Biobehav Rev, 2016

# Title

Understanding the minds of others: A neuroimaging meta-analysis.

# Keywords

Activation likelihood estimation
Medial prefrontal cortex
<mark class="annotated-text">Meta-analytic connectivity modelling</mark>
Temporoparietal junction
Theory of mind
fMRI

# Abstract
Theory of mind (ToM) is an important skill that refers broadly to the capacity to understand the mental states of others. A large number of ne…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ika and Rolke, Roman and Spehr, Marc and Habel, Ute
Rev Neurosci, 2023

# Title

Neural correlates of multisensory integration in the human brain: an ALE meta-analysis.

# Keywords

ALE meta-analysis
<mark class="annotated-text">MACM</mark> analysis
fMRI
multisensory integration
multisensory integration network

# Abstract
Previous fMRI research identified superior temporal sulcus as central integration area for audiovisual stimuli. How…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …iu, Zilong and Yang, Lian and Zhou, Yiwu
J Integr Neurosci, 2022

# Title

The Common and Different Neural Bases of Distraction and Reinterpretation: A Meta-Analysis of fMRI Studies.

# Keywords

ALE
<mark class="annotated-text">MACM</mark>
distraction
emotion regulation
fMRI
reinterpretation

# Abstract
Distraction and reinterpretation have been recognized as two different tactics of emotion regulation. As a tactic of attention deploym…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …on B and Habel, Ute and Gur, Ruben C and Nickl-Jockschat, Thomas
Brain Struct Funct, 2019

# Title

Neural networks of aggression: ALE meta-analyses on trait and elicited aggression.

# Keywords

ALE
<mark class="annotated-text">MACM</mark>
Meta-analysis
Resting-state functional connectivity
fMRI

# Abstract
There is considerable evidence that emotion dysregulation and self-control impairments lead to escalated aggression in populations…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …
Hum Brain Mapp, 2014

# Title

Bridging the gap between functional and anatomical features of cortico-cerebellar circuits using meta-analytic connectivity modeling.

# Keywords

cerebellum
cognition
<mark class="annotated-text">meta-analytic connectivity modeling</mark>

# Abstract
Theories positing that the cerebellum contributes to cognitive as well as motor control are driven by two sources of information: (1) studies highlighting connections between the cerebell…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - web of science (39 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ure search was conducted of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, ScienceDirect, Google Scholar, <mark class="annotated-text">Web</mark> of Knowledge, and Scopus electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphenidate and stimulant.…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …and arousal, such as the hippocampus, amygdala, striatum and primary visual cortex. 


## Methods 
  
### Searching 
  
#### Inclusion and exclusion criteria 
  
PubMed, Medline, Ovid, Sciencedirect, <mark class="annotated-text">Web</mark> of Science and Google Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included fMRI and MRI, with subliminal and supraliminal stimulat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …eer-reviewed English language journal. No limits were set on the ages of participants. All relevant studies published up till June 2015 were incorporated. 

The databases PubMed, EMBASE, PsycInfo and <mark class="annotated-text">Web of Science</mark> were searched, using the search terms ODD, CD, disruptive behavioural disorder, disruptive behaviour, externalising behavioural disorder, externalising behaviour, MRI, neuroimaging, and equivalent Me…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …effectiveness of different study methods. 


## M 
  
### Literature search and selection 
  
Computerized literature search was conducted through online scientific databases: PubMed/Medline, EMBASE, <mark class="annotated-text">Web of Science</mark>, and PsycINFO. The literature search was performed in March 2015, with no restrictions on the date of publication. Search terms included “cogniti*,” “rehabilitation,” “remediation,” “training,” or “e…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s underlies 4 phases: identification, screening, eligibility and inclusion ( ). Publications were searched on three databases, notably on MEDLINE, via PubMed ( ), on Science Direct (Elsevier,  ), and <mark class="annotated-text">Web</mark> of Science ( ), using the search string “(face OR facial) AND (trustworthiness OR trustworthy OR untrustworthy OR trustee) AND fMRI” (use of filter “article” and “short communication” in ScienceDirec…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5127572/"
                                       >PMC5127572</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tex, and bilateral cuneus cortices merit further investigations. 


## Methods 
  
### Identification, selection, and quality assessment of studies 
  
We comprehensively searched PubMed, Embase, and <mark class="annotated-text">Web</mark> of Science databases for studies published between January 1st, 2000 and June 24, 2016 using the following keywords “Parkinson” OR “Parkinson’s disease”, AND “amplitude of low frequency fluctuations”…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5228032/"
                                       >PMC5228032</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …atterns associated with MSIT interference processing within the dACC and in the CFP network. 


## Methods 
  
### Data sources and study selection 
  
We conducted a systematic search of PubMed ( ), <mark class="annotated-text">Web</mark> of Knowledge ( ), and Google Scholar ( ) for MSIT-related fMRI studies from 2003 to July 2017. The search term combinations used were: “multi-source interference task” and “functional magnetic resona…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5891971/"
                                       >PMC5891971</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …her relevant clinical profiles, such as age and comorbidity. 


## Methods 
  
### Search strategies 
  
A comprehensive systematic literature search was conducted using PubMed, the Cochrane Library, <mark class="annotated-text">Web</mark> of Science, and Embase databases to identify functional magnetic resonance imaging literature on anxiety disorders, published before September 2017 and including “in press” articles. The search keywo…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5953307/"
                                       >PMC5953307</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ucted a systematic literature search. The computerised search involved using the following electronic databases: Dissertations &amp; Theses A&amp;I (ProQuest), Dissertation &amp; Theses: UK &amp; Ireland (ProQuest), <mark class="annotated-text">Web</mark> of Science, PsycINFO (EBSCOhost) and MEDLINE (OVID). The following search terms were used ‘autis*’, ‘biological motion’, ‘human motion’, ‘asd’, ‘asperger*’, ‘childhood schizophrenia’, ‘kanner*’, ‘per…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6921539/"
                                       >PMC6921539</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … for Papers 
  
We used a systematic approach to review the literature and select appropriate articles for the present meta-analysis. The search for relevant literature was performed using PubMed and <mark class="annotated-text">Web</mark> of Knowledge (Web of Science); the data included in this meta-analysis have been collected from early 2019 to February 2020 and the search was run simultaneously on these databases, using the followi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7348890/"
                                       >PMC7348890</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">search terms - exact (38 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …rding exact disease mechanisms. 


## Materials and methods 
  
### Identification and selection of relevant studies 
  
We conducted a PubMed ( ) search using the following query on August 20, 2013: <mark class="annotated-text">(  “depression” OR “depressive”) AND (“fMRI” OR “functional MRI” OR “functional magnetic”) AND (“functional connectivity” OR “resting state” OR “resting-state”  )</mark>. 

Initially, 183 results were identified. In addition, we also screened a recent review for further papers (Wang et al.,  ) and a prior rather exclusive meta-analysis (Kühn and Gallinat,  ) comprisi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4159995/"
                                       >PMC4159995</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …aterials and Methods 
  
### Inclusion Criteria for Papers 
  
A systematic method was adopted to review the literature. The search was carried out with the aid of PubMed, using the following string: <mark class="annotated-text">“creativity and fMRI.”</mark> A total of 56 studies were found. 

Our   a priori   inclusion criteria for papers were: (1) Inclusion of whole-brain analysis performed using functional magnetic resonance imaging (fMRI); thus, we e…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4531218/"
                                       >PMC4531218</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ic Reviews and Meta-Analyses (PRISMA) statement ( ), references for this meta-analysis were collected by a search of the PubMed database in April 2015, and by reference tracing of retrieved articles. <mark class="annotated-text">Keywords for the search were as follows: (i) ((“Sleep Apnea Syndromes”[Mesh] OR “Sleep Apnea; Central”[Mesh] OR “Sleep Apnea; Obstructive”[Mesh]) OR sleep apnea) AND ((“functional magnetic resonance imaging”) OR “fMRI”); which resulted in 45 studies; (ii) (“Sleep Apnea Syndromes”[Mesh] OR “Sleep Apnea; Central”[Mesh] OR “Sleep Apnea; Obstructive”[Mesh]) OR sleep apnea AND ((“voxel-based morphometry”) OR “VBM”) that resulted in 21 studies ( ). </mark>No positron emission tomography (PET) studies met our criteria. Of note is that here; “study” reflects an individual scientific paper and “experiment” represents a single analysis or contrast of inter…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5103027/"
                                       >PMC5103027</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ning, eligibility and inclusion ( ). Publications were searched on three databases, notably on MEDLINE, via PubMed ( ), on Science Direct (Elsevier,  ), and Web of Science ( ), using the search string<mark class="annotated-text"> “(face OR facial) AND (trustworthiness OR trustworthy OR untrustworthy OR trustee) AND fMRI” (use of filter “article” and “short communication” in ScienceDirect; use of filter “article” in Web of Science).</mark> The search reported herein was undertaken in January 2016, without imposing any start and end date limit. Therefore, the search includes all the articles published until January 2016. References incl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5127572/"
                                       >PMC5127572</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … used the coordinate database (Fox &amp; Lancaster,  ; Fox et al.,  ; Laird et al.,  ) in Brainmap Sleuth ( ;  ) because it contains neuroimaging coordinates classified as saccade and word reading tasks. <mark class="annotated-text">The terms “[Image Modality = fMRI] AND [Paradigm = Saccade]” were entered to search for studies of eye movements; the terms “[Image Modality = fMRI] AND [Behavioral Domain = Cognition.Language‐Orthography]” were entered to search for studies of word reading. </mark>At the same time, we conducted a PubMed search ( ) using the search terms “prosaccade” and “fMRI” for studies of eye movements, and “reading,” “orthography,” and “fMRI” for studies of word reading. 

…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5434188/"
                                       >PMC5434188</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …iterature search 
  
We conducted a systematic review of PubMed articles up to December 3, 2015 in accordance with the Preferred Reporting Items for Systematic Reviews and Meta-Analyses guidelines  . <mark class="annotated-text">Search terms and combinations used are provided in  .</mark> Results were filtered for duplicates within each of the two main search categories, that is, AD dementia or MCI patients ( ). Unique search results underwent further screening as described subsequent…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5436069/"
                                       >PMC5436069</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …earch and study selection 
  
Studies examining IN-OT effects on the human brain published before March 2017, were selected through a standard search in PubMed, Embase and ScienceDirect, with keywords<mark class="annotated-text"> [‘oxytocin’] AND [‘fMRI’ OR ‘magnetic resonance imaging’].</mark> Additional studies were collected by reviewing the reference lists of relevant papers in the first step and the reference lists of several review articles. The first-level literature search yielded 4…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … be used for further validation and exploratory studies. 


## Analyses 
  
### Literature search 
  
On 28 June 2017, we conducted a PubMed literature search [ ] using the search strings as follows: <mark class="annotated-text">((Parkinson[Title/Abstract]) OR (Parkinson&#39;s[Title/Abstract])) AND ((“resting-state fMRI” OR ALFF OR ReHo OR “default mode network”)).</mark> A total of 138 articles were retrieved. 

We also reviewed articles and references to retrieve additional articles. An additional study, using the Kendall coefficient of concordance (KCC) method, was…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6025187/"
                                       >PMC6025187</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …stic research (e.g., video games, film, virtual reality). The first search string, performed on January 13, 2016, used the following string to identify relevant studies by their titles and abstracts: <mark class="annotated-text">((“naturalistic”[Title/Abstract] OR “real-world”[Title/Abstract] OR “ecologically valid”[Title/Abstract] OR “true-to-life”[Title/Abstract] OR “realistic”[Title/Abstract] OR “video game”[Title/Abstract] OR “film”[Title/Abstract] OR “movie”[Title/Abstract] OR “virtual reality”[Title/Abstract]) AND (“fMRI”[Title/Abstract] OR “functional magnetic resonance imaging”[Title/Abstract]) AND (“Humans”[MeSH])).</mark> This search yielded 679 studies (January 2016), some of which utilized stimulus types that we had not included in our initial query, including music, speech, and tactile objects. To identify any stud…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6326731/"
                                       >PMC6326731</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …music, speech, and tactile objects. To identify any studies using these tasks that may not have been returned by the initial query, a second search was performed on January 20, 2016, using the string <mark class="annotated-text">((“music”[Title/Abstract] OR “speech”[Title/Abstract] OR “spoken”[Title/Abstract] OR “tactile object”[Title/Abstract]) AND (“naturalistic”[Title/Abstract] OR “real-world”[Title/Abstract] OR “ecologically valid”[Title/Abstract] OR “true-to-life”[Title/Abstract] OR “realistic”[Title/Abstract]) AND (“fMRI”[Title/Abstract] OR “functional magnetic resonance imaging”[Title/Abstract]) AND “Humans”[MeSH]). </mark>This secondary search returned 48 studies, some of which were included in the results of the first search. The two sets of search results were pooled to identify 754 unique studies, which were then re…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6326731/"
                                       >PMC6326731</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-AES-SDM (37 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …obehav Rev, 2021

# Title

Mapping social reward and punishment processing in the human brain: A voxel-based meta-analysis of neuroimaging findings using the social incentive delay task.

# Keywords

<mark class="annotated-text">Anisotropic effect size signed differential mapping
</mark>Anticipation
Feedback
Social incentive delay
Social punishment
Social reward

# Abstract
Social rewards or punishments motivate human learning and behaviour, and alterations in the brain circuits invo…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … clinical triad including motor, cognitive and psychiatric impairment in Huntington&#39;s Disease (HD). We performed a voxel-based meta-analysis using anisotropic effect size-signed differential mapping (<mark class="annotated-text">AES-SDM</mark>) method. 6 studies (78 symptomatic HD, 102 premanifest HD and 131 healthy controls) were included in total. Altered resting-state brain activity was primarily detected in the bilateral medial part of…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … to functional neural changes in prefrontal control areas and fear-related limbic regions. Thus, discovering such therapy-associated neural changes might point to relevant mechanisms of action. Using <mark class="annotated-text">AES-SDM</mark>, we conducted a coordinate-based meta-analysis of 22 whole-brain datasets (n = 419 anxiety patients) from 18 studies identified by our systematic literature search following PRISMA criteria (preregis…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …der (rMDD) and MDD present common or distinct neuropathological mechanisms remains unclear. We performed a meta-analysis of task-related whole-brain functional magnetic resonance imaging (fMRI) using <mark class="annotated-text">anisotropic effect-size signed differential mapping</mark> software to compare brain activation between rMDD/MDD patients and healthy controls (HCs). We included 18 rMDD studies (458 patients and 476 HCs) and 120 MDD studies (3746 patients and 3863 HCs). The…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …f emotion processing tasks, as well as structural neuroimaging findings, and investigates multimodally affected brain regions. Combined coordinate- and image-based meta-analyses were calculated using <mark class="annotated-text">anisotropic effect size signed differential mapping</mark>. Nineteen functional neuroimaging studies investigating the processing of negative compared with neutral stimuli in a total of 281 patients with BPD and 293 healthy control subjects (HC) were include…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … of regional alterations. A meta-analysis has been employed to examine the common pattern of abnormal regional spontaneous brain activity in poststroke aphasia in the current study. Specifically, the <mark class="annotated-text">Anisotropic effect-size version of seed-based d mapping</mark> was utilized, and 237 poststroke aphasia patients and 242 healthy controls (HCs) from 12 resting-state functional magnetic resonance imaging studies using amplitude of low-frequency fluctuations (ALF…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …te meta-analysis for whole-brain voxel-based morphometry (VBM) studies and for functional imaging studies, and a multimodal meta-analysis across VBM and functional studies in iCD were conducted using <mark class="annotated-text">anisotropic effect size-based signed differential mapping</mark>. We included twenty-seven studies, including nine structural datasets comprising 152 iCD patients and 188 healthy controls, and seventeen functional datasets describing 352 iCD patients and 296 healt…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …rasting GAD and HC that included structure (connectivity and local indices such as volume, etc.), FC, or task-based magnetic resonance imaging data. Meta-analyses were conducted, as applicable, using <mark class="annotated-text">AES-SDM</mark> software. The literature search produced 4,645 total records, of which 85 met the inclusion criteria for the systematic review. Records included structural (n = 35), FC (n = 33), and task-based (n = …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g (AES-SDM) approach that was applied to meta-analyze the aberrant brain activity pattern of FD patients. A total of 11 articles with 260 FD patients and 202 healthy controls (HCs) were included. The <mark class="annotated-text">AES-SDM</mark> meta-analysis demonstrated that FD patients manifested increased activity in the bilateral insula, left anterior cingulate gyrus, bilateral thalamus, right precentral gyrus, left supplementary motor …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ole-brain functional magnetic resonance imaging (fMRI) or voxel-based morphometry (VBM). A CBMA of 30 fMRI (754 FRs; 959 controls) and 11 VBM (885 FRs; 775 controls) datasets were conducted using the <mark class="annotated-text">anisotropic effect-size version of signed differential mapping</mark>. Further, we conducted separate meta-analyses about functional alterations in different cognitive tasks: social cognition, executive functioning, working memory, and inhibitory control. FRs showed hi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - about ma&#39;s (35 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Lange, N
Hum Brain Mapp, 1997

# Title

<mark class="annotated-text">Empirical and substantive models, the Bayesian paradigm, and meta-analysis in functional brain imaging.
</mark>
# Keywords



# Abstract
Functional neuroimaging research is currently rediscovering and adapting established statistical methods for its use, including design of experiments, the general linear mode…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Han, Hyemin and Park, Joonsuk
Cogn Neurosci, 2019

# Title

<mark class="annotated-text">Bayesian meta-analysis of fMRI image data.
</mark>
# Keywords

-value
Bayes factors
Bayesian inference
Bayesian random-effect meta-analysis
fMRI
meta-analysis

# Abstract
We composed an R-based script for Image-based Bayesian random-effect meta-analy…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Suzuki, Keita and Yamashita, Okito
Neuroimage, 2021

# Title

<mark class="annotated-text">MEG current source reconstruction using a meta-analysis fMRI prior.
</mark>
# Keywords

Hierarchical Bayesian method
MEG inverse problem
Meta-analysis
Source reconstruction
fMRI

# Abstract
Magnetoencephalography (MEG) offers a unique way to noninvasively investigate millise…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Ramsey, J D and Spirtes, P and Glymour, C
Neuroimage, 2011

# Title

<mark class="annotated-text">On meta-analyses of imaging data and the mixture of records.
</mark>
# Keywords



# Abstract
Neumann et al. (2010) aim to find directed graphical representations of the independence and dependence relations among activities in brain regions by applying a search proce…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Smith, David V and Delgado, Mauricio R
Hum Brain Mapp, 2017

# Title

<mark class="annotated-text">Meta-analysis of psychophysiological interactions: Revisiting cluster-level thresholding and sample sizes.
</mark>
# Keywords

CBMA
PPI
fMRI
meta-analysis
open science
psychophysiological interaction

# Abstract
Within the neuroimaging community, coordinate based meta-analyses (CBMAs) are essential for aggregatin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Eickhoff, S B and Nickl-Jockschat, T and Kurth, F
Nervenarzt, 2010

# Title

<mark class="annotated-text">[Meta-analyses in clinical brain research].
</mark>
# Keywords



# Abstract
Positron emission tomography (PET) and functional magnetic resonance imaging (fMRI) have brought about an immense increase in findings on the localization of motor, cognitive…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Goutte, C and Hansen, L K and Liptrot, M G and Rostrup, E
Hum Brain Mapp, 2001

# Title

<mark class="annotated-text">Feature-space clustering for fMRI meta-analysis.
</mark>
# Keywords



# Abstract
Clustering functional magnetic resonance imaging (fMRI) time series has emerged in recent years as a possible alternative to parametric modeling approaches. Most of the work …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Neumann, Jane and von Cramon, D Yves and Lohmann, Gabriele
Hum Brain Mapp, 2008

# Title

<mark class="annotated-text">Model-based clustering of meta-analytic functional imaging data.
</mark>
# Keywords



# Abstract
We present a method for the analysis of meta-analytic functional imaging data. It is based on Activation Likelihood Estimation (ALE) and subsequent model-based clustering usi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Rokicki, Jaroslav and Quintana, Daniel S and Westlye, Lars T
Methods Mol Biol, 2022

# Title

<mark class="annotated-text">Linking Central Gene Expression Patterns and Mental States Using Transcriptomics and Large-Scale Meta-Analysis of fMRI Data: A Tutorial and Example Using the Oxytocin Signaling Pathway.
</mark>
# Keywords

Gene expression
Neuroendocrinology
Oxytocin
Oxytocin receptor
Social behavior
Social cognition

# Abstract
The measurement of gene expression levels in the human brain can help accelerate…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Neumann, Jane and Fox, Peter T and Turner, Robert and Lohmann, Gabriele
Neuroimage, 2010

# Title

<mark class="annotated-text">Learning partially directed functional networks from meta-analysis imaging data.
</mark>
# Keywords



# Abstract
We propose a new exploratory method for the discovery of partially directed functional networks from fMRI meta-analysis data. The method performs structure learning of Bayesi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA5 (34 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …tional MRI (fMRI) studies are inconclusive. To investigate the neural substrates of cue-reactivity and their relevance to treatment outcomes, alcohol craving and relapse in AUD patients, we performed <mark class="annotated-text">five</mark> meta-analyses using signed differential mapping software. Our meta-analysis revealed that alcohol cues evoke greater cue-reactivity than neutral cues in the mesocorticolimbic circuit and lower reacti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ons to merge available fMRI data on non-literal language. A literature search identified 38 fMRI studies on non-literal language (24 metaphor studies, 14 non-salient stimuli studies, 7 idiom studies, <mark class="annotated-text">8</mark> irony studies, and 1 metonymy study). Twenty-eight studies with direct comparisons of non-literal and literal studies were included in the main meta-analysis. Sub-analyses for metaphors, idioms, iron…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …on antisocial individuals based on distinct neurocognitive domains. A voxel-based meta-analysis via permutation of subject images (SDM-PSI) was performed on studies using fMRI tasks in the domains of <mark class="annotated-text">acute threat response, cognitive control, social cognition, punishment and reward processing</mark>. Overall, 83 studies were retrieved. Using a liberal statistical threshold, several key regions were identified in the meta-analysis, principally during acute threat response, social cognition and co…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es was analyzed to assess brain areas involved in vocal affect perception in general, as well as depending on the type of voice signal (speech prosody or vocalizations), the task demands (implicit or <mark class="annotated-text">explicit</mark> attention to emotions), and the specific emotion perceived. Results reassessed a consistent bilateral network of Emotional Voices Areas consisting of the superior temporal cortex and primary auditory…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ost negative and positive emotions, however there was a higher probability of activation for fear and disgust relative to happiness. The level of attentional processing affected amygdala activity, as <mark class="annotated-text">passive</mark> processing was associated with a higher probability of activation than active task instructions. Gustatory-olfactory and visual stimulus modalities increased the probability of activation relative to…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …dentify fMRI studies in youth (age 4-18) with depression or anxiety disorders. 48 studies with over 2000 participants were identified that met the inclusion criteria. Significant foci were extracted. <mark class="annotated-text">Five</mark> ALE meta-analyses were conducted: a) activation for both anxiety disorders and depression; b) activation for anxiety disorders only; c) activation for depression only; d) deactivation for both anxiet…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …NIMH&#39;s Research Domain Criteria (RDoC) framework, we evaluated consensus among studies that examined brain activity during social tasks to elucidate regions comprising the &#34;social brain&#34;. We examined <mark class="annotated-text">convergence</mark> across tasks corresponding to the four RDoC social constructs, including Affiliation and Attachment, Social Communication, Perception and Understanding of Self, and Perception and Understanding of Ot…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …is involved in the regulation of emotions toward outgroup members. Right insula can be engaged in the modulation of outgroup avoidance behavior. Fusiform gyrus (FG) appears to be directly involved in <mark class="annotated-text">social categorization process via top-down modulation of social perception</mark>. Yet it is difficult to associate any of the revealed clusters with the relational ingroup/outgroup structure. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …analysis for intervention duration showed that shorter exercise interventions induced changes in regions connected with frontoparietal and default mode networks, whereas regions exhibiting effects of <mark class="annotated-text">longer</mark> interventions connected with frontoparietal and dorsal attention networks. Our findings suggest that physical exercise interventions lead to changes in functional activation patterns primarily locate…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …in age-, sex- and IQ-matched subgroups with seed-based d mapping meta-analytic methods. Eighty-six independent VBM (1533 ADHD and 1295 controls; 1445 ASD and 1477 controls) and 60 fMRI datasets (1001 <mark class="annotated-text">ADHD</mark> and 1004 controls; 335 ASD and 353 controls) were identified. The VBM meta-analyses revealed ADHD-differentiating decreased ventromedial orbitofrontal (z = 2.22, p &lt; 0.0001) but ASD-differentiating i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">search terms - description (34 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ied through three PubMed ( ) searches. Searches for papers investigating visuomotor adaptation, motor sequence learning, and working memory were conducted separately using the following search terms: <mark class="annotated-text">“sensorimotor adaptation AND imaging,” “motor sequence learning AND imaging,” and “working memory AND imaging.” Additionally, the searches used the limits “Humans,” “English,” and “Adult 19-44 years.”</mark> These searches resulted in 45, 149, and 1997 papers, respectively. We also consulted a recent review of motor learning and included related work on sensorimotor adaptation not found in our PubMed sea…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …xamining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, ScienceDirect, Google Scholar, Web of Knowledge, and Scopus electronic search engines using keywords s<mark class="annotated-text">uch as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphenidate and stimulant. </mark>Citations within papers identified additional studies. Studies were excluded based on: 1) ROI analysis; 2) no report of coordinates; 3) no formal statistical comparison; and 4) less than 10 subjects. …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Search strategy 
  
We identified primary studies through a comprehensive literature search of the MEDLINE (using both free-text and MeSH search) and PsychINFO databases using the following keywords: <mark class="annotated-text">pediatric or child or adolescent, plus bipolar disorder or high-risk or at risk, and plus functional magnetic resonance imaging or fMRI.</mark> In addition, manual searches were conducted via reference sections of review articles and individual studies to check for any missing studies that were not identified using computerized searches. The…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217331/"
                                       >PMC4217331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … criteria 
  
PubMed, Medline, Ovid, Sciencedirect, Web of Science and Google Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included <mark class="annotated-text">fMRI and MRI, with subliminal and supraliminal stimulation as our search criteria. </mark>To be included in our meta-analysis, studies met the following criteria: a) studies were published within the last decade, between January 2001 to October 2013, b) published in a peer-reviewed journal…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tematic search strategy was performed to identify the relevant studies. We searched PubMed, MEDLINE, and EMBASE from 1993 to 2014 for all relevant published observational studies and clinical trials. <mark class="annotated-text">The following key terms were employed: “HT,” “HRT,” “HT,” “ERT,” “functional MRI or fMRI,” “cognitive dysfunction,” “postmenopausal,” “brain activation,” and “working memory.” </mark>The reference lists of these articles were searched to obtain additional relevant studies. All identified articles were reviewed by at least two authors, and studies were included in the meta-analysis…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Methods 
  
### Literature Search Methods 
  
Ovid Medline, Pubmed, and Emabase databases were searched for studies published up to April 2015 that reported functional MRI data in patients with MND. <mark class="annotated-text">Search terms included “motor neuron disease,” “MND,” “amyotrophic lateral sclerosis,” “ALS,” and these terms were combined using the AND operator with “functional magnetic resonance imaging,” “functional MRI,” “fMRI,” “blood oxygenation level dependent,” “BOLD,” “resting state,” and “connectivity.” Both text word and MeSH subject headings were used. </mark>Language was confined to English or Chinese, and reviews were excluded in the advanced search. The search strategy was supplemented by inspecting the reference lists of included articles. 


### Inclu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …o limits were set on the ages of participants. All relevant studies published up till June 2015 were incorporated. 

The databases PubMed, EMBASE, PsycInfo and Web of Science were searched, using the <mark class="annotated-text">search terms ODD, CD, disruptive behavioural disorder, disruptive behaviour, externalising behavioural disorder, externalising behaviour, MRI, neuroimaging, and equivalent MeSH terms</mark>. Furthermore, reference lists of selected studies and reviews were checked for additional relevant studies. A total of 576 studies were initially retrieved and screened, after which a total of 67 stu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …onducted through online scientific databases: PubMed/Medline, EMBASE, Web of Science, and PsycINFO. The literature search was performed in March 2015, with no restrictions on the date of publication. <mark class="annotated-text">Search terms included “cogniti*,” “rehabilitation,” “remediation,” “training,” or “enhancement,” with different combinations of “magnetic resonance imaging (MRI),” “fMRI” or “PET,” and “schizophrenia”. </mark>Two persons selected studies independently according to the following inclusion criterion: (1) they were peer-reviewed research articles; (2) they were written in English; (3) samples of participants …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …prehensive online literature search on the MEDLINE/PubMed databases was conducted, focusing on functional neuroimaging studies on MCI. Keyword searches were conducted using the following search terms:<mark class="annotated-text"> (1) ‘neuroimaging&#39; &lt;OR&gt; ‘fMRI,&#39; (2) ‘resting state&#39; OR ‘default network&#39; and (3) ‘mild cognitive impairment&#39; &lt;OR&gt; ‘MCI.&#39;</mark> These searches were confined to articles published in English up to March 2015, which yielded 228 original or review articles. We also searched through the reference lists of relevant review articles…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4872413/"
                                       >PMC4872413</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … peer-reviewed papers published in English through MEDLINE, PubMed, PsychINFO and Cochrane Library, including all potential articles from inception to July 2014. The following search terms were used: <mark class="annotated-text">‘Working Memory’ and ‘healthy adolescence/adolescents/developmental trajectories’ and “neuroimaging/fMRI”. </mark>The search was conducted without any language restrictions. Other reviews and articles were hand searched for relevant studies not identified from the computerized literature search. Authors were cont…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5153561/"
                                       >PMC5153561</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - not a full report (31 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Dugré, Jules Roger and Potvin, Stéphane
Psychol Med, 2021

# Title

<mark class="annotated-text">Impaired attentional and socio-affective networks in subjects with antisocial behaviors: a meta-analysis of resting-state functional connectivity studies.
</mark>
# Keywords

Functional connectivity
antisocial behaviors
conduct disorder
default mode network
dorsal attention network
ventral attention network

# Abstract
In the past decade, there has been a grow…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Wang, Haixia and Zhang, Jian and Jia, Huiyuan
Front Hum Neurosci, 2019

# Title

<mark class="annotated-text">Separate Neural Systems Value Prosocial Behaviors and Reward: An ALE Meta-Analysis.
</mark>
# Keywords

ALE
fMRI
prosocial behaviors
reward
social heuristic hypothesis

# Abstract

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Potvin, Stéphane and Gamache, Lydia and Lungu, Ovidiu
Front Neurol, 2019

# Title

<mark class="annotated-text">A Functional Neuroimaging Meta-Analysis of Self-Related Processing in Schizophrenia.
</mark>
# Keywords

anterior cingulate cortex
fMRI
meta-analysis
prefrontal cortex and thalamus
schizophrenia
self-processing

# Abstract

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Gao, Rong and Wang, Ping and Zhou, Sheng and Yao, Hongyan
Asian J Surg, 2023

# Title

<mark class="annotated-text">Resting-state fMRI study of vulnerable brain regions in patients with end-stage renal disease: An activation likelihood estimation meta-analysis.
</mark>
# Keywords

ALE meta-Analysis
End-stage renal disease
Impaired brain regions
Resting-state fMRI
Spontaneous neural activity

# Abstract

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Rasetti, Roberta and Chen, Qiang and Weinberger, Daniel R
Am J Psychiatry, 2020

# Title

<mark class="annotated-text">Comment on Limbic Hyperactivity in Response to Emotionally Neutral Stimuli in Schizophrenia: A Neuroimaging Meta-Analysis of the Hypervigilant Mind.
</mark>
# Keywords

Amygdala
Biological Markers
Brain Imaging Techniques
Psychosis
Schizophrenia
Schizophrenia Spectrum and Other Psychotic Disorders
fMRI

# Abstract

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Solstrand Dahlberg, Linda and Lungu, Ovidiu and Doyon, Julien
Front Neurol, 2020

# Title

<mark class="annotated-text">Cerebellar Contribution to Motor and Non-motor Functions in Parkinson&#39;s Disease: A Meta-Analysis of fMRI Findings.
</mark>
# Keywords

Parkinson&#39;s disease
cognition
fMRI
meta-analysis
motor
symptoms

# Abstract

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Cargnelutti, Elisa and Tomasino, Barbara and Fabbro, Franco
Front Hum Neurosci, 2021

# Title

<mark class="annotated-text">Effects of Linguistic Distance on Second Language Brain Activations in Bilinguals: An Exploratory Coordinate-Based Meta-Analysis.
</mark>
# Keywords

Ginger-ALE meta-analysis
age of appropriation (AoA)
bilingualism
fMRI
language families
linguistic distance

# Abstract
In this quantitative meta-analysis, we used the activation likeliho…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zang, Yu-Feng and Zuo, Xi-Nian and Milham, Michael and Hallett, Mark
Biomed Res Int, 2015

# Title

<mark class="annotated-text">Toward a Meta-Analytic Synthesis of the Resting-State fMRI Literature for Clinical Populations.
</mark>
# Keywords



# Abstract

                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Murty, Vishnu P and Ritchey, Maureen and Adcock, R Alison and LaBar, Kevin S
Neuropsychologia, 2011

# Title

<mark class="annotated-text">Reprint of: fMRI studies of successful emotional memory encoding: a quantitative meta-analysis.
</mark>
# Keywords



# Abstract
Over the past decade, fMRI techniques have been increasingly used to interrogate the neural correlates of successful emotional memory encoding. These investigations have typi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Yu, Junhong and Tao, Qian and Zhang, Ruibin and Chan, Chetwyn C H and Lee, Tatia M C
Neurosci Biobehav Rev, 2019

# Title

<mark class="annotated-text">Can fMRI discriminate between deception and false memory? A meta-analytic comparison between deception and false memory studies.
</mark>
# Keywords

Deception
fMRI
false memory
meta-analysis

# Abstract
Previous research has highlighted the potential of fMRI in discriminating between truth and falsehood. However, falsehoods may not ne…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">prospero ID (31 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …olescents with attention-deficit/hyperactivity disorder (ADHD) and in adults with ADHD to assess spatial convergence of findings from available studies. Based on a preregistered protocol in PROSPERO (<mark class="annotated-text">CRD42019119553</mark>), a large set of databases were searched up to April 9, 2019, with no language or article type restrictions. Study authors were systematically contacted for additional unpublished information/data. R…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …several insights into the potential mechanisms of acupuncture for musculoskeletal pain and provide a possible explanation for the observed clinical benefit of this therapy. https://www.crd.york.ac.uk/<mark class="annotated-text">prospero</mark>/display_record.php?RecordID=227850, identifier: CRD42021227850. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ture for musculoskeletal pain and provide a possible explanation for the observed clinical benefit of this therapy. https://www.crd.york.ac.uk/prospero/display_record.php?RecordID=227850, identifier: <mark class="annotated-text">CRD42021227850</mark>. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ide early biomarkers for clarifying the mechanism of cognitive impairment and neuropsychiatric disorders in diabetes. https://www.crd.york.ac.uk/prospero/display_record.php?RecordID=247071, PROSPERO [<mark class="annotated-text">CRD42021247071</mark>]. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tration 
  
This systematic review was conducted according to the Preferred Reporting Items for Systematic Reviews and Meta-Analysis (PRISMA) statement. The study protocol was registered on PROSPERO (<mark class="annotated-text">CRD42016047488</mark>  ). 


### Literature search 
  
A systematic search of all relevant publications was conducted in PubMed, EMBASE, Medline, Scopus, Web of Science, and the Cochrane library. A search was conducted in…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7857581/"
                                       >PMC7857581</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … and hence emerge consistently across studies, despite the use of different tasks or evaluation domains. 


## Methods 
  
### Study selection 
  
The study was pre-registered on PROSPERO repository (<mark class="annotated-text">CRD42019121856</mark>) and is reported following the PRISMA guidelines  (see   for PRISMA checklist). We conducted systematic searches in PubMed and PsychINFO from inception until 9th of July 2020. We used combinations of…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8144551/"
                                       >PMC8144551</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Items for Systematic Reviews and Meta-Analyses guidelines (PRISMA guidelines). The study was registered in the PROSPERO International prospective register of systematic reviews (registration number: <mark class="annotated-text">CRD 42020185421</mark>). 

### 2.1. Literature Search 
  
Studies that examined the neuroprotective effect of acupuncture in stroke patients were included in the present study. The PubMed, EMBASE, and Cochrane Library data…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …atasets, and explore their sensitivity and specificity in differentiating both disorders. 


## Methods 
  
Prior to the study initiation, the study was pre-registered on PROSPERO ( ) with project ID <mark class="annotated-text">CRD4201811443</mark>. The study was conducted in compliance with the PRISMA (Preferred Reporting Items for Systematic Reviews and Meta-analyses) guidelines for systematic review and met-analysis . 

### Search strategy a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8379217/"
                                       >PMC8379217</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ion with ZNF804A gene in healthy individuals, which indicate the contribution of genetic variants on brain dysfunction. 


## Registration Number 
  
This meta-analysis is registered in PROSPERO (No. <mark class="annotated-text">CRD42016051331</mark>). 

 

# Body
 
## Introduction 
  
Genome-wide association (GWA) studies have revealed that zinc finger protein 804 (ZNF804A) gene is associated with the susceptibility of mental disorders, such as …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8449690/"
                                       >PMC8449690</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …investigating changes of gray matter volume (GMV) and intrinsic functional connectivity (iFC) of large-scale intrinsic brain networks across MDD, ANX, and CP. The study was preregistered at PROSPERO (<mark class="annotated-text">CRD42019119709</mark>). 320 studies comprising 10,931 patients and 11,135 healthy controls were included. Across disorders,   common   changes focused on GMV-decrease in insular and medial-prefrontal cortices, located mai…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8938548/"
                                       >PMC8938548</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">registration - prospero (30 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ren and adolescents with attention-deficit/hyperactivity disorder (ADHD) and in adults with ADHD to assess spatial convergence of findings from available studies. Based on a preregistered protocol in <mark class="annotated-text">PROSPERO</mark> (CRD42019119553), a large set of databases were searched up to April 9, 2019, with no language or article type restrictions. Study authors were systematically contacted for additional unpublished inf…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …which provide early biomarkers for clarifying the mechanism of cognitive impairment and neuropsychiatric disorders in diabetes. https://www.crd.york.ac.uk/prospero/display_record.php?RecordID=247071, <mark class="annotated-text">PROSPERO</mark> [CRD42021247071]. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ng Items for Systematic Reviews and Meta-analyses ( ) reporting guideline  and field-standard guidelines for meta-analyses.  The following procedures and analyses conducted in this meta-analysis were <mark class="annotated-text">preregistered on </mark> . This study was deemed exempt from ethics approval by the University of Pennsylvania because only nonidentifiable summary statistics from published data were used. 

Briefly, we searched for experim…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7786252/"
                                       >PMC7786252</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tudy registration 
  
This systematic review was conducted according to the Preferred Reporting Items for Systematic Reviews and Meta-Analysis (PRISMA) statement. The study protocol was registered on <mark class="annotated-text">PROSPERO</mark> (CRD42016047488  ). 


### Literature search 
  
A systematic search of all relevant publications was conducted in PubMed, EMBASE, Medline, Scopus, Web of Science, and the Cochrane library. A search …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7857581/"
                                       >PMC7857581</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …otential nodes. This behavioral profile and MACM approach provides a reliable basis for future functional analysis. 


## Methods 
  
Details of the protocol for this meta-analysis were registered on <mark class="annotated-text">PROSPERO</mark> and can be accessed at  . 

### Literature search, study selection and data extraction 
  
The search for neuroimaging studies investigating GM differences in patients with AUD and healthy controls w…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7933165/"
                                       >PMC7933165</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ther mental functions and hence emerge consistently across studies, despite the use of different tasks or evaluation domains. 


## Methods 
  
### Study selection 
  
The study was pre-registered on <mark class="annotated-text">PROSPERO</mark> repository (CRD42019121856) and is reported following the PRISMA guidelines  (see   for PRISMA checklist). We conducted systematic searches in PubMed and PsychINFO from inception until 9th of July 20…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8144551/"
                                       >PMC8144551</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …or Systematic Reviews of Interventions  . All procedure followed the Preferred Reporting Items for Systematic Reviews and Meta-Analyses guidelines (PRISMA guidelines). The study was registered in the <mark class="annotated-text">PROSPERO</mark> International prospective register of systematic reviews (registration number: CRD 42020185421). 

### 2.1. Literature Search 
  
Studies that examined the neuroprotective effect of acupuncture in st…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mple, e.g. on more than ten datasets, and explore their sensitivity and specificity in differentiating both disorders. 


## Methods 
  
Prior to the study initiation, the study was pre-registered on <mark class="annotated-text">PROSPERO</mark> ( ) with project ID CRD4201811443. The study was conducted in compliance with the PRISMA (Preferred Reporting Items for Systematic Reviews and Meta-analyses) guidelines for systematic review and met-…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8379217/"
                                       >PMC8379217</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …clear correlation with ZNF804A gene in healthy individuals, which indicate the contribution of genetic variants on brain dysfunction. 


## Registration Number 
  
This meta-analysis is registered in <mark class="annotated-text">PROSPERO</mark> (No. CRD42016051331). 

 

# Body
 
## Introduction 
  
Genome-wide association (GWA) studies have revealed that zinc finger protein 804 (ZNF804A) gene is associated with the susceptibility of mental…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8449690/"
                                       >PMC8449690</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …I-studies investigating changes of gray matter volume (GMV) and intrinsic functional connectivity (iFC) of large-scale intrinsic brain networks across MDD, ANX, and CP. The study was preregistered at <mark class="annotated-text">PROSPERO</mark> (CRD42019119709). 320 studies comprising 10,931 patients and 11,135 healthy controls were included. Across disorders,   common   changes focused on GMV-decrease in insular and medial-prefrontal corti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8938548/"
                                       >PMC8938548</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-MKDA (29 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Fede, Samantha J and Kiehl, Kent A
Brain Imaging Behav, 2020

# Title

Meta-analysis of the moral brain: patterns of neural engagement assessed using multilevel kernel density analysis.

# Keywords

<mark class="annotated-text">MKDA</mark>
Machine learning
Meta-analysis
Moral
fMRI

# Abstract
The neuroimaging literature in moral cognition has rapidly developed in the last decade with more than 200 publications on the topic. Neuroimagin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …h-Brown, Benjamin and Roecher, Erik and Biswal, Bharat and Zweerings, Jana and Mathiak, Klaus
Addict Biol, 2022

# Title

Shared network-level functional alterations across substance use disorders: A <mark class="annotated-text">multi-level kernel density meta-analysis</mark> of resting-state functional connectivity studies.

# Keywords

functional magnetic resonance imaging
inhibitory control
meta-analysis
multi-level kernel density analysis
resting-state functional conn…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …C
Brain Struct Funct, 2017

# Title

Large-scale functional neural network correlates of response inhibition: an fMRI meta-analysis.

# Keywords

Action restrain
Interference resolution
Meta-analysis
<mark class="annotated-text">Multilevel kernel density analysis
</mark>fMRI

# Abstract
An influential hypothesis from the last decade proposed that regions within the right inferior frontal cortex of the human brain were dedicated to supporting response inhibition. Ther…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ctional neuroanatomy of peripheral inflammatory physiology: A meta-analysis of human neuroimaging studies.

# Keywords

Brain
Functional magnetic resonance imaging
Immunity
Inflammation
Meta-analysis
<mark class="annotated-text">Multilevel kernel density analysis</mark>
Neuroimaging
Positron emission tomography
Stress

# Abstract
Communication between the brain and peripheral mediators of systemic inflammation is implicated in numerous psychological, behavioral, and…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …o and Ibáñez, Agustín
Cortex, 2017

# Title

Convergence of interoception, emotion, and social cognition: A twofold fMRI meta-analysis and lesion approach.

# Keywords

Frontotemporal networks
Insula
<mark class="annotated-text">Multi-level Kernel Density Analysis
</mark>Stroke

# Abstract
Guided by indirect evidence, recent approaches propose a tripartite crosstalk among interoceptive signaling, emotional regulation, and low-level social cognition. Here we examined t…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …identified a series of different brain regions as being involved in empathy, it remains unclear concerning the activation consistence of these brain regions and their specific functional roles. Using <mark class="annotated-text">MKDA</mark>, a whole-brain based quantitative meta-analysis of recent fMRI studies of empathy was performed. This analysis identified the dACC-aMCC-SMA and bilateral anterior insula as being consistently activat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … in standard space in contrast of abstract &gt; concrete or concrete &gt; abstract concepts at a whole brain level in healthy adults were included in this meta-analysis. Multilevel kernel density analysis (<mark class="annotated-text">MKDA</mark>) was performed to identify the proportion of activated contrasts weighted by sample size and analysis type (fixed or random effects). Meta-analysis results indicated consistent and meaningful differe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …netic resonance imaging in ASD reported inconsistent findings on functional connectivity of the PCC. This study investigated the aberrant resting-state functional connectivity of the PCC in ASD using <mark class="annotated-text">multilevel kernel density analysis</mark>. Online databases (MEDLINE/PubMed) were searched for PCC-based functional connectivity in ASD. Ten studies (501 subjects; 161 reported foci) met the inclusion criteria of this meta-analysis. We found…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …f large-scale network abnormality in BD has been elusive. Whole-brain seed-based rs-FC and VBM studies comparing individuals with BD and healthy controls (HCs) were retrieved from multiple databases. <mark class="annotated-text">Multilevel kernel density analysis</mark> was used to identify brain networks in which BD was linked to hyper-connectivity or hypo-connectivity with each prior network and the overlap between dysconnectivity and GMV changes. Thirty-six seed-…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es reporting neural activity associated with interoceptive attentiveness (i.e. focused attention to a particular interoceptive signal for a given time interval) to one&#39;s heartbeat were submitted to a <mark class="annotated-text">multilevel kernel density analysis</mark>. The findings corroborated an extended network associated with heart-focused interoceptive attentiveness including the posterior right and left insula, right claustrum, precentral gyrus and medial fr…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">NO N studies found (26 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Xia</mark>, Wenqing and Chen, Yu-Chen and Ma, Jianhua
Front Aging Neurosci, 2017

# Title

Resting-State Brain Anomalies in Type 2 Diabetes: A Meta-Analysis

# Keywords

type 2 diabetes
resting-state fMRI
meta-…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">45</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5281680/"
                                       >PMC5281680</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Xiao</mark>, Bo and Wang, Shuai and Liu, Jianbo and Meng, Tiantian and He, Yuqiong and Luo, Xuerong
Neuropsychiatr Dis Treat, 2017

# Title

Abnormalities of localized connectivity in schizophrenia patients and …
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">27</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5317331/"
                                       >PMC5317331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Berlingeri</mark>, Manuela and Magnani, Francesca Giulia and Salvato, Gerardo and Rosanova, Mario and Bottini, Gabriella
J Clin Med, 2019

# Title

Neuroimaging Studies on Disorders of Consciousness: A Meta-Analytic E…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">1522</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6517954/"
                                       >PMC6517954</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Emch</mark>, Mónica and von Bastian, Claudia C. and Koch, Kathrin
Front Hum Neurosci, 2019

# Title

Neural Correlates of Verbal Working Memory: An fMRI Meta-Analysis

# Keywords

verbal working memory
meta-anal…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">589</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6581736/"
                                       >PMC6581736</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Zinchenko</mark>, Oksana
Sci Rep, 2019

# Title

Brain responses to social punishment: a meta-analysis

# Keywords

Decision
Cooperation


# Abstract
 
Many studies suggest that social punishment is beneficial for co…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">132</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6728376/"
                                       >PMC6728376</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Cook</mark>, Michael J. and Gardner, Andrew J. and Wojtowicz, Magdalena and Williams, W. Huw and Iverson, Grant L. and Stanwell, Peter
Neuroimage Clin, 2019

# Title

Task-related functional magnetic resonance i…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">8219</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6939096/"
                                       >PMC6939096</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Arsalidou</mark>, Marie and Pawliw-Levac, Matthew and Sadeghi, Mahsa and Pascual-Leone, Juan
Dev Cogn Neurosci, 2017

# Title

Brain areas associated with numbers and calculations in children: Meta-analyses of fMRI s…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">151</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6969084/"
                                       >PMC6969084</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Lin</mark>, Xiao and Deng, Jiahui and Shi, Le and Wang, Qiandong and Li, Peng and Li, Hui and Liu, Jiajia and Que, Jianyu and Chang, Suhua and Bao, Yanping and Shi, Jie and Weinberger, Daniel R. and Wu, Ping an…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">4398</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7078287/"
                                       >PMC7078287</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Meier</mark>, Sarah K. and Ray, Kimberly L. and Mastan, Juliana C. and Salvage, Savannah R. and Robin, Donald A.
PLoS One, 2021

# Title

Meta-analytic connectivity modelling of deception-related brain regions

#…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">261</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8386837/"
                                       >PMC8386837</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Gavazzi</mark>, Gioele and Giovannelli, Fabio and Currò, Tommaso and Mascalchi, Mario and Viggiano, Maria Pia
Brain Imaging Behav, 2020

# Title

Contiguity of proactive and reactive inhibitory brain areas: a cogni…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">574</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8413163/"
                                       >PMC8413163</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">guidelines - none (26 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Bernard, Jessica <mark class="annotated-text">A</mark>. and Seidler, Rachael D.
Front Hum Neurosci, 2013

# Title

Cerebellar contributions to visuomotor adaptation and motor sequence learning: an ALE meta-analysis

# Keywords

cerebellum
sequence learni…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3566602/"
                                       >PMC3566602</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Sundermann, <mark class="annotated-text">Benedikt</mark> and Olde lütke Beverborg, Mona and Pfleiderer, Bettina
Front Hum Neurosci, 2014

# Title

Toward literature-based feature selection for diagnostic classification: a meta-analysis of resting-state fMR…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4159995/"
                                       >PMC4159995</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Liebenthal, Einat <mark class="annotated-text">and</mark> Desai, Rutvik H. and Humphries, Colin and Sabri, Merav and Desai, Anjali
Front Neurosci, 2014

# Title

The functional organization of the left STS: a large scale meta-analysis of PET and fMRI studie…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4160993/"
                                       >PMC4160993</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Rubia, Katya <mark class="annotated-text">and</mark> Alegria, Analucia A. and Cubillo, Ana I. and Smith, Anna B. and Brammer, Michael J. and Radua, Joaquim
Biol Psychiatry, 2014

# Title

Effects of Stimulants on Brain Function in Attention-Deficit/Hyp…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Lee</mark>, Moon-Soo and Anumagalla, Purnima and Talluri, Prasanth and Pavuluri, Mani N.
Front Psychiatry, 2014

# Title

Meta-Analyses of Developing Brain Function in High-Risk and Emerged Bipolar Disorder

# …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217331/"
                                       >PMC4217331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Li, Ke <mark class="annotated-text">and</mark> Huang, Xiaoyan and Han, Yingping and Zhang, Jun and Lai, Yuhan and Yuan, Li and Lu, Jiaojiao and Zeng, Dong
Front Hum Neurosci, 2015

# Title

Enhanced Neuroactivation during Working Memory Task in P…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Shen, Dongchao <mark class="annotated-text">and</mark> Cui, Liying and Cui, Bo and Fang, Jia and Li, Dawei and Ma, Junfang
Front Neurol, 2015

# Title

A Systematic Review and Meta-Analysis of the Functional MRI Investigation of Motor Neuron Disease

# K…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Lau, W <mark class="annotated-text">K</mark> W and Leung, M-K and Lee, T M C and Law, A C K
Transl Psychiatry, 2016

# Title

Resting-state abnormalities in amnestic mild cognitive impairment: a meta-analysis

# Keywords



# Abstract
 
Amnesti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4872413/"
                                       >PMC4872413</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Martin, Anna and Schurz, <mark class="annotated-text">Matthias</mark> and Kronbichler, Martin and Richlan, Fabio
Hum Brain Mapp, 2015

# Title

Reading in the brain of children and adults: A meta‐analysis of 40 functional magnetic resonance imaging studies

# Keywords
…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4950303/"
                                       >PMC4950303</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Acikalin, M. <mark class="annotated-text">Yavuz</mark> and Gorgolewski, Krzysztof J. and Poldrack, Russell A.
Front Neurosci, 2017

# Title

A Coordinate-Based Meta-Analysis of Overlaps in Regional Specialization and Functional Connectivity across Subjec…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5243799/"
                                       >PMC5243799</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - embase (24 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …gnition and working memory. 


## Methods 
  
### Data sources and inclusion criteria 
  
A systematic search strategy was performed to identify the relevant studies. We searched PubMed, MEDLINE, and <mark class="annotated-text">EMBASE</mark> from 1993 to 2014 for all relevant published observational studies and clinical trials. The following key terms were employed: “HT,” “HRT,” “HT,” “ERT,” “functional MRI or fMRI,” “cognitive dysfuncti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ain activity in patients with MND and in healthy controls (HCs) to identify common findings across studies. 


## Materials and Methods 
  
### Literature Search Methods 
  
Ovid Medline, Pubmed, and <mark class="annotated-text">Emabase</mark> databases were searched for studies published up to April 2015 that reported functional MRI data in patients with MND. Search terms included “motor neuron disease,” “MND,” “amyotrophic lateral sclero…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …o be published in a peer-reviewed English language journal. No limits were set on the ages of participants. All relevant studies published up till June 2015 were incorporated. 

The databases PubMed, <mark class="annotated-text">EMBASE</mark>, PsycInfo and Web of Science were searched, using the search terms ODD, CD, disruptive behavioural disorder, disruptive behaviour, externalising behavioural disorder, externalising behaviour, MRI, ne…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ore the effectiveness of different study methods. 


## M 
  
### Literature search and selection 
  
Computerized literature search was conducted through online scientific databases: PubMed/Medline, <mark class="annotated-text">EMBASE</mark>, Web of Science, and PsycINFO. The literature search was performed in March 2015, with no restrictions on the date of publication. Search terms included “cogniti*,” “rehabilitation,” “remediation,” “…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ofrontal cortex, and bilateral cuneus cortices merit further investigations. 


## Methods 
  
### Identification, selection, and quality assessment of studies 
  
We comprehensively searched PubMed, <mark class="annotated-text">Embase</mark>, and Web of Science databases for studies published between January 1st, 2000 and June 24, 2016 using the following keywords “Parkinson” OR “Parkinson’s disease”, AND “amplitude of low frequency fluc…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5228032/"
                                       >PMC5228032</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …les. 


## Methods 
  
### Literature search and study selection 
  
Studies examining IN-OT effects on the human brain published before March 2017, were selected through a standard search in PubMed, <mark class="annotated-text">Embase</mark> and ScienceDirect, with keywords [‘oxytocin’] AND [‘fMRI’ OR ‘magnetic resonance imaging’]. Additional studies were collected by reviewing the reference lists of relevant papers in the first step and…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …l profiles, such as age and comorbidity. 


## Methods 
  
### Search strategies 
  
A comprehensive systematic literature search was conducted using PubMed, the Cochrane Library, Web of Science, and <mark class="annotated-text">Embase</mark> databases to identify functional magnetic resonance imaging literature on anxiety disorders, published before September 2017 and including “in press” articles. The search keywords were “panic disorde…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5953307/"
                                       >PMC5953307</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Search and Study Selection 
  
The meta-analysis of neuroimaging studies was conducted according to the PRISMA statement and recorded using the suggested checklist. 

#### Search Strategy 
  
PubMed, <mark class="annotated-text">Embase</mark>, and Web of science were thoroughly and systematically searched. Search keywords were as follows: (1) (“functional magnetic resonance imaging” [MeSH] OR “RESTING STATE” [MeSH]) AND [“mild cognitive i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7581707/"
                                       >PMC7581707</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …istration number: CRD 42020185421). 

### 2.1. Literature Search 
  
Studies that examined the neuroprotective effect of acupuncture in stroke patients were included in the present study. The PubMed, <mark class="annotated-text">EMBASE</mark>, and Cochrane Library databases, Web of Science, China National Knowledge Infrastructure (CNKI), Chongqing VIP (VIP), and the Wanfang Database (WF) were searched from inception until May 2020 by two …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …severity and statistical correction for multiple comparisons. 


## METHODS 
  
### Literature search 
  
A comprehensive computerized search was performed in the databases PubMed, Web of Science and <mark class="annotated-text">Embase</mark> using the following key words ALFF &lt;or&gt; ReHo &lt;or&gt; rCBF &lt;or&gt; rCMRglu &lt;or&gt; ASL &lt;or&gt; amplitude of low frequency fluctuations &lt;or&gt; low frequency fluctuations &lt;or&gt; regional homogeneity &lt;or&gt; regional cereb…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8193520/"
                                       >PMC8193520</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">read later (23 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Cauda</mark>, Franco and Cavanna, Andrea E and D&#39;agata, Federico and Sacco, Katiuscia and Duca, Sergio and Geminiani, Giuliano C
J Cogn Neurosci, 2011

# Title

Functional connectivity and coactivation of the nuc…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Lange, N
Hum Brain Mapp, 1997

# Title

<mark class="annotated-text">Empirical and substantive models, the Bayesian paradigm, and meta-analysis in functional brain imaging.
</mark>
# Keywords



# Abstract
Functional neuroimaging research is currently rediscovering and adapting established statistical methods for its use, including design of experiments, the general linear mode…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Ramsey, J D and Spirtes, P and Glymour, C
Neuroimage, 2011

# Title

<mark class="annotated-text">On meta-analyses of imaging data and the mixture of records.
</mark>
# Keywords



# Abstract
Neumann et al. (2010) aim to find directed graphical representations of the independence and dependence relations among activities in brain regions by applying a search proce…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Niu, Zhendong and Nie, Yaoxin and Zhou, Qian and Zhu, Linlin and Wei, Jieyao
BMC Neurosci, 2016

# Title

<mark class="annotated-text">A brain-region-based meta-analysis method utilizing the Apriori algorithm.
</mark>
# Keywords

Apriori algorithm
Brain network connectivity
Co-activation relationship
Meta-analysis
Word reading
fMRI

# Abstract
Brain network connectivity modeling is a crucial method for studying th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Fox, Peter T and Lancaster, Jack L and Laird, Angela R and Eickhoff, Simon B
Annu Rev Neurosci, 2014

# Title

<mark class="annotated-text">Meta-analysis in human neuroimaging: computational modeling of large-scale databases.
</mark>
# Keywords

ALE
MRI
activation likelihood estimation
fMRI
human brain mapping
magnetic resonance imaging

# Abstract
Spatial normalization--applying standardized coordinates as anatomical addresses w…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Tench, C R and Tanasescu, R and Constantinescu, C S and Auer, D P and Cottam, W J
J Neurosci Methods, 2022

# Title

<mark class="annotated-text">Easy to interpret coordinate based meta-analysis of neuroimaging studies: Analysis of brain coordinates (ABC).
</mark>
# Keywords

Functional MRI
Meta-analysis
Neuroimaging
Voxel-based morphometry

# Abstract
Functional MRI and voxel-based morphometry are important in neuroscience. They are technically challenging wi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Yeung, Andy Wai Kan and Robertson, Michaela and Uecker, Angela and Fox, Peter T and Eickhoff, Simon B
Hum Brain Mapp, 2023

# Title

<mark class="annotated-text">Trends in the sample size, statistics, and contributions to the BrainMap database of activation likelihood estimation meta-analyses: An empirical study of 10-year data.
</mark>
# Keywords

activation likelihood estimation
fMRI
meta-analysis
neuroimaging
reproducibility
statistical threshold

# Abstract
The literature of neuroimaging meta-analysis has been thriving for over …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Samartsidis, Pantelis and Montagna, Silvia and Laird, Angela R and Fox, Peter T and Johnson, Timothy D and Nichols, Thomas E
Res Synth Methods, 2020

# Title

<mark class="annotated-text">Estimating the prevalence of missing experiments in a neuroimaging meta-analysis.
</mark>
# Keywords

meta-analysis
neuroimaging
publication-bias
zero-truncated modeling

# Abstract
Coordinate-based meta-analyses (CBMA) allow researchers to combine the results from multiple functional mag…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …elis and Eickhoff, Claudia R and Eickhoff, Simon B and Wager, Tor D and Barrett, Lisa Feldman and Atzil, Shir and Johnson, Timothy D and Nichols, Thomas E
J R Stat Soc Ser C Appl Stat, 2019

# Title

<mark class="annotated-text">Bayesian log-Gaussian Cox process regression: with applications to meta-analysis of neuroimaging working memory studies.
</mark>
# Keywords

functional magnetic resonance imaging
meta-regression
random effects meta-analysis
working memory

# Abstract
Working memory (WM) was one of the first cognitive processes studied with fun…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …nd Banaschewski, Tobias and Barker, Gareth J and Bokde, Arun L W and Martinot, Jean-Luc and Lemaitre, Herve and Paus, Tomáš and Millenet, Sabina and Moerkerke, Beatrijs
Front Neurosci, 2017

# Title

<mark class="annotated-text">The Influence of Study-Level Inference Models and Study Set Size on Coordinate-Based fMRI Meta-Analyses.
</mark>
# Keywords

coordinate-based meta-analysis
fMRI
group modeling
mixed effects models
random effects models
reliability

# Abstract
Given the increasing amount of neuroimaging studies, there is a growi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-SDM-PSI (21 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … and Vieta, Eduard and Mataix-Cols, David and Radua, Joaquim
J Vis Exp, 2019

# Title

Meta-analysis of Voxel-Based Neuroimaging Studies using Seed-based d Mapping with Permutation of Subject Images (<mark class="annotated-text">SDM-PSI</mark>).

# Keywords



# Abstract
Most methods for conducting meta-analysis of voxel-based neuroimaging studies do not assess whether effects are not null, but whether there is a convergence of peaks of st…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …st). We aimed to conduct a meta-analysis of whole-brain fMRI studies on antisocial individuals based on distinct neurocognitive domains. A voxel-based meta-analysis via permutation of subject images (<mark class="annotated-text">SDM-PSI</mark>) was performed on studies using fMRI tasks in the domains of acute threat response, cognitive control, social cognition, punishment and reward processing. Overall, 83 studies were retrieved. Using a …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d on March 20, 2020. This protocol will follow the Preferred Reporting Items for Systematic review and Meta-Analysis Protocols (PRISMA-P). The Seed-based d Mapping with Permutation of Subject Images (<mark class="annotated-text">SDM-PSI</mark>) software will be used for this voxel-wise meta-analysis. This meta-analysis will identify the most consistent ReHo alterations in CP. To our knowledge, this will be the first voxel-wise meta-analysi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ch strategy was applied to select pertinent studies up to December 2022 in PubMed, Web of Science, and Embase databases. Voxel-wise meta-analysis was conducted via the latest meta-analytic algorithm, <mark class="annotated-text">seed-based d mapping with permutation of subject images</mark> software. Meta-regression analyses were also conducted to explore the potential effect of clinical variables on resting-state neural activity. Eleven studies comprising 304 patients with ESRD and 296…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …gqing VIP database, VIP; and the Wanfang database, WF). A neuroimaging meta-analysis on ALFF, ReHo was performed on the included studies using Seed-based d Mapping with Permutation of Subject Images (<mark class="annotated-text">SDM-PSI</mark>) software. Subgroup analyses were used to compare differences in brain regions between acupuncture and other groups. Meta-regression was used to explore the effect of demographic information and migr…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …I to observe the effect of acupuncture on stroke patients with motor dysfunction. R software was used to analyze the continuous variables, and Seed-based d Mapping with Permutation of Subject Images (<mark class="annotated-text">SDM-PSI</mark>) was used to perform an analysis of fMRI data.   Findings  . A total of 7 studies comprising 143 patients in the treatment group and 138 in the control group were included in the meta-analysis. The r…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …taneous neural activity abnormalities in patients with T2DM. 

 Methods:   A systematic search was conducted to identify voxel-based rs-fMRI studies comparing T2DM patients with healthy controls. The <mark class="annotated-text">permutation of subject images seed-based   d   mapping (SDM)</mark> was used to quantitatively estimate the regional spontaneous neural activity abnormalities in patients with T2DM. Metaregression was conducted to examine the associations between clinical characteris…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8245688/"
                                       >PMC8245688</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …was incomplete were excluded. 


## Data sources 
  
Ovid, Medline and PsycInfo, from 2000 to 2020, plus checking of review articles and meta-analyses. 


## Data synthesis 
  
Data were pooled using <mark class="annotated-text">Seed-based d Mapping with Permutation of Subject Images</mark> (SDM-PSI). Heterogeneity among studies was examined using the   I   statistic. Publication bias was examined using funnel plots and statistical examination of asymmetries. Moderator variables includi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8341642/"
                                       >PMC8341642</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es (Table  ). Finally, as MKDA meta-analysis cannot deal with studies reporting no significant results (Table   lists these studies), we used “Seed-based d-Mapping with Permutation of Subject Images (<mark class="annotated-text">SDM-PSI</mark>)” to test whether excluding these studies biased results ( ) [ ]. 



## Results 
  
### Included studies 
  
Concerning GMV, 63 MDD-studies (2934 patients/3284 controls), 41 ANX-studies (1021/1130),…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8938548/"
                                       >PMC8938548</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …of 17–20 studies . 

Coordinate-based meta-analysis (CBMA) was performed using the random-effects activation likelihood estimation (ALE) algorithm  implemented in the GingerALE 3.0.2 software ( ) and <mark class="annotated-text">Seed-based   d   Mapping with Permutation of Subject Images </mark>(SDM-PSI) algorithm  implemented in the SDM-PSI 6.22 software ( ). Two different CBMA algorithms were used for the cross-method validation. 

The ALE algorithm assesses the spatial convergence between…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9203582/"
                                       >PMC9203582</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA6 (18 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …olved in vocal affect perception in general, as well as depending on the type of voice signal (speech prosody or vocalizations), the task demands (implicit or explicit attention to emotions), and the <mark class="annotated-text">specific emotion</mark> perceived. Results reassessed a consistent bilateral network of Emotional Voices Areas consisting of the superior temporal cortex and primary auditory regions. Specific activations and lateralization…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ctivation for fear and disgust relative to happiness. The level of attentional processing affected amygdala activity, as passive processing was associated with a higher probability of activation than <mark class="annotated-text">active</mark> task instructions. Gustatory-olfactory and visual stimulus modalities increased the probability of activation relative to internal stimuli. Aversive learning increased the probability of amygdala act…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … to identify if each type of task involves a different neural substrate and to distinguish the neurocognitive contribution of each component of ecological validity essential to deception. We detected <mark class="annotated-text">six categories of deception tasks</mark>. Intention to lie was the component least frequently included, followed by social interaction. Monetary reward was the most frequent motivator. The results of the meta-analysis, including 59 contrast…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … subgroups with seed-based d mapping meta-analytic methods. Eighty-six independent VBM (1533 ADHD and 1295 controls; 1445 ASD and 1477 controls) and 60 fMRI datasets (1001 ADHD and 1004 controls; 335 <mark class="annotated-text">ASD</mark> and 353 controls) were identified. The VBM meta-analyses revealed ADHD-differentiating decreased ventromedial orbitofrontal (z = 2.22, p &lt; 0.0001) but ASD-differentiating increased bilateral temporal…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ilarly distribution and activation pattern (details see Table   and Fig.  ). 



### Between-group ALE analysis in a transdiagnostic approach across MDD and SZ 
  
#### Consummatory anhedonia 
  
For <mark class="annotated-text">consummatory anhedonia</mark> (29 studies and 151 foci), ALE analysis revealed five statistically significant clusters with decreased likelihood of activation in patients compared to controls (Fig.   and Table  ), including bilat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …activation pattern (details see Table   and Fig.  ). 



### Between-group ALE analysis in a transdiagnostic approach across MDD and SZ 
  
#### Consummatory anhedonia 
  
For consummatory anhedonia (<mark class="annotated-text">29</mark> studies and 151 foci), ALE analysis revealed five statistically significant clusters with decreased likelihood of activation in patients compared to controls (Fig.   and Table  ), including bilateral…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s 
  
First-level analyses on common executive (shared activation across tasks tapping inhibition, switching, and updating executive processes; Figure  ) and each specific putative executive process (<mark class="annotated-text">inhibition</mark>, updating, and switching) were conducted. First-level analyses describe clusters that pass the applied threshold for significant conjunctive activation across these groups of studies. These analyses …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5383671/"
                                       >PMC5383671</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n specific to experimental hyperalgesia in healthy controls as a model of pain sensitisation. To this end we studied the pattern of pain processing in HC after experimental induction of hyperalgesia (<mark class="annotated-text">HYPER</mark>  subgroup;  ) in comparison with normalgesia by CBMA of the hyperalgesia group, and by CMA and MAC between hyperalgesia and normalgesia. The frequency of reporting brain structures activated in each …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5554296/"
                                       >PMC5554296</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …  P   &lt;     0.05; 41 ‘OT &gt; PL’ contrasts, 250 activation coordinates;  ) and decreased neural activity in right amygdala (FWE   P   &lt;     0.05; 36 ‘OT &lt; PL’ contrasts, 228 activation coordinates;  ). <mark class="annotated-text">Twenty-one</mark> contrasts examined the effects of IN-OT in clinical population. ALE analysis from FWE correction revealed that IN-OT increased neural activity in the dorsal anterior cingulate cortex (dACC) (FWE   P …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …en different task domains, contrast analyses ( ) were conducted between each pair of the Think/No-Think, Stop-signal and Go/No-Go Tasks (i.e., Think/No-Think &amp; Stop-signal; Think/No-Think &amp; Go/No-Go; <mark class="annotated-text">Stop-signal &amp; Go/No-Go</mark>). For analysing each pair of the tasks, the thresholded activation maps from the individual analyses, as well as the pooled results from both tasks were used as inputs. The outputs were conjunction a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5759998/"
                                       >PMC5759998</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">exclusion - min n (18 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …vestigating a specific comorbidity) compared to healthy controls. Of these 51 studies identified, whole text versions were screened for studies fulfilling these criteria as well as including at least <mark class="annotated-text">10</mark> subjects per group and reporting resulting coordinates of group comparisons (depression vs. healthy controls) in either MNI/ICBM (Mazziotta et al.,  ) or Talairach ( ) space. Thirty Two studies fulfi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4159995/"
                                       >PMC4159995</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ates in Talairach space (Talairach and Tournoux,  ). From these, 485 activation peaks from 253 different studies meeting the inclusion criteria of representing data collected from a group of at least <mark class="annotated-text">8</mark> healthy adults of mixed gender, and using a high-level baseline, were incorporated in the meta-analysis. Functional contrasts using a low-level baseline, such as fixation or rest, were excluded due t…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4160993/"
                                       >PMC4160993</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d standard Talairach or Montreal Neurological Institute (MNI) spatial co-ordinates for the key findings, (4) patient participants had been diagnosed with bipolar disorder, and (5) there were at least <mark class="annotated-text">five</mark> members in each of the participant groups. We included only those studies that reported activation foci as 3D co-ordinates in stereotactic space, examined active task constructs, and presented result…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">5</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217331/"
                                       >PMC4217331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …so sufficiently open-ended to be construct-valid assays of creativity (i.e., they must allow freedom for divergent production)” ( , p. 924). (5) Only group studies involving a sample size of at least <mark class="annotated-text">five</mark> participants were included. (6) There could be no pharmacological manipulation. (7) Only activation foci were considered. Thus, studies reporting only deactivation foci were excluded from our meta-an…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">5</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4531218/"
                                       >PMC4531218</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …sub-sample. 
  
Intervention studies (pre/post treatment contrasts such as CPAP). 
  
Studies without a “control group” i.e. those focused only on a group of OSA patients. 
  
Studies where less than <mark class="annotated-text">7</mark> patients were included in each group. 
  


### Data extraction 
  
Two investigators independently extracted the information (M.T and A.A.S). Recorded data included the first author’s name, year of …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5103027/"
                                       >PMC5103027</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …iews; (3) they only reported region of interest results instead of whole-brain findings; (4) task activation analyses using the fMRI method were not used; (5) either the patient or HC group included ≤<mark class="annotated-text">10</mark> patients; and (6) where the same patient group was used in different publications, only the study with the largest sample was included. 


### Quality assessment and data extraction 
  
We performed …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5953307/"
                                       >PMC5953307</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …2) region of interest analyses, small volume corrected results and experiments with only partial brain coverage, (3) methodological studies and study protocols, (4) studies with small sample sizes (&lt; <mark class="annotated-text">10</mark> per group) and (5) studies with statistical approaches not correcting for multiple comparisons or setting a minimum cluster extension as statistical threshold for significance . Unlike conventional m…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7933165/"
                                       >PMC7933165</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …) used secondary outcomes to assess clinical efficacy. The exclusion criteria were as follows: (1) the study only used region of interest (ROI) method; (2) the sample size in each group was less than <mark class="annotated-text">5</mark>; (3) if separate papers used the same or similar datasets, only the largest sample was included. 


### 2.3. Data Extraction and Quality Assessment 
  
Data were extracted from the included studies i…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … whole-brain contrasts comparing BD and MDD subjects in rs-fMRI, (3) both compared samples currently depressed, (4) moderate severity of depression when enrolled (MADRS ≥ 20, HAMD ≥ 17), (5) at least <mark class="annotated-text">ten</mark> subjects per group. Subsequently, excluding criteria were applied: (1) reported psychiatric or neurological comorbidity, (2) study included only bipolar type II participants, (3) seasonal depression,…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">10</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8379217/"
                                       >PMC8379217</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …participants with other types of addictive or psychiatric disorders; (ii) literature lacking anatomical coordinates for the main results; (iii) repeated publications; (iv) studies with a sample size &lt;<mark class="annotated-text">15</mark> cases. 


### Data Extraction 
  
According to the literature retrieval method, the researchers (JW and QHH) independently downloaded the literature that met the requirements and removed the duplicat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9062178/"
                                       >PMC9062178</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-ES-SDM (15 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …Title

The prefrontal dysfunction in individuals with Internet gaming disorder: a meta-analysis of functional magnetic resonance imaging studies.

# Keywords

Effect size signed differential mapping (<mark class="annotated-text">ES-SDM</mark>)
Internet gaming disorder (IGD)
functional magnetic resonance imaging (fMRI)
impulsivity
reward system
the prefrontal lobe

# Abstract
With the advancement in high-resolution magnetic resonance imagi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …im and Palaniyappan, Lena
Neurosci Biobehav Rev, 2015

# Title

Localized connectivity in depression: a meta-analysis of resting state functional imaging studies.

# Keywords

Connectivity
Depression
<mark class="annotated-text">Effect size – signed differential mapping</mark>
Regional homogeneity
Resting-state fMRI

# Abstract
Resting-state fMRI studies investigating the pathophysiology of depression have identified prominent abnormalities in large-scale brain networks. H…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ehav Brain Res, 2014

# Title

Reward pathway dysfunction in gambling disorder: A meta-analysis of functional magnetic resonance imaging studies.

# Keywords

Effect size signed differential mapping (<mark class="annotated-text">ES-SDM</mark>)
Functional magnetic resonance imaging (FMRI)
Gambling disorder (GD)
The frontostriatal cortical pathway

# Abstract
Recent emerging functional magnetic resonance imaging (fMRI) studies have identifi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … language comprehension in human children. Our analysis included 27 independent experiments involving n ​= ​625 children (49% girls) with a mean age of 8.9 years. Activation likelihood estimation and <mark class="annotated-text">seed-based effect size mapping</mark> revealed activation peaks in the pars triangularis of the left inferior frontal gyrus and bilateral superior and middle temporal gyri. In contrast to this distribution of activation in children, prev…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s accept an offer. We present the first quantitative summary of neuroimaging studies in social decision-making with a meta-analysis of 11 fMRI studies of the UG, including data from 282 participants. <mark class="annotated-text">Effect-Size Signed Differential Mapping</mark> was used to estimate effect sizes from statistical parametric maps and reported peak information before meta-analysing them. Consistent activations were seen in the anterior insula, anterior cingulat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …onance imaging (fMRI) findings in people at familial high risk for schizophrenia compared with a control group. A voxel-wise meta-analysis with the effect-size version of Signed Differential Mapping (<mark class="annotated-text">ES-SDM</mark>) identified regional abnormalities of functional brain response. Similarly, an ES-SDM meta-analysis was conducted on VBM studies. A multi-modal imaging meta-analysis was used to highlight brain regio…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ordinate-based, quantitative meta-analysis. We compiled functional magnetic resonance imaging studies that examined neural correlates of priming tasks using perceptual, conceptual and lexical primes. <mark class="annotated-text">Effect-size signed differential mapping</mark> was used to perform a neuroimaging meta-analysis on the negative priming effect. Results from fourteen studies (245 participants; 85 foci) show concordance across studies in the right middle frontal …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …using emotional tasks), published between 2003 and 2013. These studies included 467 healthy relatives of patients with schizophrenia and 768 controls. To conduct the statistical analysis, we used the <mark class="annotated-text">effect-size signed differential mapping</mark> software, a voxel-based meta-analytic approach. In healthy relatives of patients with schizophrenia, we observed a general pattern of overactivation across the 21 fMRI studies in right-sided frontal,…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …psies Methods: A systematic review was conducted on 22 published articles before October 2020, indexed in PubMed and Web of Science. A meta-analysis with a random-effect model was performed using the <mark class="annotated-text">effect-size signed differential mapping</mark> approach. Subgroup analyses were performed in three groups: Idiopathic Generalized Epilepsy (IGE), mixed Temporal Lobe Epilepsy (TLE), and mixed Focal Epilepsy (FE) with different foci. The meta-anal…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … to the AM network have not been explored recently and have never been analyzed with consideration to the different processes of AM, them being retrieval and re-experiencing. We conducted a series of <mark class="annotated-text">effect-size signed differential mapping</mark> meta-analyses across twenty-eight studies investigating the neural correlates of trauma-related AMs in participants with PTSD as compared with controls. Studies included either trauma-related scripts…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">guidelines - moose (15 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …. Functional and structural magnetic resonance imaging studies investigating RELs and healthy controls (HCs) published by July 2017 were included in the meta-analyses. Study procedures were conducted <mark class="annotated-text">in accordance with the Meta-analysis Of Observational Studies in Epidemiology (MOOSE) guidelines.</mark> Random-effects coordinate-based meta-analyses were performed across all the studies per imaging modality using Seed-based d Mapping (SDM). For fMRI studies, meta-analyses were calculated for each tas…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …late ALE analyses (Eickhoff et al.  ). Study selection was done by three researchers (PM, SJB and HBS) and cross-checked between them. For a list of excluded studies, see Additional file  : Table S1. <mark class="annotated-text">For details of our meta-analysis MOOSE checklist inclusions, </mark>see Additional file  : Table S2. 


#### Selected studies 
  
We found 77 studies that were initially screened for inclusion in the systematic review, but 20 of these did not meet the eligibility crit…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … selection, and data extraction with a standard form were independently performed by two authors (P.L.P and Y.Z.). Any discrepancies were discussed with a third researcher for a final decision (Y.L.).<mark class="annotated-text"> The Meta-analysis Of Observational Studies in Epidemiology (MOOSE) guidelines were followed in this study . </mark>



## Data analysis 
  
### Voxel-wise meta-analysis 
  
This voxel-wise meta-analysis was carried out using the SDM software package available at  . The details of the approach have been described e…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5228032/"
                                       >PMC5228032</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n core of brain regions linked to tinnitus generation despite the heterogeneity of the patients and experimental methods. 


## Materials and Methods 
  
### Search Strategies and Study Selection 
  
<mark class="annotated-text">Our analysis was performed according to the Meta-Analysis of Observational Studies in Epidemiology (MOOSE) criteria</mark> (Stroup et al.,  ). A comprehensive literature search up to September, 2016 was conducted in PubMed, Science Direct, Web of Knowledge, and Embase using the following search terms: (1) “neuroimaging” …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5258692/"
                                       >PMC5258692</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …itatively conduct a meta-analysis using the ALE algorithm to determine the resting-state brain anomalies underlying T2DM. 


## Materials and Methods 
  
### Search Strategies and Study Selection 
  
<mark class="annotated-text">This meta-analysis was performed according to the Meta-analysis of Observational Studies in Epidemiology (MOOSE) criteria (</mark>Stroup et al.,  ). A comprehensive literature search up to May 2016 was conducted in PubMed, Web of Knowledge and Embase using the following search terms: (1) “neuroimaging” &lt;OR &gt; “fMRI,” (2) “resting…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5281680/"
                                       >PMC5281680</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …at cannabis metabolites are no longer detectable in urine. 


## Methods 
  
### Study identification 
  
A systematic search was competed on the 13/12/2017 following the Cochrane Handbook ( ) and the<mark class="annotated-text"> MOOSE ( ) guidelines,</mark> using the database PubMed. Two categories of search terms were used: 1) cannabis, marijuana, marihuana, THC, tetrahydrocannabinol and 2) imaging, fMRI, functional activation, BOLD. Following screenin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6331661/"
                                       >PMC6331661</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ions Stimulus is Visual Letters, and Subjects Handedness is Right). Further studies (11 publications) were identified through chasing citations from the selected studies (see   for flowchart diagram).<mark class="annotated-text"> The “Meta-analysis of Observational Studies in Epidemiology” (MOOSE) guidelines Stroup et al. ( ) were used for the literature search and selection of studies. </mark>All articles were identified, selected and coded by a single investigator (M.E.). The same investigator double-checked the manually extracted peak coordinates and effect size values from the selected …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6581736/"
                                       >PMC6581736</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ibute to the elucidation of central pathophysiological mechanisms involved in TN/TNP. 


## Materials and methods 
  
### Search strategy 
  
Literature was searched for until August 2018. PRISMA and <mark class="annotated-text">MOOSE</mark> guidelines were followed during the conduction of this systematic review ( ;  ). Pubmed, MEDLINE, Embase, The Cochrane Library and Google Scholar were systematically searched in order to find eligibl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6978224/"
                                       >PMC6978224</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, study evaluation, and selection were independently performed by three investigators (G.J.Y., Q.S.J., and C.P.). Any discrepancies were resolved by a fourth investigator (W.Y.) for a final decision. <mark class="annotated-text">The current study was conducted with reference to the Meta-analysis of Observational Studies in Epidemiology (MOOSE) guidelines for the meta-analyses of observational studies . </mark>


### Voxel-wise meta-analysis 
  
A meta-analysis of ALFF differences between patients and HCs was conducted for MDD and BD separately using the seed-based   d   mapping (SDM) software package (vers…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7573621/"
                                       >PMC7573621</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …reement. 


### Statistical Analysis 
  
We used an anisotropic effect-size version of the Seed-based d Mapping software package (AES-SDM) (version 5.15) to conduct the voxel-wise meta-analysis ( ), f<mark class="annotated-text">ollowing MOOSE guidelines for meta-analyses of observational studies. </mark>The AES-SDM data processing procedure is briefly summarized here ( ). AES-SDM uses an anisotropic non-normalized Gaussian kernel to recreate an effect-size map and an effect-size variance map for the …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8281314/"
                                       >PMC8281314</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - psychinfo (14 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …nd TD groups. 


## Materials and Methods 
  
### Search strategy 
  
We identified primary studies through a comprehensive literature search of the MEDLINE (using both free-text and MeSH search) and <mark class="annotated-text">PsychINFO</mark> databases using the following keywords: pediatric or child or adolescent, plus bipolar disorder or high-risk or at risk, and plus functional magnetic resonance imaging or fMRI. In addition, manual se…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217331/"
                                       >PMC4217331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …lished in a peer-reviewed English language journal. No limits were set on the ages of participants. All relevant studies published up till June 2015 were incorporated. 

The databases PubMed, EMBASE, <mark class="annotated-text">PsycInfo</mark> and Web of Science were searched, using the search terms ODD, CD, disruptive behavioural disorder, disruptive behaviour, externalising behavioural disorder, externalising behaviour, MRI, neuroimaging…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762933/"
                                       >PMC4762933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ferent study methods. 


## M 
  
### Literature search and selection 
  
Computerized literature search was conducted through online scientific databases: PubMed/Medline, EMBASE, Web of Science, and <mark class="annotated-text">PsycINFO</mark>. The literature search was performed in March 2015, with no restrictions on the date of publication. Search terms included “cogniti*,” “rehabilitation,” “remediation,” “training,” or “enhancement,” w…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …rred Reporting Items for Systematic Reviews and Meta Analyses ( ) method. 


### Information source and search 
  
We first searched peer-reviewed papers published in English through MEDLINE, PubMed, <mark class="annotated-text">PsychINFO</mark> and Cochrane Library, including all potential articles from inception to July 2014. The following search terms were used: ‘Working Memory’ and ‘healthy adolescence/adolescents/developmental trajector…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5153561/"
                                       >PMC5153561</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s frequently reported to activate upon basic taste stimulations, such as the bilateral thalamus and insula. 


## Materials and Methods 
  
### Literature search and selection criteria 
  
PubMed and <mark class="annotated-text">PsycInfo</mark> were searched (van der Laan et al.,  ; Tang, Fellows, Small, &amp; Dagher,  ; Veldhuizen et al.,  ) to identify human taste functional magnetic resonance imaging (fMRI) studies indexed until May 2016. Th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5390838/"
                                       >PMC5390838</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ic literature search. The computerised search involved using the following electronic databases: Dissertations &amp; Theses A&amp;I (ProQuest), Dissertation &amp; Theses: UK &amp; Ireland (ProQuest), Web of Science, <mark class="annotated-text">PsycINFO</mark> (EBSCOhost) and MEDLINE (OVID). The following search terms were used ‘autis*’, ‘biological motion’, ‘human motion’, ‘asd’, ‘asperger*’, ‘childhood schizophrenia’, ‘kanner*’, ‘pervasive development* d…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6921539/"
                                       >PMC6921539</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …– ), and focus our discussion on the functional neural correlates of psychopathy across tasks. 


## Methods 
  
### Study selection and coding 
  
We conducted a forward literature search in PubMed, <mark class="annotated-text">PsycINFO</mark>, and Google Scholar, and a backward literature search in the reference sections of relevant papers. The following search terms were used in the forward literature search: psychopathy, psychopathic, m…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7203015/"
                                       >PMC7203015</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … . 

### Literature search, study selection and data extraction 
  
The search for neuroimaging studies investigating GM differences in patients with AUD and healthy controls was conducted on PubMed, <mark class="annotated-text">PsycINFO</mark> and Web of Science databases (up to June 1, 2020) and by reference-tracing of the retrieved articles. Keywords were: (Alcohol Dependence OR Dependence, Alcohol OR Alcohol Addiction OR Addiction, Alco…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7933165/"
                                       >PMC7933165</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …els of WM that treat WM span as a limited resource. 



## Method 
  
### Literature Search 
  
The identification of articles relating to WM training was conducted by a series of Boolean searches of <mark class="annotated-text">PsychINFO</mark>, PubMed, and Web of Science databases last updated in January 2022. The following keywords were used: “working memory training,” “brain training,” “cognitive training,” “fMRI,” and “PET.” Furthermore…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9005969/"
                                       >PMC9005969</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …registered at The Open Science Framework:  . 

### Information sources and search strategy 
  
The formal search strategy consisted of systematically examining 3 electronic databases (PubMed, Scopus, <mark class="annotated-text">PsycINFO</mark>) through August 2022 using the MeSH search terms (fMRI OR functional magnetic resonance imaging OR neuroimaging) AND (willing to pay OR willing-to-pay OR willingness to pay OR willingness-to-pay OR W…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10332630/"
                                       >PMC10332630</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">guidelines - cochrane (14 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ods of abstinence sufficiently long such that cannabis metabolites are no longer detectable in urine. 


## Methods 
  
### Study identification 
  
A systematic search was competed on the 13/12/2017 <mark class="annotated-text">following the Cochrane Handbook ( </mark>) and the MOOSE ( ) guidelines, using the database PubMed. Two categories of search terms were used: 1) cannabis, marijuana, marihuana, THC, tetrahydrocannabinol and 2) imaging, fMRI, functional activ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6331661/"
                                       >PMC6331661</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ant research and review papers were searched for mention of additional studies. Researchers identified as leading the field were contacted to enquire whether they had carried out additional research. <mark class="annotated-text">The methodology was in line with the principles of systematic reviews as outlined by the Cochrane Handbook for Systematic Reviews of Interventions (2011).</mark> 


### Method of meta-analysis 
  
Estimates of association were meta-analysed using the software GingerALE (Eickhoff et al.  ), which is suitable for studies with comparable experimental paradigms e…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6440933/"
                                       >PMC6440933</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ta subjects into account (uncorrected p &lt;0.001, minimal Volume of 100 mm ). Results were presented on an MNI template using Mango, multi-image viewing software ( ). 


### Risk of bias assessment 
  
<mark class="annotated-text">The Cochrane Risk of Bias Assessment tool together with an assessment of the main confounders following recommendations of the Cochrane handbook for nonrandomized comparative studie</mark>s [ , ] were used to perform a risk of bias analysis for included nonrandomized comparative studies. Firstly, a manual was developed for scoring the added confounders. Secondly, the main and added con…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7857581/"
                                       >PMC7857581</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …of just using no-placebo conditions) because for some studies  only pooled estimates of the main effect of pain were available (see Supplementary Methods and Results for details). 


### Analysis 
  
<mark class="annotated-text">We applied the Cochrane risk of bias tool  to assess the risk-of-bias of included studies</mark>. (Supplementary Methods and Results and Supplementary Table  ). 

Images underwent systematic quality control, as described previously  (see Supplementary Methods and Results for details). Voxels mis…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7925520/"
                                       >PMC7925520</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e can not only elucidate the central mechanism of acupuncture but also possibly provide novel ideas for applying acupuncture to the treatment of other neurodegenerative diseases. 


## 2. Methods 
  
<mark class="annotated-text">We conducted the meta-analysis in line with the   Cochrane Handbook for Systematic Reviews of Interventions </mark> . All procedure followed the Preferred Reporting Items for Systematic Reviews and Meta-Analyses guidelines (PRISMA guidelines). The study was registered in the PROSPERO International prospective regi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … bias 
  
If more than 10 studies were included, a funnel plot would be used to evaluate the publication bias. Egger or Begg test would be conducted to analyze the potential publication bias, and the <mark class="annotated-text">results would be estimated based on the Cochrane Handbook for Systematic Reviews of Interventions. </mark>


### Ethics and dissemination 
  
No human or animal subjects or samples were/will be used. The results will be published in a peer-reviewed journal, and will be disseminated at local and internatio…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8519237/"
                                       >PMC8519237</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mary acupoints, acupuncture modality, frequency, duration, duration of treatment); (4) participants (gender, age, education, Symptom severity); (5) neuroimaging results. 


### Quality assessment 
  
<mark class="annotated-text">Quality assessment was based on the Cochrane Risk of Bias tool and was conducted independently by two researchers.</mark> All reports were assessed according to the following seven criteria: random sequence generation, allocation concealment, blinding of participants and personnel, blinding of outcome assessment, incomp…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9540390/"
                                       >PMC9540390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e reported neuroimaging abnormalities from different studies, shedding light on a neurophysiologic mechanism of this disorder. 


## Methods 
  
### Literature search and selection 
  
In this study, <mark class="annotated-text">we adopted the meta-analysis definition embraced by the Cochrane Collaboration</mark> and followed the   Preferred Reporting Items for Systematic Reviews and Meta-Analyses   (PRISMA)   Statement   guidelines. A systematic search was carried out to thoroughly include all relevant studi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9581858/"
                                       >PMC9581858</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … disagreement, a third reviewer (YZ) participated in the decision. 



### Quality assessments 
  
Two reviewers (WRR and WW) scored the completeness using a 10-point checklist (Strakowski et al.,  ),<mark class="annotated-text"> and assessed the methodological quality using the Cochrane risk of bias (ROB) tools ( ).</mark> The measurement items of ROB tools contained seven different items: random sequence generation, allocation concealment, blinding of participants and personnel, blind of outcome assessment, incomplete…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9795831/"
                                       >PMC9795831</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tudy was supervised, a “yes” was given. If an item was unable to be determined a “no” was given. Scores were compared and disagreements resolved by a third reviewer (AS). 


### 2.6. Risk of bias 
  
<mark class="annotated-text">Studies were assessed for bias independently by two reviewers (TT and RLC) using the Cochrane Risk of Bias 2 tool (Sterne et al.,  ). </mark>Included studies were evaluated as having ‘low,&#39; ‘high,&#39; or ‘unclear&#39; risk of bias using the following domains: randomization, allocation concealment, blinding of intervention instructors, blinding of…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10228832/"
                                       >PMC10228832</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - medline (13 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …nd motor dysfunction ( ,  ,  ) relative to the HR and TD groups. 


## Materials and Methods 
  
### Search strategy 
  
We identified primary studies through a comprehensive literature search of the <mark class="annotated-text">MEDLINE</mark> (using both free-text and MeSH search) and PsychINFO databases using the following keywords: pediatric or child or adolescent, plus bipolar disorder or high-risk or at risk, and plus functional magne…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217331/"
                                       >PMC4217331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ons linked to implicit memory and arousal, such as the hippocampus, amygdala, striatum and primary visual cortex. 


## Methods 
  
### Searching 
  
#### Inclusion and exclusion criteria 
  
PubMed, <mark class="annotated-text">Medline</mark>, Ovid, Sciencedirect, Web of Science and Google Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included fMRI and MRI, with subliminal…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …nvolved in cognition and working memory. 


## Methods 
  
### Data sources and inclusion criteria 
  
A systematic search strategy was performed to identify the relevant studies. We searched PubMed, <mark class="annotated-text">MEDLINE</mark>, and EMBASE from 1993 to 2014 for all relevant published observational studies and clinical trials. The following key terms were employed: “HT,” “HRT,” “HT,” “ERT,” “functional MRI or fMRI,” “cogniti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4324146/"
                                       >PMC4324146</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … studies comparing brain activity in patients with MND and in healthy controls (HCs) to identify common findings across studies. 


## Materials and Methods 
  
### Literature Search Methods 
  
Ovid <mark class="annotated-text">Medline</mark>, Pubmed, and Emabase databases were searched for studies published up to April 2015 that reported functional MRI data in patients with MND. Search terms included “motor neuron disease,” “MND,” “amyot…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4656846/"
                                       >PMC4656846</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s to explore the effectiveness of different study methods. 


## M 
  
### Literature search and selection 
  
Computerized literature search was conducted through online scientific databases: PubMed/<mark class="annotated-text">Medline</mark>, EMBASE, Web of Science, and PsycINFO. The literature search was performed in March 2015, with no restrictions on the date of publication. Search terms included “cogniti*,” “rehabilitation,” “remedia…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4804440/"
                                       >PMC4804440</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … focusing on aMCI patients could provide a reasonable means to resolving discrepancies in previously reported findings. 


## Materials and Methods 
  
A comprehensive online literature search on the <mark class="annotated-text">MEDLINE</mark>/PubMed databases was conducted, focusing on functional neuroimaging studies on MCI. Keyword searches were conducted using the following search terms: (1) ‘neuroimaging&#39; &lt;OR&gt; ‘fMRI,&#39; (2) ‘resting stat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4872413/"
                                       >PMC4872413</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ollowed the Preferred Reporting Items for Systematic Reviews and Meta Analyses ( ) method. 


### Information source and search 
  
We first searched peer-reviewed papers published in English through <mark class="annotated-text">MEDLINE</mark>, PubMed, PsychINFO and Cochrane Library, including all potential articles from inception to July 2014. The following search terms were used: ‘Working Memory’ and ‘healthy adolescence/adolescents/deve…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5153561/"
                                       >PMC5153561</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … computerised search involved using the following electronic databases: Dissertations &amp; Theses A&amp;I (ProQuest), Dissertation &amp; Theses: UK &amp; Ireland (ProQuest), Web of Science, PsycINFO (EBSCOhost) and <mark class="annotated-text">MEDLINE</mark> (OVID). The following search terms were used ‘autis*’, ‘biological motion’, ‘human motion’, ‘asd’, ‘asperger*’, ‘childhood schizophrenia’, ‘kanner*’, ‘pervasive development* disorder*’, ‘PDD-NOS’, ‘P…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6921539/"
                                       >PMC6921539</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …red reporting items for systematic review and meta-analysis (PRISMA) guidelines ( ) and registered on PROSPERO (registration No: CRD42021258119). 

### Search Strategy 
  
We searched PubMed, EMBASE, <mark class="annotated-text">MEDLINE</mark>, and Web of Science (WOS) databases for publications published before July 1, 2021. The following search terms and their derivatives were used: (“pathological Internet use” OR “problematic Internet u…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9062178/"
                                       >PMC9062178</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …uidelines and published research protocol on INPLASY (INPLASY2021120035). 

### Search Strategy 
  
We searched for studies indexed in the following online databases from inception to September 2021: <mark class="annotated-text">MEDLINE</mark>, Embase, Cochrane Library, Web of Science, China National Knowledge Infrastructure, Wanfang database, WeiPu database, and China Biology Medicine. The following terms were used for the search: (“ST 36…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9373901/"
                                       >PMC9373901</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA7 (12 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …stigate a broad range of emotions, but without the convenience of the BrainMap database. We used the BrainMap database and analysis resources to run separate meta-analyses on coordinates reported for <mark class="annotated-text">anger, anxiety, disgust, fear, happiness, humor, and sadness.</mark> Resultant ALE maps were compared to determine areas of convergence between emotions, as well as to identify affect-specific networks. Five out of the seven emotions demonstrated consistent activation…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …essing consistently engages modality-specific areas. Here, we performed an activation likelihood estimation (ALE) meta-analysis across 212 neuroimaging experiments on conceptual processing related to <mark class="annotated-text">7</mark> perceptual-motor modalities (action, sound, visual shape, motion, color, olfaction-gustation, and emotion). We found that conceptual processing consistently engages brain regions also activated durin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … activation and deactivation for four common styles of meditation (focused attention, mantra recitation, open monitoring, and compassion/loving-kindness), and suggestive differences for three others (<mark class="annotated-text">visualization, sense-withdrawal, and non-dual awareness practices</mark>). Overall, dissociable activation patterns are congruent with the psychological and behavioral aims of each practice. Some brain areas are recruited consistently across multiple techniques-including …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …gust relative to happiness. The level of attentional processing affected amygdala activity, as passive processing was associated with a higher probability of activation than active task instructions. <mark class="annotated-text">Gustatory-olfactory</mark> and visual stimulus modalities increased the probability of activation relative to internal stimuli. Aversive learning increased the probability of amygdala activation as well. There was some evidenc…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … respectively 
    
ALE results in a transdiagnostic approach across MDD and SZ 
  
 p &lt;   0.01, FDR corrected, cluster size &gt;400 mm ;   BA   = Brodmann area 
  


#### Anticipatory anhedonia 
  
For <mark class="annotated-text">anticipatory anhedonia </mark>(30 studies and 119 foci), prefrontal cortex and striatal areas showed significantly different activity (Fig.   and Table  ). Decreased likelihood of activation was observed in bilateral caudate head,…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …results in a transdiagnostic approach across MDD and SZ 
  
 p &lt;   0.01, FDR corrected, cluster size &gt;400 mm ;   BA   = Brodmann area 
  


#### Anticipatory anhedonia 
  
For anticipatory anhedonia (<mark class="annotated-text">30</mark> studies and 119 foci), prefrontal cortex and striatal areas showed significantly different activity (Fig.   and Table  ). Decreased likelihood of activation was observed in bilateral caudate head, le…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …level analyses on common executive (shared activation across tasks tapping inhibition, switching, and updating executive processes; Figure  ) and each specific putative executive process (inhibition, <mark class="annotated-text">updating</mark>, and switching) were conducted. First-level analyses describe clusters that pass the applied threshold for significant conjunctive activation across these groups of studies. These analyses were compu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5383671/"
                                       >PMC5383671</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …complete study reporting, we were unable to perform CMA between normal and low mood. Instead, we performed MAC of studies comparing painful stimulation with or without concomitant low mood condition (<mark class="annotated-text">LM</mark>  subgroup;  ). We expected to detect increase in activation intensity during the low mood condition in emotional circuits and structures contributing to central pain augmentation and chronification. …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5554296/"
                                       >PMC5554296</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …y Material for included studies and  ). Coordinates from experimental hyperalgesia in HC and CP (11 studies, 116 subjects; 3 studies, 26 subjects) and pain studies in HC involving low mood induction (<mark class="annotated-text">5</mark> studies, 114 subjects) were also extracted.   
Flowchart of fMRI papers included in the analysis. 
  Fig. 1   

The studies were divided into modality and condition-specific sub datasets ( ). Relevan…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5554296/"
                                       >PMC5554296</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mined the effects of IN-OT in clinical population. ALE analysis from FWE correction revealed that IN-OT increased neural activity in the dorsal anterior cingulate cortex (dACC) (FWE   P   &lt;     0.05; <mark class="annotated-text">14</mark> ‘OT &gt; PL’ contrasts, 114 activation coordinates;  ) and decreased the left amygdala activity (FWE   P   &lt;     0.05; 7 ‘OT &gt; PL’ contrasts, 33 activation coordinates;  ).
   
The effects of IN-OT on b…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-neurosynth decoding (12 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    de la Vega, Alejandro and Yarkoni, Tal and Wager, Tor D and Banich, Marie T
Cereb Cortex, 2018

# Title

<mark class="annotated-text">Large-scale Meta-analysis</mark> Suggests Low Regional Modularity in Lateral Frontal Cortex.

# Keywords



# Abstract
Extensive fMRI study of human lateral frontal cortex (LFC) has yet to yield a consensus mapping between discrete …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …trol, affect, and social cognition. However, there have been few large-scale efforts to comprehensively map specific psychological functions to subregions of medial frontal anatomy. Here we applied a <mark class="annotated-text">meta-analytic data-driven approach to nearly 10,000 fMRI studies to identify putatively separable regions of MFC and determine which psychological states preferentially recruit their activation. </mark>We identified regions at several spatial scales on the basis of meta-analytic coactivation, revealing three broad functional zones along a rostrocaudal axis composed of 2-4 smaller subregions each. Mu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ponent regions each exhibit distinct, but partially overlapping functional profiles. To date, there has been minimal effort to disentangle the functions of these regions. In the present study, we use <mark class="annotated-text">Neurosynth ( http://neurosynth.org ) to conduct an unbiased meta-analysis of the PMC based on fMRI coactivation and semantic information extracted from 11,406 studies.</mark> Our analyses revealed six PMC clusters with distinct functional profiles: superior and inferior dorsal PCC, anterior and posterior PrC, ventral PCC, and RSC. We discuss these findings in the context …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …during episodic encoding and retrieval, semantic retrieval, working memory, spatial navigation, simulation/scene construction, transitive inference, and social cognition tasks. The second was to use a<mark class="annotated-text"> large meta-analytic database (neurosynth) to find text terms and coactivation maps associated with the anterior and posterior hippocampal regions identified in the literature search. </mark>The third approach was to contrast the resting-state functional connectivity of the anterior and posterior hippocampal regions using a publicly available database that includes a large sample of adult…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …al posterior cingulate cortex and superior frontal gyrus (key components of the default mode network) and in the bilateral paracentral lobule (a part of the sensorimotor network). We also performed a <mark class="annotated-text">functional association analysis of the identified areas</mark>, whose dysfunction is clinically consistent with the well-known deficits affecting individuals with ASD. Importantly, we did not find relevant clusters of local hyper-connectivity, which is contrary …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …h represented plausible network constructs. These included PCNs such as “self” and “empathy” as well as BCNs such as “occipito-temporal” and “temporal-parietal”. For each term pairing, we performed a <mark class="annotated-text">reverse inference meta-analysis</mark> (FDR corrected at p &lt; 0.01) identifying fMRI spatial activation profiles stored in Neurosynth. Each pair-wise comparison between search queries   i   and   j   was conditional, ensuring that no artic…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5347156/"
                                       >PMC5347156</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e not included in standard neuroimaging paradigm ontologies such as BrainMap (Fox et al.,  ) or CogPO (Turner &amp; Laird,  ). 
  
Manual functional decoding results across meta-analytic groupings 
    

<mark class="annotated-text">#### Automated Neurosynth annotations. 
</mark>  
To complement the manual annotation analysis, we used Neurosynth’s automated annotations, which describes experiments that engage each MAG based on published neuroimaging data, allowing comparison …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6326731/"
                                       >PMC6326731</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …on its meta-analytical data corpus. Clearly, some terms in the table are brain regions (e.g., “ventromedial,” “vmpfc”), while others are cognitive processes (e.g., “terms,” “decision,” “choice”). 
  
<mark class="annotated-text">Meta-analysis results generated by   (retrieved on June 26, 2020). 
</mark>  
Not surprisingly, the term “reward” (highlighted in  ) appears in the association table. For this term of interest, the meta-analysis first returns a   z  -score of 5.39. This z-score shows whether…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7674591/"
                                       >PMC7674591</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Keywords

mentalizing
emotions
cerebellum
functional neuroimaging
review
meta-analysis


# Abstract
 
This meta-analysis explores the role of the posterior cerebellum Crus I/II in social mentalizing. <mark class="annotated-text">We identified over 200 functional magnetic resonance imaging (fMRI) studies via NeuroSynth that met our inclusion criteria and fell within bilateral Crus II areas related to ‘sequencing’ during mentalizing </mark>(coordinates ±24 −76 −40; from earlier studies) and mere social ‘mentalizing’ or self-related emotional cognition (coordinates ±26 −84 −34; from NeuroSynth), located in the cerebellar mentalizing netw…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7851889/"
                                       >PMC7851889</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d number of studies available in that category. 


### Meta-analytic decoding of intentional decision 
  
ALE activation maps indicate brain regions of consistent fMRI/PET activations between studies.<mark class="annotated-text"> We then used NeuroSynth ( ) to perform a “reverse-inference” type of meta-analysis.</mark> That is, we meta-analytically decoded which cognitive functions or processes are likely to give rise to the consistent brain activations observed in ALE activation maps. As highlighted previously, on…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8463837/"
                                       >PMC8463837</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">has NO flow chart (12 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Liebenthal, <mark class="annotated-text">Einat</mark> and Desai, Rutvik H. and Humphries, Colin and Sabri, Merav and Desai, Anjali
Front Neurosci, 2014

# Title

The functional organization of the left STS: a large scale meta-analysis of PET and fMRI st…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4160993/"
                                       >PMC4160993</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Meneguzzo, <mark class="annotated-text">Paolo</mark> and Tsakiris, Manos and Schioth, Helgi B and Stein, Dan J and Brooks, Samantha J
BMC Psychol, 2014

# Title

Subliminal versus supraliminal stimuli activate neural responses in anterior cingulate cor…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Boccia, <mark class="annotated-text">Maddalena</mark> and Piccardi, Laura and Palermo, Liana and Nori, Raffaella and Palmiero, Massimiliano
Front Psychol, 2015

# Title

Where do bright ideas occur in our brain? Meta-analytic evidence from neuroimaging …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4531218/"
                                       >PMC4531218</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Martin, <mark class="annotated-text">Anna</mark> and Schurz, Matthias and Kronbichler, Martin and Richlan, Fabio
Hum Brain Mapp, 2015

# Title

Reading in the brain of children and adults: A meta‐analysis of 40 functional magnetic resonance imaging…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4950303/"
                                       >PMC4950303</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhou, <mark class="annotated-text">Wei</mark> and Shu, Hua
Brain Behav, 2017

# Title

A meta‐analysis of functional magnetic resonance imaging studies of eye movements and visual word reading

# Keywords

functional magnetic resonance imaging
m…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5434188/"
                                       >PMC5434188</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Deng, <mark class="annotated-text">Yuqin</mark> and Wang, Xiaochun and Wang, Yan and Zhou, Chenglin
Behav Brain Funct, 2018

# Title

Neural correlates of interference resolution in the multi-source interference task: a meta-analysis of functional…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5891971/"
                                       >PMC5891971</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Wang, <mark class="annotated-text">Jue</mark> and Zhang, Jia-Rong and Zang, Yu-Feng and Wu, Tao
Gigascience, 2018

# Title

Consistent decreased activity in the putamen in Parkinson&#39;s disease: a meta-analysis and an independent validation of res…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6025187/"
                                       >PMC6025187</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Kurashige, <mark class="annotated-text">Hiroki</mark> and Kaneko, Jun and Yamashita, Yuichi and Osu, Rieko and Otaka, Yohei and Hanakawa, Takashi and Honda, Manabu and Kawabata, Hideaki
Front Hum Neurosci, 2019

# Title

Revealing Relationships Among Co…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6965330/"
                                       >PMC6965330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Cao, <mark class="annotated-text">C</mark>. Clark and Reimann, Martin
Front Psychol, 2020

# Title

Data Triangulation in Consumer Neuroscience: Integrating Functional Neuroimaging With Meta-Analyses, Psychometrics, and Behavioral Data

# Key…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7674591/"
                                       >PMC7674591</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Si, <mark class="annotated-text">Ruoguang</mark> and Rowe, James B and Zhang, Jiaxiang
Neuroimage, 2021

# Title

Functional localization and categorization of intentional decisions in humans: A meta-analysis of brain imaging studies

# Keywords

I…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8463837/"
                                       >PMC8463837</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - protocol (11 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …nfrastructure (CNKI), WanFang, and SinoMed databases until June 15, 2019 and updated on March 20, 2020. This protocol will follow the Preferred Reporting Items for Systematic review and Meta-Analysis <mark class="annotated-text">Protocols</mark> (PRISMA-P). The Seed-based d Mapping with Permutation of Subject Images (SDM-PSI) software will be used for this voxel-wise meta-analysis. This meta-analysis will identify the most consistent ReHo al…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … and Outhred, Tim and Westlye, Lars T. and Malhi, Gin S. and Andreassen, Ole A.
Syst Rev, 2016

# Title

The impact of oxytocin administration on brain activity: a systematic review and meta-analysis <mark class="annotated-text">protocol</mark>

# Keywords

Oxytocin
Brain imaging
Systematic review
Meta-analysis
Protocol


# Abstract
 
## Background 
  
Converging evidence demonstrates the important role of the neuropeptide hormone oxytocin …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5129649/"
                                       >PMC5129649</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Hu, Yiru and Fu, Yu and Cao, Liping and Zhang, Bin
BMJ Open, 2020

# Title

Functional MRI in the effect of transcranial magnetic stimulation therapy for patients with schizophrenia: a meta-analysis <mark class="annotated-text">protocol</mark>

# Keywords

neuroradiology
schizophrenia &amp; psychotic disorders
magnetic resonance imaging


# Abstract
 
## Introduction 
  
Schizophrenia is a psychiatric illness associated with brain function alt…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7713205/"
                                       >PMC7713205</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Horácio
Trends Psychiatry Psychother, 2021

# Title

Attention-deficit/hyperactivity disorder and brain metabolites from proton magnetic resonance spectroscopy: a systematic review and meta-analysis <mark class="annotated-text">protocol</mark>

# Keywords

MRS
spectroscopy
ADHD
meta-analysis
protocol


# Abstract
 
Despite major advances in the study of the brain, investigations on neurochemistry in vivo still lack the solid ground of more…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7932040/"
                                       >PMC7932040</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g
Medicine (Baltimore), 2021

# Title

Study on acupuncture improving insomnia comorbid with depression and anxiety based on rs-fMRI

# Keywords

acupuncture
anxiety
depression
insomnia
meta-analysis
<mark class="annotated-text">protocol</mark>
rs-fMRI
systematic review


# Abstract
 
## Background: 
  
Long term insomnia and low sleep quality often lead to depression, anxiety and other negative emotions, and often interact with each other.…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8136997/"
                                       >PMC8136997</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Ubalde, Leonard and Liang, Jing-Nong
Brain Sci, 2021

# Title

Neurophysiological Assessments of Brain and Spinal Cord Associated with Lower Limb Functions in Children with Cerebral Palsy: A <mark class="annotated-text">Protocol</mark> for Systematic Review and Meta-Analysis

# Keywords

cerebral palsy
walking
neuroplasticity
neurophysiology
systematic review


# Abstract
 
Background: Task-dependent neurophysiological adaptations …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8153104/"
                                       >PMC8153104</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, Haizhu and Cao, Jiazhen and Wang, Guan and Liu, Yanze and Wang, Hongfeng
BMJ Open, 2021

# Title

Study on acupuncture in the treatment of painful diabetic peripheral neuropathy based on rs-fMRI: a <mark class="annotated-text">protocol</mark> for systematic review and meta-analysis

# Keywords

complementary medicine
diabetic neuropathy
magnetic resonance imaging
diabetes &amp; endocrinology
neurology


# Abstract
 
## Introduction 
  
Studie…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8388266/"
                                       >PMC8388266</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Lyu, Diyang and Li, Taoran and Lyu, Xuanxin
BMJ Open, 2021

# Title

Resting-state functional reorganisation in Alzheimer’s disease and amnestic mild cognitive impairment: <mark class="annotated-text">protocol</mark> for a systematic review and meta-analysis

# Keywords

NEUROLOGY
Dementia
Diagnostic radiology
neurology
dementia
diagnostic radiology


# Abstract
 
## Introduction 
  
The incidence of Alzheimer’s …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8513263/"
                                       >PMC8513263</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Sun, <mark class="annotated-text">Yi</mark>-ming and Peng, Yu-xuan and Wen, Quan and Dai, Yu and Liu, Xin-ru and Yang, Xue-ping and Ye, Qing
Medicine (Baltimore), 2021

# Title

Resting-state fMRI in temporal lobe epilepsy patients with cognit…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8519237/"
                                       >PMC8519237</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d Li, Danyang and Me, Yutong and Fan, Hongyu and Wu, Hao and Zhang, Gaofeng
BMJ Open, 2021

# Title

Effect of repetitive transcranial magnetic stimulation on patients with severe depression: a study <mark class="annotated-text">protocol</mark> for systematic review and meta-analysis of randomised clinical trials

# Keywords

radiotherapy
depression &amp; mood disorders
radiology &amp; imaging
complementary medicine


# Abstract
 
## Introduction 
…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8671925/"
                                       >PMC8671925</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - scopus (11 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ed of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, ScienceDirect, Google Scholar, Web of Knowledge, and <mark class="annotated-text">Scopus</mark> electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphenidate and stimulant. Citations within papers …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …S 
  
### Literature selection 
  
We obtained articles including four kinds of substances that are regularly abused namely cocaine, cannabis, alcohol, and nicotine (cigarettes or tobacco). Utilizing <mark class="annotated-text">Scopus</mark>, PubMed, and Web of Science, peer‐reviewed studies published between January 1, 2000 and November 1, 2019 were collected using the following search terms; “Alcohol” or “Cocaine” or “Cannabis” or “Nic…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7555084/"
                                       >PMC7555084</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ure search following PRISMA ( ) guidelines was conducted to identify whole-brain task-based activation studies of substance use vulnerability (records from January 1st, 1990–November 1st, 2018) using <mark class="annotated-text">Scopus</mark> and PubMed databases. Literature searches used substance use vulnerability search stems (‘substance use risk’, ‘alcoholism risk’, ‘substance use initiation’, ‘prospective prediction of substance use’…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7992390/"
                                       >PMC7992390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mples, and diversity of analytical methods. This meta-analysis investigated resting-state activity differences in BD and MDD depression using activation likelihood estimation. PubMed, Web of Science, <mark class="annotated-text">Scopus</mark> and Google Scholar databases were searched for whole-brain rs-fMRI studies which compared MDD and BD currently depressed patients between Jan 2000 and August 2020. Ten studies were included, represen…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8379217/"
                                       >PMC8379217</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tematic Reviews and Meta-Analyses) guidelines. Systematic and comprehensive searches of VBM and fMRI studies of CD from Jan 1, 2010, to Dec 31, 2021 was performed using the PubMed, Web of Science and <mark class="annotated-text">Scopus</mark> database, combined with the following keywords: (“cocaine” or “cocaine related disorders” or “cocaine addiction” or “CD”) and (“voxel-based morphometry” or “VBM” or “gray matter” or “functional magne…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9263080/"
                                       >PMC9263080</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …  -analyses, and second, to extend previous findings by separately assessing different subprocesses of inhibitory control. 


## Method 
  
We systematically searched Web of Knowledge, ScienceDirect, <mark class="annotated-text">Scopus</mark>, PubMed and the functional BrainMap database for fMRI articles that compared activation during performance of inhibitory control tasks in patients with OCD and healthy control (HC) subjects. Thirty-f…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9723317/"
                                       >PMC9723317</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …he computer-based literature search to retrieve all the published articles in English regarding the above-described topics. We conducted our search in the three principal databases: PubMed (MEDLINE), <mark class="annotated-text">Scopus</mark> and Web of Science. 

Importantly, we identify fMRI studies on the basis of the following inclusion criteria: (1) whole brain fMRI studies; (2) Studies in which participants have been involved in a c…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9832372/"
                                       >PMC9832372</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …st and access the review protocol via  ). All authors first decided on the keywords and electronic databases to search, followed by the first title/abstract/keyword search of the electronic databases <mark class="annotated-text">Scopus</mark>, Embase, ScienceDirect and PubMed conducted on April 2022 using the keywords (“mindful*” OR “mind–body” OR “yoga” OR “tai chi” OR “qigong”) AND (“magnetic resonance imaging” OR “functional magnetic r…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10326064/"
                                       >PMC10326064</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … was preregistered at The Open Science Framework:  . 

### Information sources and search strategy 
  
The formal search strategy consisted of systematically examining 3 electronic databases (PubMed, <mark class="annotated-text">Scopus</mark>, PsycINFO) through August 2022 using the MeSH search terms (fMRI OR functional magnetic resonance imaging OR neuroimaging) AND (willing to pay OR willing-to-pay OR willingness to pay OR willingness-t…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10332630/"
                                       >PMC10332630</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s 
  
### Study selection 
  
#### Data sources 
  
Two independent investigators performed a bibliographic search using the following databases: PubMed, Web of Science, PsycInfo, Google Scholar, and <mark class="annotated-text">Scopus</mark>. Some examples of the Boolean algorithm with the keywords used are presented in the Appendix A. The search included all the studies published until 28 February 2021. We conducted this meta-analysis a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392089/"
                                       >PMC10392089</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - google scholar (9 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ehensive literature search was conducted of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, ScienceDirect, <mark class="annotated-text">Google</mark> Scholar, Web of Knowledge, and Scopus electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphenidate a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s the hippocampus, amygdala, striatum and primary visual cortex. 


## Methods 
  
### Searching 
  
#### Inclusion and exclusion criteria 
  
PubMed, Medline, Ovid, Sciencedirect, Web of Science and <mark class="annotated-text">Google</mark> Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included fMRI and MRI, with subliminal and supraliminal stimulation as our search crit…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …udies to use in the meta-analysis. Any disagreement was resolved through a group discussion. 


### Searching strategies 
  
Literature searches were performed in related databases, including PubMed, <mark class="annotated-text">Google</mark> scholar, and CNKI, before October 2016. The following search terms were combined and used: “schizophrenia/schizophrenic/SZ/SCZ”, “functional MRI/fMRI”, “regional homogeneity/ReHo/localized connectivi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5317331/"
                                       >PMC5317331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …IT interference processing within the dACC and in the CFP network. 


## Methods 
  
### Data sources and study selection 
  
We conducted a systematic search of PubMed ( ), Web of Knowledge ( ), and <mark class="annotated-text">Google</mark> Scholar ( ) for MSIT-related fMRI studies from 2003 to July 2017. The search term combinations used were: “multi-source interference task” and “functional magnetic resonance imaging”. A total of 603 …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5891971/"
                                       >PMC5891971</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … our discussion on the functional neural correlates of psychopathy across tasks. 


## Methods 
  
### Study selection and coding 
  
We conducted a forward literature search in PubMed, PsycINFO, and <mark class="annotated-text">Google Scholar</mark>, and a backward literature search in the reference sections of relevant papers. The following search terms were used in the forward literature search: psychopathy, psychopathic, magnetic resonance im…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7203015/"
                                       >PMC7203015</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …diversity of analytical methods. This meta-analysis investigated resting-state activity differences in BD and MDD depression using activation likelihood estimation. PubMed, Web of Science, Scopus and <mark class="annotated-text">Google Scholar</mark> databases were searched for whole-brain rs-fMRI studies which compared MDD and BD currently depressed patients between Jan 2000 and August 2020. Ten studies were included, representing 234 BD and 296…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8379217/"
                                       >PMC8379217</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Reviews and Meta-Analyses (PRISMA) framework (Moher et al.,  ). A PRISMA flow diagram for the literature search is documented in  . The search criteria for each database are reported in  . PubMed and <mark class="annotated-text">Google Scholar </mark>were periodically searched between August 2015 and December 2020 to locate peer-reviewed articles published prior to December 2020 that used fMRI or PET to measure brain activations to speech and lang…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8572938/"
                                       >PMC8572938</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …hrenia. 


## Methods 
  
### Study selection 
  
#### Data sources 
  
Two independent investigators performed a bibliographic search using the following databases: PubMed, Web of Science, PsycInfo, <mark class="annotated-text">Google</mark> Scholar, and Scopus. Some examples of the Boolean algorithm with the keywords used are presented in the Appendix A. The search included all the studies published until 28 February 2021. We conducted …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392089/"
                                       >PMC10392089</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …acceptance-based strategies may involve subcortical limbic structures (Messina et al.,  ). 


## Methods 
  
### Study selection 
  
The authors conducted a systematic online search on PubMed ( ) and <mark class="annotated-text">Google scholar</mark> ( ) up until August 2022 to select the studies. The search used the keywords such as “emotion regulation,” “emotion regulation strategies” AND “reappraisal,” “acceptance” and/or “mindfulness” AND “fM…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10403290/"
                                       >PMC10403290</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - chinese national knowledge infrastructure (9 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ion 
  
A comprehensive literature search was conducted of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, <mark class="annotated-text">ScienceDirect</mark>, Google Scholar, Web of Knowledge, and Scopus electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …meta-analysis. Any disagreement was resolved through a group discussion. 


### Searching strategies 
  
Literature searches were performed in related databases, including PubMed, Google scholar, and <mark class="annotated-text">CNKI</mark>, before October 2016. The following search terms were combined and used: “schizophrenia/schizophrenic/SZ/SCZ”, “functional MRI/fMRI”, “regional homogeneity/ReHo/localized connectivity/coherence/conco…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5317331/"
                                       >PMC5317331</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …uroprotective effect of acupuncture in stroke patients were included in the present study. The PubMed, EMBASE, and Cochrane Library databases, Web of Science, China National Knowledge Infrastructure (<mark class="annotated-text">CNKI</mark>), Chongqing VIP (VIP), and the Wanfang Database (WF) were searched from inception until May 2020 by two independent researchers. The following English search terms were used: (stroke OR Poststroke OR…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Y (INPLASY2021120035). 

### Search Strategy 
  
We searched for studies indexed in the following online databases from inception to September 2021: MEDLINE, Embase, Cochrane Library, Web of Science, <mark class="annotated-text">China</mark> National Knowledge Infrastructure, Wanfang database, WeiPu database, and China Biology Medicine. The following terms were used for the search: (“ST 36” or “ST36” or “  zusanli  ”) and (“fMRI” or “fun…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9373901/"
                                       >PMC9373901</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ctivity OR functional connection OR regional homogeneity OR BOLD(in title or abstract) 
  
①AND②AND(③OR④OR⑤) 
  

Three English databases (PubMed, Web of Science, EmBase) and three Chinese databases (<mark class="annotated-text">China National Knowledge Infrastructure</mark>, Wanfang and China Biology Medicine disc) were queried. Inclusion criteria for eligible literature are as follows: (1) original clinical studies on human; (2) participants included patients diagnosed…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9581858/"
                                       >PMC9581858</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …performed a comprehensive search in the following databases from their inception to August 18, 2022: PubMed, EMBASE, Web of Science, the Cochrane Library, the China National Knowledge Infrastructure (<mark class="annotated-text">CNKI</mark>), the China Science and Technology Journal Database (VIP), Wanfang Database, and the China Biology Medicine (CBM). Both Medical Subject Headings (MeSH) and free-text words related to acupuncture, mig…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9911686/"
                                       >PMC9911686</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …
### Selection procedure 
  
#### Search strategies 
  
Studies of acupuncture on some acupoints were searched from PubMed, Web of Science, Wanfang, and the Chinese National Knowledge Infrastructure (<mark class="annotated-text">CNKI</mark>) from the inception of the databases up to August 2021 to identify relevant studies. The following search terms were used: (“acupuncture” or “acupuncture therapy” or “electroacupuncture” or “EA”) and…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10287969/"
                                       >PMC10287969</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … published between the establishment of the following publication databases until December 2022: Web of Science, PubMed, ScienceDirect, Embase, Wan Fang (WF), China National Knowledge Infrastructure (<mark class="annotated-text">CNKI</mark>), and Chinese Scientific Journal Database (VIP). The following search terms were used under the “subject words plus free words” retrieval strategy: (“Acupuncture” OR “Needle” OR “Acupoint”) AND (“fMR…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392941/"
                                       >PMC10392941</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … contradictory findings in the literature and enhance the understanding of LDH-related pain. 


## Materials and methods 
  
PubMed, Web of Science, Embase, Chinese National Knowledge Infrastructure (<mark class="annotated-text">CNKI</mark>), SinoMed, and Wanfang databases were searched for literature that studies the changes of brain basal activity in patients with LDH using regional homogeneity (ReHo) and amplitude of low-frequency fl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10876805/"
                                       >PMC10876805</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - sciencedirect (9 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ion 
  
A comprehensive literature search was conducted of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, <mark class="annotated-text">ScienceDirect</mark>, Google Scholar, Web of Knowledge, and Scopus electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mplicit memory and arousal, such as the hippocampus, amygdala, striatum and primary visual cortex. 


## Methods 
  
### Searching 
  
#### Inclusion and exclusion criteria 
  
PubMed, Medline, Ovid, <mark class="annotated-text">Sciencedirect</mark>, Web of Science and Google Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included fMRI and MRI, with subliminal and supraliminal sti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …and systematic manner. This process underlies 4 phases: identification, screening, eligibility and inclusion ( ). Publications were searched on three databases, notably on MEDLINE, via PubMed ( ), on <mark class="annotated-text">Science Direct</mark> (Elsevier,  ), and Web of Science ( ), using the search string “(face OR facial) AND (trustworthiness OR trustworthy OR untrustworthy OR trustee) AND fMRI” (use of filter “article” and “short communi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5127572/"
                                       >PMC5127572</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Methods 
  
### Literature search and study selection 
  
Studies examining IN-OT effects on the human brain published before March 2017, were selected through a standard search in PubMed, Embase and <mark class="annotated-text">ScienceDirect</mark>, with keywords [‘oxytocin’] AND [‘fMRI’ OR ‘magnetic resonance imaging’]. Additional studies were collected by reviewing the reference lists of relevant papers in the first step and the reference lis…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ices for   meta  -analyses, and second, to extend previous findings by separately assessing different subprocesses of inhibitory control. 


## Method 
  
We systematically searched Web of Knowledge, <mark class="annotated-text">ScienceDirect</mark>, Scopus, PubMed and the functional BrainMap database for fMRI articles that compared activation during performance of inhibitory control tasks in patients with OCD and healthy control (HC) subjects. …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9723317/"
                                       >PMC9723317</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … 
A comprehensive literature search of fMRI and VBM studies of ADHD from January 2010 to November 2021 was conducted primarily using PubMed, as well as additional searches in the Web of Knowledge and <mark class="annotated-text">Science</mark> Direct databases, with a combination of the following keywords: “voxel-based morphometry” or “VBM” or “morphometry” or “gray matter” or “functional magnetic resonance imaging” or “fMRI” and “ADHD” or…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9853532/"
                                       >PMC9853532</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tegy 
  
The articles included in the meta‐analyses were retrieved using a systematic search strategy. We searched for articles published up until May 2022 without any starting date in the PubMed and <mark class="annotated-text">ScienceDirect</mark> databases. We used the following terms for the reality‐monitoring meta‐analysis: (“source‐monitoring” OR “reality‐monitoring” OR “self‐related”) AND (“fMRI” OR “functional magnetic resonance imaging”…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10318245/"
                                       >PMC10318245</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e review protocol via  ). All authors first decided on the keywords and electronic databases to search, followed by the first title/abstract/keyword search of the electronic databases Scopus, Embase, <mark class="annotated-text">ScienceDirect</mark> and PubMed conducted on April 2022 using the keywords (“mindful*” OR “mind–body” OR “yoga” OR “tai chi” OR “qigong”) AND (“magnetic resonance imaging” OR “functional magnetic resonance imaging” OR “M…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10326064/"
                                       >PMC10326064</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …search 
  
We performed a methodical and comprehensive search of the literature published between the establishment of the following publication databases until December 2022: Web of Science, PubMed, <mark class="annotated-text">ScienceDirect</mark>, Embase, Wan Fang (WF), China National Knowledge Infrastructure (CNKI), and Chinese Scientific Journal Database (VIP). The following search terms were used under the “subject words plus free words” r…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392941/"
                                       >PMC10392941</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-neurosynth encoding (8 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ere, we used a large-scale, unbiased, and data-driven approach combining functional MRI meta-analysis and resting-state functional connectivity (rsFC) methods to test the nature of this heterogeneity.<mark class="annotated-text"> The automated toolset Neurosynth was used to conduct meta-analyses </mark>in order to (a) identify heterogeneous areas in the retrosplenial region (RS region) associated with one or more cognitive domains, and (b) contrast the activation profiles related to these domains. T…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …g tactile versus visual stimuli identified additional regions involved in sensory specific aversive anticipation across these sensory modalities. Results from complementary multi-study voxel-wise and <mark class="annotated-text">NeuroSynth</mark> analyses generally provide converging evidence for a core circuit involved in aversive anticipation. The multi-study voxel-wise analyses also implicate a more widespread preparatory response across s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …two commonly employed tasks of episodic retrieval and mentalizing. In a subset of participants, relationships among task-evoked regions were examined at rest, in the absence of an overt task. Finally,<mark class="annotated-text"> large-scale fMRI meta-analyses were conducted to identify brain regions</mark> that most strongly predicted the presence of episodic retrieval and mentalizing, and these results were compared to meta-analyses of autobiographical tasks. Across studies, laboratory-based episodic …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ysis and confirmatory data from an independent study of simple appraisal of social vs. non-social images. Results of 1,000 published fMRI studies containing the keyword of “social” were subject to an <mark class="annotated-text">automated meta-analysis ( )</mark>. To confirm that significant brain regions in the meta-analysis were driven by a social effect, these brain regions were used as regions of interest (ROIs) to extract and compare BOLD fMRI signals of…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5933734/"
                                       >PMC5933734</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …-attentional network and the MCS map, while UWS patients, being unresponsive to external stimuli, by definition, should not activate this network. To explicitly test this assumption, we extracted the <mark class="annotated-text">dorsal-attentional uniformity map from the neurosynth toolbox ( ) by searching the term “dorsal-attentional”.</mark> The UWS and MCS ALE maps were binarised into VOIs using the software MRIcron [ ]. We then applied a standard intersection analysis to identify the regions of anatomical overlap between each category …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6517954/"
                                       >PMC6517954</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …at are used as general words in neuroscience literature, such as ‘focus’ and ‘strength.’ Thus, we selected the 121 cognitive terms shown in   as the targets to be considered in this study. 

Then, we <mark class="annotated-text">reconstructed the binary activation map</mark> on the 2-mm-resolution MNI 152 brain for each article registered in Neurosynth data by the following steps. First, we transformed the coordinates reported in the Talairach brain into the MNI brain us…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6965330/"
                                       >PMC6965330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e using finite impulse response models (time window from 1 to 12 s). Regions of interest (ROIs) located in the SM cortex were defined as the overlap between anatomical and a priori functional masks . <mark class="annotated-text">Functional masks were obtained using the Neurosynth platform for an automatic meta-analysis ( ). We used a uniformity test with a default false discovery rate (FDR) corrected p &lt; 0.01 threshold for the “motor” term (2565 studies). </mark>To obtain anatomical masks, we used voxels with the maximum probability for “precentral gyrus” and “precentral gyrus” labels according to the probabilistic Harvard–Oxford atlas . ROI analysis was perf…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9203582/"
                                       >PMC9203582</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, executive functioning (EF), and visuospatial abilities (VS) across ~1.5–2 years of follow-up, which matches follow-up periods of several recent phase 2b&amp;3 clinical trials (e.g., EMERGE/ENGAGE) [ ]. <mark class="annotated-text">To assess the association between tau-PET and cognitive-domain-specific decline, we obtained meta-analytical maps of task-fMRI studies from Neurosynth [ ,  ] to determine brain regions that are consistently associated with MEM/LAN/EF/VS across ~1900 task-fMRI studies. </mark>We then mapped patient-specific tau-PET to cognitive-domain-specific brain activation maps and tested whether determining baseline tau-PET in regions involved in a given cognitive domain improves the …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9639286/"
                                       >PMC9639286</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-brainmap decoding (8 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …istinct aspects of emotion processing, we applied an emergent meta-analytic clustering approach to the extensive body of affective neuroimaging results archived in the BrainMap database. Specifically,<mark class="annotated-text"> we performed hierarchical clustering on the modeled activation maps from 1,747 experiments in the affective processing domain, resulting in five meta-analytic groupings of experiments demonstrating whole-brain recruitment. </mark>Behavioral inference analyses conducted for each of these groupings suggested dissociable networks supporting: (1) visual perception within primary and associative visual cortices, (2) auditory percep…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e fMRI datasets and the functional roles of other DICCCOLs are unknown yet. This work aims to take the advantage of existing literature fMRI studies (1110 publications) reported and aggregated in the <mark class="annotated-text">BrainMap</mark> database to examine the possible functional roles of 358 DICCCOLs via meta-analysis. Our experimental results demonstrate that a majority of 358 DICCCOLs can be functionally annotated by the BrainMap…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …mation meta-analysis of 24 task-based fMRI studies in adults with ADHD. Each ADHD-related dysfunctional region resulting from the activation likelihood estimation meta-analysis was then analyzed using<mark class="annotated-text"> functional decoding based on ~7500 fMRI experiments in the BrainMap database.</mark> This approach allows mapping brain regions to functions not necessarily tested in individual studies, thus suggesting possible novel functions for those regions. Additionally, ADHD-related dysfunctio…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …est sample. Materials and Methods Model fit testing was conducted with structural equation modeling, which is based on the computation of semipartial correlations. Model verification was performed in <mark class="annotated-text">coordinate-based data of healthy control participants from the BrainMap</mark> database ( 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …) analyses using two independent healthy subject data sets, we found that the regions showing convergent aberrations in PD formed an interconnected network mainly with the default mode network (DMN). <mark class="annotated-text">Behavioral characterization of these regions using the BrainMap database </mark>suggested associated dysfunction of perception and executive processes. Taken together, our findings highlight the role of parietal cortex in the pathophysiology of PD. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es, there were no differences in gray matter density between FRs and healthy controls. Furthermore, multi-modal meta-analysis obtained no differences between FRs and healthy controls. By utilizing the<mark class="annotated-text"> BrainMap database, we showed that the brain region which showed functional alterations in FRs </mark>(i) overlapped only slightly with the brain regions that were affected in the meta-analysis of schizophrenia patients and (ii) correlated positively with the brain regions that exhibited increased act…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …nt analysis approach tested for convergence by experiments (random effects) rather than foci (fixed effects) ( ); for further details and a summary of the ALE method please refer to ( ,  ,  ). 


### <mark class="annotated-text">Functional decoding using the BrainMap</mark> database 
  
To assess the functional roles of the abnormal brain regions in OSA, behavioral decoding using the BrainMap database was consequently performed. More specifically, we tested which types …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5103027/"
                                       >PMC5103027</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s plugin tool is implemented in Mango software (version 4.1;  ). This plugin tool enables the analysis of behaviors and cognitive functions regarding the set ROI. This tool was developed based on the <mark class="annotated-text">BrainMap</mark> database. Foci corresponding with five behavioral domains (“Action”, “Cognition”, “Emotion”, “Interoception”, and “Perception”) are organized in the BrainMap database. Moreover, these behavioral doma…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9207674/"
                                       >PMC9207674</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">ask about this one (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Peiffer</mark>, Ann M. and Maldjian, Joseph A. and Laurienti, Paul J.
Int J Biomed Imaging, 2007

# Title

Resurrecting Brinley Plots for a Novel Use: Meta-Analyses of Functional Brain Imaging Data in Older Adults
…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">I don&#39;t get this study</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2233772/"
                                       >PMC2233772</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …in each cluster. Clusters were further considered if they contained a number of coordinates greater than the median of the distribution for each analysis and, in any event, with no &lt;3 coordinates. 


<mark class="annotated-text">### Activation likelihood analyses 
</mark>  
To assess to what extent the functional segregations identified by the HC analyses could be replicated on a much larger dataset of studies on action, we interrogated the BrainMap.org database to ge…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">did they do mcam? how many ma&#39;s did they do? 3?</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5434171/"
                                       >PMC5434171</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Burles</mark>, Ford and Umiltá, Alberto and McFarlane, Liam H. and Potocki, Kendra and Iaria, Giuseppe
Front Hum Neurosci, 2018

# Title

Ventral—Dorsal Functional Contribution of the Posterior Cingulate Cortex in…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">did they do macm?</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5951926/"
                                       >PMC5951926</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ons of different stimuli were interpreted to provide insight into how information processing is functionally segregated across cooperating neural systems during naturalistic tasks. 



## RESULTS 
  
<mark class="annotated-text">The literature search yielded a combined set of 110 studies that reported coordinates of brain activation from naturalistic fMRI tasks among healthy adults ( ; PubMed IDs available in Supporting Information Table S1, Bottenhorn, Flannery, Boeving, Riedel, Eickhoff, Sutherland, &amp; Laird,  ). The final dataset included activation foci from 376 experimental contrasts (  N   = 1,817 subjects) derived from tasks using a variety of stimulus types and sensory modalities. </mark>Across our corpus of naturalistic fMRI experiments, approximately 55% assessed a single stimulus modality, including 40% visual stimuli, 13% auditory, and 1% tactile. 

Conversely, 45% of experiments …
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">They clustered maps into 6 groups then performed 6 meta-analyses, but I can&#39;t find the number of studies in each analysis.</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6326731/"
                                       >PMC6326731</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Jauniaux</mark>, Josiane and Khatibi, Ali and Rainville, Pierre and Jackson, Philip L
Soc Cogn Affect Neurosci, 2019

# Title

A meta-analysis of neuroimaging studies on pain empathy: investigating the role of visua…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">how to code individual analyses</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Sinha</mark>, Preeti and Joshi, Himanshu and Ithal, Dhruva
Front Hum Neurosci, 2020

# Title

Resting State Functional Connectivity of Brain With Electroconvulsive Therapy in Depression: Meta-Analysis to Understa…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">seems like they resorted to desperate measures to find more experiments to include.</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7859100/"
                                       >PMC7859100</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Zunhammer</mark>, Matthias and Spisák, Tamás and Wager, Tor D. and Bingel, Ulrike and nan, nan
Nat Commun, 2021

# Title

Meta-analysis of neural systems underlying placebo analgesia from individual participant fMRI …
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">is this a meta-analysis? they analyzed participant-level maps</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7925520/"
                                       >PMC7925520</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA8 (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ss. The level of attentional processing affected amygdala activity, as passive processing was associated with a higher probability of activation than active task instructions. Gustatory-olfactory and <mark class="annotated-text">visual</mark> stimulus modalities increased the probability of activation relative to internal stimuli. Aversive learning increased the probability of amygdala activation as well. There was some evidence of hemisp…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …hippocampus, ACC, mPFC and MFG (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm ). Increased likelihood of activation was observed in the left IFG and MFG. 


#### Emotional processing 
  
For the <mark class="annotated-text">emotional experience task</mark> (31 studies and 163 foci), decreased likelihood of activation was observed in a number of brain areas from the cortical-subcortical network (Fig.   and Table  ), including right GPe, right putamen, r…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …MFG (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm ). Increased likelihood of activation was observed in the left IFG and MFG. 


#### Emotional processing 
  
For the emotional experience task (<mark class="annotated-text">31</mark> studies and 163 foci), decreased likelihood of activation was observed in a number of brain areas from the cortical-subcortical network (Fig.   and Table  ), including right GPe, right putamen, right…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … on common executive (shared activation across tasks tapping inhibition, switching, and updating executive processes; Figure  ) and each specific putative executive process (inhibition, updating, and <mark class="annotated-text">switching</mark>) were conducted. First-level analyses describe clusters that pass the applied threshold for significant conjunctive activation across these groups of studies. These analyses were computed for both th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5383671/"
                                       >PMC5383671</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tion coordinates;  ).
   
The effects of IN-OT on brain activity in healthy volunteers and patients (threshold: FWE   P   &lt;     0.05, 1000 permutations,   k   &gt; 15 mm ) 
    


### Comparison between <mark class="annotated-text">patients and healthy volunteers </mark>
  
Given that the majority of IN-OT fMRI studies examined neural substrates mediating OT effects in healthy population, a key issue for OT clinical translation was to reveal the common and differenti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …the pain visual cue factor 
  
Higher ALE values or   Z   scores are associated with greater probability of activation across experiments. 
  

### Self/other cognitive perspective taking 
  
For the <mark class="annotated-text">SEO</mark> condition, the single ALE map showed consistent activation in the left IFG, IPL, ACC, aMCC, AI, PreCG, MFG and claustrum, and right IPL and MOG (  and   for peak coordinates and ALE values). Several …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Gao, <mark class="annotated-text">Xinyu</mark> and Zhang, Mengzhe and Yang, Zhengui and Wen, Mengmeng and Huang, Huiyu and Zheng, Ruiping and Wang, Weijian and Wei, Yarui and Cheng, Jingliang and Han, Shaoqiang and Zhang, Yong
Front Psychiatry, 2…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8281314/"
                                       >PMC8281314</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …iform gyrus, and left middle temporal gyrus (Table  ). 


### Group differences for angry facial expressions 
  
The whole-brain meta-analysis of responses to angry facial expressions images included <mark class="annotated-text">five</mark> contrasts, one selected from each included study. No results survived FWER-correction. Uncorrected group differences in activation were observed in a cluster spanning left supplementary motor area an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10063659/"
                                       >PMC10063659</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">IMBA (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Luijten, Maartje and Schellekens, Arnt F and Kühn, Simone and Machielse, Marise W J and Sescousse, Guillaume
JAMA Psychiatry, 2017

# Title

Disruption of Reward Processing in Addiction : An <mark class="annotated-text">Image-Based Meta-analysis </mark>of Functional Magnetic Resonance Imaging Studies.

# Keywords



# Abstract
Disrupted reward processing, mainly driven by striatal dysfunction, is a key characteristic of addictive behaviors. However,…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …Michael C and Laird, Angela R
Brain Topogr, 2021

# Title

What Executive Function Network is that? An Image-Based Meta-Analysis of Network Labels.

# Keywords

Brain networks
Executive function
FMRI
<mark class="annotated-text">Image-based meta-analysis
</mark>Network labels

# Abstract
The current state of label conventions used to describe brain networks related to executive functions is highly inconsistent, leading to confusion among researchers regardin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ing body of evidence suggests that empathy for pain is underpinned by neural structures that are also involved in the direct experience of pain. In order to assess the consistency of this finding, an <mark class="annotated-text">image-based meta-analysis</mark> of nine independent functional magnetic resonance imaging (fMRI) investigations and a coordinate-based meta-analysis of 32 studies that had investigated empathy for pain using fMRI were conducted. Th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … unclear. Here, we systematically reviewed functional magnetic resonance studies that used emotion processing task paradigms in FEP patients, and in people at clinical high-risk for psychosis (CHRp). <mark class="annotated-text">Image-based meta-analyses</mark> with Seed-based d Mapping on available studies (n = 6) were also performed. Compared to controls, FEP patients showed decreased neural responses to emotion, particularly in the amygdala and anterior …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …, the aim here was to perform a meta-analysis of the existing literature using unthresholded statistical maps from previous studies. A voxelwise seed-based d mapping meta-analysis was performed using <mark class="annotated-text">t-maps from studies </mark>comparing patients with OCD and healthy control subjects (HCs) during error processing and inhibitory control. For the error processing analysis, 239 patients with OCD (120 male; 79 medicated) and 229…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n response to emotional stimuli in patients, in particular, decreased amygdala activation. In contrast, brain-level abnormalities in at-risk individuals are more elusive. We address this gap using an <mark class="annotated-text">image-based meta-analysis</mark> of the functional magnetic resonance imaging literature. Functional magnetic resonance imaging studies investigating brain responses to negative emotional stimuli and reporting a comparison between a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …redictive methods of individual placebo analgesia from neuroimaging data, which would be of crucial importance both from a clinical and drug development point of view. Here, we conducted a systematic <mark class="annotated-text">participant-level meta-analysis of 20 independent neuroimaging studies</mark> on experimental placebo analgesia. Based on whole-brain activation patterns in a total of   N   = 603 healthy participants, we mapped the effects of placebo treatment on pain-related brain activity a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7925520/"
                                       >PMC7925520</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - review (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Miyahara, Motohide
Front Integr Neurosci, 2013

# Title

<mark class="annotated-text">Meta review of systematic and meta analytic reviews on movement differences, effect of movement based interventions, and the underlying neural mechanisms in autism spectrum disorder.
</mark>
# Keywords

MRI and fMRI
autism
developmental coordination disorder
motor development
movement

# Abstract
To identify and appraise evidence from published systematic and meta analytic reviews on (1)…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Stevens, Jennifer S and Jovanovic, Tanja
Genes Brain Behav, 2019

# Title

<mark class="annotated-text">Role of social cognition in post-traumatic stress disorder: A review and meta-analysis.
</mark>
# Keywords

G × SE
PTSD
fMRI
face stimuli
genetic risk
meta-analysis
neuroimaging
social brain
social cognition
trauma exposure

# Abstract
Social functioning is a key component of recovery after a p…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Peyron, R and Laurent, B and García-Larrea, L
Neurophysiol Clin, 2000

# Title

<mark class="annotated-text">Functional imaging of brain responses to pain. A review and meta-analysis (2000).
</mark>
# Keywords



# Abstract
Brain responses to pain, assessed through positron emission tomography (PET) and functional magnetic resonance imaging (fMRI) are reviewed. Functional activation of brain reg…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Bliksted, Vibeke and Ubukata, Shiho and Koelkebeck, Katja
Schizophr Res, 2016

# Title

<mark class="annotated-text">Discriminating autism spectrum disorders from schizophrenia by investigation of mental state attribution on an on-line mentalizing task: A review and meta-analysis.
</mark>
# Keywords

ASD
Autism
Differential diagnosis
Schizophrenia
Theory of mind
fMRI

# Abstract
In recent years, theories of how humans form a &#34;theory of mind&#34; of others (&#34;mentalizing&#34;) have increasingly…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Yeung, Andy Wai Kan and Wong, Natalie Sui Miu and Lau, Hakwan and Eickhoff, Simon B
Neuroimage, 2019

# Title

<mark class="annotated-text">Human brain responses to gustatory and food stimuli: A meta-evaluation of neuroimaging meta-analyses.
</mark>
# Keywords

Activation likelihood estimation
Food
Gustation
Literature analysis
Meta-analysis
Meta-evaluation
Neuroimaging
Review
Taste
fMRI

# Abstract
Multiple neuroimaging meta-analyses have been …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Dias, Alvaro Machado and Queiroz, Artur Trancoso Lopo and Maracaja-Coutinho, Vinícius
Med Hypotheses, 2010

# Title

<mark class="annotated-text">Schizophrenia, brain disease and meta-analyses: integrating the pieces and testing Fusar-Poli&#39;s hypothesis.
</mark>
# Keywords



# Abstract
This paper aims to discuss and test the hypothesis raised by Fusar-Poli [Fusar-Poli P. Can neuroimaging prove that schizophrenia is a brain disease? A radical hypothesis. Med…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    van Montfort, S.J.T. and van Dellen, E. and Stam, C.J. and Ahmad, A.H. and Mentink, L.J. and Kraan, C.W. and Zalesky, A. and Slooter, A.J.C.
Neuroimage Clin, 2019

# Title

<mark class="annotated-text">Brain network disintegration as a final common pathway for delirium: a systematic review and qualitative meta-analysis
</mark>
# Keywords

Delirium
Brain
Networks
Connectome
Aging
Cognitive impairment


# Abstract
 
Delirium is an acute neuropsychiatric syndrome characterized by altered levels of attention and awareness with…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6461601/"
                                       >PMC6461601</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - wanfang (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … were included in the present study. The PubMed, EMBASE, and Cochrane Library databases, Web of Science, China National Knowledge Infrastructure (CNKI), Chongqing VIP (VIP), and the Wanfang Database (<mark class="annotated-text">WF</mark>) were searched from inception until May 2020 by two independent researchers. The following English search terms were used: (stroke OR Poststroke OR Cerebrovascular Accident OR Cerebrovascular Apoplex…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …egy 
  
We searched for studies indexed in the following online databases from inception to September 2021: MEDLINE, Embase, Cochrane Library, Web of Science, China National Knowledge Infrastructure, <mark class="annotated-text">Wanfang</mark> database, WeiPu database, and China Biology Medicine. The following terms were used for the search: (“ST 36” or “ST36” or “  zusanli  ”) and (“fMRI” or “functional MRI” or “functional magnetic resona…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9373901/"
                                       >PMC9373901</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …nal homogeneity OR BOLD(in title or abstract) 
  
①AND②AND(③OR④OR⑤) 
  

Three English databases (PubMed, Web of Science, EmBase) and three Chinese databases (China National Knowledge Infrastructure, <mark class="annotated-text">Wanfang</mark> and China Biology Medicine disc) were queried. Inclusion criteria for eligible literature are as follows: (1) original clinical studies on human; (2) participants included patients diagnosed with MOH…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9581858/"
                                       >PMC9581858</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … their inception to August 18, 2022: PubMed, EMBASE, Web of Science, the Cochrane Library, the China National Knowledge Infrastructure (CNKI), the China Science and Technology Journal Database (VIP), <mark class="annotated-text">Wanfang</mark> Database, and the China Biology Medicine (CBM). Both Medical Subject Headings (MeSH) and free-text words related to acupuncture, migraine, and fMRI were used to retrieve relevant studies. We addition…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9911686/"
                                       >PMC9911686</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ered with PROSPERO  (registration number: CRD42020204050). 

### Selection procedure 
  
#### Search strategies 
  
Studies of acupuncture on some acupoints were searched from PubMed, Web of Science, <mark class="annotated-text">Wanfang</mark>, and the Chinese National Knowledge Infrastructure (CNKI) from the inception of the databases up to August 2021 to identify relevant studies. The following search terms were used: (“acupuncture” or “…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10287969/"
                                       >PMC10287969</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …cal and comprehensive search of the literature published between the establishment of the following publication databases until December 2022: Web of Science, PubMed, ScienceDirect, Embase, Wan Fang (<mark class="annotated-text">WF</mark>), China National Knowledge Infrastructure (CNKI), and Chinese Scientific Journal Database (VIP). The following search terms were used under the “subject words plus free words” retrieval strategy: (“A…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392941/"
                                       >PMC10392941</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ngs in the literature and enhance the understanding of LDH-related pain. 


## Materials and methods 
  
PubMed, Web of Science, Embase, Chinese National Knowledge Infrastructure (CNKI), SinoMed, and <mark class="annotated-text">Wanfang</mark> databases were searched for literature that studies the changes of brain basal activity in patients with LDH using regional homogeneity (ReHo) and amplitude of low-frequency fluctuation/fraction ampl…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10876805/"
                                       >PMC10876805</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">registration - osf (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … AES-SDM, we conducted a coordinate-based meta-analysis of 22 whole-brain datasets (n = 419 anxiety patients) from 18 studies identified by our systematic literature search following PRISMA criteria (<mark class="annotated-text">preregistration available at OSF: https://osf.io/dgc4p</mark>). In these studies, fMRI data was collected in response to negative stimuli during cognitive-emotional tasks before and after psychotherapy. Post-psychotherapy, activation decreased in the right insu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n the OSF ( ) including full reporting of any analyses not reported. Any digit materials or data that are inaccessible due to the programme used can be released by contacting the corresponding author.<mark class="annotated-text"> The study was registered on OSF prior to beginning the systematic search an</mark>d all manipulation and measure of this study are reported in the following sections. 



## RESULTS 
  
Nineteen fMRI publications of divergent thinking, with an average sample size of 24.79 and a mea…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7643395/"
                                       >PMC7643395</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ods 
  
### 2.1. Study Selection and Inclusion Criteria 
  
The current meta-analysis was performed according to the Preferred Reporting Items for Systematic reviews and Meta Analyses guidelines ( ). <mark class="annotated-text">A protocol for this work was registered on the Open Science Framework (OSF:  )</mark>. To obtain functional imaging studies of viewing high-calorie food cues for use in the current meta-analysis, a topic search in the databases PubMed, ISI Web of Knowledge, PsycINFO, and ProQuest Diss…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8699077/"
                                       >PMC8699077</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …low-up meta-regression that included callous-unemotional traits to predict amygdala activity to fearful expressions. All hypotheses, included contrasts, sampling criteria, and analysis techniques were<mark class="annotated-text"> pre-registered at  . 
</mark>
Hypotheses included that youth with conduct problems would show (1) Reduced responding in prefrontal and limbic regions such as ventromedial prefrontal cortex, anterior cingulate cortex (ACC), and am…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10063659/"
                                       >PMC10063659</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …be the average coordinates of each cognitive function listed above. The age range is birth to 21 years of age. 


## METHODS 
  
### Article selection and literature search 
  
This meta‐analysis was <mark class="annotated-text">preregistered on Open Science Framework ( )</mark> prior to beginning. Literature searches were conducted using Medline, Pubmed, Neurosynth, and Web of Science without restriction on dates. We also searched Google Scholar, and scanned reference lists…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10318218/"
                                       >PMC10318218</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ion and fMRI recording, as the WTP values would be automatically invoked even in non-incentivized tasks or during the passive viewing of objects even in absence of choice selection. 


## Methods 
  
<mark class="annotated-text">An a priori protocol for this meta-analysis was preregistered at The Open Science Framework</mark>:  . 

### Information sources and search strategy 
  
The formal search strategy consisted of systematically examining 3 electronic databases (PubMed, Scopus, PsycINFO) through August 2022 using the …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10332630/"
                                       >PMC10332630</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …


## METHOD 
  
This systematic review is reported following the Preferred Reporting Items for Systematic Reviews and Meta‐Analyses guidelines (Moher et al.,  ). The review protocol was registered on<mark class="annotated-text"> Open Science Framework ( ) </mark>on November 3, 2020. 

### Data search and extraction 
  
Three electronic databases were examined during February 2023 (PubMed, PsycINFO, and Web of Science) using the Medical Subject Headings search…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10636420/"
                                       >PMC10636420</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - cochrane library (7 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … Items for Systematic Reviews and Meta Analyses ( ) method. 


### Information source and search 
  
We first searched peer-reviewed papers published in English through MEDLINE, PubMed, PsychINFO and <mark class="annotated-text">Cochrane</mark> Library, including all potential articles from inception to July 2014. The following search terms were used: ‘Working Memory’ and ‘healthy adolescence/adolescents/developmental trajectories’ and “neu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5153561/"
                                       >PMC5153561</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s of gender and other relevant clinical profiles, such as age and comorbidity. 


## Methods 
  
### Search strategies 
  
A comprehensive systematic literature search was conducted using PubMed, the <mark class="annotated-text">Cochrane</mark> Library, Web of Science, and Embase databases to identify functional magnetic resonance imaging literature on anxiety disorders, published before September 2017 and including “in press” articles. The…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5953307/"
                                       >PMC5953307</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …umber: CRD 42020185421). 

### 2.1. Literature Search 
  
Studies that examined the neuroprotective effect of acupuncture in stroke patients were included in the present study. The PubMed, EMBASE, and<mark class="annotated-text"> Cochrane Library</mark> databases, Web of Science, China National Knowledge Infrastructure (CNKI), Chongqing VIP (VIP), and the Wanfang Database (WF) were searched from inception until May 2020 by two independent researcher…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s conducted according to the PRISMA statement and recorded using the suggested checklist. 


### Search strategy 
  
We have systematically searched all articles in Pubmed, Embase, Web of science and <mark class="annotated-text">Cochrane</mark> Library. The search strategy was performed with Medical Subject Heading (MESH) keywords and their related phrases in “Schizophrenia” [MeSH] OR “Schizophrenias” [Title/Abstract] OR “Schizophrenic diso…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8390947/"
                                       >PMC8390947</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …lished research protocol on INPLASY (INPLASY2021120035). 

### Search Strategy 
  
We searched for studies indexed in the following online databases from inception to September 2021: MEDLINE, Embase, <mark class="annotated-text">Cochrane</mark> Library, Web of Science, China National Knowledge Infrastructure, Wanfang database, WeiPu database, and China Biology Medicine. The following terms were used for the search: (“ST 36” or “ST36” or “  …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9373901/"
                                       >PMC9373901</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …dies in epidemiological (MOOSE) guideline ( ) and had been pre-registered in the PROSPERO database (CRD42022348694). 

### Literature search and study selection 
  
A comprehensive search of MEDLINE, <mark class="annotated-text">Cochrane Library</mark>, PubMed, Web of Science, and EMBASE databases for studies from inception until July 2022 that reported altered brain activation in patients with ESRD using the ALFF/fALFF method was conducted. The fo…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9751321/"
                                       >PMC9751321</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es (PRISMA) statement ( ). 

### 2.1. Literature search 
  
We performed a comprehensive search in the following databases from their inception to August 18, 2022: PubMed, EMBASE, Web of Science, the <mark class="annotated-text">Cochrane</mark> Library, the China National Knowledge Infrastructure (CNKI), the China Science and Technology Journal Database (VIP), Wanfang Database, and the China Biology Medicine (CBM). Both Medical Subject Head…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9911686/"
                                       >PMC9911686</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA10 (6 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …l stimuli. Aversive learning increased the probability of amygdala activation as well. There was some evidence of hemispheric specialization with a relative left-lateralization for stimuli containing <mark class="annotated-text">language</mark> and a relative right-lateralization for masked stimuli. Methodological variables, such as type of analysis and magnet strength, were also independent predictors of amygdala activation. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …temporal cortex only at the acupuncture points. 



### Results from the ALE meta-analysis 
  
A total of 34 studies were eligible for the inclusion criteria for the ALE meta-analyses ( ). A total of <mark class="annotated-text">10</mark> meta-analyses were performed. 
   Studies included in the ALE meta-analyses.        
The meta-analysis for verum acupuncture stimuli on greater activation of verum acupuncture points compared to base…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3322129/"
                                       >PMC3322129</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ith significant different activation between SZ patients and healthy controls. ALE clusters are projected on a standard anatomical template in axial orientation, referring to Talairach space 
  

For <mark class="annotated-text">anticipatory anhedonia in MDD </mark>(17 studies and 89 foci), decreased likelihood of activation was observed in bilateral caudate head and left MFG, and increased activation was observed in left IFG and right MFG. 

For emotional proce…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ation between SZ patients and healthy controls. ALE clusters are projected on a standard anatomical template in axial orientation, referring to Talairach space 
  

For anticipatory anhedonia in MDD (<mark class="annotated-text">17</mark> studies and 89 foci), decreased likelihood of activation was observed in bilateral caudate head and left MFG, and increased activation was observed in left IFG and right MFG. 

For emotional processi…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ation coordinates). During the positive social and affective processes, we found that IN-OT increased activity in the caudate head (−7.2/3.2/2.8,   k   = 56 mm , FWE   P   &lt;     0.05; ALE analysis on <mark class="annotated-text">17</mark> ‘OT &gt; PL’ contrasts, 102 activation coordinates), whereas no brain activity decreased by IN-OT was significant (FWE   P   &lt;     0.05; ALE analysis on 13 ‘OT &lt; PL’ contrasts, 48 activation coordinates…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ion in the bilateral AI, IFG, MFG and fusiform gyrus; left PI, IPL, caudate head, ACC, claustrum and IOG; and right SPL, aMCC, culmen and PosCG (see   and   for peak coordinates and ALE values). When <mark class="annotated-text">adding studies using an EC paradigm</mark>, the analysis revealed a similar pattern, but with more regions of activation. Specifically, in this analysis, the bilateral AI, IFG, SPL, SFG and IPL, left ACC, claustrum, and fusiform gyrus and rig…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Arioli</mark>, Maria and Cattaneo, Zaira and Ricciardi, Emiliano and Canessa, Nicola
Hum Brain Mapp, 2021

# Title

Overlapping and specific neural correlates for empathizing, affective mentalizing, and cognitive …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8410528/"
                                       >PMC8410528</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - brainmap (6 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … of the posterior middle temporal gyrus (pMTG), AG, and possibly SMG. We chose to use the same parcellation for consistency and to ensure adequate sampling of activation in the terminal STS. 

In the <mark class="annotated-text">BrainMap</mark> database (Laird et al.,  ), 675 PET and fMRI studies published in the years 1990–2010 were identified that reported activation peaks located within the left STS mask, as assessed based on reported co…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4160993/"
                                       >PMC4160993</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …rtra et al.,  ). We converted the subset of results reported in Talairach space to MNI space using the Lancaster (icbm2tal) transformation (Lancaster et al.,  ). 

For the DMN dataset, we conducted a <mark class="annotated-text">BrainMap</mark> search using the same search criteria used in Laird et al. ( ) to access published task independent activations, using Sleuth 2.3. The search criteria were (1) “Normal Mapping” context (healthy parti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5243799/"
                                       >PMC5243799</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … ). 


### Stimuli and procedure 
  
A systematic search strategy was used to identify relevant studies. First, we used the coordinate database (Fox &amp; Lancaster,  ; Fox et al.,  ; Laird et al.,  ) in <mark class="annotated-text">Brainmap</mark> Sleuth ( ;  ) because it contains neuroimaging coordinates classified as saccade and word reading tasks. The terms “[Image Modality = fMRI] AND [Paradigm = Saccade]” were entered to search for studie…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5434188/"
                                       >PMC5434188</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ctive 
  
The current study sought to create an anatomically specific connectivity model of the neural substrates involved in the salience network. 


## Methods 
  
A literature search of PubMed and <mark class="annotated-text">BrainMap</mark> Sleuth was conducted for resting‐state and task‐based fMRI studies relevant to the salience network according to PRISMA guidelines. Publicly available meta‐analytic software was utilized to extract r…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9304834/"
                                       >PMC9304834</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … previous findings by separately assessing different subprocesses of inhibitory control. 


## Method 
  
We systematically searched Web of Knowledge, ScienceDirect, Scopus, PubMed and the functional <mark class="annotated-text">BrainMap</mark> database for fMRI articles that compared activation during performance of inhibitory control tasks in patients with OCD and healthy control (HC) subjects. Thirty-five experiments from 21 articles met…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9723317/"
                                       >PMC9723317</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d a meta-analysis of the relevant neuroimaging literature to understand the roles of subregions of the dorsal striatum in performing different functions. 


## Methods 
  
PubMed, Web of Science, and <mark class="annotated-text">BrainMap</mark> Functional Database were searched to find original functional magnetic resonance imaging (fMRI) studies conducted on healthy adults under reward, memory, emotion, and decision-making tasks, and relev…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9816733/"
                                       >PMC9816733</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA9 (5 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ociated with a higher probability of activation than active task instructions. Gustatory-olfactory and visual stimulus modalities increased the probability of activation relative to internal stimuli. <mark class="annotated-text">Aversive learning </mark>increased the probability of amygdala activation as well. There was some evidence of hemispheric specialization with a relative left-lateralization for stimuli containing language and a relative right…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d, cluster size &gt; 400 mm ). Increased likelihood of activation was observed in the left middle occipital gyrus and fusiform gyrus. 



### Between-group ALE analysis in MDD or SZ 
  
#### MDD 
  
For <mark class="annotated-text">consummatory anhedonia in MDD</mark> (21 studies and 107 foci), decreased likelihood of activation was observed in the left GPe, right caudate body, left putamen, right insula and left ACC (  p   &lt; 0.01, FDR corrected, cluster size &gt; 40…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …reased likelihood of activation was observed in the left middle occipital gyrus and fusiform gyrus. 



### Between-group ALE analysis in MDD or SZ 
  
#### MDD 
  
For consummatory anhedonia in MDD (<mark class="annotated-text">21</mark> studies and 107 foci), decreased likelihood of activation was observed in the left GPe, right caudate body, left putamen, right insula and left ACC (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ted number of IN-OT fMRI studies on patients). During negative social and affective processes, IN-OT increased parahippocampus activity (26.8/1.2/−13.1,   k   = 56 mm , FWE   P   &lt;     0.05; based on <mark class="annotated-text">16</mark> ‘OT &gt; PL’ contrasts, 72 activation coordinates), whereas decreased right amygdala (18.1/−5/−8,   k   = 256 mm , FWE   P   &lt;     0.05; ALE analysis on 21 ‘OT &lt; PL’ contrasts, 136 activation coordinate…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ndition when studies using an EC paradigm were added, namely, the bilateral IPL and claustrum, and left AI, IFG, PreCG, aMCC, ACC and MFG. Refer to   in   for peak coordinates and ALE values. For the <mark class="annotated-text">OTO</mark> condition, the single ALE map revealed consistent activation in the bilateral AI, IFG, MFG and fusiform gyrus; left PI, IPL, caudate head, ACC, claustrum and IOG; and right SPL, aMCC, culmen and PosC…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … conducted due to a lack of sufficient available studies (  n   = 1). 


### Group differences for empathic pain images 
  
The whole-brain meta-analysis of responses to empathic pain images included <mark class="annotated-text">3</mark> contrasts (Table  ). Three regions survived FWER-correction, including a region that spanned right temporal pole and included areas of middle and inferior temporal gyrus in which youths with conduct …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10063659/"
                                       >PMC10063659</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-other ma method (5 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …rdly integrated in order to construct a model of the underlying neural correlates of neuroticism. The aim of the current meta-analysis was to provide a quantitative summary of the literature, using a <mark class="annotated-text">parametric coordinate-based meta-analysis (PCM)</mark> approach. Data were pooled for emotion processing tasks investigating the contrasts (negative&gt;neutral) and (positive&gt;neutral) to identify brain regions that are consistently associated with neurotici…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ts&#39; BOLD signal in several 
brain regions; however, within the
clusters identified as significantly deviant 
from one, R-squared values were
lower and ranged between 0.1–0.46. 


## 4. DISCUSSION 
  
<mark class="annotated-text">Here we report the preliminary use of a 
novel meta-analysis technique </mark>in studies on
aging, which localizes one factor of general 
cognitive slowing to the
sensorimotor transfer. These findings lend support to 
existing data from
event-related potential work indicating t…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">new technique</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2233772/"
                                       >PMC2233772</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … interactions do arise when assessing grammatical class specificity in different tasks (e.g., Palti et al.,  ; Berlingeri et al.,  ), this would have been a serious limitation of the ALE procedure. 

<mark class="annotated-text">We thus resorted to hierarchical clustering to carry out the meta-analysis</mark> (Jobard et al.,  ), using in particular the algorithm designed by Cattinelli et al. ( ) and previously adopted by Cattinelli et al. ( ). This algorithm permits the identification of clusters from a d…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">hierarchical clustering</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3695563/"
                                       >PMC3695563</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …te the assumption of independence. Instances of repeated coordinates were identified and removed to prevent bias. 


### Coordinate based meta-analysis 
  
Here we use a recently developed algorithm (<mark class="annotated-text">LocalALE</mark>), which is freely available from  . This algorithm utilizes the coordinates from fMRI studies to estimate where there is consistently reported activation across studies. It is based on the commonly u…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">based on ALE</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5554296/"
                                       >PMC5554296</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …h cluster was then reshaped to a spherical volume around the peak coordinate for the subsequent statistical analysis resulting in a total of 60 clusters for the inclusion into the further analysis. 

<mark class="annotated-text">The Tensor Imaging and Fiber Tracking (TIFT) software package was used for statistical analyses, as described in a previous meta-analysis with diffusion-weighted MRI data. </mark> The statistical process was transferred to the present rs-fMRI data set: each of the 60 coordinates was placed as Gaussian shaped result-spheres with its corresponding size, weighted with the square-…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">fibre tracking ma?</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7412904/"
                                       >PMC7412904</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-brainmap (5 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … connectivity of the left and right hippocampi: Evidence for functional lateralization along the long-axis using meta-analytic approaches and ultra-high field functional neuroimaging.

# Keywords

7T
<mark class="annotated-text">BrainMap</mark>
DTI
Long-axis
MACM
fMRI

# Abstract
Theories regarding the functional specialization of the hippocampus date back to over a century ago. Two main theories have dominated the field. First, evidence ha…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … convergence of activation across studies within affective categories. Others have used ALE to investigate a broad range of emotions, but without the convenience of the BrainMap database. We used the <mark class="annotated-text">BrainMap</mark> database and analysis resources to run separate meta-analyses on coordinates reported for anger, anxiety, disgust, fear, happiness, humor, and sadness. Resultant ALE maps were compared to determine a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …y sought to determine the underlying neurofunctional differences observed during working memory, a pivotal cognitive process shown to be predictive of academic achievement and intelligence. Using the <mark class="annotated-text">BrainMap</mark> database, we performed a meta-analysis and applied activation likelihood estimation to our search set. Our results demonstrate consistent working memory networks across genders, but also provide evid…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es, there were no differences in gray matter density between FRs and healthy controls. Furthermore, multi-modal meta-analysis obtained no differences between FRs and healthy controls. By utilizing the<mark class="annotated-text"> BrainMap</mark> database, we showed that the brain region which showed functional alterations in FRs (i) overlapped only slightly with the brain regions that were affected in the meta-analysis of schizophrenia patie…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ets, we found that the regions showing convergent aberrations in PD formed an interconnected network mainly with the default mode network (DMN). Behavioral characterization of these regions using the <mark class="annotated-text">BrainMap</mark> database suggested associated dysfunction of perception and executive processes. Taken together, our findings highlight the role of parietal cortex in the pathophysiology of PD. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA11 (4 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ility of amygdala activation as well. There was some evidence of hemispheric specialization with a relative left-lateralization for stimuli containing language and a relative right-lateralization for <mark class="annotated-text">masked</mark> stimuli. Methodological variables, such as type of analysis and magnet strength, were also independent predictors of amygdala activation. 
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …hedonia in MDD (17 studies and 89 foci), decreased likelihood of activation was observed in bilateral caudate head and left MFG, and increased activation was observed in left IFG and right MFG. 

For <mark class="annotated-text">emotional processing in MDD</mark> (25 studies and 124 foci), decreased likelihood of activation was observed in right GPe and putamen, bilateral amygdala and anterior lobe, right IFG and left ACC, and increased activation was observe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d 89 foci), decreased likelihood of activation was observed in bilateral caudate head and left MFG, and increased activation was observed in left IFG and right MFG. 

For emotional processing in MDD (<mark class="annotated-text">25</mark> studies and 124 foci), decreased likelihood of activation was observed in right GPe and putamen, bilateral amygdala and anterior lobe, right IFG and left ACC, and increased activation was observed in…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … 56 mm , FWE   P   &lt;     0.05; ALE analysis on 17 ‘OT &gt; PL’ contrasts, 102 activation coordinates), whereas no brain activity decreased by IN-OT was significant (FWE   P   &lt;     0.05; ALE analysis on <mark class="annotated-text">13</mark> ‘OT &lt; PL’ contrasts, 48 activation coordinates). 


### OT effects in healthy males and females 
  
Conjunction and subtraction analyses on ‘OT &gt; PL’ contrasts (male: 164 activation coordinates in 25…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …n, but with more regions of activation. Specifically, in this analysis, the bilateral AI, IFG, SPL, SFG and IPL, left ACC, claustrum, and fusiform gyrus and right MOG, were recruited (see  ). For the <mark class="annotated-text">STO</mark> condition, the single ALE map showed consistent activations in the bilateral IPL and additionally in the right PosCG and IOG, and left IFG, PreCG, ITG and fusiform (  and  ). When adding studies usin…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">label-based review/MA (4 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …wise quantitative meta-analysis using activation likelihood estimation [Laird, A. R., McMillan, K. M., Lancaster, J. L., Kochunov, P., Turkeltaub, P. E., &amp; Pardo, J. V., et al. (2005). A comparison of<mark class="annotated-text"> label-based review</mark> and ALE meta-analysis in the stroop task. Human Brain Mapping, 25, 6-21]. We conducted separate meta-analyses for four contrasts of interest: episodic encoding success as measured in the subsequent-m…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … the superior parietal lobule, inferior parietal lobule, and the dorsal premotor cortex but not the inferior frontal gyrus, are all commonly involved in imitation. An additional meta-analysis using a <mark class="annotated-text">label-based review</mark> confirmed that in the frontal lobe, the premotor cortex rather than the inferior frontal gyrus is consistently active in studies investigating imitation. In the parietal region the superior and infer…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …h study. Thus, the current work is aimed at identifying whether there are spatially consistent structural and functional brain abnormalities in individuals with 22q11.2 DS through (i) a comprehensive <mark class="annotated-text">label-based systematic review</mark> and (ii) a coordinate-based meta-analysis of magnetic resonance imaging studies. The systematic review identified the frontal middle gyri, posterior cingulum, right cuneus and bilateral precuneus as …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … the ALE map.   shows a flow chat that illustrated the process of this ALE meta-analysis. 
  
Flow chart that illustrates the process of activation likelihood estimation (ALE) meta-analysis. 
  

### <mark class="annotated-text">Label-based meta-analysis</mark> 
  
In addition, a “label-based meta-analysis” [method based on ( )] was performed to tabulate/summarize the activated brain regions commonly reported across the studies. The extracted activation foc…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9808082/"
                                       >PMC9808082</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - none reported (4 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Martin, Anna <mark class="annotated-text">and</mark> Schurz, Matthias and Kronbichler, Martin and Richlan, Fabio
Hum Brain Mapp, 2015

# Title

Reading in the brain of children and adults: A meta‐analysis of 40 functional magnetic resonance imaging stu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4950303/"
                                       >PMC4950303</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Janiri, Delfina <mark class="annotated-text">and</mark> Moser, Dominik A. and Doucet, Gaelle E. and Luber, Maxwell J. and Rasgon, Alexander and Lee, Won Hee and Murrough, James W. and Sani, Gabriele and Eickhoff, Simon B. and Frangou, Sophia
JAMA Psychiat…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6822098/"
                                       >PMC6822098</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Kurashige, Hiroki and Kaneko, <mark class="annotated-text">Jun</mark> and Yamashita, Yuichi and Osu, Rieko and Otaka, Yohei and Hanakawa, Takashi and Honda, Manabu and Kawabata, Hideaki
Front Hum Neurosci, 2019

# Title

Revealing Relationships Among Cognitive Function…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6965330/"
                                       >PMC6965330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Sartin, Samantha and <mark class="annotated-text">Ranzini</mark>, Mariagrazia and Scarpazza, Cristina and Monaco, Simona
Curr Res Neurobiol, 2022

# Title

Cortical areas involved in grasping and reaching actions with and without visual information: An ALE meta-an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9826890/"
                                       >PMC9826890</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">guidelines - pico (4 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …lysis to fMRI results measured during painful tasks (painful stimulation task or pain-related motor task) with whole-brain coordinate-level data (peak x, y, z coordinates, and anatomical template). 

<mark class="annotated-text">Our research question according to the Population, Intervention, Comparator and Outcome (PICO) protocol </mark>(Higgins et al.,  ) then is: in which brain regions functional and molecular brain activities in chronic pain patients, measured by functional neuroimaging techniques such as fMRI and PET, would show …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8287208/"
                                       >PMC8287208</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e screened for title, abstract and full text and were conducted independently by two researchers (ML and ZZ). In case of disagreement, the two researchers reached an agreed result through discussion. <mark class="annotated-text">The following inclusion criteria were based on PICO standards: </mark>

Participants: Clinical trials with clear diagnostic criteria for MCI, with no restrictions on participant age or gender. 
  
(1) Interventions: The treatment group used various acupuncture therapies…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9540390/"
                                       >PMC9540390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) guidelines were employed for our systematic review and meta-analysis. We conducted a computer-based literature search, following the <mark class="annotated-text">Population, Intervention, Comparison and Outcomes (PICO) approach</mark>, to retrieve all published articles in English regarding the above-described topics from PubMed (MEDLINE), Scopus, and Web of Science. 


## Study eligibility criteria, participants, and intervention…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9832372/"
                                       >PMC9832372</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … et al.,  ). 

### 2.1. Eligibility criteria 
  
To formulate and refine the eligibility criteria and search strategy, a scoping review was performed. Existing literature was reviewed to identify the <mark class="annotated-text">population, intervention, comparisons, outcome, and study design (PICOS)</mark> principles used in this systematic review. 
  
 Population:   Adults classified as having either subjective or objective cognitive impairment associated with dementia risk (e.g., SCD, MCI, VCI). 
  
…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10228832/"
                                       >PMC10228832</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">N group-level stat maps included (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … (fMRI), yielding a pooled sample of 677 participants from 27 independent studies. As a distinguishing feature of this meta-analysis, original statistical brain maps were obtained from the authors of <mark class="annotated-text">13</mark> of these studies. Our primary analyses demonstrate that human fear conditioning is associated with a consistent and robust pattern of neural activation across a hypothesized genuine network of brain …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ed neuroimaging findings of affect processing in BPD, MDD, and PTSD and calculated combined coordinate- and image-based meta-analyses. The analysis comprised 70 distinct study samples with a total of <mark class="annotated-text">31</mark> unthresholded statistical parametric maps. Twenty-four studies had a focus on BPD (431 individuals with BPD, 436 healthy control subjects [HCs]), 32 studies on MDD (789 individuals with current MDD, …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …th 677 participants (366 males, mean age 25.4 years) using a delay differential cue-conditioning paradigm were obtained. All studies reported a CS +  &gt; CS−, 19 of them also the opposite contrast. For <mark class="annotated-text">13</mark> of them, original empirical 3D statistical images were available [ ]. The entire data of fear conditioning have been published before in [ ]. 


### Meta-analytic procedure 
  
Functional activation …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10025232/"
                                       >PMC10025232</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA12 (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …observed in right GPe and putamen, bilateral amygdala and anterior lobe, right IFG and left ACC, and increased activation was observed in middle occipital gyrus and fusiform gyrus. 


#### SZ 
  
For <mark class="annotated-text">consummatory anhedonia in SZ</mark> (8 studies and 44 foci), decreased likelihood of activation was observed in left putamen and caudate head, pulvinar and right red nucleus (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm3; Table  …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …men, bilateral amygdala and anterior lobe, right IFG and left ACC, and increased activation was observed in middle occipital gyrus and fusiform gyrus. 


#### SZ 
  
For consummatory anhedonia in SZ (<mark class="annotated-text">8</mark> studies and 44 foci), decreased likelihood of activation was observed in left putamen and caudate head, pulvinar and right red nucleus (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm3; Table   an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … 


### OT effects in healthy males and females 
  
Conjunction and subtraction analyses on ‘OT &gt; PL’ contrasts (male: 164 activation coordinates in 25 contrasts; female: 84 activation coordinates in <mark class="annotated-text">14</mark> contrasts) were conducted to reveal significant similarities as well as differences in brain activity increased by IN-OT between healthy males and females (this analysis was also only performed on he…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …see  ). For the STO condition, the single ALE map showed consistent activations in the bilateral IPL and additionally in the right PosCG and IOG, and left IFG, PreCG, ITG and fusiform (  and  ). When <mark class="annotated-text">adding studies using an EC paradigm</mark>, several additional clusters were found, including in the bilateral IPL, left AI, ITG, IFG and claustrum, and right PosCG, IOG, fusiform gyrus and SFG (see   for peak coordinate and ALE values). 

Wh…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA13 (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …tamen and caudate head, pulvinar and right red nucleus (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm3; Table   and Fig.  ). No areas with increased likelihood of activation were observed. 

For <mark class="annotated-text">anticipatory anhedonia in SZ</mark> (13 studies and 30 foci) decreased likelihood of activation was observed in left putamen, ACC, and mPFC and right caudate head. No areas with increased likelihood of activation were observed. 

For e…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ar and right red nucleus (  p   &lt; 0.01, FDR corrected, cluster size &gt; 400 mm3; Table   and Fig.  ). No areas with increased likelihood of activation were observed. 

For anticipatory anhedonia in SZ (<mark class="annotated-text">13</mark> studies and 30 foci) decreased likelihood of activation was observed in left putamen, ACC, and mPFC and right caudate head. No areas with increased likelihood of activation were observed. 

For emoti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ncreased right amygdala activity (23.7/−1.7/−11,   k   = 128 mm ) was overlapped in males and females. Conjunction and subtraction analyses on ‘OT &lt; PL’ contrasts (male: 187 activation coordinates in <mark class="annotated-text">22</mark> contrasts; female: 39 activation coordinates in 13 contrasts) showed that IN-OT decreased brain activity in the right amygdala (extending to medial GP; 17.3/−4.2/−9.1,   k   = 656 mm , FDR   P   &lt;   …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5647800/"
                                       >PMC5647800</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ional clusters were found, including in the bilateral IPL, left AI, ITG, IFG and claustrum, and right PosCG, IOG, fusiform gyrus and SFG (see   for peak coordinate and ALE values). 

When running the <mark class="annotated-text">conjunction</mark> and subtraction analyses, results showed common and distinct patterns of activation for certain conditions. Conjunction analyses showed consistent activities in the bilateral IPL, left PreCG and righ…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6847411/"
                                       >PMC6847411</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-ABC (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … Becker, Benjamin
Hum Brain Mapp, 2022

# Title

Dysregulated anterior insula reactivity as robust functional biomarker for chronic pain-Meta-analytic evidence from neuroimaging studies.

# Keywords

<mark class="annotated-text">ABC</mark>
ALE
chronic pain
functional magnetic resonance imaging
meta-analysis

# Abstract
Neurobiological pain models propose that chronic pain is accompanied by neurofunctional changes that mediate pain proc…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ci Biobehav Rev, 2022

# Title

The central autonomic system revisited - Convergent evidence for a regulatory role of the insular and midcingulate cortex from neuroimaging meta-analyses.

# Keywords

<mark class="annotated-text">ABC</mark>
ALE
Arousal
Central autonomic system
Cingulate cortex
Cognition
Coordinate-based
Emotion
Functional magnetic resonance imaging
Insula
Meta-analysis
Parasympathetic
Sympathetic
fMRI

# Abstract
The au…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …CBMA) offers this, but the multiple algorithms can produce different results, making interpretation conditional on the algorithm. Here a new model based CBMA algorithm, Analysis of Brain Coordinates (<mark class="annotated-text">ABC</mark>), is presented. ABC aims to be simple to understand by avoiding empirical elements where possible and by using a simple to interpret statistical threshold, which relates to the primary aim of detecti…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - china biology medicine disc (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …d in the following online databases from inception to September 2021: MEDLINE, Embase, Cochrane Library, Web of Science, China National Knowledge Infrastructure, Wanfang database, WeiPu database, and <mark class="annotated-text">China</mark> Biology Medicine. The following terms were used for the search: (“ST 36” or “ST36” or “  zusanli  ”) and (“fMRI” or “functional MRI” or “functional magnetic resonance imaging”). Titles and abstracts …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9373901/"
                                       >PMC9373901</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ity OR BOLD(in title or abstract) 
  
①AND②AND(③OR④OR⑤) 
  

Three English databases (PubMed, Web of Science, EmBase) and three Chinese databases (China National Knowledge Infrastructure, Wanfang and <mark class="annotated-text">China Biology Medicine disc</mark>) were queried. Inclusion criteria for eligible literature are as follows: (1) original clinical studies on human; (2) participants included patients diagnosed with MOH according to International Clas…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9581858/"
                                       >PMC9581858</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …E, Web of Science, the Cochrane Library, the China National Knowledge Infrastructure (CNKI), the China Science and Technology Journal Database (VIP), Wanfang Database, and the China Biology Medicine (<mark class="annotated-text">CBM</mark>). Both Medical Subject Headings (MeSH) and free-text words related to acupuncture, migraine, and fMRI were used to retrieve relevant studies. We additionally searched the references of the included s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9911686/"
                                       >PMC9911686</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">search terms - none (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …lyses (PRISMA) framework (Moher et al.,  ). A PRISMA flow diagram for the literature search is documented in  . The search criteria for each database are reported in  . PubMed and Google Scholar were <mark class="annotated-text">periodically searched between August 2015 and December 2020 to locate peer-reviewed articles published prior to December 2020 that used fMRI or PET to measure brain activations to speech and language stimuli in PWA. </mark>The PubMed search yielded a total of 759 articles. For Google Scholar, we extracted the first 150 citations for each search criteria, which resulted in 1,500 citations (150 citations x 10 search crite…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8572938/"
                                       >PMC8572938</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Sartin, Samantha and Ranzini, <mark class="annotated-text">Mariagrazia</mark> and Scarpazza, Cristina and Monaco, Simona
Curr Res Neurobiol, 2022

# Title

Cortical areas involved in grasping and reaching actions with and without visual information: An ALE meta-analysis of neu…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9826890/"
                                       >PMC9826890</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …# Study selection 
  
#### Data sources 
  
Two independent investigators performed a bibliographic search using the following databases: PubMed, Web of Science, PsycInfo, Google Scholar, and Scopus. <mark class="annotated-text">Some examples of the Boolean algorithm with the keywords used are presented in the Appendix A. </mark>The search included all the studies published until 28 February 2021. We conducted this meta-analysis according to the Preferred Reporting Items for Systematic Reviews and Meta-analysis (PRISMA) guide…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392089/"
                                       >PMC10392089</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - chongqing vip (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …f acupuncture in stroke patients were included in the present study. The PubMed, EMBASE, and Cochrane Library databases, Web of Science, China National Knowledge Infrastructure (CNKI), Chongqing VIP (<mark class="annotated-text">VIP</mark>), and the Wanfang Database (WF) were searched from inception until May 2020 by two independent researchers. The following English search terms were used: (stroke OR Poststroke OR Cerebrovascular Acci…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8192216/"
                                       >PMC8192216</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s from their inception to August 18, 2022: PubMed, EMBASE, Web of Science, the Cochrane Library, the China National Knowledge Infrastructure (CNKI), the China Science and Technology Journal Database (<mark class="annotated-text">VIP</mark>), Wanfang Database, and the China Biology Medicine (CBM). Both Medical Subject Headings (MeSH) and free-text words related to acupuncture, migraine, and fMRI were used to retrieve relevant studies. W…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9911686/"
                                       >PMC9911686</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …owing publication databases until December 2022: Web of Science, PubMed, ScienceDirect, Embase, Wan Fang (WF), China National Knowledge Infrastructure (CNKI), and Chinese Scientific Journal Database (<mark class="annotated-text">VIP</mark>). The following search terms were used under the “subject words plus free words” retrieval strategy: (“Acupuncture” OR “Needle” OR “Acupoint”) AND (“fMRI” OR “Magnetic resonance imaging” OR “FC” OR “…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10392941/"
                                       >PMC10392941</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">registration - inplasy (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …# Methods 
  
### Study registration 
  
This protocol was registered with the International Platform of Registered Systematic Review and Meta-Analysis Protocols (INPLASY). The registration number is <mark class="annotated-text">INPLASY202130092</mark> (Doi: 10.37766/inplasy2021.3.0092). The protocol is according to Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA-P) statement guidelines.  The results of this meta-analysis…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8519237/"
                                       >PMC8519237</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …in healthy subjects was conducted according to Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) and for Acupuncture (PRISMA-A) guidelines and published research protocol on <mark class="annotated-text">INPLASY</mark> (INPLASY2021120035). 

### Search Strategy 
  
We searched for studies indexed in the following online databases from inception to September 2021: MEDLINE, Embase, Cochrane Library, Web of Science, C…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9373901/"
                                       >PMC9373901</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …thods 
  
The protocol of this ALE-meta analysis has already been registered on the International Platform of Registered Systematic Review and Meta-analysis Protocols (INPLASY)  (registration number: <mark class="annotated-text">INPLASY2022110026</mark>). The present study was reported in accordance with the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) statement ( ). 

### 2.1. Literature search 
  
We performed a comp…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9911686/"
                                       >PMC9911686</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-GPR (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …n Reasoning.

# Keywords

Bayesian meta-analysis of the cortical surface (BMACS)
functional magnetic resonance imaging
inductive and deductive reasoning
integrated nested Laplace approximation (INLA)
<mark class="annotated-text">log-Gaussian Cox process</mark>

# Abstract
Recent advances in neuroimaging have augmented numerous findings in the human reasoning process but have yielded varying results. One possibility for this inconsistency is that reasoning …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …rly 2011. Data from 34 case-control comparisons (n=1165) and 6 treatment studies (n=105) were analysed separately with two meta-analytic methods for imaging data: Activation Likelihood Estimation and <mark class="annotated-text">Gaussian-Process Regression</mark>. There was broad support for limbic-cortical and cortico-striatal models in the case-control data. Evidence for the role of the default mode network was weaker. Treatment-sensitive regions were prima…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-CluB (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …r a more detailed contrast characterization see the  . Further, all the Talairach coordinates were converted to MNI space through the Talairach to MNI (SPM) transformation implemented in the software <mark class="annotated-text">CluB</mark> (Clustering the Brain, see below). 

The final dataset included 474 participants (mean age = 27.35 ± 4) and 34 contrasts. 


##### Cluster analysis and cluster composition analysis: motor intention a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6473038/"
                                       >PMC6473038</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … first performed a HC analysis using the unique-solution clustering algorithm developed by Cattinelli et al. . This method is implemented in a suite of MATLAB (2014a MathWorks) and C++ scripts called <mark class="annotated-text">CluB</mark> (Clustering the Brain ). The CluB toolbox permits both to extract a set of spatially coherent clusters of activations from a database of stereotactic coordinates, and to explore each single cluster o…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8776875/"
                                       >PMC8776875</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-neuroelf (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …; Wager et al.,  ). 


### Multilevel Kernel Density Analysis (MKDA) 
  
We first converted all peak coordinates reported in Talairach space to MNI space (Lancaster et al.,  ), and imported them into <mark class="annotated-text">NeuroElf</mark>  to perform an MKDA. The coordinates were then smoothed using a 12-mm Gaussian kernel and combined to form a single map for each classified contrast, ensuring that contrasts reporting more coordinate…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5951926/"
                                       >PMC5951926</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …tus of the target and reference (i.e. in-group or out-group), and coordinates of peak activation. 



## Data analysis 
  
MKDA (see   for more information) was implemented through the Matlab toolbox <mark class="annotated-text">NeuroElf</mark> ( ). Consistent with MKDA and neuroimaging meta-analytic procedures ( ;  ;  ), contrast coordinates in Talairach space were first converted to MNI space and then convolved using a smoothing kernel of…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8421705/"
                                       >PMC8421705</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-MKDA toolbox (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …we used a threshold of 15 studies. See Tables  –  for preliminary results from models that did not meet this threshold. 


### Multilevel kernel density analysis 
  
Analyses were conducted using the <mark class="annotated-text">MKDA toolbox</mark> in SPM12 . Foci in Talairach space were converted to MNI space . Binary indicator maps for each contrast were created by convolving peak foci using a 10-mm spherical kernel, with voxels related to ps…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7203015/"
                                       >PMC7203015</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e whole brain.  MKDA meta-analyses can, therefore, identify regions that are consistently or reliably activated in a set of studies.  We performed our meta-analysis in MATLAB version R2021b using the <mark class="annotated-text">MKDA toolbox</mark>.  Data analysis was conducted from August to November 2022. 



## Results 
  
### All Neurocognitive Domains 
  
A total of 83 studies  were included with a pooled sample size of 5242 participants a…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10620621/"
                                       >PMC10620621</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-none-or-unclear (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …nts receiving any psychotropic medication in each study sample. Further details of the database construction are provided in the eMethods in the  . 


### Activation Likelihood Estimation 
  
We used <mark class="annotated-text">ALE, implemented in MATLAB</mark> (MathWorks), to test whether the whole-brain coordinates of case-control differences across experiments and disorders converged into discrete clusters with a nonrandom spatial distribution.  The fund…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6822098/"
                                       >PMC6822098</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Funch</mark> Uhre, Valdemar and Melissa Larsen, Kit and Marc Herz, Damian and Baaré, William and Katrine Pagsberg, Anne and Roman Siebner, Hartwig
Neuroimage Clin, 2022

# Title

Inhibitory control in obsessive c…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9723317/"
                                       >PMC9723317</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - sinomed (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ion 
  
A comprehensive literature search was conducted of task-related fMRI studies up to June 2013 examining the effect of methylphenidate/other stimulants in ADHD children and adults using PubMed, <mark class="annotated-text">ScienceDirect</mark>, Google Scholar, Web of Knowledge, and Scopus electronic search engines using keywords such as attention-deficit/hyperactivity disorder, ADHD, and hyperkinetic, plus fMRI, neuroimaging, and methylphe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4183380/"
                                       >PMC4183380</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …dictory findings in the literature and enhance the understanding of LDH-related pain. 


## Materials and methods 
  
PubMed, Web of Science, Embase, Chinese National Knowledge Infrastructure (CNKI), <mark class="annotated-text">SinoMed</mark>, and Wanfang databases were searched for literature that studies the changes of brain basal activity in patients with LDH using regional homogeneity (ReHo) and amplitude of low-frequency fluctuation/…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10876805/"
                                       >PMC10876805</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">stopped here (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Cao, Huiling <mark class="annotated-text">and</mark> Lin, Feng and Ke, Ben and Song, Jianling and Xue, Yuting and Fang, Xiangdong and Zeng, Erming
Front Hum Neurosci, 2022

# Title

Alterations of amplitude of low-frequency fluctuations and fractional …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9751321/"
                                       >PMC9751321</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">candidate for replication (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Yu</mark>, Miaomiao and Gao, Xinyu and Niu, Xiaoyu and Zhang, Mengzhe and Yang, Zhengui and Han, Shaoqiang and Cheng, Jingliang and Zhang, Yong
Front Psychiatry, 2022

# Title

Meta-analysis of structural and …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9853532/"
                                       >PMC9853532</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">NO N studies included (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Zhu</mark>, Tingting and Wang, Zixu and Zhou, Chao and Fang, Xinyu and Huang, Chengbing and Xie, Chunming and Ge, Honglin and Yan, Zheng and Zhang, Xiangrong and Chen, Jiu
Front Psychiatry, 2022

# Title

Meta-…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">21</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9552970/"
                                       >PMC9552970</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhu, <mark class="annotated-text">Tingting</mark> and Wang, Zixu and Zhou, Chao and Fang, Xinyu and Huang, Chengbing and Xie, Chunming and Ge, Honglin and Yan, Zheng and Zhang, Xiangrong and Chen, Jiu
Front Psychiatry, 2022

# Title

Meta-analysis o…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">4</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9552970/"
                                       >PMC9552970</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhu, Tingting <mark class="annotated-text">and</mark> Wang, Zixu and Zhou, Chao and Fang, Xinyu and Huang, Chengbing and Xie, Chunming and Ge, Honglin and Yan, Zheng and Zhang, Xiangrong and Chen, Jiu
Front Psychiatry, 2022

# Title

Meta-analysis of st…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">6</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9552970/"
                                       >PMC9552970</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhu, Tingting and <mark class="annotated-text">Wang</mark>, Zixu and Zhou, Chao and Fang, Xinyu and Huang, Chengbing and Xie, Chunming and Ge, Honglin and Yan, Zheng and Zhang, Xiangrong and Chen, Jiu
Front Psychiatry, 2022

# Title

Meta-analysis of structu…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">5</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9552970/"
                                       >PMC9552970</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    Zhu, Tingting and Wang, <mark class="annotated-text">Zixu</mark> and Zhou, Chao and Fang, Xinyu and Huang, Chengbing and Xie, Chunming and Ge, Honglin and Yan, Zheng and Zhang, Xiangrong and Chen, Jiu
Front Psychiatry, 2022

# Title

Meta-analysis of structural an…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">22</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9552970/"
                                       >PMC9552970</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">MA14 (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …Z (13 studies and 30 foci) decreased likelihood of activation was observed in left putamen, ACC, and mPFC and right caudate head. No areas with increased likelihood of activation were observed. 

For <mark class="annotated-text">emotional processing in SZ </mark>(6 studies and 39 foci), decreased likelihood of activation was observed in the right ventral lateral nucleus. No areas with increased likelihood of activation were observed. 




## Discussion 
  
Th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ecreased likelihood of activation was observed in left putamen, ACC, and mPFC and right caudate head. No areas with increased likelihood of activation were observed. 

For emotional processing in SZ (<mark class="annotated-text">6</mark> studies and 39 foci), decreased likelihood of activation was observed in the right ventral lateral nucleus. No areas with increased likelihood of activation were observed. 




## Discussion 
  
This…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838562/"
                                       >PMC4838562</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-canlab mkda (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …elow), and 5) used targeted voxelwise reporting (n = 8, see below). 



### Data and code availability 
  
All data used in this project (coded foci of activation differences) are available in the  . <mark class="annotated-text">The MKDA code used to perform meta-analyses is freely available via CANLAB ( ). </mark>



## Results 
  
### Included Studies. 
  
See   for flow diagram and detailed information on study selection. The initial database search yielded a total of 2213 articles. Of these, 76 met initial …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7992390/"
                                       >PMC7992390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-nimare (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …med a series of coordinate-based meta-analyses using the activation likelihood estimate (ALE) method. Meta-analysis was performed on whole-brain coordinates reported from 864 fMRI contrasts using the <mark class="annotated-text">NiMARE</mark> Python package, revealing convergence in medial prefrontal cortex, anterior cingulate cortex, posterior cingulate cortex, temporoparietal junction, bilateral insula, amygdala, fusiform gyrus, precune…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-other (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …



### Data and code availability 
  
All data used in this project (coded foci of activation differences) are available in the  . The MKDA code used to perform meta-analyses is freely available via <mark class="annotated-text">CANLAB</mark> ( ). 



## Results 
  
### Included Studies. 
  
See   for flow diagram and detailed information on study selection. The initial database search yielded a total of 2213 articles. Of these, 76 met in…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7992390/"
                                       >PMC7992390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-neurosynth MACM (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    <mark class="annotated-text">Bezdicek</mark>, Ondrej and Ballarini, Tommaso and Růžička, Filip and Roth, Jan and Mueller, Karsten and Jech, Robert and Schroeter, Matthias L
Neuropsychologia, 2018

# Title

Mild cognitive impairment disrupts att…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - previous ma for seed / roi (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    Kim, M Justin and Knodt, Annchen R and Hariri, Ahmad R
Soc Cogn Affect Neurosci, 2022

# Title

<mark class="annotated-text">Meta-analytic activation maps</mark> can help identify affective processes captured by contrast-based task fMRI: the case of threat-related facial expressions

# Keywords

fMRI
meta-analysis map
emotion
fear
anger
facial expression


# …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9433847/"
                                       >PMC9433847</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - not a ma, doesn&#39;t fit other exclusion (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …gions based on studies from different research groups. We included twelve suitable studies that examined nine different target regions amounting to a total of 175 subjects and 899 neurofeedback runs. <mark class="annotated-text">Data analysis included a standard first- (single subject, extracting main paradigm)</mark> and second-level (single subject, all runs) general linear model (GLM) analysis of all participants taking into account the individual timing. Subsequently, at the third level, a random effects model…
                </div>
                <div class="annotation-footer">
                    <div class="extra-data">mega-analysis</div>
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMCNone/"
                                       >PMCNone</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - springerlink (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …l fMRI or PET articles that examined episodic memory retrieval of spatial or temporal information in healthy young adults. The following databases were searched to identify relevant articles: PubMed, <mark class="annotated-text">SpringerLink</mark>, PsycInfo, and Scopus. All relevant studies, regardless of publication date, were included. The search was performed with the following keywords: episodic memory, context memory, source memory, recol…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10827973/"
                                       >PMC10827973</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - proquest (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …election 
  
In order to identify eligible studies, we conducted a systematic literature search. The computerised search involved using the following electronic databases: Dissertations &amp; Theses A&amp;I (<mark class="annotated-text">ProQuest</mark>), Dissertation &amp; Theses: UK &amp; Ireland (ProQuest), Web of Science, PsycINFO (EBSCOhost) and MEDLINE (OVID). The following search terms were used ‘autis*’, ‘biological motion’, ‘human motion’, ‘asd’, ‘…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6921539/"
                                       >PMC6921539</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">guidelines - joanna briggs institute (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …e recoded as having a &#34;waitlist control group”. 


### Quality of reporting appraisal and risk of bias within the studies 
  
The revised Cochrane risk-of-bias tool for randomized trials (RoB 2)  and <mark class="annotated-text">Joanna Briggs Institute’s (JBI) critical appraisal checklist for analytical cross-sectional studies</mark>  were used to evaluate the methodological quality of the included RCTs and cross-sectional studies, respectively. Bias arising from the randomization process, bias due to deviations from intended int…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10326064/"
                                       >PMC10326064</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - pubmed central (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …e conducted a systematic literature search in accordance with the PRISMA guidelines ( ) to identify brain imaging studies of intentional choice. The literature search was performed on both PubMed and <mark class="annotated-text">PubMed Central</mark> (PMC) databases, because the two databases may contain different publications. The PubMed database was searched with specified keywords as following: (&#34;volitional decision&#34; OR &#34;volitional choice&#34; OR …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8463837/"
                                       >PMC8463837</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - ovid (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …d to implicit memory and arousal, such as the hippocampus, amygdala, striatum and primary visual cortex. 


## Methods 
  
### Searching 
  
#### Inclusion and exclusion criteria 
  
PubMed, Medline, <mark class="annotated-text">Ovid</mark>, Sciencedirect, Web of Science and Google Scholar were searched, and hand searches of reference lists up to October 2013. Search terms for online searches included fMRI and MRI, with subliminal and s…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4271330/"
                                       >PMC4271330</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - elsevier (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …## Literature search and selection criteria 
  
In May 2020, the relevant studies were identified through a systematic online database search for peer‐reviewed articles on Web of Science, PubMed, and <mark class="annotated-text">Elsevier</mark>. The searches were conducted with the keywords “stroke” or “apoplexy” or “cerebralvascular accident” or “cerebral infarction” or “cerebral haemorrhage”, “aphasia”, “resting‐state functional magnetic …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7749604/"
                                       >PMC7749604</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - neurosynth (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ibution of mentalizing reasoning in the posterior cerebellum in more general. 



## Method 
  
### Selection of studies 
  
The fMRI studies reviewed in the current meta-analysis were taken from the <mark class="annotated-text">NeuroSynth</mark> database (neurosynth.org). A study was defined as a single fMRI experiment, and all coordinates from all task-related analyses in each study were eligible (in the same manner as in NeuroSynth). No at…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7851889/"
                                       >PMC7851889</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">database - neurovault (1 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ether coordinates of activation differences or un-thresholded statistical images could be provided. This did not yield any additional studies to be included. Ad-hoc searches were also performed using <mark class="annotated-text">NeuroVault</mark> ( ) with basic keywords (‘family history’, ‘prospective’, ‘substance use’, ‘alcohol’) to try and identify relevant un-thresholded statistical images. No relevant maps were identified. Based on the la…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7992390/"
                                       >PMC7992390</a></div>
                    <div class="annotator-name">Kendra_Oudyk</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details style="--label-color: #eeeeec;">
        <summary class="label-display">no-access (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #ffbb78;">
        <summary class="label-display">NO N contrasts included (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #c49c94;">
        <summary class="label-display">N MAs (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #ff9896;">
        <summary class="label-display">algorithm-KDA (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-abc (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #c5b0d5;">
        <summary class="label-display">software-spm (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-neuroquery encoding (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #98df8a;">
        <summary class="label-display">largescale-other-or-undefined (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - cites ma as justification (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - not about the brain (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - cites ma as consistent with findings (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - non-human focus (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - preprint (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #888a85;">
        <summary class="label-display">EXCLUDE - ma not in title (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
    <details style="--label-color: #4e9a06;">
        <summary class="label-display">has prisma chart (0 docs)</summary>
        
        <p>(No annotations with this label in the current project)</p>
        
    </details>
    
</div>
"""
displays.HTMLDisplay(text)
```