### Sources

* Common peaks between replicates for H3K27ac ChIP-seq experiments on a few well-characterized cell lines were obtained from ENCODE.
     * [GM12878](https://www.encodeproject.org/experiments/ENCSR000AKC/) (lymphoblastoid cell line)
     * [H1-hESC](https://www.encodeproject.org/experiments/ENCSR000ANP/) (human embryonic stem cell line)
     * [HUVEC](https://www.encodeproject.org/experiments/ENCSR000ALB/) (human umbilical vein endothelial cell line)
     * [K562](https://www.encodeproject.org/experiments/ENCSR000AKP/) (myelogenous leukemia cell line)
     * [NHEK](https://www.encodeproject.org/experiments/ENCSR000ALK/) (normal human epidermal keratinocytes cell line)

* Top 25000 peaks were picked based on the lowest q-values.

* [Previously published](https://doi.org/10.1101/gr.121541.111) cell-specific open chromatin regions were [downloaded](http://fureylab.web.unc.edu/datasets/open-chromatin/) and converted from NCBI36 to hg19 using UCSC liftOver.

* Since GREAT requires that the background set be a superset of the test set, OCR intervals overlapping peaks were removed and then the remaining ones were concatenated with the peaks to generate the background set.

### Results
**All peaks as test set, whole genome as background set**
<details><summary>GM12878</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/1.all.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>non-membrane spanning protein tyrosine kinase activity</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.74168e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.88895e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4650&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02292e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>immune response-activating signal transduction</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.85196e-289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86091e-286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3232&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.51127e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1950&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.90%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>immune response-activating cell surface receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21161e-214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.61406e-212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1345&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.67%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;258&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.48072e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1957&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>antigen receptor-mediated signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95541e-141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.55182e-139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1007&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1443&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;442&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35264e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1927&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>T cell costimulation</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18399e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.32662e-128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;706&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;810&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.93826e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1782&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>lymphocyte costimulation</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.02955e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.19886e-128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;708&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;794&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52708e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1796&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>interferon-gamma-mediated signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.45715e-108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.71651e-106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6097&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;704&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;675&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.57969e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1989&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc-gamma receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47845e-106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02900e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;640&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.42335e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1909&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc receptor mediated stimulatory signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.71596e-106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85325e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;940&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;640&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.42335e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1909&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc-gamma receptor signaling pathway involved in phagocytosis</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.01776e-106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72373e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2361&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;939&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;651&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.37683e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1899&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of type I interferon production</td>
    <td nowrap="nowrap" align="right">&nbsp;232&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.69945e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.56475e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0650&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;803&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.91417e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.72%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular response to interferon-gamma</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12207e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.76197e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;830&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;538&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03849e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1994&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of B cell proliferation</td>
    <td nowrap="nowrap" align="right">&nbsp;265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.20827e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65790e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0040&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;774&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;851&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.19529e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1867&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of defense response to virus</td>
    <td nowrap="nowrap" align="right">&nbsp;266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.48436e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76003e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2549&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;587&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;651&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.37683e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1899&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.51229e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.08508e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0315&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;724&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00918e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleotide-binding domain, leucine rich repeat containing receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55511e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.84005e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2730&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;555&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;510&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.94601e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>apoptotic mitochondrial changes</td>
    <td nowrap="nowrap" align="right">&nbsp;283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63689e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.72761e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2815&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;540&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;740&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52614e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2094&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>intrinsic apoptotic signaling pathway in response to DNA damage</td>
    <td nowrap="nowrap" align="right">&nbsp;328&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.12940e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90582e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2896&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;480&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;699&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09358e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>negative regulation of type I interferon production</td>
    <td nowrap="nowrap" align="right">&nbsp;333&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77514e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.56532e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8542&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;825&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.10045e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular response to topologically incorrect protein</td>
    <td nowrap="nowrap" align="right">&nbsp;345&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.70781e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12201e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;625&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;273&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.94409e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2472&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>peptidyl-lysine methylation</td>
    <td nowrap="nowrap" align="right">&nbsp;354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35652e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.94974e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;818&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06324e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>PcG protein complex</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.51570e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.39125e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1608&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;481&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17742e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MLL1 complex</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.59775e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.67028e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1882&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31601e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.27669e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.01880e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2953&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.23617e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal B cell differentiation</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0867&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 9.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.26553e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1804&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;407&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased mature B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79404e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2011&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;232&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen white pulp morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1249&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3486&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28903e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1726&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;292&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;314&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.04%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal mature B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3901&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57812e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1741&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;284&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal immature B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2854&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.02144e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1841&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal B cell activation</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05469e-310&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54649e-308&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3665&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2436&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.76711e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1916&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased immunoglobulin level</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74908e-308&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51804e-306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0301&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3377&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43339e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1661&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal B cell proliferation</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52474e-306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15588e-304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4069&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43753e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1929&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased IgG level</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95805e-285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.54161e-283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60071e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1734&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;245&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased immature B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.77419e-264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.72758e-262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2731&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2252&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.58308e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal lymph node size</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.28904e-255&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.11381e-253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2830&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.82958e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1310&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal follicular B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.51986e-253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.15581e-251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.81339e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal marginal zone B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91132e-227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.81120e-225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1479&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.35971e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1984&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal pre-B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.17622e-222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07606e-220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1818&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00685e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1957&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>enlarged lymph nodes</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.21093e-222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02668e-220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;345&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21812e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen marginal zone morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.29852e-218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.93573e-216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4072&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87793e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1826&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased B cell proliferation</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30462e-208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18736e-206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4009&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1597&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.63896e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2252&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.72%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen B cell follicle morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23783e-207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11377e-205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2092&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1887&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.82835e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1840&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>increased mature B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.56948e-198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.51469e-196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.50123e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1455&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.90%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased pre-B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.55350e-190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.29496e-188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1532&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.67%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66172e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1909&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Disease Ontology</td>
    <td>Burkitt's lymphoma</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57989e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.49610e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;431&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.35255e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of DDB1</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45063e-132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.09708e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1503&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86726e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2504&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of STAT6</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67324e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.28295e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7361&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;725&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.48580e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2449&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HLA-C</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.18754e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.37010e-112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5866&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.83906e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MYD88</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26051e-110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.98042e-109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0431&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.81358e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59753e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.26342e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2983&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;830&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.96158e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2510&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CASP1</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.36142e-97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50907e-95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1997&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;888&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.93803e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1452&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of BMI1</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55185e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.48759e-95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4794&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;692&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.00200e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2294&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDX5</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.75304e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.34339e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;676&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12676e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PTPRC</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.00597e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.34812e-87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3871&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;680&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.32926e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2424&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of APEX1</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.11030e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49619e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;683&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53450e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PPP2R5E</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.51252e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29816e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3279&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;654&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.77497e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10150e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.09428e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5762&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;535&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13648e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HDAC1</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.87422e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.09098e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.4231&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;334&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.35694e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of TNFRSF1B</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.93842e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.04743e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6495&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;495&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;273&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.91141e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.68536e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.24891e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2444&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;677&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76720e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2513&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CBFB</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55482e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70232e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1996&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;349&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49256e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ITGAL</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20966e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35881e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2014&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;668&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;257&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03258e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1692&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CD53</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11951e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.24885e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4798&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.02693e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAF1</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.43982e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.40884e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1048&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;727&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30397e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2492&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of INPP5D</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.13601e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.89563e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9401&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;376&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12823e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">PANTHER Pathway</td>
    <td>Apoptosis signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.72358e-124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.61985e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2915&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1047&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07677e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2489&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>B cell activation</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.96989e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.29712e-97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;806&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.40316e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>PDGFR-beta signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.24165e-188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.74632e-185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2665&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1618&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.96776e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2027&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Signaling by the B Cell Receptor (BCR)</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.62168e-172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17516e-169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2934&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1443&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01990e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2507&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Antigen Activates B Cell Receptor Leading to Generation of Second Messengers</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76852e-135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.89074e-133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1322&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;661&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.54991e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Costimulation by the CD28 family</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.65593e-134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06655e-131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8998&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;735&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.12216e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Class I PI3K signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.29690e-133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.08988e-131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7904&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;777&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14138e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>EPO signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97289e-126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.89358e-124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9693&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;668&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;309&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58183e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TCR signaling in na&amp;amp;#xef;ve CD4+ T cells</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.54282e-126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.63653e-124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;834&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98905e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2027&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL2-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.34001e-123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12080e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5443&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;841&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.86680e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Interferon Signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46867e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61553e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.72211e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Signaling by SCF-KIT</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.84603e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.56911e-115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2782&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;996&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.53350e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2443&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>B cell receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00691e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.86079e-115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3099&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;965&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.37923e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc gamma R-mediated phagocytosis</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31432e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08432e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1076&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13839e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1690&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Signaling events mediated by Hepatocyte Growth Factor Receptor (c-Met)</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.11462e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.19488e-112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1643&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1086&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80603e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>BCR signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94926e-107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22525e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2776&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;914&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.94697e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2415&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TCR signaling in na&amp;amp;#xef;ve CD8+ T cells</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.61059e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07216e-102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5788&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31853e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Interferon gamma signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28971e-102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.09340e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5861&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;681&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20469e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>CXCR4-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26982e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.70464e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0386&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.18483e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1507&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Members of the BCR signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24636e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.87568e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4517&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;730&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18919e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MAPKinase Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34904e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06922e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0416&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.57125e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IFN-gamma pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40977e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.94031e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4725&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;643&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.12%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;346&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.90489e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1994&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes up-regulated in Daudi cells (B lymphocytes) stably expressing CD5 [GeneID=921] off a plasmid vector.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4469&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98247e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes with promoters occupied by PML-RARA fusion 
[GeneID=5371,5914] protein in acute promyelocytic leukemia(APL) cells 
NB4 and two APL primary blasts, based on  Chip-seq data.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2479&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4341&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.57%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16575e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;407&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;423&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.84%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Gene up-regulated by CD40 [GeneID=958] signaling in Ramos cells (EBV negative Burkitt lymphoma).</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2928&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1688&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;311&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31370e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic vs non-metastatic HNSCC (head and neck squamous cell carcinoma) samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20859e-293&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.38807e-291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5569&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1992&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.86986e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1588&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>The 'MLL signature 1': genes up-regulated in pediatric AML 
(acute myeloid leukemia) with rearranged MLL [GeneID=4297] compared to 
all AML cases with the intact gene.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.08990e-292&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57588e-289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1364&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2842&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.24326e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1345&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;332&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>The 'MLL signature 2': genes up-regulated in pediatric AML 
(acute myeloid leukemia) with rearranged MLL [GeneID=4297] compared to 
the AML cases with intact MLL and NPM1 [GeneID=4869].</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14731e-291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.75682e-289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0701&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3053&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.05150e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1336&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;406&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Up-regulated genes that best disciminate plasmablastic plasmacytoma from plasmacytic plasmacytoma tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.84399e-290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53488e-287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1708&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2724&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.60141e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.47543e-277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.87725e-275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1348&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2706&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40750e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;382&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes enriched at every T lymphocyte differentiation stage compared to the early passage fetal thymic stromal cultures (TSC).</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65133e-225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98396e-223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2269&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33551e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in DO11.10 cells (hybridoma) by expression of
 transciptionally activating form of HDAC7 [GeneID=51564] and 
down-regulated by its transcriptionally repressing form.</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53409e-212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61271e-210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1912&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.20477e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2009&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.67128e-186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.47954e-184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2478&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1628&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.12204e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1860&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.99%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Set 'Myc targets1': targets of c-Myc [GeneID=4609] identified by
 ChIP on chip in cultured cell lines, focusing on E-box-containing 
genes; high affinity bound subset</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.64768e-173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.71707e-171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1699&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;472&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64910e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in BJAB cells (B-lymphoma) after leucine [PubChem=857] deprivation.</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.62747e-164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.02783e-162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2861&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1387&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.81267e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1551&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated genes in the B lymphocyte developmental 
signature, based on expression profiling of lymphomas from the Emu-myc 
transgenic mice: the Pre-BI stage.</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.69781e-157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.83349e-155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6096&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1029&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;396&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.96707e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in BJUB cells (B-lymphoma) in response to  rapamycin [PubChem=6610346] treatment.</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49374e-152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.66337e-151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1698&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;405&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.62661e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cluster 3: genes up-regulated in B2264-19/3 cells (primary B 
lymphocytes) within 60-180 min after activation of LMP1 (an oncogene 
encoded by Epstein-Barr virus, EBV).</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67067e-152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06041e-150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;863&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;352&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35011e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Clusters 1 and 2: genes up-regulated in B2264-19/3 cells 
(primary B lymphocytes) within 30-60 min after activation of LMP1 (an 
oncogene encoded by Epstein-Barr virus, EBV).</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.07173e-145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.46192e-143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8480&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;819&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;385&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36617e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2415&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Up-regulated genes in the B lymphocyte developmental signature 
based on expression profiling of lymphomas from the Emu-myc transgenic 
mice: the immature B stage.</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.97180e-143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15502e-141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0006&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;745&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;511&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.80110e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2362&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IRF4 [GeneID=3662] target genes up-regulated in plasmacytoid dendritic cells compared to monocytes.</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34796e-123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.96651e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5656&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;834&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;313&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35946e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic breast cancer tumors having  
type 2 amplification in the 20q13 region; involves MYBL2, STK6 and 
ZNF217 [GeneID=4605;6790;7764]</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61655e-123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.06241e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.24%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90293e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2527&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>SH2D</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.79840e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.59637e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;823&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59661e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.74993e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.60924e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;310&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.93754e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9661&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1875&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;371&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.67576e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1956&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of B cells from influenza 
vaccinee at day 7 post-vaccination versus plasmacytoid dendritic cells 
(pDC) at day 7 post-vaccination.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.37806e-305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.09105e-302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2088&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2756&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.61325e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.24363e-275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.70178e-272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1902&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47169e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2282&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of B cells versus plasmacytoid dendritic cells (pDC) .</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19184e-274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.69105e-272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2752&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52250e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.56706e-268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.65462e-265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7582&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1595&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;236&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80534e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2092&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of unstimulated peripheral 
blood mononuclear cells (PBMC) 3 days after stimulation with YF17D 
vaccine versus PBMC 21 days after the stimulation.</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.31237e-266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00944e-263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3551&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;330&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56256e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2055&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of healthy CD4 [GeneID=920] T cells versus healthy CD19 [GeneID=920] B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27343e-248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.47465e-246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0624&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2635&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.55190e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control polymorphonuclear 
leukocytes (PMN) at 12 h versus PMN treated with F. tularensis vaccine 
at 24 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18825e-247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.61195e-245&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79247e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2346&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.69481e-239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.84121e-237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2750&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1098&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.09281e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control polymorphonuclear 
leukocytes (PMN) at 12 h versus PMN treated with F. tularensis vaccine 
at 48 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18787e-237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.08883e-235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2531&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2064&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.19575e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control thymocytes versus thymocytes treated with dexamethasone [PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54693e-225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68604e-223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2517&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1966&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02216e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of memory CD4 [GeneID=920] T cells versus B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.23344e-219&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.14656e-217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.69807e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43729e-216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11170e-214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4461&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1599&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08673e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with 1 ng/ml LPS 
(TLR4 agonist).</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18834e-214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62123e-212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2349&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;670&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.34555e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1713&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of unstimulated dendritic cells (DC) versus 1 day DC stimulated with LPS (TLR4 agonist).</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44528e-214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84033e-212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1884&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1990&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86184e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of IgD+ peripheral blood B cells versus dark zone germincal center B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.79903e-214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16976e-211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2853&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1807&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.79902e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of systemic lupus 
erythematosus CD4 [GeneID=920] T cells versus systemic lupus 
erythematosus B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25900e-212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.66159e-210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0097&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18277e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1961&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of control polymorphonuclear 
leukocytes (PMN) at 0 h versus PMN treated with F. tularensis vaccine at
 6 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05418e-209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11860e-207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2029&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.48040e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 ng/ml LPS (TLR4 agonist) versus monocytes treated with vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.16075e-206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.18265e-204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4818&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1481&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79247e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2346&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of naive B cells versus unstimulated neutrophils.</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.66618e-194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.33448e-192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1970&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1787&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;770&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.98187e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1574&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 57,369 genomic regions picked 14,308 genes (79%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Disease Ontology</i> has 2,235 terms covering 7,886 (44%) of all 18,041 genes.</td>
    <td>2,235 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>PANTHER Pathway</i> has 152 terms covering 2,197 (12%) of all 18,041 genes.</td>
    <td>152 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>H1-hESC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/2.all.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50399e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.28067e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0640&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;688&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.00%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.90973e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2882&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, nonsense-mediated decay</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.34619e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24032e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2327&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;462&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20902e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2742&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.86897e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05900e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1965&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;470&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74148e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2947&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein localization to endoplasmic reticulum</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24926e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.55732e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0573&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;543&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.32644e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2869&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.89%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>establishment of protein localization to endoplasmic reticulum</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.32514e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79289e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.37440e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2950&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral gene expression</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88697e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.14849e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.03%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.87826e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2769&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational termination</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62475e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45831e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.99%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.67900e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2889&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.19731e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.14245e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1593&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;424&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.55069e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.80975e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.96402e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4484&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;325&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.76985e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2875&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.27159e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.33805e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1401&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;429&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.19471e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2945&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10682e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39219e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1088&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;340&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.49468e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2252&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65485e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.06841e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0907&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11997e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA poly(A) tail shortening</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.10798e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73633e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3368&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;610&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.69467e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>negative regulation of gene expression, epigenetic</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09303e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.10476e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;595&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31713e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein export from nucleus</td>
    <td nowrap="nowrap" align="right">&nbsp;286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.71245e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35517e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3069&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;637&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14062e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>peptidyl-lysine methylation</td>
    <td nowrap="nowrap" align="right">&nbsp;314&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33243e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.75494e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0621&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;595&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31713e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>chromatin silencing</td>
    <td nowrap="nowrap" align="right">&nbsp;321&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18883e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03711e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1557&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;705&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.43849e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>cytosolic ribosome</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17034e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79610e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0314&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.36474e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2636&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic mRNA processing body</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57243e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.14402e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1061&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33274e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2028&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.37874e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.78673e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.40351e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3009&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytosolic large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.15361e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70742e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3252&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24379e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2936&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.09651e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.47859e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2378&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.71976e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MLL1 complex</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13455e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43262e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.82937e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal DNA repair</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02377e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.00687e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0062&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;348&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.61422e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2013&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of DDB1</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.94633e-125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53908e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3025&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1033&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.00%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30183e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2526&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.47051e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.40953e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;979&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16790e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2966&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30886e-119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86294e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1875&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31621e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2773&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;279&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.04%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.87491e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05415e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4384&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;861&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.17288e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2760&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HDAC1</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22731e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.90212e-102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1030&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.99%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86407e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2876&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18180e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.41046e-97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5852&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;652&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.88465e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2910&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.03%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of BUB3</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.77936e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30541e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0046&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1089&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.12521e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2663&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NME2</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.84354e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.72132e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;646&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.32671e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AATF</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.75946e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62390e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1656&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73126e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2993&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.25088e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.29177e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5827&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;560&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.56235e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3081&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.28917e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73729e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2895&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;701&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.31713e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2947&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PSMC1</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65077e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.08485e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2531&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;719&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.81949e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2775&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.97570e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13175e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1519&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.79868e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3054&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DAP3</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49334e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.98534e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1644&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;759&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.43586e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2913&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ANP32B</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45024e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64265e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;785&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.12037e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.45164e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.18806e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6478&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;500&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.88392e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAB1A</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20495e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.57257e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.59078e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2297&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RPA2</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60780e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.98492e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;805&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.83982e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2633&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of APEX1</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00783e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.29748e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5973&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;459&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.10461e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3072&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CTBP1</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30586e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64667e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1582&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;666&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30256e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2873&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">PANTHER Pathway</td>
    <td>General transcription regulation</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.90388e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49078e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0019&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.52127e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Genes involved in Metabolism of mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.85693e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.41115e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0911&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;796&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.55628e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2692&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.51%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Translation</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.52671e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31175e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0936&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;554&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52732e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2557&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Influenza Life Cycle</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.58612e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.16342e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0995&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;508&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.44993e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2800&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Nonsense Mediated Decay Enhanced by the Exon Junction Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28642e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.39616e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3370&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;392&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.02574e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2692&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Peptide chain elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.58388e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.68454e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.23217e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2725&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.93099e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.83613e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1415&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;421&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30252e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2706&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Influenza Viral RNA Transcription and Replication</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.40163e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.92239e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2496&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05565e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2668&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.72%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Processing of Capped Intron-Containing Pre-mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49450e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97274e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0416&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;442&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.43758e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2991&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in 3' -UTR-mediated translational regulation</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75397e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10477e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1524&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;389&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.13%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.75797e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2687&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18774e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30652e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2848&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;334&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.48676e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2939&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I Promoter Opening</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70190e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24806e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.3094&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30129e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2068&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Unfolded Protein Response</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10938e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.32189e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0664&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;269&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.91221e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2500&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Activation of Chaperone Genes by XBP1(S)</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.40891e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.31360e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3908&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56049e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Deposition of New CENPA-containing Nucleosomes at the Centromere</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31307e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.25203e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62868e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2334&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Packaging Of Telomere Ends</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.17314e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44962e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8089&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;231&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62645e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2086&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Telomere Maintenance</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.30285e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66661e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0496&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.82763e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.43278e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92378e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.75486e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1914&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Meiotic Recombination</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.31272e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11015e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63607e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2059&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Downregulation of SMAD2/3:SMAD4 transcriptional activity</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.23340e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.76017e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0899&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.89187e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Elongation arrest and recovery</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.40507e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76106e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7541&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44523e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2760&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.40457e-239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48170e-235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3914&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1820&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59689e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;371&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.71%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.10689e-154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.43591e-151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4973&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1086&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68573e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1880&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;273&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.00%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated by induction of exogenous BRCA1 in EcR-293 cells</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.20095e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.43538e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3313&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;619&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;313&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92415e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1971&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cluster 2: genes up-regulated in B493-6 cells (B lymphocytes) by
 serum alone or in combination with MYC [GeneID=4609] but not by MYC 
alone.</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.66237e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.80896e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7454&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;457&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;669&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.86035e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1664&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01554e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13876e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;462&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.85065e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1280&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50039e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62817e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3005&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;598&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;653&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.14048e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1500&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes co-regulated in uterus during a time course response to progesterone [PubChem=5994]: SOM cluster 17.</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.50080e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.33382e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1079&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;658&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.09228e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2397&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated by 2-methoxyestradiol (2ME2) [PubChem=1573]
 in the MM.1S cell line (multiple myeloma) sensitive to dexamethasone 
[PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31067e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52563e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0577&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;484&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;400&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.03392e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes encoding mRNA transcripts specifically bound by DCP2 [GeneID=167227].</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52517e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07527e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6352&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;271&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.68750e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2730&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in head and neck tumor samples which clustered around known hypoxia genes.</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.54647e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34048e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;379&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;453&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.52748e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Protein biosynthesis, transport or catabolism genes up-regulated
 in hyperploid multiple myeloma (MM) compared to the non-hyperploid MM 
samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34488e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.81007e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6944&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;589&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22557e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2439&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated by 2-methoxyestradiol (2ME2) [PubChem=1573] 
in the MM.1S cell line (multiple myeloma) sensitive to dexamethasone 
[PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.46905e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76903e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3866&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;508&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.12476e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2658&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in samples from B-CLL (B-cell chronic lymphocytic leukemia) with the immunoglobulin heavy chain VH3-21 gene.</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.74915e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.80306e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8099&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;617&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11509e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2586&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes within amplicon 16q24 identified in a copy number alterations study of 191 breast tumor samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54067e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.35530e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2671&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;770&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10169e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Up-regulated in hepatocytes upon expression of NOS2 [GeneID=4843].</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.21386e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43766e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;449&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.11160e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2421&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in Caco-2 cells (intestinal epithelium) after coculture with the probiotic bacteria L. casei for 6h.</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54032e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.21273e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0780&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;530&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26047e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2479&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated by forced expression of APC [GeneID=324] in the APC-deficient SW480  cell line (colon cancer).</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53563e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17368e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;856&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.93352e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1644&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in 786-0 cells (renal carcinoma, RCC) by the loss of VHL [GeneID=7428] and in response to hypoxia.</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.83220e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.49893e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;903&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62794e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2386&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in HDMEC cells (microvascular endothelium): proliferating vs quiescent cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;146&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74039e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.01005e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;309&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;750&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.23306e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Top genes up-regulated in liver tissue from mice with knockout of ZMPSTE24 [GeneID=10269].</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.29292e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.41129e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1922&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;578&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.06524e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Predicted Promoter Motifs</td>
    <td>Motif GGAANCGGAANY (no known TF)</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84674e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26194e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;320&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88650e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2926&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Motif KRCTCNNNNMANAGC (no known TF)</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08103e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54613e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0480&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27028e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2017&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.53%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.52125e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08058e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3676&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20629e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2936&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.42631e-174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72425e-171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5519&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;715&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06383e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2378&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.20272e-142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.01360e-139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7859&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;828&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52027e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26994e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.08527e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1716&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;754&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.55736e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.0818&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with acute influenza infection versus PBMC 
from patients with acute E. coli infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.20995e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.31000e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1010&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;552&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;973&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.92043e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 34,445 genomic regions picked 13,683 genes (76%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>PANTHER Pathway</i> has 152 terms covering 2,197 (12%) of all 18,041 genes.</td>
    <td>152 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Predicted Promoter Motifs</i> has 615 terms covering 11,991 (66%) of all 18,041 genes.</td>
    <td>615 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>HUVEC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/3.all.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>regulation of transcription from RNA polymerase II promoter in response to stress</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.07849e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43090e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2046&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;401&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;762&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.83566e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2254&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;355&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73834e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.11219e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0321&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;380&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04954e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of transcription from RNA polymerase II promoter in response to hypoxia</td>
    <td nowrap="nowrap" align="right">&nbsp;442&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.12154e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.37304e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0835&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;323&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;731&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22727e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>release of cytochrome c from mitochondria</td>
    <td nowrap="nowrap" align="right">&nbsp;532&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.61166e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.12514e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.84293e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal fibroblast migration</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24761e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.82015e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;293&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.63488e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased fibroblast cell migration</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12688e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.04104e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;567&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15059e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>spontaneous skin ulceration</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.54173e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46060e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2808&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;401&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;397&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.21507e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2279&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.41865e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00961e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0532&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;591&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.28803e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2498&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.18585e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.32228e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.03791e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2314&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of GPX4</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.19668e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.68040e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3456&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;229&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60562e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2361&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of USP5</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.83280e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.19371e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1863&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33969e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2352&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PPP2R4</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.28608e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.39541e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0780&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97801e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Genes involved in Signaling by TGF-beta Receptor Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.50169e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71645e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2597&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;732&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31936e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2384&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcriptional activity of SMAD2/SMAD3:SMAD4 heterotrimer</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10780e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.08900e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;507&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65419e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in TGF-beta receptor signaling activates SMADs</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97479e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86194e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4509&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;371&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35745e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Keratinocyte Differentiation</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43260e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26069e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;555&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63679e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2034&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Integrin Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.83333e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.52941e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2016&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;431&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.51512e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1913&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Downregulation of TGF-beta receptor signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.80471e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.64327e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.62585e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TNF receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.31417e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.78438e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;470&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.72014e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>HIV-I Nef: negative effector of Fas and TNF</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07665e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.73727e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;473&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.85673e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Sema4D in semaphorin signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.38427e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80851e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5423&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;281&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;311&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.48533e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>VEGF, Hypoxia, and Angiogenesis</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.20753e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.46789e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1665&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;343&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;311&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.48533e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>NFkB activation by Nontypeable Hemophilus influenzae</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67465e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79814e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0425&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;331&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69997e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Regulation of Hypoxia-inducible Factor (HIF) by Oxygen</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.54039e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.69823e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69997e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ATM Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.41131e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.89357e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;301&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.34011e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Smooth Muscle Contraction</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01242e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.76976e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0055&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69997e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Lysosome Vesicle Biogenesis</td>
    <td nowrap="nowrap" align="right">&nbsp;230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.55061e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18557e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0700&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35745e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cell Cycle: G2/M Checkpoint</td>
    <td nowrap="nowrap" align="right">&nbsp;234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21792e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.87031e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0880&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35745e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing - Minor Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47297e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.36484e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1427&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43816e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1994&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes up-regulated upon overexpression of PARVB [GeneID=29780] in MDA-MB-231 cells (breast cancer) cultured in 3D Matrigel only.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0063&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4035&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03389e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2054&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.81%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22080e-223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.15907e-221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0321&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2458&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.49%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92562e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;380&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.65%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in BEC (blood endothelial cells) compared to LEC (lymphatic endothelial cells).</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.89596e-203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10189e-200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0687&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67264e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1972&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 480 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.24927e-189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.21501e-187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1746&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.96791e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2053&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression positively correlated with sensitivity of breast cancer cell lines to dasatinib [PubChem=3062316].</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.50969e-137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.72298e-135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1384&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;405&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82267e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2279&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in five primary endothelial cell types (lung, aortic, iliac, dermal, and colon) by TNF [GeneID=7124].</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.43045e-133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.38297e-131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0750&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1396&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;231&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11177e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24694e-110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.59294e-109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2777&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.16835e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in DU-145 cells (prostate cancer) in the 
absence and presence of a dominant negative form of AKT1 [GeneID=207] 
upon exposure to HGF [GeneID=3082] for 48 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.82463e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33262e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0711&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;500&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;921&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14136e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes specific to BEC (blood endothelium cells) repressed in BEC by expression of PROX1 [GeneID=5629] off adenovirus vector.</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.84880e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07678e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2049&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;877&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.69022e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in macrophages by aerolysin-related cytotoxic enterotoxin (Act) from Aeromonas hydrophila.</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07479e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.05010e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1828&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;851&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;618&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.06085e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1853&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 120 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00439e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.37878e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3508&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;721&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;520&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.05435e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 40 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11155e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.70225e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;679&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.24%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;552&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.73732e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.42626e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.92421e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1862&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;524&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40567e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in five primary endothelial cell types (lung, aortic, iliac, dermal, and colon) by IFNG [GeneID=3458].</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14155e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.86112e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1077&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;871&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.10179e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2448&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes known to be induced by hypoxia</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.16769e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49863e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0085&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;561&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.16215e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1972&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Top genes up-regulated in liver tissue from mice with knockout of ZMPSTE24 [GeneID=10269].</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67987e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.67032e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7362&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;488&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;846&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.69159e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in brain tumors induced by retroviral delivery of PDGFB [GeneID=5155].</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.86270e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00730e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2998&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;648&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20631e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes regulated in MCF7 cells (breast cancer) by expression of 
full-length and truncated (611-CTF) forms of ERBB2 [GeneID=2064] at both
 15 h and 60 h time points.</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17279e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.75893e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1685&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;703&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;670&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28181e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Delayed early genes (DEG) which are coordinately down-regulated in multiple epithelial tumor types.</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.05131e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.67104e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6612&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.44355e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in head and neck tumor samples which clustered around known hypoxia genes.</td>
    <td nowrap="nowrap" align="right">&nbsp;222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.38054e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.15321e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1095&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;599&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;343&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.28112e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2311&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Predicted Promoter Motifs</td>
    <td>Motif ATGCCCATATATGGWNNT matches SRF: serum response factor (c-fos serum response element-binding transcription factor)</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.94830e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.44382e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0803&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;405&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.83397e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1566&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98434e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79009e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0655&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;624&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15304e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1485&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.87050e-107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18711e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0622&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;679&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.97431e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1432&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.15854e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.11521e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2942&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;734&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.43898e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1952&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.30%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 54,746 genomic regions picked 14,325 genes (79%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Predicted Promoter Motifs</i> has 615 terms covering 11,991 (66%) of all 18,041 genes.</td>
    <td>615 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>K562</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/4.all.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>unfolded protein binding</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44206e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.33567e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;471&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16026e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1960&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ribonucleoprotein complex binding</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.79661e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.63496e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2255&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.59394e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2425&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63710e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.35124e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0898&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1035&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67531e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2487&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, nonsense-mediated decay</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.49986e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53384e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1436&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;659&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14086e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral gene expression</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70246e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70901e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3843&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;518&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91524e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.65%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07048e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62752e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0729&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;659&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13445e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2404&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.44755e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.11230e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;619&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13735e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2398&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88351e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.16749e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1019&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;626&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.40353e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular response to topologically incorrect protein</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00648e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.02112e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1449&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;593&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.20487e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29640e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.80755e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0945&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;605&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;362&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.85024e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1961&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ER-nucleus signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25873e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.12580e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;655&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;257&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.38859e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>endoplasmic reticulum unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.37657e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.23887e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1331&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10092e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular response to unfolded protein</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11381e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38793e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1014&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;567&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;299&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73887e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational termination</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.77288e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.44394e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;467&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.46854e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2348&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.06018e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.36806e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2564&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;445&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10092e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of RNA stability</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.32859e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.77750e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1853&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;465&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;728&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.80899e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2058&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.47900e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.51636e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2814&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;406&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;425&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.55163e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2255&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57792e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.91992e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1911&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;422&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60372e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1767&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>activation of signaling protein activity involved in unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.64179e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.47379e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;386&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.54915e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>negative regulation of gene expression, epigenetic</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.77198e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17640e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4913&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;714&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.34719e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of mitochondrion organization</td>
    <td nowrap="nowrap" align="right">&nbsp;255&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27630e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.22530e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0508&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;428&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.46815e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of mitochondrial outer membrane permeabilization</td>
    <td nowrap="nowrap" align="right">&nbsp;262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.63797e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.04353e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2458&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;340&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;534&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.30710e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>mitochondrial membrane part</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.61722e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.39165e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;861&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.75412e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>PcG protein complex</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.56472e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51825e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4877&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;494&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31464e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic mRNA processing body</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.92596e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54251e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0801&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;405&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90387e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>small ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.01703e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.80827e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1572&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.77276e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2030&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.33241e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.50752e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9025&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35592e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2271&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic stress granule</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.37533e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31972e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2939&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.80226e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mitochondrial intermembrane space</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.73657e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03924e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1790&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.19839e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytosolic large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.93715e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07671e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0089&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.19839e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MLL1 complex</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.09444e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.32600e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2623&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34324e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>poikilocytosis</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.45430e-107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10216e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.7030&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;415&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;328&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.67146e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal mean corpuscular volume</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.56725e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.00968e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0870&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.87596e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased mean corpuscular hemoglobin</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25381e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.15542e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.24165e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2083&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal DNA repair</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.83138e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.74529e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1961&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;566&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00299e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2351&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>increased nucleated erythrocyte cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.55828e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25157e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2065&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;439&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.50235e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>increased cellular sensitivity to ultraviolet irradiation</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15965e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.65371e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7375&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.95455e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of DDB1</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.89135e-175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66161e-172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1509&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.98533e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2474&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.89110e-174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25775e-171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3040&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1445&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.78769e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45921e-172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07694e-170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1718&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1627&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.61798e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.02%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HDAC1</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.17778e-172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.32477e-170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1973&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1584&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.09330e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.48634e-158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12334e-156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3693&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22488e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CTBP1</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59052e-147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13192e-145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.48692e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ANP32B</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.50228e-137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.93684e-135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20577e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.23739e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80937e-128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4846&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;931&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.66212e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2544&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.00%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAB1A</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.83071e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.26337e-128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.23681e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACP1</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52696e-127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25501e-125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1418&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31767e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.51%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.30545e-124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.41418e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1849&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;590&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.28972e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NME2</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.76115e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.42151e-121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64500e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2552&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.98515e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.55777e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2774&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1036&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.84559e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2556&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04737e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63076e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5361&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;817&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04828e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.89%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AATF</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.05862e-115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.03581e-113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0737&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04322e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2571&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDX5</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36086e-108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.86708e-107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6951&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;667&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30003e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2438&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of FBL</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69576e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.00473e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3970&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;806&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.57%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.11169e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50912e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68498e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5829&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36468e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DAP3</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47652e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52190e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0652&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1076&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47046e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2567&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K3</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31773e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00953e-95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;675&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;255&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.84620e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">PANTHER Pathway</td>
    <td>Apoptosis signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.64548e-107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.02113e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2646&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21322e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2271&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Transcription regulation by bZIP transcription factor</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.96535e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53367e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7934&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.46028e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Interferon-gamma signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.84189e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07993e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3401&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.81577e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Genes involved in Metabolism of mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17189e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54689e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1059&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.93104e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>PDGFR-beta signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.21363e-111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.73997e-109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0021&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.49%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20097e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1952&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Translation</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.41208e-87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.70658e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1443&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;843&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21325e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Processing of Capped Intron-Containing Pre-mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03493e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51790e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2539&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;725&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.48508e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2539&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.73712e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.93299e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;550&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.53868e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in trans-Golgi Network Vesicle Budding</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07154e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.27870e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4398&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;517&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36500e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Influenza Life Cycle</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.43043e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.17727e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0445&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;735&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02931e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2355&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Nonsense Mediated Decay Enhanced by the Exon Junction Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.08292e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.11297e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2832&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;569&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.01033e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2396&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Golgi Associated Vesicle Biogenesis</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.84791e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.08847e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4082&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;483&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.98720e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Role of Calcineurin-dependent NFAT signaling in lymphocytes</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.33289e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31548e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1442&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;608&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.51877e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23785e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.16978e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;619&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.21300e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Links between Pyk2 and Map Kinases</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.27072e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.19874e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6629&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;385&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.55667e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL-2 Receptor Beta Chain in T cell Activation</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12661e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.75967e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4840&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;436&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.93846e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in 3' -UTR-mediated translational regulation</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05133e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.95627e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1079&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;566&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.71939e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Signaling events mediated by HDAC Class I</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53577e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.53942e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;533&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11016e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>GMCSF-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59452e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.57739e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3590&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;441&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.03131e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1949&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Unfolded Protein Response</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.37886e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75155e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;450&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.58018e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Peptide chain elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98733e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.49508e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2710&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;459&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64343e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL2 signaling events mediated by PI3K</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78540e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.54645e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3774&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.89786e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>EPO Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02046e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.45385e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.6004&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;334&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.65354e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes down-regulated in NB4 cells (acute promyelocytic leukemia,
 APL) in response to tretinoin [PubChem=444795]; based on Chip-seq data.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 8.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56290e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1935&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;736&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes with promoters occupied by PML-RARA fusion 
[GeneID=5371,5914] protein in acute promyelocytic leukemia(APL) cells 
NB4 and two APL primary blasts, based on  Chip-seq data.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0520&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3535&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.21150e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1915&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;399&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;423&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in NHEK cells (normal epidermal keratinocytes) after UVB irradiation.</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.92186e-310&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.32645e-307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0383&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.47344e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1313&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;489&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;546&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94759e-289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.27964e-287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2533&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.42033e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;382&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in lymphoblastoid cells from the European population compared to those from the Asian population.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.97098e-250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.68798e-248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2790&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35754e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;471&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in K562 cells (lymphoblast) by MYC [GeneID=4609] in the presence of PSMD9 [GeneID=5715].</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.62117e-226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.16567e-224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0089&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.02769e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2083&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic vs non-metastatic HNSCC (head and neck squamous cell carcinoma) samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80659e-217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.37631e-215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3973&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1666&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.44804e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1353&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.42238e-207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.75644e-205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.08522e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2090&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.03%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in fibroblasts expressing mutant forms of ERCC3 [GeneID=2071] after UV irradiation.</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47713e-198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.25866e-196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2840&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1678&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55379e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2383&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.09%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Set 'Myc targets1': targets of c-Myc [GeneID=4609] identified by
 ChIP on chip in cultured cell lines, focusing on E-box-containing 
genes; high affinity bound subset</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73094e-165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.23957e-163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1798&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1548&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68679e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.95227e-152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.42463e-150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2817&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50286e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1623&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in macrophages by aerolysin-related cytotoxic enterotoxin (Act) from Aeromonas hydrophila.</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.29008e-152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.81061e-150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6534&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;967&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;632&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.80106e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1592&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated by induction of exogenous BRCA1 in EcR-293 cells</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71081e-132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51451e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4564&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;969&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.83659e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2050&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes co-regulated in uterus during a time course response to progesterone [PubChem=5994]: SOM cluster 17.</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.98411e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.89470e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1050&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00328e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in BJAB cells (B-lymphoma) after leucine [PubChem=857] deprivation.</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94373e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18885e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1258&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36201e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2496&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in ES cells (embryonic stem) heterozygotic 
for KDM1A [GeneID=23028] loss of function mutant compared to the 
homozygotic loss of the gene.</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23852e-112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.30944e-111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0437&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;236&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02299e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1712&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes encoding mRNA transcripts specifically bound by DCP2 [GeneID=167227].</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34809e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17895e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;492&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.05519e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2487&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Selected gradually up-regulated genes in the TLX1 [GeneID=3195] Tet On iEBHX15-4 cells (pro-erythroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.79660e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.27914e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4975&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;703&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.71007e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.25645e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02577e-97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;868&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.70%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;791&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44235e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Selected genes changed in K562 (immortalized erythroleukemia) 
cells induced by hemin [PubChem=26945] treatment to express erythroid 
properties.</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.01429e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73129e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;787&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.30236e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2464&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Predicted Promoter Motifs</td>
    <td>Motif NNNSANTTCCGGGAANTGNSN matches STAT1: signal transducer and activator of transcription 1, 91kDa</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.77249e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.31512e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0099&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;400&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.48872e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2066&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66637e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.99131e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.80999e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.27328e-245&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38920e-241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.4707&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1038&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.03%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53683e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06497e-234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01705e-231&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7392&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1413&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;494&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.97883e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1596&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12770e-203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.17970e-201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7538&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.35119e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2504&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 ng/ml LPS (TLR4 agonist) versus monocytes treated with vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53383e-198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20990e-195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5473&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1356&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.67709e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1842&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.60298e-170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.28634e-167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3674&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;769&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.01871e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1323&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with anti-TREM1 
[GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist).</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.21766e-164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.05956e-162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1351&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.12836e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1971&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with type 1 diabetes at the time of the 
diagnosis versus those at 4 months later.</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.78535e-164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12429e-161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1634&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.98436e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52274e-141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.63553e-139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1418&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;627&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.08006e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1454&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with type 1 diabetes at the time of the 
diagnosis versus those at 1 month later.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.37357e-141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56483e-138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0662&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1492&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78608e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2308&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of control RAW264.7 cells (macrophages) versus those infected with B. abortus.</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29403e-128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.47159e-126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0456&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1396&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;796&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68117e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
5000 ng/ml LPS (TLR4 agonist) versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.27537e-126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.81228e-124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1086&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.49%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;292&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.19371e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1851&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with acute influenza infection versus PBMC 
from patients with acute E. coli infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16721e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48625e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3876&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;932&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.32542e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1084&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 
ng/ml LPS (TLR4 agonist) versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.58790e-117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.52523e-115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0536&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10700e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.83406e-115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.37392e-113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0716&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.23819e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1855&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of dendritic cells (DC) 
stimulated with LPS (TLR4 agonist) at 4 h versus DC cells stimulated 
with Pam3Csk4 (TLR1/2 agonist) at 4 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.21189e-114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.24985e-112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71667e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2043&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 
ng/ml LPS (TLR4 agonist) versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.71771e-113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.59541e-111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71667e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2043&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control dendritic cells (DC)
 at 1 h versus those stimulated with Pam3Csk4 (TLR1/2 agonist) at 1 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.34103e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.19310e-102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0438&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.74154e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2034&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of unstimulated NK cells versus those stimulated with IL2 [GeneID=3558] at 16 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.42390e-102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59643e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08606e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 51,176 genomic regions picked 14,282 genes (79%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>PANTHER Pathway</i> has 152 terms covering 2,197 (12%) of all 18,041 genes.</td>
    <td>152 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Predicted Promoter Motifs</i> has 615 terms covering 11,991 (66%) of all 18,041 genes.</td>
    <td>615 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>NHEK</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/5.all.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>extrinsic apoptotic signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.67699e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.69907e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3871&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;616&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;693&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86479e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1806&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>intrinsic apoptotic signaling pathway in response to DNA damage</td>
    <td nowrap="nowrap" align="right">&nbsp;257&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.80721e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95281e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1736&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;483&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;607&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.74870e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2011&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of extrinsic apoptotic signaling pathway in absence of ligand</td>
    <td nowrap="nowrap" align="right">&nbsp;284&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.43939e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26434e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1505&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;457&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;623&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.08015e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11255e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.03301e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1035&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;476&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.33163e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of mitochondrial outer membrane permeabilization</td>
    <td nowrap="nowrap" align="right">&nbsp;405&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.90104e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77894e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0624&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;371&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;643&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07830e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>membrane protein proteolysis</td>
    <td nowrap="nowrap" align="right">&nbsp;622&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13167e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.89945e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;770&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.74032e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>squamous cell carcinoma</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88477e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33028e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1939&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;596&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;299&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25074e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2006&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased fibroblast cell migration</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.76085e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.15380e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0006&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;622&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;361&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68189e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>skin papilloma</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.58614e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.76807e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;468&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.62950e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Human Phenotype</td>
    <td>Dermal atrophy</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.05936e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.21895e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1811&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;578&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.69247e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Disease Ontology</td>
    <td>laryngeal squamous cell carcinoma</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61932e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.73111e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;790&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.37997e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1456&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>carcinoma of larynx</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58204e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07466e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0368&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;815&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68525e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1476&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>progressive multifocal leukoencephalopathy</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.91782e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.89616e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;641&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.76952e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1843&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of AP3D1</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.35791e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.58457e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0036&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1066&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.98409e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of SERPINB5</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.04537e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.29768e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;461&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87896e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CDH3</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.39415e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.50812e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8325&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;463&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.80271e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.34016e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.90021e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;709&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.91260e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PHB</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.54797e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.41066e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;629&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.03%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43571e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1846&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45849e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14749e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;490&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54507e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDX5</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39897e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92696e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0301&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;597&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.42447e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of GPX4</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.21122e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.74238e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;273&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.91861e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2024&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17581e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.47304e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7488&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69565e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1979&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of USP5</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.69752e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.63111e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.33220e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2016&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAD21</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92771e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12758e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2064&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;257&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31461e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Validated transcriptional targets of TAp63 isoforms</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45325e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.09574e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3996&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;736&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.33762e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2020&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>a6b1 and a6b4 Integrin signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.22329e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80912e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3964&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.69324e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1985&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Signaling by TGF-beta Receptor Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34482e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53594e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1845&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.37775e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Bladder cancer</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71330e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73966e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3583&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.40400e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1959&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fas Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.56582e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.59180e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1915&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;596&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.27100e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1868&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Class I PI3K signaling events mediated by Akt</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.15816e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70219e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1686&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;408&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.51458e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1901&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcriptional activity of SMAD2/SMAD3:SMAD4 heterotrimer</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.86998e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53375e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;459&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.64128e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in TGF-beta receptor signaling activates SMADs</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84979e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.81363e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;376&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.63394e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SMAD2/SMAD3:SMAD4 heterotrimer regulates transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.19168e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.80189e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2636&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;329&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07638e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cell Cycle: G1/S Check Point</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16795e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65810e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2026&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.57%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.06608e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>PDGFR-alpha signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.03510e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43329e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1459&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;327&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;315&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.79891e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I Promoter Opening</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54805e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11663e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.38742e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1421&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MGI Expression: Detected</td>
    <td>TS23_rest of skin epidermis</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04188e-165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.12002e-163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0516&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1790&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.44029e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1598&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Down-regulated genes that vary between HNSCC (head and neck 
squamous cell carcinoma) groups formed on the basis of their level of 
pathological differentiation: well vs poorly differentiated tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1781&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4084&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.64417e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1984&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated upon overexpression of PARVB [GeneID=29780] in MDA-MB-231 cells (breast cancer) cultured in 3D Matrigel only.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4495&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55356e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1668&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;400&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.72%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Class III of genes transiently induced by EGF [GeneID =1950] in 184A1 cells (mammary epithelium).</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;0.00000&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0940&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.76885e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2077&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic vs non-metastatic HNSCC (head and neck squamous cell carcinoma) samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.63632e-320&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01938e-317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5831&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.30719e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1706&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;236&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 480 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57684e-289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.08039e-287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63154e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1800&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with NRG1 [GeneID=3084].</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64802e-281&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.18130e-279&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2527&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27587e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1886&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression positively correlated with sensitivity of breast cancer cell lines to dasatinib [PubChem=3062316].</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.58276e-168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.14620e-166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1753&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1584&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;412&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32399e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2098&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.57695e-162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.34313e-160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5672&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1093&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;800&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.39063e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1814&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in HFK cells (primary keratinocytes) in response to UVB irradiation.</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13160e-158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25802e-156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7892&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;927&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;812&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.06562e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.81511e-153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55246e-151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1672&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1457&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;520&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22827e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Metastatic propensity markers of head and neck squamous cell 
carcinoma (HNSCC): down-regulated in metastatic vs non-metastatic 
tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.55805e-152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.47311e-150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5429&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1045&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;412&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32399e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2098&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in Calu-6 cells (lung cancer) at 1 h time point after TNF [GeneID=7124] treatment.</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.97138e-149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.02420e-147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;570&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.95347e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2054&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 120 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.81442e-149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91936e-147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7007&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;920&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;929&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16817e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1520&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.24826e-147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08045e-145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;540&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.96123e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in macrophages by aerolysin-related cytotoxic enterotoxin (Act) from Aeromonas hydrophila.</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.85440e-140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.25003e-138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1050&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.75567e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1098&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in 786-0 cells (renal carcinoma, RCC) upon 
expression of VHL [GeneID=7428] off a retroviral vector under normoxia 
(normal oxygen) condition.</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.76214e-133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30760e-131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1571&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;350&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.15956e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1794&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in head and neck tumor samples which clustered around known hypoxia genes.</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.54308e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.55491e-121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5841&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;815&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;348&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.76537e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 240 min after stimulation of MCF10A cells with serum.</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46317e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.06785e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2817&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;895&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;653&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.59795e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2028&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in HeLa cells (cervical carcinoma) 24 h after infection with adenovirus Ad12.</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.62638e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.99929e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6771&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;657&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1095&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.78394e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1681&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 120 min after stimulation of MCF10A cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.23251e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.38909e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;542&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.89%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;856&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.72370e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1966&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with type 1 diabetes at the time of the 
diagnosis versus those at 4 months later.</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07733e-161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46943e-158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0071&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1839&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.80029e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1623&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of peripheral blood 
mononuclear cells (PBMC) from patients with acute E. coli infection 
versus PBMC from patients with acute S. aureus infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.39923e-148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.63755e-146&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1707&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1405&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;391&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48048e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1614&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.77528e-128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17644e-125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1095&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1293&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.13%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.95511e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.0932&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.53671e-125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35876e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1504&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.49928e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.0664&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.12851e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.92840e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;870&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;355&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.77832e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1564&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82834e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.76030e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0069&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1053&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;491&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.13050e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 60,808 genomic regions picked 14,726 genes (82%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Human Phenotype</i> has 6,146 terms covering 2,822 (16%) of all 18,041 genes.</td>
    <td>6,146 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Disease Ontology</i> has 2,235 terms covering 7,886 (44%) of all 18,041 genes.</td>
    <td>2,235 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MGI Expression: Detected</i> has 9,337 terms covering 11,602 (64%) of all 18,041 genes.</td>
    <td>9,337 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>
<br><br>
**All peaks as test set, open chromatin region as background set**
<details><summary>GM12878</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/1.all.bg.png">
No terms found
</p>
</details>

<details><summary>H1-hESC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/2.all.bg.png">
No terms found
</p>
</details>

<details><summary>HUVEC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/3.all.bg.png">
No terms found
</p>
</details>

<details><summary>K562</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/4.all.bg.png">
No terms found
</p>
</details>

<details><summary>NHEK</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/5.all.bg.png">
No terms found
</p>
</details>
<br><br>
**Top 25000 peaks as test set, whole genome as background set**
<details><summary>GM12878</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/1.25.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>non-membrane spanning protein tyrosine kinase activity</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.49584e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08894e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18357e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>unfolded protein binding</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51338e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72628e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0886&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70190e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3025&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>polyubiquitin binding</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11497e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.51870e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1681&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.28638e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein phosphorylated amino acid binding</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.49419e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73184e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0084&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35216e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>interferon-gamma-mediated signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.47210e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36731e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.65546e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00518e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40622e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0419&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;494&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.34222e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4497&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of type I interferon production</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45526e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13380e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0713&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;351&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02665e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>B cell receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62808e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25905e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4766&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;728&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00233e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3800&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>B cell homeostasis</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.14176e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.15620e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;927&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.95087e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4014&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc-gamma receptor signaling pathway involved in phagocytosis</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.06761e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52013e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0055&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;483&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00304e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3297&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc receptor mediated stimulatory signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40375e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75491e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0039&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;534&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.47954e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fc-gamma receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.58753e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.87596e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0031&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;534&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.47954e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of mitochondrial membrane permeability</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.41391e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45802e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5802&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;876&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.71060e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4049&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>lymphocyte homeostasis</td>
    <td nowrap="nowrap" align="right">&nbsp;156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.86403e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.60131e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2563&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;798&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98207e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2908&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>release of cytochrome c from mitochondria</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15937e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.66065e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0966&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;771&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48170e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>intrinsic apoptotic signaling pathway in response to DNA damage</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06771e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.75570e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;553&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.93790e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53653e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56695e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0412&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.64446e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4353&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>apoptotic mitochondrial changes</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.40920e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.97221e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;498&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.48302e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3848&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, nonsense-mediated decay</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39937e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.41594e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52415e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4380&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>peptidyl-lysine methylation</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.58432e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90051e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9449&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.57%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;709&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.96286e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear export</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.73181e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.93757e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0046&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.18288e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3884&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleotide-binding domain, leucine rich repeat containing receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25890e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62014e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2086&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;466&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36472e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4096&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.44122e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.69464e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2957&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;424&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67382e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3539&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;219&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.85928e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.26990e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3466&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;360&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.08502e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3871&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>nucleosome</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36416e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.56667e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7885&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45382e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1976&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>DNA packaging complex</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.92432e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.82232e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01378e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1994&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>methyltransferase complex</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46751e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.86750e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0329&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.90335e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>histone methyltransferase complex</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.58760e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18435e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29920e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.45448e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.40369e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1836&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31613e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>PcG protein complex</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.97017e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.78040e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0308&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.77329e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3617&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MHC protein complex</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.32439e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.92805e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.4304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.42819e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytosolic large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77254e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11426e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.43282e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mitochondrial ribosome</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.01574e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.22774e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.95189e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MLL1 complex</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.58550e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01593e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5497&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.50987e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic stress granule</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39402e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12461e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.01780e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MHC class II protein complex</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43457e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16040e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.9305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.27257e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68450e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.99516e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6336&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78938e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3908&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>integral to lumenal side of endoplasmic reticulum membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17220e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66610e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9950&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.26040e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cyclin-dependent protein kinase holoenzyme complex</td>
    <td nowrap="nowrap" align="right">&nbsp;93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01994e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38734e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2670&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06895e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>exon-exon junction complex</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.04641e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.69975e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2355&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06895e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ESC/E(Z) complex</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54549e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58947e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.22008e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.11%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>anaphase-promoting complex</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.05923e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.10475e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3036&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65360e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal mature B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44416e-146&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.37580e-144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1585&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.70351e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2672&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal B cell activation</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.08501e-123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.55161e-121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2873&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1026&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15975e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3293&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased mature B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00282e-121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52407e-119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0601&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.96281e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;232&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal B cell proliferation</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.91952e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.46799e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;975&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66182e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased IgG level</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.08093e-119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49797e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0789&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.02637e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2524&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;245&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal immature B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.70971e-110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.12605e-108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0696&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1146&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.94575e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3254&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal follicular B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76078e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53489e-97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8870&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;544&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17762e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3722&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.65%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen marginal zone morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.04690e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65695e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;703&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.68300e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2920&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal marginal zone B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11677e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.70332e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5043&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;616&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.74831e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.89%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased immature B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02152e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28387e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0753&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;896&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45421e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>enlarged lymph nodes</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39465e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55533e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0045&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;906&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.84079e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased B cell proliferation</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.59044e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.04821e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2908&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;664&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58263e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3777&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen B cell follicle morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28037e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33394e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0901&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;778&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52607e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2323&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal pre-B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30154e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30451e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1372&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;729&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08684e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3480&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen secondary B follicle morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.54991e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.03296e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95041e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased marginal zone B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.63642e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.26874e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;469&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67359e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal spleen germinal center morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.54535e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.22667e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2378&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;584&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.92759e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2876&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal transitional stage B cell morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.16552e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.30406e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5042&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;457&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.79882e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased IgM level</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.20762e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.01164e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1836&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07610e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2971&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>increased mature B cell number</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55817e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34104e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0310&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;712&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.85%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10137e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Human Phenotype</td>
    <td>Abnormality of macrophages</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.82479e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71754e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.0695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.60248e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Oculomotor apraxia</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10286e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.28515e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.57097e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Basal cell carcinoma</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.19327e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31465e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0292&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.60248e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Disease Ontology</td>
    <td>Burkitt's lymphoma</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06785e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.50309e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0027&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.96248e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of GNB1</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39751e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.96737e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0398&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1040&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.36845e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;297&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;306&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HDAC1</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43393e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06143e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1666&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;763&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.41458e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4406&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.04%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of BUB3</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.87782e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.40957e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0644&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;814&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.46942e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4433&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of EIF3S2</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.72552e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.74360e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1468&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;734&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02489e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4452&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDB1</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63786e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.87727e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1651&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;705&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.53910e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03229e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.29697e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0849&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;763&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48293e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;280&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35520e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.23336e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1999&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;674&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.70%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.99254e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4629&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DAP3</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.05602e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.87324e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2749&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;579&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.74646e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4523&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.56%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HLA-C</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.81123e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62740e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.1152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.09493e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4438&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of STAT6</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.91406e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.29573e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0051&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39944e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4378&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35503e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.45077e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1890&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;561&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.24%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.31324e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4412&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ANP32B</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.09723e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.39656e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1445&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;576&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.85343e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4529&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.88592e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39086e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1493&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.46208e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MYD88</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.09810e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36056e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.3052&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.94274e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CTBP1</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.03780e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.01891e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2502&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;504&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15966e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4577&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.28340e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.13164e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;395&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24218e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AATF</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06241e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.53824e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0749&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;589&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04496e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4465&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.65%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of APEX1</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73788e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.31398e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.90718e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.75051e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.96291e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51559e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of FBL</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.50820e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02926e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3560&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;387&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36509e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4433&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">PANTHER Pathway</td>
    <td>Apoptosis signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.25783e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.99190e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2299&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;444&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.74041e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>B cell activation</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.44705e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.25317e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0311&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31669e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4501&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>JAK/STAT signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28872e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.89715e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1730&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.77978e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>PDGFR-beta signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63455e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.19201e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1794&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;678&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.71%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.47195e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3617&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Interferon Signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38088e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64553e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2607&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;549&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33653e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2740&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Costimulation by the CD28 family</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03183e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.27002e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.54389e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2817&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Signaling by the B Cell Receptor (BCR)</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16141e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.07580e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0643&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;566&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.27718e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4032&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Class I PI3K signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73956e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.61622e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6619&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;323&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.07969e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3866&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Metabolism of mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.24188e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.89026e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;559&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.24%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31851e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4407&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.71%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Antigen Activates B Cell Receptor Leading to Generation of Second Messengers</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.59703e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63698e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12828e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Interferon gamma signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.95487e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.61459e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5882&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;297&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17336e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3030&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30327e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14688e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0673&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82451e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3656&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>B cell receptor signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.56953e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.59486e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1862&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;398&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.44210e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3587&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.57%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL2-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.49687e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.20835e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2979&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;331&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63333e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4483&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>BCR signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74835e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04901e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1387&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15774e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Processing of Capped Intron-Containing Pre-mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.93100e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.82997e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2019&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;346&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.73300e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Signaling by SCF-KIT</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.76494e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.82072e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0733&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;395&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.53013e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TCR signaling in na&amp;amp;#xef;ve CD4+ T cells</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.23434e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64205e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2468&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;315&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;348&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.44240e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>EPO signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.91830e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84720e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5297&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.99%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45003e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10084e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.84371e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4506&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.35728e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4476&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Spliceosome</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.04316e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.69992e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1434&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56112e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4515&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TCR signaling in na&amp;amp;#xef;ve CD8+ T cells</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16929e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.06175e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2990&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52972e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Signaling events mediated by HDAC Class I</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.24507e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.59870e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2734&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57793e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes with promoters occupied by PML-RARA fusion 
[GeneID=5371,5914] protein in acute promyelocytic leukemia(APL) cells 
NB4 and two APL primary blasts, based on  Chip-seq data.</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.10701e-221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.84799e-218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1889&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.75675e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;423&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in Daudi cells (B lymphocytes) stably expressing CD5 [GeneID=921] off a plasmid vector.</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.07890e-199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.43036e-196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1016&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1969&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45981e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3565&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;423&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;460&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Gene up-regulated by CD40 [GeneID=958] signaling in Ramos cells (EBV negative Burkitt lymphoma).</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70799e-175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.57612e-173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.3976&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;759&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72938e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4021&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10047e-163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.62746e-161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1294&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69221e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3851&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.02%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in lymphoblastoid cells from the European population compared to those from the Asian population.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.24453e-139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.29217e-137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0890&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1412&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97043e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3925&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;455&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.72%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Up-regulated genes that best disciminate plasmablastic plasmacytoma from plasmacytic plasmacytoma tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.63806e-126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71296e-123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1615&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43035e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1915&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.72%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>The 'MLL signature 1': genes up-regulated in pediatric AML 
(acute myeloid leukemia) with rearranged MLL [GeneID=4297] compared to 
all AML cases with the intact gene.</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06634e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.44697e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1045&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.96887e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2473&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic vs non-metastatic HNSCC (head and neck squamous cell carcinoma) samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.97115e-121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18159e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4978&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;848&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;282&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.40378e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>The 'MLL signature 2': genes up-regulated in pediatric AML 
(acute myeloid leukemia) with rearranged MLL [GeneID=4297] compared to 
the AML cases with intact MLL and NPM1 [GeneID=4869].</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25276e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.75910e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1299&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.98038e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;339&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;406&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.27131e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.23257e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3509&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;742&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.53324e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3047&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in fibroblasts expressing mutant forms of ERCC3 [GeneID=2071] after UV irradiation.</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44583e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65412e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1845&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77406e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3005&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Set 'Myc targets1': targets of c-Myc [GeneID=4609] identified by
 ChIP on chip in cultured cell lines, focusing on E-box-containing 
genes; high affinity bound subset</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59940e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63042e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1763&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;755&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;334&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.08310e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Clusters 1 and 2: genes up-regulated in B2264-19/3 cells 
(primary B lymphocytes) within 30-60 min after activation of LMP1 (an 
oncogene encoded by Epstein-Barr virus, EBV).</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.49220e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.61894e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9446&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;379&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.60607e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3844&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in BJAB cells (B-lymphoma) after leucine [PubChem=857] deprivation.</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33345e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06803e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2543&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;596&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;382&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88644e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2688&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated genes in the B lymphocyte developmental 
signature, based on expression profiling of lymphomas from the Emu-myc 
transgenic mice: the Pre-BI stage.</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.39519e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.12487e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6013&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;309&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20179e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3954&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.57%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in BJUB cells (B-lymphoma) in response to  rapamycin [PubChem=6610346] treatment.</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.88204e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.39715e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0372&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;744&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;439&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63198e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2089&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Up-regulated genes in the B lymphocyte developmental signature 
based on expression profiling of lymphomas from the Emu-myc transgenic 
mice: the immature B stage.</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.45127e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.36940e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;329&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.13998e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4462&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cluster 3: genes up-regulated in B2264-19/3 cells (primary B 
lymphocytes) within 60-180 min after activation of LMP1 (an oncogene 
encoded by Epstein-Barr virus, EBV).</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.51067e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.77619e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6638&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;352&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16425e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.70998e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.82583e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0875&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;577&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;523&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85794e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1667&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cluster 2: genes up-regulated in B493-6 cells (B lymphocytes) by
 serum alone or in combination with MYC [GeneID=4609] but not by MYC 
alone.</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.89156e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.45495e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7314&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;330&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00946e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">InterPro</td>
    <td>Histone-fold</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.77870e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.32241e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1531&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.34093e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2644&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>G-patch domain</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.40426e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.84231e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3663&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.96350e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>HIST</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28011e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.11893e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.5430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.92201e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2855&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>SH2D</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.85409e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.82127e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0657&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.77309e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.10306e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.13088e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3044&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.82736e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MRPL</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.23147e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.41264e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01047e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3496&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87272e-156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.30689e-153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;818&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.56375e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3070&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55959e-141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48941e-138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.7234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;544&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.65153e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3999&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.65580e-125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.32752e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;711&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.23390e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60067e-124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.64321e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5561&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;837&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07994e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3758&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of B cells from influenza 
vaccinee at day 7 post-vaccination versus plasmacytoid dendritic cells 
(pDC) at day 7 post-vaccination.</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73596e-123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04514e-120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1518&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.22767e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3746&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of unstimulated peripheral 
blood mononuclear cells (PBMC) 3 days after stimulation with YF17D 
vaccine versus PBMC 21 days after the stimulation.</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54978e-110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.93348e-108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;902&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78458e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of B cells versus plasmacytoid dendritic cells (pDC) .</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.54662e-110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51343e-107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.99195e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4085&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of IgD+ peripheral blood B cells versus dark zone germincal center B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.00480e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43365e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3595&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;813&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.01682e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.51%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.47566e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.25389e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;716&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20554e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control thymocytes versus thymocytes treated with dexamethasone [PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.54649e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.77380e-96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2419&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;853&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70742e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3397&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 ng/ml LPS (TLR4 agonist) versus monocytes treated with vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56614e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.71939e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;654&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25969e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3445&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with acute influenza infection versus PBMC 
from patients with acute E. coli infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.86530e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.33560e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;536&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16698e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3990&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control polymorphonuclear 
leukocytes (PMN) at 12 h versus PMN treated with F. tularensis vaccine 
at 48 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.90953e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.74401e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1718&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;867&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75235e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3535&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of control polymorphonuclear 
leukocytes (PMN) at 0 h versus PMN treated with F. tularensis vaccine at
 6 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.26015e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.44778e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1446&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;883&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.02263e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3574&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.20200e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.89721e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6516&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;572&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76504e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3932&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of unstimulated dendritic cells (DC) versus 1 day DC stimulated with LPS (TLR4 agonist).</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.30551e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.72095e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1602&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;856&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00677e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of plasma cells versus memory B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85197e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.08074e-87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0350&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;969&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.53955e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control polymorphonuclear 
leukocytes (PMN) at 12 h versus PMN treated with F. tularensis vaccine 
at 24 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31042e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20645e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0531&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;905&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.83495e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3599&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of memory CD4 [GeneID=920] T cells versus B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.99986e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.81892e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;904&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.53955e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of IgD- peripheral blood B cells versus dark zone germinal center B cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78904e-81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55322e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0908&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;827&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.53981e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4219&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 25,000 genomic regions picked 12,230 genes (68%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Human Phenotype</i> has 6,146 terms covering 2,822 (16%) of all 18,041 genes.</td>
    <td>6,146 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Disease Ontology</i> has 2,235 terms covering 7,886 (44%) of all 18,041 genes.</td>
    <td>2,235 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>PANTHER Pathway</i> has 152 terms covering 2,197 (12%) of all 18,041 genes.</td>
    <td>152 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>InterPro</i> has 9,422 terms covering 17,343 (96%) of all 18,041 genes.</td>
    <td>9,422 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>H1-hESC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/2.25.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>RNA methyltransferase activity</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.86051e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.90227e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0454&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.55700e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.21992e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02755e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1865&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;529&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.12%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71804e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3877&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39282e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.05875e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0427&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;550&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.89230e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3824&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, nonsense-mediated decay</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.82605e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.81738e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3571&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.75870e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3807&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein localization to endoplasmic reticulum</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47994e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.41445e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0986&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.20810e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3945&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral gene expression</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84275e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.69226e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18452e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3836&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63304e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.39278e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.09065e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4030&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational termination</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43072e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17803e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.83414e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3967&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>macromolecular complex disassembly</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.72282e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.30306e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;407&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92666e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3321&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>establishment of protein localization to endoplasmic reticulum</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.24302e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.18163e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.70080e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4033&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.13196e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.73643e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40074e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3951&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.22284e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.99784e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1788&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.10931e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4028&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.33858e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00265e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1892&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38601e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4023&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.44996e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.86021e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1544&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.28534e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>RNA 3'-end processing</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17319e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.24786e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0254&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45011e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3566&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53005e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47905e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2249&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;280&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.74628e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4023&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mRNA 3'-end processing</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.60644e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.04128e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0725&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.92067e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3607&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.06689e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.83499e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1044&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;537&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.35340e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2526&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.89945e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.24775e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1511&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;385&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85554e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>activation of signaling protein activity involved in unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.47969e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.24777e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1034&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;402&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.13077e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>transcription elongation from RNA polymerase II promoter</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61560e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02847e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0087&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;343&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.95371e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3422&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.46941e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.92279e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0842&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;360&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.12104e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3870&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytosolic ribosome</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27400e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.88368e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64195e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3692&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.60732e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40581e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1729&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.88541e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4097&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytosolic large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61994e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36005e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3873&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.74746e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic mRNA processing body</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98119e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.22126e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.06986e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>euchromatin</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.50393e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.52397e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8700&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07558e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear euchromatin</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.54095e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08383e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0294&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.83244e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cajal body</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.27993e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.17988e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1926&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66444e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3930&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>exon-exon junction complex</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09656e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98164e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.7622&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07558e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic stress granule</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.45318e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24056e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.08845e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MLL1 complex</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39731e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84125e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1854&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.11173e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.42137e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.53458e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1839&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.86057e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3879&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>anaphase-promoting complex</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.88404e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.87662e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2593&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.20403e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal DNA repair</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.07534e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13135e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0889&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.04938e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2383&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.05589e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.77864e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4512&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;751&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.00%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66519e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4050&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02182e-95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18158e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2516&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;824&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12667e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3593&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;274&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDB1</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75229e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.49409e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;753&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.63853e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HDAC1</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24443e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32843e-87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.61612e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3730&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.62148e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38474e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4699&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;633&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.84332e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3563&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.05655e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.69450e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7096&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;496&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11024e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3990&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of BUB3</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.18602e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.23429e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0822&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;821&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.04874e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3568&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;264&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.09%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67999e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.97063e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;444&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.01189e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AATF</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53383e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08194e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2898&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;650&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.37001e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.50193e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.30030e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.4808&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;315&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.83937e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3722&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NME2</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29297e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.60083e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5987&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;485&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.61126e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4016&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.75471e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23328e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;542&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90529e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3943&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAN</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.48480e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.07341e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0382&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;769&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.08%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.50812e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4077&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;271&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.11%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PSMC1</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.57951e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.88406e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3617&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;547&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01936e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3769&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08647e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72896e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8236&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;387&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.79938e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3930&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DAP3</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39781e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31592e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2710&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;578&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.24201e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3993&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ANP32B</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31392e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.95286e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.46938e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.56%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of APEX1</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73882e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.71238e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7911&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43070e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3799&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.89%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of SKP1A</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01017e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.05401e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0628&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;645&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.98818e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3800&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.57%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of EIF3S2</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06989e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98627e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0006&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;684&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.76923e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3533&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.85%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Genes involved in Metabolism of mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.96776e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.91744e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;616&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63289e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3620&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Metabolism of RNA</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51311e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65865e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0432&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;721&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15814e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3626&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.96%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.37012e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48285e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;471&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17637e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Translation</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31970e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.65502e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1869&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.31660e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3510&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Nonsense Mediated Decay Enhanced by the Exon Junction Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.66869e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.04534e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4806&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.14232e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3754&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Influenza Life Cycle</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.10796e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78375e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1752&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;382&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52655e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3766&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Processing of Capped Intron-Containing Pre-mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09664e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.06796e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1956&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;345&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.48016e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3972&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12555e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85715e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4977&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.45880e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3887&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Peptide chain elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65496e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.89394e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5523&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;252&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75897e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3789&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.72885e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.27462e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1867&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33444e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3768&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Influenza Viral RNA Transcription and Replication</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14098e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35508e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;273&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.56990e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3587&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in 3' -UTR-mediated translational regulation</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30222e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22781e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.97783e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3614&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I Promoter Opening</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.99071e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75182e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.9243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.80515e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2592&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I, RNA Polymerase III, and Mitochondrial Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04114e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.08416e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72404e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2933&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Unfolded Protein Response</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32695e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.21881e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2756&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00076e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3360&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.57%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Regulation of mRNA Stability by Proteins that Bind AU-rich Elements</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.57267e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.50282e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;252&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.67919e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Deposition of New CENPA-containing Nucleosomes at the Centromere</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44057e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.64345e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.14421e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Packaging Of Telomere Ends</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.75143e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15299e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.00579e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2799&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase II Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12625e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.94660e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0053&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25803e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3580&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Activation of Chaperone Genes by XBP1(S)</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.55400e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67546e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6069&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.47750e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes down-regulated in NB4 cells (acute promyelocytic leukemia,
 APL) in response to tretinoin [PubChem=444795]; based on Chip-seq data.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62423e-184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.82792e-181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0506&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1934&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22159e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2325&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;672&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69609e-183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53483e-180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4331&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74119e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;362&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.39352e-108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.97436e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4618&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;777&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.06708e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;257&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.04%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated by induction of exogenous BRCA1 in EcR-293 cells</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.52364e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.24643e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;469&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;219&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16177e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2784&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Set 'Myc targets1': targets of c-Myc [GeneID=4609] identified by
 ChIP on chip in cultured cell lines, focusing on E-box-containing 
genes; high affinity bound subset</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52214e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.73939e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0062&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;696&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;316&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05125e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1937&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.57%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.87251e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.98640e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0658&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;571&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;569&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86412e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;209&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes co-regulated in uterus during a time course response to progesterone [PubChem=5994]: SOM cluster 17.</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07839e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.95877e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1715&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;492&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55411e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2968&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cluster 2: genes up-regulated in B493-6 cells (B lymphocytes) by
 serum alone or in combination with MYC [GeneID=4609] but not by MYC 
alone.</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12909e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05507e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6735&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;323&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;685&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.92445e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1952&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.71121e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.46500e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2580&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.70%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;753&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00489e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1602&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in BJAB cells (B-lymphoma) after leucine [PubChem=857] deprivation.</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.84432e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.31597e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;536&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.01702e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes with copy number gains in primary neuroblastoma tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65051e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04761e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0006&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;224&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55742e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2617&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated by 2-methoxyestradiol (2ME2) [PubChem=1573]
 in the MM.1S cell line (multiple myeloma) sensitive to dexamethasone 
[PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.63117e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.91355e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0912&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;346&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.53449e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2644&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes encoding mRNA transcripts specifically bound by DCP2 [GeneID=167227].</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09148e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.22329e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63613e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2974&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in head and neck tumor samples which clustered around known hypoxia genes.</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.56720e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19945e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1979&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;476&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.27246e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated by 2-methoxyestradiol (2ME2) [PubChem=1573] 
in the MM.1S cell line (multiple myeloma) sensitive to dexamethasone 
[PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.83914e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.45405e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4693&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;529&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07068e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Up-regulated in hepatocytes upon expression of NOS2 [GeneID=4843].</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.78386e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11487e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4738&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;560&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59615e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2631&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in Caco-2 cells (intestinal epithelium) after coculture with the probiotic bacteria L. casei for 6h.</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.60525e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82260e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2037&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.69370e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Protein biosynthesis, transport or catabolism genes up-regulated
 in hyperploid multiple myeloma (MM) compared to the non-hyperploid MM 
samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.45034e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10746e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7372&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;571&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.90417e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2940&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in 786-0 cells (renal carcinoma, RCC) by the loss of VHL [GeneID=7428] and in response to hypoxia.</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.43619e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20932e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;663&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.34702e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3422&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes highly expressed in prenatal hippocampus (cluster 1).</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56829e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.75291e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6883&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.61267e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Predicted Promoter Motifs</td>
    <td>Motif GGAANCGGAANY (no known TF)</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26068e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.69145e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1383&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.99%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31409e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4007&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Motif KRCTCNNNNMANAGC (no known TF)</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.65979e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.37820e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2332&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02381e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">InterPro</td>
    <td>SANT domain</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.04937e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00806e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0684&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.12360e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94400e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.64617e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4391&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.74811e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MRPL</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.19314e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.34053e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0778&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68641e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3680&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MRPS</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94205e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03145e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12397e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.28736e-129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00989e-125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5728&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;522&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.29835e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2757&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09331e-109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04412e-106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8463&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;614&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.31506e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2700&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.87149e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82818e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;536&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.32712e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.0917&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with acute influenza infection versus PBMC 
from patients with acute E. coli infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13604e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.09976e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0872&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;398&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;948&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.40058e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 25,000 genomic regions picked 12,627 genes (70%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Predicted Promoter Motifs</i> has 615 terms covering 11,991 (66%) of all 18,041 genes.</td>
    <td>615 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>InterPro</i> has 9,422 terms covering 17,343 (96%) of all 18,041 genes.</td>
    <td>9,422 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>HUVEC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/3.25.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>rRNA binding</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.56878e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31617e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52780e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4515&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mitogen-activated protein kinase kinase kinase binding</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.80165e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34434e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.25868e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51514e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53574e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;488&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.62972e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3980&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.91772e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.15209e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0540&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.37736e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cell-substrate junction assembly</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13052e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.79852e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3922&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;692&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.10673e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3764&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, nonsense-mediated decay</td>
    <td nowrap="nowrap" align="right">&nbsp;234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.82239e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.59768e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.71638e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral gene expression</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.56162e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04466e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1860&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;232&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08329e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4067&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>extrinsic apoptotic signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19059e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.72616e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1679&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;425&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18221e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;311&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.95410e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32736e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1497&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59690e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3903&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;315&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.09541e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68305e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.99460e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4309&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational termination</td>
    <td nowrap="nowrap" align="right">&nbsp;316&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.58322e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.16610e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0763&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16439e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of DNA-dependent transcription in response to stress</td>
    <td nowrap="nowrap" align="right">&nbsp;357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86233e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.37053e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;798&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78321e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>intrinsic apoptotic signaling pathway in response to DNA damage</td>
    <td nowrap="nowrap" align="right">&nbsp;364&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.20898e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49400e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0578&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.75%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;792&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.68438e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2954&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.59754e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14955e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0820&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;535&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.89219e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;379&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16758e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.97085e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;585&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00828e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2958&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>release of cytochrome c from mitochondria</td>
    <td nowrap="nowrap" align="right">&nbsp;385&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.45039e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.35637e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4773&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;742&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05687e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>activation of signaling protein activity involved in unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;417&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.75631e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.40428e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0329&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;570&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64184e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>extrinsic apoptotic signaling pathway via death domain receptors</td>
    <td nowrap="nowrap" align="right">&nbsp;440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43472e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.77694e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4036&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;877&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91552e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3860&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>negative regulation of lipid storage</td>
    <td nowrap="nowrap" align="right">&nbsp;633&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.56179e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.17299e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4428&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;808&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92863e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>retrograde vesicle-mediated transport, Golgi to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;649&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.19338e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31801e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4727&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;568&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58835e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;650&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.45472e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35796e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2557&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;919&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.82622e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>membrane protein ectodomain proteolysis</td>
    <td nowrap="nowrap" align="right">&nbsp;766&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.77957e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.78834e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1879&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;685&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.71033e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38020e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11777e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0330&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.43716e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4014&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>pre-autophagosomal structure</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.90531e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.95540e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.71970e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal cell adhesion</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.77846e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02201e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0029&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.97070e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3046&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>spontaneous skin ulceration</td>
    <td nowrap="nowrap" align="right">&nbsp;176&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53251e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.89458e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2295&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19004e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>disorganized yolk sac vascular plexus</td>
    <td nowrap="nowrap" align="right">&nbsp;270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.42843e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.12160e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0010&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;159&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;493&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51344e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4333&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Disease Ontology</td>
    <td>sporadic breast cancer</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.88501e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.21737e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2524&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.19433e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>tuberous sclerosis</td>
    <td nowrap="nowrap" align="right">&nbsp;333&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54089e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03420e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0531&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.25656e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4333&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74693e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.45939e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;546&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.51160e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4047&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.71258e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.64212e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0705&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;379&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25717e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51687e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.39752e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;327&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13361e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3951&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.89176e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.85989e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1597&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.72519e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of FBL</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.96873e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21364e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;332&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52833e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4043&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.40618e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18932e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3758&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.19586e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18335e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88454e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0997&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.37823e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3755&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.00%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of APEX1</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.60377e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.27620e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0894&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;268&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32297e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PSME1</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79203e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.78285e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1903&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18525e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3980&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CCNI</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.07456e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.43699e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0627&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;242&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06007e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4333&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of JUND</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.88286e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.21245e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.41078e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of TPT1</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.19070e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.44739e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1845&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.86483e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4604&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.37766e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.34712e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05403e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4348&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of GPX4</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.41754e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31585e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.83532e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2791&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PFN1</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.83624e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.52307e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4969&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00829e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of BECN1</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.38746e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.96047e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0712&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.66827e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PPP2R4</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27223e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.70075e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3286&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.98474e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4438&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAD21</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.64563e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.14870e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84407e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4610&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NUMA1</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.87518e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.75386e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54003e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2417&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of G22P1</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20977e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19440e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.60052e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">PANTHER Pathway</td>
    <td>Apoptosis signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70973e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29940e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0893&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;416&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48824e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3585&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Genes involved in Signaling by TGF-beta Receptor Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56146e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.15282e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3457&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87886e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcriptional activity of SMAD2/SMAD3:SMAD4 heterotrimer</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.68536e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17810e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6519&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60820e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4598&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Signaling events mediated by focal adhesion kinase</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.50787e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.67822e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.57%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.28038e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3997&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Validated transcriptional targets of AP1 family members Fra1 and Fra2</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.48104e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72914e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4635&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.70153e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Integrin Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.04177e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.24420e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3826&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79977e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3798&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL6-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12674e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.08234e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0023&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67314e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3418&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Keratinocyte Differentiation</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.59385e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.55631e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0932&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46477e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3681&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Downregulation of SMAD2/3:SMAD4 transcriptional activity</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15618e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.10462e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5799&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.39869e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SMAD2/SMAD3:SMAD4 heterotrimer regulates transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.65646e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.27649e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5605&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;153&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.80741e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4415&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>HIV-I Nef: negative effector of Fas and TNF</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08836e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.13082e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1054&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;226&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11323e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Nonsense Mediated Decay Enhanced by the Exon Junction Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16404e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.29840e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.99%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.46478e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4033&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in TGF-beta receptor signaling activates SMADs</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.58521e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57749e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4014&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.05874e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Peptide chain elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.73730e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22742e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1067&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.07174e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Integrin-linked kinase signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25620e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.60608e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;332&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43136e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2680&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Downregulation of TGF-beta receptor signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.41664e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.78040e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3845&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;259&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14826e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.55119e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33502e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.48586e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3752&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>HIF-2-alpha transcription factor network</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.20190e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48846e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0454&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.74945e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3691&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ATM Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44314e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.28680e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7730&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;284&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50472e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>VEGF, Hypoxia, and Angiogenesis</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79139e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.94386e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;300&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92275e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3462&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Hypoxia and p53 in the Cardiovascular system</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.85882e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.31498e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4948&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.60196e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3710&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MGI Expression: Detected</td>
    <td>TS13_arterial system</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.80617e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67235e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0585&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;295&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;533&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57944e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3691&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TS28_primary spermatocyte</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05075e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92370e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;543&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86584e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TS11_parietal endoderm</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.15767e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.93217e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0857&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.99526e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3814&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TS9_parietal endoderm</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12360e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23424e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1969&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;634&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.96024e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TS28_renal vesicle</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.96292e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.69298e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;634&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.96024e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes up-regulated upon overexpression of PARVB [GeneID=29780] in MDA-MB-231 cells (breast cancer) cultured in 3D Matrigel only.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.05218e-177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.13377e-174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0438&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1877&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78325e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2835&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.99%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10556e-141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.29775e-139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.52804e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4022&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in BEC (blood endothelial cells) compared to LEC (lymphatic endothelial cells).</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.05263e-94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.49193e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0704&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;978&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.30937e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 480 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94679e-88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.51885e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1816&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;815&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;223&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74337e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with NRG1 [GeneID=3084].</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.90023e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.37346e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0088&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.04826e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3764&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Set 'Myc targets1': targets of c-Myc [GeneID=4609] identified by
 ChIP on chip in cultured cell lines, focusing on E-box-containing 
genes; high affinity bound subset</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.09106e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.04852e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0668&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;717&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.87%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;981&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.21039e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.54817e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.06039e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4064&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;454&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;513&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.29477e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2532&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 40 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.92703e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15759e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7576&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;353&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.90255e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.14095e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44389e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4451&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;428&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.71%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;397&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.18201e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in five primary endothelial cell types (lung, aortic, iliac, dermal, and colon) by TNF [GeneID=7124].</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.85929e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.48113e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0442&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;628&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.22521e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in DU-145 cells (prostate cancer) in the 
absence and presence of a dominant negative form of AKT1 [GeneID=207] 
upon exposure to HGF [GeneID=3082] for 48 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34169e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.18282e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2281&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;803&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73328e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3728&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in macrophages by aerolysin-related cytotoxic enterotoxin (Act) from Aeromonas hydrophila.</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.25265e-52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.80452e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3254&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;375&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.01980e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3602&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Top genes up-regulated in liver tissue from mice with knockout of ZMPSTE24 [GeneID=10269].</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.14345e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.05983e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0204&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;717&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14473e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3830&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes known to be induced by hypoxia</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.09633e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46596e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;452&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49741e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3718&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 120 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;96&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.79030e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.27349e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4062&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;399&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.36431e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3895&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in brain tumors induced by retroviral delivery of PDGFB [GeneID=5155].</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.36302e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16631e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4714&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;318&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;445&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85313e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3962&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated by induction of exogenous BRCA1 in EcR-293 cells</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.41351e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85827e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1639&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;417&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.67%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.10820e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2941&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes specific to BEC (blood endothelium cells) repressed in BEC by expression of PROX1 [GeneID=5629] off adenovirus vector.</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64833e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.33172e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1802&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;396&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.26932e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4546&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Delayed early genes (DEG) which are coordinately down-regulated in multiple epithelial tumor types.</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.91725e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.56390e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9560&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;813&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73687e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in five primary endothelial cell types (lung, aortic, iliac, dermal, and colon) by IFNG [GeneID=3458].</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25944e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.56029e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1091&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;398&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39411e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4317&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Predicted Promoter Motifs</td>
    <td>Motif ATGCCCATATATGGWNNT matches SRF: serum response factor (c-fos serum response element-binding transcription factor)</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.50361e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.24721e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1934&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.94989e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1951&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>BZIP</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.59509e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71845e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.63291e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3550&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.73138e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.91799e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0949&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.41022e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Oncogenic Signatures</td>
    <td>Immune or inflammatory genes induced by NF-kappaB in primary keratinocytes and fibroblasts.</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26325e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.21651e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0030&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.32119e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.5015&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26131e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.03037e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1548&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;543&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;541&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.81406e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.86424e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62214e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;368&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.51121e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2257&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.56155e-54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.72543e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0547&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;566&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1025&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51261e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1592&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;149&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.04909e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20547e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2020&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.99752e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2968&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07058e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.29567e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0080&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;572&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.58216e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2551&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 ng/ml LPS (TLR4 agonist) versus monocytes treated with vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.51385e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.63189e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0573&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;535&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;825&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.64399e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1809&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 25,000 genomic regions picked 12,015 genes (67%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Disease Ontology</i> has 2,235 terms covering 7,886 (44%) of all 18,041 genes.</td>
    <td>2,235 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>PANTHER Pathway</i> has 152 terms covering 2,197 (12%) of all 18,041 genes.</td>
    <td>152 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MGI Expression: Detected</i> has 9,337 terms covering 11,602 (64%) of all 18,041 genes.</td>
    <td>9,337 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Predicted Promoter Motifs</i> has 615 terms covering 11,991 (66%) of all 18,041 genes.</td>
    <td>615 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Oncogenic Signatures</i> has 187 terms covering 10,315 (57%) of all 18,041 genes.</td>
    <td>187 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>K562</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/4.25.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>ribonucleoprotein complex binding</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.35256e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.67625e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.41409e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>unfolded protein binding</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.57549e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09887e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0005&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.91%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.69878e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3049&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ribosome binding</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.93757e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16538e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5481&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38397e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3915&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>polyubiquitin binding</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.97811e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.66651e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.75434e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3965&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>2 iron, 2 sulfur cluster binding</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.69677e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.25857e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67938e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>snRNA binding</td>
    <td nowrap="nowrap" align="right">&nbsp;426&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.51351e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.90747e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0766&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.80252e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26052e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53786e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0832&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;504&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23899e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral gene expression</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95668e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.83718e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3462&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;249&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.00%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.50116e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.29312e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.70962e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1331&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.49539e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.69640e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.31468e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30258e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>protein targeting to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36335e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82479e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0669&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;321&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64250e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.87%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, nonsense-mediated decay</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94695e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.57293e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0841&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;313&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;146&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.73211e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4067&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular response to topologically incorrect protein</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.99713e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.86297e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1472&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;249&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.31684e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3646&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>endoplasmic reticulum unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.09187e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18392e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;272&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.68211e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3582&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular response to unfolded protein</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.87781e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.83851e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0864&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;271&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.98945e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3592&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.65%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.20752e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17818e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3696&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;327&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.24106e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3569&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;109&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.21959e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12592e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0339&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;229&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.25501e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3537&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>activation of signaling protein activity involved in unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.79664e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53745e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3501&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;349&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.89114e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3542&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.21036e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.54485e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2638&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;494&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30960e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2849&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>translational termination</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.40518e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.73150e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1933&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.57889e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>viral transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;129&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39915e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13233e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2316&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.58552e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4091&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of DNA-dependent transcription in response to stress</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66937e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18559e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1606&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;642&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.80821e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3056&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of mitochondrial outer membrane permeabilization</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.49899e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.20057e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.28149e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>myeloid cell development</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.77632e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34671e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3795&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;650&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95115e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3499&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>signal transduction involved in DNA damage checkpoint</td>
    <td nowrap="nowrap" align="right">&nbsp;178&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.94360e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.72647e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1423&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;376&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.49074e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>DNA damage response, signal transduction by p53 class mediator resulting in cell cycle arrest</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.40987e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98877e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1441&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;390&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09916e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>mitochondrial membrane part</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22342e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.52312e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0776&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;431&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.72%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77885e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2817&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>PcG protein complex</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.31365e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.65175e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2782&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.96998e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mitochondrial respiratory chain</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17027e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90274e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2249&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.02211e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.29568e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13801e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1474&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.94703e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4018&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic mRNA processing body</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.56417e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.64182e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0396&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.88354e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3418&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>small ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.34527e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84715e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0846&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.41334e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytoplasmic stress granule</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.14169e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15959e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2497&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.27906e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3949&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mitochondrial intermembrane space</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.67796e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86840e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1527&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44869e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>BLOC complex</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.25493e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01442e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6082&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.45536e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3709&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mitochondrial ribosome</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.43149e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.00729e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0493&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.43366e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>exon-exon junction complex</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.63768e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.59236e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.59415e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cytosolic large ribosomal subunit</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.31246e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10122e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0023&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44869e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MLL1 complex</td>
    <td nowrap="nowrap" align="right">&nbsp;111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.24938e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.12205e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.02494e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Cul4-RING ubiquitin ligase complex</td>
    <td nowrap="nowrap" align="right">&nbsp;114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.00637e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.99391e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3901&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.09195e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>H4/H2A histone acetyltransferase complex</td>
    <td nowrap="nowrap" align="right">&nbsp;120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.00654e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.16939e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3218&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.18839e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>COPI-coated vesicle membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;124&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.65549e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.72919e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4738&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.19963e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.11%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>DNA-directed RNA polymerase III complex</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87583e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.89518e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.3837&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.19963e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.11%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>integral to mitochondrial membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.68607e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.47913e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.26251e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3993&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>COPI-coated vesicle</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.14522e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.88312e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2338&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.15647e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>preribosome</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.26446e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.68982e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4652&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.45536e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3709&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>poikilocytosis</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07844e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64570e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5435&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;229&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.69797e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal DNA repair</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00208e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44113e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.88623e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3629&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased mean corpuscular volume</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.49286e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.78188e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.87441e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2747&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal mean corpuscular volume</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.17515e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.83660e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0521&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;452&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52182e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2580&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.82%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>abnormal red blood cell distribution width</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.08193e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.69542e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2273&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;284&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.30237e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2945&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>increased red blood cell distribution width</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76987e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25904e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2356&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.17296e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2900&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>increased cellular sensitivity to ultraviolet irradiation</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00705e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56350e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1605&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.56%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44939e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>decreased mean corpuscular hemoglobin</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07727e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.51219e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.73051e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3489&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>anisocytosis</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43965e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.44948e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4720&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33073e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>pancytopenia</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.87134e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08155e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4944&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11797e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Human Phenotype</td>
    <td>Progressive macrocephaly</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82407e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.63357e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0486&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;235&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17592e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.17%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Acute necrotizing encephalopathy</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.58658e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97469e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79051e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00910e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.57887e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3090&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;845&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.97440e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4380&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.21349e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.59081e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4284&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;744&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.54766e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;241&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.93%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of HDAC1</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.13063e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.45592e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;796&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.29818e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;256&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.55986e-89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73265e-87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4777&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;635&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.95401e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4364&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDB1</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.07606e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62695e-84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;736&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.48271e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4010&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;240&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CTBP1</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.35339e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.04557e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4556&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;550&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57625e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ANP32B</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.41855e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.89215e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3083&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;620&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18005e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NME2</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34682e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11344e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5826&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.96707e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4339&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.69650e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.58549e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5894&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;474&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.90%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.97600e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4330&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;144&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAN</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.76451e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.83706e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0461&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;772&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.90858e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4377&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;271&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAB1A</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23138e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.04462e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1781&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;652&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.54132e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4281&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of NPM1</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01625e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.09956e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3760&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;528&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.87290e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4344&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACP1</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48669e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.96761e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;697&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.67430e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;213&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.70%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33261e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.34719e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7844&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;366&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24012e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DAP3</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17521e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.53231e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;563&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.23563e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4282&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.54%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.79746e-63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.53430e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5989&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;409&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.81320e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.02%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48887e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02736e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1825&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.09028e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of EIF3S2</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.58063e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.00876e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0064&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;686&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79826e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4255&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;243&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.94%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of FBL</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.21540e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.82598e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;413&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.67599e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4327&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PHB</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.75019e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.45137e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7466&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;353&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.19063e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3953&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">PANTHER Pathway</td>
    <td>Apoptosis signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46388e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22509e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0592&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38835e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2644&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Transcription regulation by bZIP transcription factor</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.23938e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70193e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7407&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;162&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.88850e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3803&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Interferon-gamma signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47822e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.49379e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2950&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.70171e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3400&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>JAK/STAT signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15953e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.10310e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5447&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.09369e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>De novo purine biosynthesis</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.71478e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.58496e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.70171e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3400&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>General transcription regulation</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06359e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.65666e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3533&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.12273e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3965&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">BioCyc Pathway</td>
    <td>purine nucleotides &lt;i&gt;de novo&lt;/i&gt; biosynthesis</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86238e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.18310e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6141&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86991e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3094&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>purine nucleotide salvage</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.38951e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.96658e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3467&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.86991e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3094&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>Genes involved in Metabolism of mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.21964e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.10496e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;583&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30509e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3958&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03831e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.42643e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;493&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78110e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3073&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;183&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;202&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL3-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78437e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.71073e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.7053&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;443&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.99639e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2827&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Processing of Capped Intron-Containing Pre-mRNA</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.76440e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14817e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;383&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.53%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77223e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.08%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.38701e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.50121e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;288&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.15%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.62339e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4296&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Translation</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68938e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.43747e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1400&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;411&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.12677e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4038&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;147&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Processing</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.00654e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17429e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1120&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;419&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64967e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Influenza Life Cycle</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.65295e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03835e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1069&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;370&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.21600e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I, RNA Polymerase III, and Mitochondrial Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.15016e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.41214e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3480&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03483e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>GMCSF-mediated signaling events</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.61026e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32847e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.59994e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Nonsense Mediated Decay Enhanced by the Exon Junction Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.03106e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.48945e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2671&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.18103e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Spliceosome</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.03621e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.80410e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0807&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;332&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65871e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SRP-dependent cotranslational protein targeting to membrane</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84383e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.10630e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1376&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.13738e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4037&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Unfolded Protein Response</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.98700e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71428e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4343&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;230&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.23608e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3681&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Deposition of New CENPA-containing Nucleosomes at the Centromere</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82243e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00234e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0558&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18034e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2336&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in trans-Golgi Network Vesicle Budding</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06255e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55483e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3088&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.17481e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Late Phase of HIV Life Cycle</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.47945e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.14551e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0641&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;292&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.17%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.49236e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>IL-2 Receptor Beta Chain in T cell Activation</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.20382e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.40968e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3675&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;203&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.81%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53738e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Golgi Associated Vesicle Biogenesis</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82887e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.89745e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2454&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57975e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3069&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Peptide chain elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07909e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.62334e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2384&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.97590e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4095&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Genes down-regulated in NB4 cells (acute promyelocytic leukemia,
 APL) in response to tretinoin [PubChem=444795]; based on Chip-seq data.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.42488e-248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.82493e-244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2425&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 8.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.59065e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3078&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;706&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;779&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.65%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91555e-148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63465e-145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2684&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.01%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.06103e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3659&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;372&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.98%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in lymphoblastoid cells from the European population compared to those from the Asian population.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.19395e-136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.20051e-134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0756&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1403&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 5.61%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.44652e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3532&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;452&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;482&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.62%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in K562 cells (lymphoblast) by MYC [GeneID=4609] in the presence of PSMD9 [GeneID=5715].</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.81860e-118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.70598e-116&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.0823&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;587&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;238&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.52900e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3301&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91493e-106&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.76813e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4491&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;773&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.09%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.94559e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic vs non-metastatic HNSCC (head and neck squamous cell carcinoma) samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66317e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.10827e-98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3446&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;796&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;326&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.67896e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1977&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.64%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in fibroblasts expressing mutant forms of ERCC3 [GeneID=2071] after UV irradiation.</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08194e-99&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.91561e-97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2959&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;824&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.61692e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;279&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Set 'Myc targets1': targets of c-Myc [GeneID=4609] identified by
 ChIP on chip in cultured cell lines, focusing on E-box-containing 
genes; high affinity bound subset</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60707e-92&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45736e-90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2657&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.45840e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2604&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.99986e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.49167e-75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3010&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;636&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;254&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36626e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;222&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.78%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes co-regulated in uterus during a time course response to progesterone [PubChem=5994]: SOM cluster 17.</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29813e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.55961e-70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4055&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;545&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.18%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;90&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.93938e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4038&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;179&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Down-regulated by induction of exogenous BRCA1 in EcR-293 cells</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.61614e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.26474e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4960&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;481&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.92%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;160&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.01858e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3481&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in BJAB cells (B-lymphoma) after leucine [PubChem=857] deprivation.</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.42141e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44898e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2419&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;594&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.07205e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4043&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;181&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes encoding mRNA transcripts specifically bound by DCP2 [GeneID=167227].</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.28711e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.68048e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5102&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01542e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in macrophages by aerolysin-related cytotoxic enterotoxin (Act) from Aeromonas hydrophila.</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.94676e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87924e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4714&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;590&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85550e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Top genes up-regulated in liver tissue from mice with knockout of ZMPSTE24 [GeneID=10269].</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.70492e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.59712e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.06%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;797&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.38526e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2911&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.28977e-45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16709e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1838&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;412&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;586&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74771e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1935&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Selected genes changed in K562 (immortalized erythroleukemia) 
cells induced by hemin [PubChem=26945] treatment to express erythroid 
properties.</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52415e-44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.54006e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2602&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;375&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.87997e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Clusters 1 and 2: genes up-regulated in B2264-19/3 cells 
(primary B lymphocytes) within 30-60 min after activation of LMP1 (an 
oncogene encoded by Epstein-Barr virus, EBV).</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.44344e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44157e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4498&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;808&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52668e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.44%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Top 50 most up-regulated genes in human platelet cells.</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.16957e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.13226e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.3891&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.38173e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2927&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated by 2-methoxyestradiol (2ME2) [PubChem=1573]
 in the MM.1S cell line (multiple myeloma) sensitive to dexamethasone 
[PubChem=5743].</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30702e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.63693e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1908&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;374&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.50%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;427&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00864e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2515&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.78%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Predicted Promoter Motifs</td>
    <td>Motif ATGCCCATATATGGWNNT matches SRF: serum response factor (c-fos serum response element-binding transcription factor)</td>
    <td nowrap="nowrap" align="right">&nbsp;21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58176e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.63229e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0922&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;186&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.99453e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2074&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">InterPro</td>
    <td>Ribosomal protein S5 domain 2-type fold</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.53194e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.27999e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0450&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78469e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>BZIP</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.96605e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.47887e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.77%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71295e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3375&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>RPL</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.99395e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.57777e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0052&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36852e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MRPL</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.83174e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.95976e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0362&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.39%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.59683e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MRPS</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.37601e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.20124e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0469&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.96920e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4430&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43256e-122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.64620e-119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.4907&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;510&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.12407e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3841&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;188&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.50%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19476e-104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14100e-101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7954&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.66342e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3847&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97340e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25640e-100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6270&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;662&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.65%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;452&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.62690e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 ng/ml LPS (TLR4 agonist) versus monocytes treated with vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08643e-87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.18768e-85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4495&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;637&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;305&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.68738e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2702&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;169&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with anti-TREM1 
[GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist).</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.66221e-86&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.01696e-83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3619&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;673&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.69%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;210&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.97782e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2919&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with type 1 diabetes at the time of the 
diagnosis versus those at 4 months later.</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11218e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.72379e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;802&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;251&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.93480e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2802&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with type 1 diabetes at the time of the 
diagnosis versus those at 1 month later.</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60519e-74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.37989e-72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1063&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;743&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.75640e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3690&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.39164e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28726e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1225&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.78%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;391&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.44043e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2486&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with anti-TREM1 [GeneID=54210] versus monocytes treated wth vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.42595e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36373e-66&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;611&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;511&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.29019e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.31%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.07760e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.69821e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;602&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;281&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43312e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2728&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of dendritic cells (DC) 
stimulated with LPS (TLR4 agonist) at 4 h versus DC cells stimulated 
with Pam3Csk4 (TLR1/2 agonist) at 4 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18472e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.06902e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;562&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.08507e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3085&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with acute influenza infection versus PBMC 
from patients with acute E. coli infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.50422e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.08697e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3599&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;450&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;529&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.81067e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2475&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.07%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
5000 ng/ml LPS (TLR4 agonist) versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.29501e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.85962e-55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0498&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;605&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;289&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02731e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2720&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;194&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 
ng/ml LPS (TLR4 agonist) versus monocytes treated with control IgG.</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.43951e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.06056e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;606&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26830e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2466&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;165&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;191&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of control dendritic cells (DC)
 at 1 h versus those stimulated with Pam3Csk4 (TLR1/2 agonist) at 1 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62747e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.00739e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0381&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;550&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;155&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.16123e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3063&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;172&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;190&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.38%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of unstimulated NK cells versus those stimulated with IL2 [GeneID=3558] at 16 h.</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.10905e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.95703e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;563&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.07717e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3856&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.54%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 25,000 genomic regions picked 12,502 genes (69%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Human Phenotype</i> has 6,146 terms covering 2,822 (16%) of all 18,041 genes.</td>
    <td>6,146 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>PANTHER Pathway</i> has 152 terms covering 2,197 (12%) of all 18,041 genes.</td>
    <td>152 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>BioCyc Pathway</i> has 332 terms covering 1,034 (6%) of all 18,041 genes.</td>
    <td>332 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Predicted Promoter Motifs</i> has 615 terms covering 11,991 (66%) of all 18,041 genes.</td>
    <td>615 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>InterPro</i> has 9,422 terms covering 17,343 (96%) of all 18,041 genes.</td>
    <td>9,422 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>

<details><summary>NHEK</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/5.25.all.png">
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr valign="top">
    <th width="200" nowrap="nowrap" align="left">Ontology</th>
    <th width="300" nowrap="nowrap" align="left"># Term Name</th>
    <th align="left">Binom Rank</th>
    <th align="left">Binom Raw P-Value</th>
    <th align="left">Binom FDR Q-Val</th>
    <th align="left">Binom Fold Enrichment</th>
    <th align="left">Binom Observed Region Hits</th>
    <th align="left">Binom Region Set Coverage</th>
    <th align="left">Hyper Rank</th>
    <th align="left">Hyper FDR Q-Val</th>
    <th align="left">Hyper Fold Enrichment</th>
    <th align="left">Hyper Observed Gene Hits</th>
    <th align="left">Hyper Total Genes</th>
    <th align="left">Hyper Gene Set Coverage</th>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Molecular Function</td>
    <td>unfolded protein binding</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.00023e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30553e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0446&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;232&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;72&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34117e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2658&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>polyubiquitin binding</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44282e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23413e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1455&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;100&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86895e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3741&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>rRNA binding</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.34847e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.49877e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2796&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.70453e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3710&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Biological Process</td>
    <td>nuclear-transcribed mRNA catabolic process</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28073e-43&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15658e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0047&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;485&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.08746e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>extrinsic apoptotic signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.77642e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.08380e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4695&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;262&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.05%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;484&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36023e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.57386e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.55969e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;361&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.84626e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3873&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.65198e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.01086e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1741&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;451&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.26298e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3154&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.49%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of nuclease activity</td>
    <td nowrap="nowrap" align="right">&nbsp;265&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.28774e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.07320e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0938&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.79%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;507&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.91651e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2878&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>activation of signaling protein activity involved in unfolded protein response</td>
    <td nowrap="nowrap" align="right">&nbsp;278&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.53800e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70420e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1386&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.73%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;483&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.34886e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of mRNA 3'-end processing</td>
    <td nowrap="nowrap" align="right">&nbsp;298&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.15560e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45586e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9457&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;821&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.96551e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cell-substrate junction assembly</td>
    <td nowrap="nowrap" align="right">&nbsp;324&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45329e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.68281e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0357&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;177&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.71%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;843&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.47666e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3057&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of mitochondrial outer membrane permeabilization</td>
    <td nowrap="nowrap" align="right">&nbsp;342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.09045e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.85919e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1093&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;156&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.62%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;843&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.47666e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3057&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>regulation of mRNA 3'-end processing</td>
    <td nowrap="nowrap" align="right">&nbsp;354&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.42616e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.20595e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5713&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;712&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11753e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of mRNA processing</td>
    <td nowrap="nowrap" align="right">&nbsp;530&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.55938e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.01130e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0574&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;556&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.95551e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>extrinsic apoptotic signaling pathway via death domain receptors</td>
    <td nowrap="nowrap" align="right">&nbsp;545&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.52960e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05925e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1483&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;853&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.69290e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3559&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>cellular metabolic compound salvage</td>
    <td nowrap="nowrap" align="right">&nbsp;578&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.45278e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62406e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0021&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;857&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.68484e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3267&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>exonucleolytic nuclear-transcribed mRNA catabolic process involved in deadenylation-dependent decay</td>
    <td nowrap="nowrap" align="right">&nbsp;673&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.36212e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.21553e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2704&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;720&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14895e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3676&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>retrograde vesicle-mediated transport, Golgi to ER</td>
    <td nowrap="nowrap" align="right">&nbsp;700&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.97121e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.03971e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3057&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.28%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;740&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.38690e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4050&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>termination of RNA polymerase II transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;712&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.56687e-10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25615e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0067&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.38%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;372&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.43200e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4050&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA poly(A) tail shortening</td>
    <td nowrap="nowrap" align="right">&nbsp;734&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.49367e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12452e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0953&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;660&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33762e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>positive regulation of DNA-dependent transcription, elongation</td>
    <td nowrap="nowrap" align="right">&nbsp;760&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.02969e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.16183e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.25%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;531&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.81801e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>nuclear-transcribed mRNA catabolic process, exonucleolytic</td>
    <td nowrap="nowrap" align="right">&nbsp;767&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.29061e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.47901e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.31%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;684&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64048e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3710&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Golgi vesicle budding</td>
    <td nowrap="nowrap" align="right">&nbsp;1003&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.81922e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.93446e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2700&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;773&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86617e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.13%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">GO Cellular Component</td>
    <td>nucleolar part</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.13467e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.58340e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6014&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;97&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.73520e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3850&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>exon-exon junction complex</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.63768e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.18861e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.5365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;126&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44987e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.14%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>exosome (RNase complex)</td>
    <td nowrap="nowrap" align="right">&nbsp;138&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23492e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13201e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1777&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.98788e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3955&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Mouse Phenotype</td>
    <td>abnormal epidermis stratum spinosum morphology</td>
    <td nowrap="nowrap" align="right">&nbsp;63&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.36184e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.71160e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1622&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;308&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.34691e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2623&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">Disease Ontology</td>
    <td>keratosis</td>
    <td nowrap="nowrap" align="right">&nbsp;95&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.44209e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.09796e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;128&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.08283e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2486&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Cancer Neighborhood</td>
    <td>Neighborhood of AP2M1</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.84088e-50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.04352e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0563&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;527&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.74495e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3877&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;205&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;217&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.67%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of SERPINB5</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.24885e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.49029e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1055&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;201&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.62946e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of FBL</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.88910e-42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.94165e-40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2221&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.18958e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;139&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CDH3</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.85369e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.57963e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9612&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;161&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.76929e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK2B</td>
    <td nowrap="nowrap" align="right">&nbsp;17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30623e-38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.28095e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.96%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.56737e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4253&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;98&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;101&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of MAP2K2</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.10914e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.74001e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2975&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;302&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.58480e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3792&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;123&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.00%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of ACTG1</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.76909e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32696e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1414&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;337&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.78126e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.99%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PHB</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.42267e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84085e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2097&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;284&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.57688e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3111&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;108&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.88%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of APEX1</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26827e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.46365e-28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1440&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.10%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.69085e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4187&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PSME1</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.78564e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.33660e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1505&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47836e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4351&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DDX5</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.92207e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.21026e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0347&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.98%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.03310e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4463&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of UBE2I</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.66965e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.06927e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.1341&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15392e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4363&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;45&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.36%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of JUND</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.42459e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.91722e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1919&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.64188e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.53%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of DAP</td>
    <td nowrap="nowrap" align="right">&nbsp;61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.61770e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.23239e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0099&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.80%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;125&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.54432e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3435&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.61%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of USP5</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.10786e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.20654e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4616&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.51%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.51590e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3842&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.40%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of CSNK1D</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.18237e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.99834e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0610&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.67%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;206&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.60863e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2560&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of RAD21</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.44358e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.93475e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3806&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13928e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.30%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PPP1CC</td>
    <td nowrap="nowrap" align="right">&nbsp;87&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78665e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.76897e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.98324e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4174&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PFN1</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.45085e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17586e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.80775e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4401&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Neighborhood of PPP2R4</td>
    <td nowrap="nowrap" align="right">&nbsp;91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.58285e-14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.15042e-13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1508&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;121&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;110&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98037e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4406&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Pathway</td>
    <td>a6b1 and a6b4 Integrin signaling</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.84842e-37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.87983e-35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3734&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.13%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;248&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53976e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2773&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Signaling by TGF-beta Receptor Complex</td>
    <td nowrap="nowrap" align="right">&nbsp;7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.75110e-36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27307e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1835&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;323&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.29%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.11564e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3465&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;55&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.45%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Validated transcriptional targets of TAp63 isoforms</td>
    <td nowrap="nowrap" align="right">&nbsp;8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.06775e-34&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.06179e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2601&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;285&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.73836e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3858&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.41%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Fas Signaling Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.78896e-32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.36142e-30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3075&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;258&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.03%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;117&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.28591e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3082&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>mTOR signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;13&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.19098e-31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.28623e-29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0862&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;307&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;237&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44323e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2313&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>ERK1/ERK2 MAPK Pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.94749e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.43168e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3037&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;215&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;246&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.53744e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Regulation of mRNA Stability by Proteins that Bind AU-rich Elements</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.55461e-27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.54005e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0966&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;261&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.80386e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3465&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;84&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in mRNA Splicing</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11185e-26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.72443e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1961&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;233&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.93%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.86675e-12&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4277&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;104&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;107&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.85%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Unfolded Protein Response</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.57755e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.14653e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2332&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.84%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;122&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.17371e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2781&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Stabilization and expansion of the E-cadherin adherens junction</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.11266e-25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.93422e-23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0359&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;260&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.04%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;319&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.25858e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2591&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.29%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Erk1/Erk2 Mapk Signaling pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.63031e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.94197e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3301&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;171&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.68%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;220&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22355e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3640&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.21%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>C-MYC pathway</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.91200e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.35891e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5816&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;131&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.52%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40906e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in SMAD2/SMAD3:SMAD4 heterotrimer regulates transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;42&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.60790e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.39105e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4266&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;287&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.40906e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3514&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Transcriptional activity of SMAD2/SMAD3:SMAD4 heterotrimer</td>
    <td nowrap="nowrap" align="right">&nbsp;54&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.36123e-19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.21634e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0626&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;189&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;180&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.31349e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3465&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.27%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in Deadenylation-dependent mRNA decay</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09604e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.49444e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3684&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;135&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;114&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.16835e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3687&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;44&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Tumor Necrosis Factor Pathway.</td>
    <td nowrap="nowrap" align="right">&nbsp;60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.34232e-18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.39531e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3077&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;136&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;207&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.45064e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3676&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;27&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I Transcription</td>
    <td nowrap="nowrap" align="right">&nbsp;64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26559e-17&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.61028e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2794&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;137&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.04573e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3096&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;83&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in TGF-beta receptor signaling activates SMADs</td>
    <td nowrap="nowrap" align="right">&nbsp;75&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.12997e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.98875e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;148&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.01881e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3465&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes involved in RNA Polymerase I Promoter Opening</td>
    <td nowrap="nowrap" align="right">&nbsp;76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.22389e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.86255e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.9525&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;151&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.79563e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2946&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;52&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Induction of apoptosis through DR3 and DR4/5 Death Receptors</td>
    <td nowrap="nowrap" align="right">&nbsp;79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11818e-16&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.21013e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3438&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;118&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;335&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.21964e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2853&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;28&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MGI Expression: Detected</td>
    <td>TS23_rest of skin epidermis</td>
    <td nowrap="nowrap" align="right">&nbsp;19&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.44115e-71&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.19963e-68&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0686&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;742&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.97%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;365&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.71030e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2437&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.03%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>TS22_nephron</td>
    <td nowrap="nowrap" align="right">&nbsp;193&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.47123e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.11753e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0651&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.34%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;677&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.30091e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.12%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Perturbation</td>
    <td>Down-regulated genes that vary between HNSCC (head and neck 
squamous cell carcinoma) groups formed on the basis of their level of 
pathological differentiation: well vs poorly differentiated tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.97038e-185&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.69479e-182&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1845&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1684&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.83173e-22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;330&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.69%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated upon overexpression of PARVB [GeneID=29780] in MDA-MB-231 cells (breast cancer) cultured in 3D Matrigel only.</td>
    <td nowrap="nowrap" align="right">&nbsp;5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.32900e-175&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.94149e-173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0384&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1872&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 7.49%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.19838e-15&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2521&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;420&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.91%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Class III of genes transiently induced by EGF [GeneID =1950] in 184A1 cells (mammary epithelium).</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.78809e-170&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.68452e-167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0858&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1720&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 6.88%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67506e-20&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;200&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;211&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.63%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in metastatic vs non-metastatic HNSCC (head and neck squamous cell carcinoma) samples.</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.92692e-143&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.09402e-140&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6539&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;901&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.60%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.30762e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2608&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;212&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;247&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.73%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with NRG1 [GeneID=3084].</td>
    <td nowrap="nowrap" align="right">&nbsp;14&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.63176e-130&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.11295e-127&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2948&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1075&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.30%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;197&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.08131e-11&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3290&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;152&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;168&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.24%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Housekeeping genes identified as expressed across 19 normal tissues.</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.53727e-115&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.22174e-112&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0964&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1158&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 4.63%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;35&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.27335e-33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3717&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;393&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.99%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 480 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;26&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.51346e-105&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.13357e-103&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3047&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;861&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.44%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;227&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.23613e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3157&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;146&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.19%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in MCF7 cells (breast cancer) after stimulation with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;31&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;8.61238e-93&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.34583e-91&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8907&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;506&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.02%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.61537e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3377&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.42%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in macrophages by aerolysin-related cytotoxic enterotoxin (Act) from Aeromonas hydrophila.</td>
    <td nowrap="nowrap" align="right">&nbsp;36&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.33821e-82&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.11937e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7410&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;488&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.95%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;670&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.91947e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2615&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;85&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in Calu-6 cells (lung cancer) at 1 h time point after TNF [GeneID=7124] treatment.</td>
    <td nowrap="nowrap" align="right">&nbsp;37&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.25062e-80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.13705e-78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.5345&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;549&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.20%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;375&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.66672e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3978&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.48%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Metastatic propensity markers of head and neck squamous cell 
carcinoma (HNSCC): down-regulated in metastatic vs non-metastatic 
tumors.</td>
    <td nowrap="nowrap" align="right">&nbsp;40&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.32784e-79&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.95772e-77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7581&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;466&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.86%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;370&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.44817e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3587&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;80&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.60%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes whose expression peaked at 120 min after stimulation of HeLa cells with EGF [GeneID=1950].</td>
    <td nowrap="nowrap" align="right">&nbsp;50&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.70453e-69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.14681e-67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.8132&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;394&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.58%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;886&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.72154e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2497&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in SKOV3ip1 cells (ovarian cancer) upon knockdown of EZH2 [GeneID=2146] by RNAi.</td>
    <td nowrap="nowrap" align="right">&nbsp;57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.24619e-65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.35469e-64&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1816&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;603&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.41%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1275&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.85309e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.0891&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;263&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.59%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Proteins secreted in co-culture of LKR-13 tumor cells (non-small cell lung cancer, NSCLC) and MLg stroma cells (fibroblasts).</td>
    <td nowrap="nowrap" align="right">&nbsp;67&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.65140e-62&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.33124e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.4276&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;458&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.83%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;510&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.32299e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2480&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;113&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;133&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.92%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in 786-0 cells (renal carcinoma, RCC) upon 
expression of VHL [GeneID=7428] off a retroviral vector under normoxia 
(normal oxygen) condition.</td>
    <td nowrap="nowrap" align="right">&nbsp;69&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.96401e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.57528e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.2228&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;541&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.16%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;312&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.76382e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3045&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;119&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;134&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.97%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in head and neck tumor samples which clustered around known hypoxia genes.</td>
    <td nowrap="nowrap" align="right">&nbsp;70&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.13138e-61&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02428e-59&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7609&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;358&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.43%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;387&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.33885e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3369&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;81&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;89&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.66%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in HFK cells (primary keratinocytes) in response to UVB irradiation.</td>
    <td nowrap="nowrap" align="right">&nbsp;74&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.21249e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.91497e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6859&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;367&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.47%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;608&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.78046e-4&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;32&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;33&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.26%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in non-metastatic breast cancer tumors 
having type 1 amplification in the 20q13 region; involves ZNF217 
[GeneID=7764] locus only.</td>
    <td nowrap="nowrap" align="right">&nbsp;77&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.76790e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.64613e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0214&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;638&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.55%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;415&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.78036e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1829&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;244&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;303&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.99%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Clusters 1 and 2: genes up-regulated in B2264-19/3 cells 
(primary B lymphocytes) within 30-60 min after activation of LMP1 (an 
oncogene encoded by Epstein-Barr virus, EBV).</td>
    <td nowrap="nowrap" align="right">&nbsp;78&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.27781e-57&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.51096e-56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.7291&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;342&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.37%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;827&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.87129e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2655&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;56&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;65&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.46%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Delayed early genes (DEG) which are coordinately down-regulated in multiple epithelial tumor types.</td>
    <td nowrap="nowrap" align="right">&nbsp;94&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.35054e-53&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.34630e-51&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.2938&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;234&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.94%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;850&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.88921e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;18&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.15%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">InterPro</td>
    <td>G-patch domain</td>
    <td nowrap="nowrap" align="right">&nbsp;208&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.59547e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.98762e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0484&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.23%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;25&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3.67526e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4689&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.20%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">HGNC Gene Families</td>
    <td>BZIP</td>
    <td nowrap="nowrap" align="right">&nbsp;1&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.44580e-24&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.12509e-21&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.3293&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;184&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.74%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.47827e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.3972&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.32%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>MRPS</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.94205e-9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;9.28301e-8&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0239&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;88&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.35%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.16305e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.4199&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;29&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;30&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 0.24%&nbsp;</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
    <td valign="top" nowrap="nowrap">MSigDB Immunologic Signatures</td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from patients with type 1 diabetes at the time of the 
diagnosis versus those at 4 months later.</td>
    <td nowrap="nowrap" align="right">&nbsp;3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.13578e-76&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.63312e-73&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0786&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;783&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 3.13%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;250&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.67146e-7&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2504&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;166&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.35%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 
anti-TREM1 [GeneID=54210] and 5000 ng/ml LPS (TLR4 agonist) versus 
monocytes treated with vehicle (control).</td>
    <td nowrap="nowrap" align="right">&nbsp;9&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.02693e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.17938e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.1905&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;552&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.21%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1451&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.34402e-2&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.0923&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;145&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;195&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.18%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in peripheral blood mononuclear cells (PBMC) 
from patients with type 1 diabetes at the time of diagnosis versus those
 with type 2 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;10&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.52541e-60&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.91352e-58&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.6283&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;384&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.54%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;428&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;5.19959e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2216&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;163&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;196&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.33%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of monocytes treated with 1 ng/ml LPS (TLR4 agonist) versus monocytes treated with vehicle.</td>
    <td nowrap="nowrap" align="right">&nbsp;22&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.40244e-49&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.42666e-47&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0304&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;528&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.11%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1077&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.30940e-3&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.1476&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;150&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;192&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.22%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes down-regulated in comparison of peripheral blood 
mononuclear cells (PBMC) from patients with acute E. coli infection 
versus PBMC from patients with acute S. aureus infection.</td>
    <td nowrap="nowrap" align="right">&nbsp;23&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.26908e-48&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.05389e-46&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;536&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 2.14%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;636&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;6.89066e-5&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2057&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;142&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;173&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.16%&nbsp;</td>
  </tr>
  <tr>
    <td></td>
    <td>Genes up-regulated in comparison of peripheral blood mononuclear
 cells (PBMC) from healthy donors versus PBMCs from patients with type 2
 diabetes at the time of diagnosis.</td>
    <td nowrap="nowrap" align="right">&nbsp;38&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;4.32925e-41&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.17602e-39&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;2.0351&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;439&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.76%&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;461&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;7.48573e-6&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;1.2167&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;164&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp;198&nbsp;</td>
    <td nowrap="nowrap" align="right">&nbsp; 1.34%&nbsp;</td>
  </tr>
</tbody></table>
<p>
</p><table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr>
    <td>
      The test set of 25,000 genomic regions picked 12,282 genes (68%) of all 18,041 genes.
</td><td></td>
  </tr>
  <tr>
    <td><i>GO Molecular Function</i> has 3,688 terms covering 15,090 (84%) of all 18,041 genes.</td>
    <td>3,688 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Biological Process</i> has 10,440 terms covering 15,441 (86%) of all 18,041 genes.</td>
    <td>10,440 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>GO Cellular Component</i> has 1,265 terms covering 16,807 (93%) of all 18,041 genes.</td>
    <td>1,265 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Mouse Phenotype</i> has 7,918 terms covering 7,524 (42%) of all 18,041 genes.</td>
    <td>7,918 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>Disease Ontology</i> has 2,235 terms covering 7,886 (44%) of all 18,041 genes.</td>
    <td>2,235 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Cancer Neighborhood</i> has 427 terms covering 4,758 (26%) of all 18,041 genes.</td>
    <td>427 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Pathway</i> has 1,320 terms covering 8,117 (45%) of all 18,041 genes.</td>
    <td>1,320 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MGI Expression: Detected</i> has 9,337 terms covering 11,602 (64%) of all 18,041 genes.</td>
    <td>9,337 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Perturbation</i> has 3,364 terms covering 17,091 (95%) of all 18,041 genes.</td>
    <td>3,364 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>InterPro</i> has 9,422 terms covering 17,343 (96%) of all 18,041 genes.</td>
    <td>9,422 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>HGNC Gene Families</i> has 478 terms covering 7,310 (41%) of all 18,041 genes.</td>
    <td>478 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
  <tr>
    <td><i>MSigDB Immunologic Signatures</i> has 1,910 terms covering 16,609 (92%) of all 18,041 genes.</td>
    <td>1,910 ontology terms were tested (100%) using an annotation count range of [1, Inf].</td>
  </tr>
</tbody></table>
<table width="100%" cellspacing="0" cellpadding="1" border="1">
  <tbody><tr><td>
GREAT version 3.0.0
  </td></tr>
  <tr><td>
Species assembly: hg19
  </td></tr>
  <tr><td>
Association rule: Basal+extension: 5000 bp upstream, 1000 bp downstream,
 1000000 bp max extension, curated regulatory domains included
  </td></tr>
</tbody></table>
</p>
</details>
<br><br>
**Top 25000 peaks as test set, open chromatin region as background set**
<details><summary>GM12878</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/1.25.bg.png">
No terms found
</p>
</details>

<details><summary>H1-hESC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/2.25.bg.png">
No terms found
</p>
</details>

<details><summary>HUVEC</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/3.25.bg.png">
No terms found
</p>
</details>

<details><summary>K562</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/4.25.bg.png">
No terms found
</p>
</details>

<details><summary>NHEK</summary>
<p>
<img src="https://github.com/frnkhu/h3k27ac_go/raw/master/img/5.25.bg.png">
No terms found
</p>
</details>

### Interpretation
So it would seem like using cell-specific OCR as background removed the sampling bias that gave rise to term associations when using the whole genome as the background set.