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


# dynamic_functional_connectivity

You can see the full contents of this project [on GitHub](https://github.com/neurodatascience/labelbuddy-annotations/tree/main/projects/dynamic_functional_connectivity/).

## Dynamic Functional Connectivity methods

The focus of this project is to explore how methods for estimating Dynamic Functional Connectivity (DFC) are used in the literature.
Related code and documentation can be found in a dedicated GitHub [repository](https://github.com/neurodatascience/dfc_text_mining).

The documents have been collected with **pubget** and the whole **pubget** output can be found on [OSF](https://osf.io/2ekbd).




## Labels in this project



```{code-cell}
:tags: [remove-input]

from labelrepo import displays
text = """
<div class="detailed-label-set">
    
    <details >
        <summary class="label-display">SW (32 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …e location of neighbouring voxels around the centre voxel, and the neighbourhood was also defined as a 3 × 3 × 3 cluster of voxels. 

We first calculated the ReHo using the data from the entire scan. <mark class="annotated-text">To calculate ReHoV for the Human Connectome Project data, scans were split into sliding time-windows, with each lasting 160 TRs (i.e., 1 min 55.2 sec) and 75% overlap between two successive windows. Then, ReHoV was defined as the standard deviation of ReHo across windows for each voxel. To confirm our results regarding ReHoV, we also tested different window lengths and overlaps</mark>. 

For the resting-state and continuous HCO task data, ReHoV was computed using sliding windows with 30 TR length (i.e., 60 sec) and 10 TR increment, as longer sliding window length will yield fewer …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4882585/"
                                       >PMC4882585</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … while unmedicated (  n   = 34), after 1 week (  n   = 29) and 6 weeks of treatment with risperidone (  n   = 24), as well as matched controls at baseline (  n   = 35) and after 6 weeks (  n   = 19). <mark class="annotated-text">After identifying 41 independent components (ICs) comprising resting-state networks, sliding window analysis was performed on IC timecourses using an optimal window size validated with linear support vector machines. </mark>Windowed correlation matrices were then clustered into three discrete connectivity states (a relatively sparsely connected state, a relatively abundantly connected state, and an intermediately connect…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5292583/"
                                       >PMC5292583</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … outlined with a small black box are indicated if   p   < 0.05. No significant differences were observed when week 1 patients were compared to baseline and week 6 patients. 
  

### dFNC Analysis 
  
<mark class="annotated-text">A sliding window technique was used to estimate dFNC where windowed segments of the component time courses were used to compute transient functional network connectivity patterns (Figure  ). Sliding window analysis was iteratively performed with window sizes of 30, 40, 44, 50, and 60 s. </mark>Window sizes were selected based on previous studies indicating functional connectivity can be robustly estimated using a window size between 30 and 60 s ( ,  ), as well as previous implementation of …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5292583/"
                                       >PMC5292583</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …spherical ROI in the medial primary motor cortex (Montreal Neurological Institute coordinates=−1, −8, 63), a region not previously linked to depression. 


### Sliding window correlation analysis 
  
<mark class="annotated-text">The sliding window analysis was performed using custom Python ( ) scripts. The data were split into 40 s Gaussian moving windows, staggered by one repetition time, created using a Gaussian kernel with a standard deviation of 8 s (see   for a detailed discussion of the sliding window methodology).</mark> This time period has been shown to be appropriate for characterizing dynamic functional connectivity  and provides a fine-grained picture of temporal changes in connectivity. For each window, correla…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5416685/"
                                       >PMC5416685</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …network graph. However, brain network dynamic changes occur at many temporal scales and other strategies have been used to take full advantage of the temporal information contained in the fcMRI data. <mark class="annotated-text">The sliding-window approach extracts the dynamic interactions between brain areas by using a time moving-window along the BOLD time-series (Hutchison et al.,  ; Allen et al.,  ; Leonardi and Van De Ville,  ). Following that strategy, we use an overlapping time-moving window   w[t]   of length 15 on the time series (15 time-points per window, corresponding to 45 s) to calculate Pearson's cross-correlations (R) (Figure  ):</mark> 

Where   i   denotes the sliding window position,   t   states the specific time point,   n  , being the sliding offset, indicates how many time points the window has shifted along the time axis, an…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6125351/"
                                       >PMC6125351</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …es in these measures between ASD and TD. 
  
Demographic details of the samples included in this study. 
  

### Dynamic FC 
  
We used the DynamicBC toolbox (Liao et al.,  ) for Dynamic FC creation. <mark class="annotated-text">We used a tapered sliding window length of 30 s in accordance with previous studies (Allen et al.,  ; Betzel et al.,  ) and the window was moved with a stride of 1. A set of sliding window correlation matrices was calculated for each subject. </mark>A Fisher Z-Transformation (to transform the Pearson's   r  , i.e., the correlation coefficient) was then applied to improve the normality of the distribution of the correlation matrices. Finally, the …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6367662/"
                                       >PMC6367662</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … 


## Methods 
  
Whole-brain resting-state functional MRI data were acquired on a 3 T whole-body clinical MRI scanner from 18 subjects clinically diagnosed with JME and 25 healthy control subjects. <mark class="annotated-text">2-min sliding-window approach was incorporated in the quantitative data-driven data analysis framework to assess both the dynamic and static functional connectivity in the resting brains. </mark>Two-sample   t  -tests were performed voxel-wise to detect the differences in functional connectivity metrics based on connectivity strength and density. 


## Results 
  
The static functional connec…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6412974/"
                                       >PMC6412974</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … 2) Connection Count Index (CCI) which is the number of voxel pairs involving the current voxel in question with the absolute CC ≥ 0.3. 


### Dynamic functional connectivity with SWATCH analysis 
  
<mark class="annotated-text">To characterize the time variations of the CCI and CSI maps we incorporated a 2 min sliding window into the quantitative data-driven analysis procedure. We computed CCI and CSI maps for every 2 min window (60 time-frames). The increment between the adjacent sliding windows was one frame, therefore, we obtained a time series of CCI and CSI maps with 235 time-frames for each Resting-state functional MRI dataset. </mark>Then, we computed the voxel-wise temporal averages of the 2-min sliding window CCI and CSI time series for each Resting-state functional MRI dataset for further statistical analysis. The pipeline of t…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6412974/"
                                       >PMC6412974</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …olation of outliers using a third-order spline fit to the clean parts of the time courses, and (3) low-pass filtering using a fifth-order Butterworth filter with a cutoff frequency of 0.15 Hz. 


### <mark class="annotated-text">Sliding window analysis</mark> 
  
The postprocessed dual regression time series were analyzed with a sliding window method to assess changes in between-network connectivity over time ( C). This analysis was performed in Matlab (R…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6462776/"
                                       >PMC6462776</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …third-order spline fit to the clean parts of the time courses, and (3) low-pass filtering using a fifth-order Butterworth filter with a cutoff frequency of 0.15 Hz. 


### Sliding window analysis 
  
<mark class="annotated-text">The postprocessed dual regression time series were analyzed with a sliding window method to assess changes in between-network connectivity over time ( C)</mark>. This analysis was performed in Matlab (R2016b) based on functions from GIFT ( ). A tapered window was created by convolving a rectangle of 22TR (66 s) with a Gaussian with sigma of 3TR and moved in …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6462776/"
                                       >PMC6462776</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">SWC (19 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … 41 independent components (ICs) comprising resting-state networks, sliding window analysis was performed on IC timecourses using an optimal window size validated with linear support vector machines. <mark class="annotated-text">Windowed correlation matrices were then clustered into three discrete connectivity states (a relatively sparsely connected state, a relatively abundantly connected state, and an intermediately connected state)</mark>. In unmedicated patients, static connectivity was increased between five pairs of ICs and decreased between two pairs of ICs when compared to controls, dynamic connectivity showed increased connectiv…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5292583/"
                                       >PMC5292583</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …y in differentiating control and patient ALFF-FC using the SVM classifier. This SVM classification was performed using the Statistics and Machine Learning Toolbox in MATLAB ( ). 


### Clustering 
  
<mark class="annotated-text">In order to characterize reoccurring patterns of connectivity across groups and time,   k  -means clustering was performed on the windowed correlation matrices for all subjects (Figure  B)</mark>. Clustering of a sub-sampled number of windows (i.e., windows with relative maxima of variance) for all groups and time points was carried out in order to estimate initial cluster centroids (cluster …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5292583/"
                                       >PMC5292583</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …were organized in nine groups: subcortical (SBC), cerebellum (CER), auditory (AUD), sensorimotor (SEN), visual (VIS), salience (SAL), default mode (DMN), executive control (ECN) and language (LAN). 

<mark class="annotated-text">A dFNC analysis was performed using the dynamic FNC Toolbox (dFNC v1.0a) available in the GIFT package. The dFNC sliding window size was set to 15 TRs (30 s) of a rectangular window convolved with a Gaussian (  σ   = 3 TRs). To find dFNC states we utilized k-means clustering.</mark> The number of clusters was selected by running k-means for values of k from 2 to 9 and using the elbow criteria. The clustering index results for different k-values used to determine the number of st…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6051314/"
                                       >PMC6051314</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …d the effect of covariates) can be estimated ( ,  ,  ). Bootstrapping with 1000 simulations was applied in order to ensure stability of estimations. 


### Dynamic functional network connectivity 
  
<mark class="annotated-text">Recent studies have shown that FNC has dynamic properties ( ). With regard to rs-fMRI data, dynamic behavior of FNC can be captured, for example, by applying a sliding window approach ( ). In this approach, FNC is first estimated within smaller portions of the time course (tapered windows with a size of 30 TRs = 60s). Then, these windowed FNC matrices are used to identify recurring patterns of whole-brain connectivity via   k  -means clustering, yielding distinct ‘states’ (see   for further details). </mark>The optimal number of clusters can be estimated based on objective criteria like the elbow criterion that reflects the ratio of within- to between-cluster distances while testing for different numbers…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6354288/"
                                       >PMC6354288</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …s all connections between RSN pairs was computed. Additionally, the mean SD for each network across all other networks was considered and each RSN-to-RSN connection was also tested separately. 


### <mark class="annotated-text">K-means clustering </mark>
  
To assess patterns of functional connectivity that reoccur over time across different participants, k-means clustering was applied to the windowed covariance matrices from all windows and all part…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6462776/"
                                       >PMC6462776</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …en RSN pairs was computed. Additionally, the mean SD for each network across all other networks was considered and each RSN-to-RSN connection was also tested separately. 


### K-means clustering 
  
<mark class="annotated-text">To assess patterns of functional connectivity that reoccur over time across different participants, k-means clustering was applied to the windowed covariance matrices from all windows and all participants using the Manhattan (L1) distance function ( D). The optimal number of clusters k was chosen based on the elbow criterion of the cluster validity index, computed as the ratio of within-cluster to between-cluster distance ( ).</mark> The clustering algorithm was repeated 500 times in Matlab with random initializations of cluster centroid positions to get a stable solution. In addition to using the optimal value for k, the analyse…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6462776/"
                                       >PMC6462776</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … of the sliding window correlations; (4) run clustering analysis on all subjects’ tvFNC data to identify reoccurring connectivity states and their derivatives patterns. 


### Clustering Analysis 
  
<mark class="annotated-text">In both methods dFNC and tvFNC, time-varying connectivity is captured by performing k-means clustering analysis, assigning all subjects’ temporal FNC data into a selected number of clusters representing distinct functional connectivity states. </mark>The clustering algorithm selection is based on previous connectivity studies that successfully applied k-means algorithm to identify reoccurring patterns of connectivity within and between subjects ac…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6611425/"
                                       >PMC6611425</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e produced for each timepoint (using MATLAB code made freely available by Shine et al. at  ) , since together, these two measures quantify both a node’s inter- modular and intra-modular connectivity. <mark class="annotated-text">For each subject, the joint patterns were then used to assign each timepoint to one of two clusters, using an unsupervised machine learning algorithm known as k-means clustering (setting   k   = 2)</mark> . To avoid the possibility of the algorithm becoming stuck in local minima, it was repeated 500 times with random re-initialisation of the two clusters’ initial points. This was performed individuall…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6787094/"
                                       >PMC6787094</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ion matrix was calculated. The sliding step was 1 sample, resulting in a total of 178 dynamic FNC matrices. 
  
The whole data processing steps. 
  

### Brain State Clustering and State Analysis 
  
<mark class="annotated-text">To examine the reoccurring FNC patterns in the temporal process, we used k-means clustering on all sliding-window FNC matrixes of all subjects by Manhattan distance because L  distance is more suitable for calculating similarity of high-dimensional data ( ).</mark> A maximum iteration of 150 was used on the time-varying FNC matrices to cluster brain states. Different number of clusters was calculated from 2 to 10. Through dividing within- by between-cluster dis…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6872968/"
                                       >PMC6872968</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …could be quantitatively estimated and compared between different groups. The original FCV matrices were then Fisher   z  -transformed and were statistically compared. 


###  k  -means Clustering 
  
<mark class="annotated-text">To identify dFNC patterns reoccurring across temporal matrices,   k  -means clustering was employed on all the dynamic correlation matrices to divide the dFNC into discrete clusters. </mark>The   k  -means algorithm aggregates information with similarities into “  k  ” groups, ensuring that the sum of squares within clusters is minimal. During the clustering estimation, the correlation d…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6902076/"
                                       >PMC6902076</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">others (5 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …ct was excluded from the analysis due to segmentation error in any single ROI. However, no difference was observed in the results between 26 of the MDD subjects and the 27 healthy control subjects. 

<mark class="annotated-text">The Hilbert transform [Glerean et al.,  ] was used for the assessment of dynamic functional connectivity. This approach allowed us to extract dFC with a higher temporal resolution given the short length of the resting‐state fMRI session.</mark> A recent study illustrated the use of this approach to detect the community structure, and compared them with well‐established methods such as independent component analysis [Ponce‐Alvarez et al.,  ]…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5074271/"
                                       >PMC5074271</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … temporal and spectral domains. (d) Temporal and spectral features are concatenated and (e) used as the feature vector for subject-level prediction. 
  

### Dynamic Conditional Correlation Model 
  
<mark class="annotated-text">To model dynamic functional connectivity between resting-state networks, we consider the Dynamic Conditional Correlation (DCC) model of [ ]</mark>. Let    Z    = (  Z  ,   Z  )′ be a random vector representing a pair of BOLD time series of any two ROIs in the brain at time   t  , for each of   i   = 1, …,   N   subjects. For simplicity, below w…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5761874/"
                                       >PMC5761874</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …us pallidus, amygdala, and hippocampus;  ), and 28 cerebellar regions from the SUIT atlas (Diedrichsen et al.,  ) for each participant in the study. 


#### Time-resolved functional connectivity. 
  
<mark class="annotated-text">To estimate time-resolved functional connectivity (Hutchison et al.,  ; Sakoğlu et al.,  ) between the 375 ROIs, we used the multiplication of temporal derivatives approach (MTD;  ; Shine et al.,  ). The MTD is computed by calculating the pointwise product of temporal derivative of pairwise time series ( ). To reduce the contamination of high-frequency noise in the time-resolved connectivity data, the MTD is averaged by calculating the mean value over a temporal window,   w  . Time-resolved functional connectivity was calculated between all 375 brain regions by using the MTD within a sliding temporal window of 15 time points (33 seconds at 2.2 s per window), which allowed for estimates of signals amplified at approximately 0.1 Hz. Individual functional connectivity matrices were then calculated within each temporal window, thus generating an unthresholded (i.e., signed and weighted) three-dimensional adjacency matrix (region × region × time) for each participant.</mark> The MTD for the pairwise interaction between region   i   and   j   is defined according to  : where   dt   is the first temporal derivative of the   i   or   j   time series at time   t  ,   σ   is …
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6145851/"
                                       >PMC6145851</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …instantaneous phase coherence, multiple temporal derivative, or dynamic conditional correlation approach (Glerean, Salmi, Lahnakoski, Jääskeläinen, & Sams,  ; Lindquist et al.,  ; Shine et al.,  ). 

<mark class="annotated-text">This study used dynamic conditional correlation (DCC) without moving average (Engle,  ; Lindquist et al.,  ), which is based on the multivariate generalized autoregressive conditional heteroscedasticity model (Engle,  ) that can be effective for estimating nonstationary temporal associations when the model of time series is well‐known</mark> (Lebo & Box‐Steffensmeier,  ). We used the code implemented by Lindquist et al. ( ) shared in  , which ran on MATLAB R2018b utilizing 120 high‐performance computing SLURM nodes. It first performs est…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7416060/"
                                       >PMC7416060</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ng functional magnetic resonance imaging to track spatiotemporal activity patterns at the whole brain level in lightly anesthetized mice, during both resting conditions and visual stimulation trials. <mark class="annotated-text">Our results provide evidence that quasiperiodic patterns (QPPs) are the most prominent component of mouse resting brain dynamics</mark>. These QPPs captured the temporal alignment of anticorrelation between the default mode (DMN)- and task-positive (TPN)-like networks, with global brain fluctuations, and activity in neuromodulatory n…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7869084/"
                                       >PMC7869084</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    … desired analysis, global signal regression (GSR) was performed. To determine spatiotemporal patterns, a brain mask was used to exclude ventricles. 


### Spatiotemporal Pattern Finding Algorithm 
  
<mark class="annotated-text">QPPs were determined using the spatiotemporal pattern finding algorithm described by  ). Briefly, the algorithm identifies BOLD spatiotemporal patterns</mark> (distribution and propagation of BOLD activity across different brain areas over the duration of a specific predefined time window) that recur frequently over the duration of the functional scans. Th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7869084/"
                                       >PMC7869084</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">CAP (3 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    … to allow for signal stabilization, and timeseries were concatenated within and across participants. 


### Coactivation pattern analysis 
  
A summary of the analytic steps is presented in Figure  . <mark class="annotated-text">Within REST1, a   k   means clustering analysis of coactivation patterns (CAPs) was conducted to identify “states” of resting brain activity after an initial PCA dimensionality reduction step. </mark>Silhouette scores were calculated to evaluate the optimal clustering solution, and   k   means clustering solutions employing between 4 and 18 clusters were explored. The   k   = 8 was selected, as th…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7268046/"
                                       >PMC7268046</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …selected, as this solution had the highest mean silhouette score (average silhouette scores shown in  ) and the lowest number of individuals for which the solution failed to fit the data (  n   = 1). <mark class="annotated-text">To confirm that these CAPs represent reliable states of resting brain activity rather than noise, the CAP analysis for   k   = 8 was run 100 more times on the REST1 data, and a PCA was run to verify congruence among the states. </mark>State data within   k   = 8 were then normalized (by subtracting the within‐state global average) and projected back into anatomic space for visualization (Figure  , raw unnormalized representation of…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7268046/"
                                       >PMC7268046</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …ivation with the precuneus superimposed with clusters of increased global signal representation (in blue) in iNPH compared with HCs 
  

#### Step 3: Temporal characterization of   DMN   dynamics 
  
<mark class="annotated-text">The fMRI volumes selected by precuneus activations were clustered into three states using the   k  ‐means algorithm. The z‐scored centroids of the clusters represent distinct precuneus co‐activation patterns (CAPs) with positive and negative cortical contributions (Liu & Duyn,  ; Liu, Zhang, Chang, & Duyn,  )</mark>. The relative temporal occurrence (defined as the number of fMRI volumes classified in one CAP‐cluster normalized by the number of volumes corresponding to precuneus activations), average duration (t…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7927299/"
                                       >PMC7927299</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …thm. The z‐scored centroids of the clusters represent distinct precuneus co‐activation patterns (CAPs) with positive and negative cortical contributions (Liu & Duyn,  ; Liu, Zhang, Chang, & Duyn,  ). <mark class="annotated-text">The relative temporal occurrence (defined as the number of fMRI volumes classified in one CAP‐cluster normalized by the number of volumes corresponding to precuneus activations), average duration (the average number of consecutive volumes classified in one CAP‐cluster) and frequency (the number of disjoint volume‐sets classified in one CAP‐cluster normalized by the recording time) of the three CAPs were computed for each subject.</mark> The choice of the number of clusters (  k   = 3) was based on a consensus clustering assessment from data bootstrapping (Bolton et al.,  ; Monti, Tamayo, Mesirov, & Golub,  ) and ensuring a minimum c…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7927299/"
                                       >PMC7927299</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …e volumes and mask were later used with FSL randomise. 

The volumes were reshaped and concatenated, and the resulting data matrix was transferred to the R environment (Bengtsson,  ; R Core Team,  ). <mark class="annotated-text">We applied clustering to all the BOLD fMRI volumes acquired from the 55 participants that had survived censoring.</mark> As mentioned in the introduction, the volumes are described by their voxels' signal amplitudes, and their relation to other volumes has to be defined via a suitable function. Here, individual volumes…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8213933/"
                                       >PMC8213933</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …r‐package function hclust (method = "ward.D2") (Müllner,  ). The results from 30 to 2 clusters (in total, 58 clusters or CAPs) were evaluated. We aggregated the fMRI volumes assigned to each cluster. <mark class="annotated-text">The mean image of such a cluster's volumes provided an overall view of the resulting CAP and was then normalized by the standard error (within‐cluster and across fMRI volumes) to generate   z  ‐statistic maps, which quantify the degree of significance to which the CAP map values for each voxel deviate from zero (Liu et al.,  ,  ). </mark>


### Group comparison   t   tests 
  
The 11,930 RS‐fMRI volumes concatenated into one file were used as input for FSL's randomise (Anderson & Robinson,  ; Winkler et al.,  ). The voxel‐wise differe…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8213933/"
                                       >PMC8213933</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
    <details >
        <summary class="label-display">HMM (2 docs)</summary>
        
        <p><b>Example annotations:</b></p>
        <div class="annotation-set">
            
            <div class="annotation">
                <div class="context">
                    …t  ] 
  

## DYNAMIC FUNCTIONAL CONNECTIVITY IN REAL DATA 
  
Having demonstrated the utility of the NPC approach to relate FC to behavior in a synthetic scenario where the estimation was very noisy, <mark class="annotated-text">we next evaluated it using real data by applying the Hidden Markov model (HMM) to resting state fMRI data from the Human Connectome Project (HCP). The HMM assumes that the data can be described using a finite number of states. </mark>Each state is represented using a probability distribution, which in this case is chosen to be a Gaussian distribution (Vidaurre, Smith, & Woolrich,  ); that is, each state is described by a character…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6492297/"
                                       >PMC6492297</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
            <div class="annotation">
                <div class="context">
                    …pocampus, thalamus, as well caudate, putamen, and pallidum regions that they are heavily connected to (see   for the independent components grouped into the 7 ICNs). 


### Hidden markov modeling 
  
<mark class="annotated-text">We applied a hidden Markov model (HMM) to the minimally preprocessed region-wise BOLD time-series, resulting in   K   discrete states of whole-brain connectivity, each associated with state-specific timecourse. The HMM assumes that time series data can be described using a finite sequence of a hidden number of states. Each state and its associated time series comprise a unique connectivity pattern that temporally re-occurs over time. Using the HMM-MAR (multivariate autoregressive) toolbox ( ), discrete connectome states were inferred from region-wise BOLD time-series temporally concatenated across all subjects</mark>. Whereas the states are estimated at the grouplevel, each individual has a subject-specific state time course, indicating when a given state is active. For a given K, the best fitting model correspon…
                </div>
                <div class="annotation-footer">
                    <div class="pcmid"><a target="_blank"
                                          href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9223440/"
                                       >PMC9223440</a></div>
                    <div class="annotator-name">mtorabi59</div>
                </div>
            </div>
            
        </div>
        
    </details>
    
</div>
"""
displays.HTMLDisplay(text)
```