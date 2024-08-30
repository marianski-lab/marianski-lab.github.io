---
layout: default
---

# Research focus at Marianski group

---

The research interest at Marianski lab at Hunter College CUNY ranges from a single bond formation under applied mechanical force to noncovalent interactions between the most complex biomolecules in biology. The tools we apply to investigate these problems are tailored to the specific demands of these problems. For instance, investigating a bond formation process necessitates methods that explicitly consider the molecular electronic structure, such as Density Functional Theory (DFT). On the other end of the spectrum, understanding recognition between large biomolecules, such as binding of synthetic carbohydrate receptors to a glycan portion of a protein, merits methods of classical molecular simulations. Finally, some other problems, such as glycoside reactions in an enzymatic center under mechanical stress, will require both quantum and classical approaches merged in a QM/MM scheme.

<figure class="w-100 tc">
 <img src="/assets/img/Fig1_overview.png" alt="drawing"/>
</figure>


### 1. Mechanochemistry: Altering organic reactions with mechanical forces

Background: The organic solvents employed in the great majority of organic reactions carried out in industry account for >60% of all chemical manufacturing waste. Because of the energy demand of so-called solvothermal syntheses, where solvent and heat drive reactions, the chemical industry consumes 37% of the total energy used in manufacturing. Replacing solvothermal with mechanically-activated organic chemistry – where force, rather than heat and solvent, drives the making and breaking of covalent bonds – can solve the waste and energy challenges of organic synthesis. Mechanochemically-activated conditions can also yield stereoisomers and regioisomers that are not favored under solvothermal conditions. Despite its many potential advantages, significant gaps in the understanding of reaction kinetics under mechanochemical activation limits adoption of mechanochemistry in chemical synthesis and manufacturing. 

This project is a part of a new NSF CCI: [Center for the Mechanical Control of Chemistry](https://www.chem.tamu.edu/cmcc/).

<figure class="third">
 <img src="/assets/img/DA.png" alt="drawing"/>
</figure>

#### Key papers:

> [2] **''Kinetics of primary mechanochemical covalent-bond-forming reactions''**
> Y. Zholdassov, R. W. Krow, M. A. Shlain, M. Patel, M. Marianski, A. B. Brauschweig
> _RSC Mechanochemistry_ **2024**, 1, 11-32
> doi: [10.1039/D3MR00018D](https://pubs.rsc.org/en/content/articlelanding/2024/mr/d3mr00018d)
>
> [1] **''Acceleration of Diels-Alder Reactions by Mechanical Distortion''**
> Y. S. Zholdassov, L. Yuan, S. R. Garcia, R. W. Kwok, A. Boscoboinik, D. J. Valles, M. Marianski, A. Martini, R. W. Carpick, A. B. Braunschweig 
> _Science_, **2023**, 380, p.~1053
> doi: [10.1126/science.adf52](https://www.science.org/doi/full/10.1126/science.adf5273)

### 2. Glycosylation Reaction: Reviving the reaction mechanism with molecular simulations

Carbohydrates - or glycans - play an essential role in a variety of biochemical processes, such as cell-cell communication, and immune system recognition. Being the identification card of a cell, glycans have given rise to over 170 commercial drugs and vaccines that exploit their functions. However,
carbohydrate-based drugs and vaccines remain niche on account of their complex and time-consuming synthesis, which necessitates scrupulous control over the regio- and stereoselctivity of the glycosidic bond formation.

The glycosylation reaction couples a glycosyl donor to an acceptor and proceeds through an idiosyncratic glycosyl-donor intermediate, which is believed to exist as a continuum of potential intermediates. The dominant structure will then orchestrate the reaction mechanism, and the ability to in fluence this dominant intermediate is essential to establish better stereochemical control over the reaction. In previous work, by combining high-throughput DFT calculations, and a cryogenic-ion IR spectroscopy (prof. Kevin Pagel/FHI of the Max Planck Society, Berlin), we have shown that the glycosyl donors intermediates equipped with the protecting groups at positions C2[1] or C4[2] adopt a dioxolenium-type of a structure.

Importantly, we demonstrated that the formation of this type of an intermediate correlates with the stereoselectivity of the glycosylation reaction, which proofs that the fine-tuning of the stereoelectronic properties of the protecting groups can significantly influence the outcome of the reaction. 

<figure class="third">
<img src="/assets/img/glycR_nomagic.png" alt="drawing"/>
</figure>

####  Key papers:

> [2] **''Direct Evidence for Remote Participation in Galactose Building Blocks during Glycosylation Revealed by Cryogenic Vibrational Spectroscopy''** 
> M. Marianski, E. Mucha, K. Greis, D. S. Moon, A. Pardo, C. Kirschbaum, D. A. Thomas, G. Meijer, G. von Helden, K. Gillmore, P. Seeberger, K. Pagel,
> _Angewandte Chemie International Edition_, **2020**, 59, pp.~6166-6171
>doi: [10.1002/anie.201916245](https://onlinelibrary.wiley.com/doi/10.1002/anie.201916245)
>
> [1] **''Unravelling the structure of glycosyl cations via cold-ion infrared spectroscopy''**
> E. Mucha\*, M.  Marianski\*, F. Xu, D. A. Thomas, G. Meijer, G. von Helden, P. H. Seeberger, K. Pagel,
>_Nature Communications_, **2018**, 9, p.~4174
> doi: [10.1038/s41467-018-06764-3](https://www.nature.com/articles/s41467-018-06764-3)


### 3. Glycoanalysis: Fingerprints please – fragment-based analysis of glycans in a gas phase

Glycan expression and composition in the glycocalyx – the layer of glycolipids, glycoproteins, and glycopolymers on the surface of all eukaryotic cells as well as many bacteria and viruses – have been correlated to developmental status, cell type, and the disease state of a cell. These cell-, tissue-, and species-specific inventories of glycans comprise the “sugar code”, but much of this encoded information remains undeciphered, leaving critical gaps in knowledge about biological processes and networks that could be exploited to treat disease. Thus, there remains a need for new tools to ana
lyze and utilize the information buried within the glycocalyx. One promising technique is combining gas-phase analysis of carbohydrates, using techniques such as mass-spectrometry (MS), ion-mobility spectrometry (IMS) or action IR spectroscopy, with high-throughput DFT calculations. 

While working at the FHI Berlin, we have established that 1) DFT provides excellent theoretical framework to study carbohydrates in a gas phase;[1] and 2) glycans have unique IR fingerprints that can be used to decode their structure.[2] Synergy between these two techniques enabled study of the sequence-structure relationship in glycans,[3] and glycosphingolipids.[4] We proposed, that the combination of computational and experimental techniques can be used to create a reference library to facilitate fragment-based analysis of glycans.[5] In a recent contribution, we have combined several gas-phase techniques and high-throughput DFT calculations to reveal the rearrangement products of the fucose migration in blood
group epitopes.[6] The computational work has also catalyzed the development of Carbohydrate Parser in python (CarPpy) which streamlines the DFT computations, and the subsequent analysis, of carbohydrates.[See Developed Code]

<figure class="third">
<img src="/assets/img/IR-structure.png" alt="drawing"/>
</figure>

#### Key papers:

> [7] **''Reinvestigation of the internal glycan rearrangement of Lewis a and blood group type H1 epitopes''**
> V. Kontodimas, M. Yaman, K. Greis, M. Lettow, K. Pagel, M. Marianski
> _Phys. Chem. Chem. Phys._ **2024**, 26, 14160-14170
> doi:[10.1032/D3CP04491B](https://pubs.rsc.org/en/content/articlelanding/2024/cp/d3cp04491b)
>
> [6] **''Decoding the Fucose Migration Product during Mass-Spectrometric Analysis of Blood Group Epitopes''**
> M. Lettow, K. Greis, E. Mucha, T. R. Lambeth, M. Yaman, V. Kontodimas, C. Manz, W. Hoffmann, G. Meijer, R. R. Julian, G. von Helden, M. Marianski, K. Pagel
>_Angewandte Chemie International Edition_ , **2023**, _Just Accepted_
>doi: [10.1002/ange.202302883](https://onlinelibrary.wiley.com/doi/10.1002/ange.202302883)
>
> [5] **''In-depth structural analysis of glycans in the gas phase''**
>E. Mucha\*, A. Stuckmann\*, M. Marianski\*, W. Struwe, G. Meijer, K. Pagel,
>_Chemical Science_, **2019**, 10, pp.~1272-1284
> doi: [10.1039/C8SC05426F](https://pubs.rsc.org/--/content/articlehtml/2019/sc/c8sc05426f)
>
> [4] **''Unravelling the Structural Complexity of Glycolipids with Cryogenic Infrared Spectroscopy''**
> C. Kirschbaum, K. Greis, E. Mucha, L. Kain, S. Deng, A. Zappe, S. Gewinner, W. Schöllkopf, G. von Helden, G. Meijer, P. B. Savage, M. Marianski, L. Teyton, K. Pagel,
>_Nature Communications_ , **2021**, 12, p. 1201
>doi: [10.1038/s41467-021-21480-1](https://www.nature.com/articles/s41467-021-21480-1)
>
> [3] **''Fucose Migration in Intact Protonated Glycan Ions: A Universal Phenomenon in Mass Spectrometry''**
> E. Mucha, M. Lettow, M. Marianski, D. A. Thomas, W. B. Struwe, D. J. Harvey, K. Pagel,
> _Angewandte Chemie International Edition_, **2018**, 57, pp.~7440–7443
> doi: [10.1002/anie.2018.01418](https://onlinelibrary.wiley.com/doi/full/10.1002/anie.201801418)
>
> [2] **''Glycan fingerprinting using cold-ion infrared spectroscopy''**
>E. Mucha, A. I. Gonz\'{a}lez Fl\'{o}res, M. Marianski, D. A. Thomas, W. Hoffmann, W. B. Struwe, H. S. Hahm, S. Gewinner, W. Sch\"{o}llkopf, P. H. Seeberger, G. von Helden, K. Pagel,
> _Angewandte Chemie International Edition_, **2017**, 56, pp.~11248-11251,
> doi: [10.1002/anie.201702896](https://onlinelibrary.wiley.com/doi/full/10.1002/anie.201702896)
>
> [1] **''Assessing the accuracy of across-the scale methods for predicting carbohydrate conformational energies on the example of glucose and $\alpha$-maltose''**
> M. Marianski, A. Supady, T. Ingram, M. Schneider and C. Baldauf,
> _Journal of Chemical Theory and Computations_, **2016**, 12, pp.~6157-6168
> doi: [10.1021/acs.jctc.6b00876](https://pubs.acs.org/doi/full/10.1021/acs.jctc.6b00876)

### 4. Antivirals: Can viral glycans be targeted to detect and stop viral diseases?

The recognition events between glycans and receptors have a central role in the viral life cycle. Understanding how these binding processes are involved in pathogen infection and reproduction could lead to new and desperately needed antiviral agents to counter the threat of viral outbreaks, especially those posed by enveloped viruses (EnV). The glycans can be either on proteins on the viral envelope, such as oligomannosides on the surface of Dengue Virus binding to the host cell protein DC-SIGN, or on the host cell, such as N-linked glycans terminated by sialic acid which are targets for influenza virus. Being able to inhibit these interactions will open new therapeutic strategies for novel antivirals. 

In collaboration with prof. Adam Braunschweig (ASRC CUNY), we have synthesized a large library of over 80 synthetic carbohydrate receptors (SCRs), and characterized their binding towards biologically-relevant carbohydrates. We have established design rules to anticipate the SCR selectivity and to optimize its binding affinity.[1−4] Importantly, these  SCRs show strong antiviral activity. We hypothesize that  the SCRs interact with N-glycans on the surface of EnV,  which leads to the inhibition of the docking of a virus to  a host cell. We have demonstrated, using MD  simulations, that SCRs are selective towards specific N-glycans, abundance of which correlates with the measured antiviral activity of SCRs.[5]

<figure class="third">
<img src="/assets/img/flexibleSCR-1.png" alt="drawing"/>
</figure>

#### Key papers:
> [5] **''Binding of Synthetic Carbohydrate Receptors to Enveloped Virus Glycans: Insights From Molecular Dynamics Simulations''**
> B. Tapia, G. Yagudayeva, M. F. Bravo, K. Thakur, A. B. Braunschweig, M. Marianski,
>_Carbohydrate Research_ , **2022**, 518, pp. 108574
>doi: [10.1016/j.carres.2022.108574](https://www.sciencedirect.com/science/article/pii/S0008621522000751)
>
> [4] **''Regiochemical Effects on the Carbohydrate Binding and Selectivity of Flexible Synthetic Carbohydrate Receptors with Indole and Quinoline Heterocyclic Groups''**
> K. Thakur, M. A. Shlain, M. Marianski, A. B. Braunschweig,
>_European Journal of Organic Chemistry_ , **2021**, 37, pp. 5262-5274
>doi: [10.1002/ejoc.202100763](https://chemistry-europe.onlinelibrary.wiley.com/doi/full/10.1002/ejoc.202100763)
>
> [3] **''Flexible Synthetic Carbohydrate Receptors as Inhibitors of Viral Attachment''**
> F. Bravo, M. Lema, M. Marianski, A.  B. Braunschweig,
>_Biochemistry_ , **2021**, 60, pp. 999-1018
>doi: [10.1021/acs.biochem.0c00732](https://pubs.acs.org/doi/abs/10.1021/acs.biochem.0c00732)
>
> [2] **''Synthesis and Binding of Mannose-Specific Synthetic Carbohydrate Receptors''**
> F. Bravo, K. Palanichamy,  M. A. Shlain, F. Schiro, Y. Naeem, M. Marianski, A.  B. Braunschweig,
>_Chemistry - European Journal_ ,  **2020**, 26, pp. 11782-11795
>doi: [10.1002/chem.202000481](https://chemistry-europe.onlinelibrary.wiley.com/doi/10.1002/chem.202000481)
>
> [1] **''Binding Studies on a Library of Induced-Fit Synthetic Carbohydrate Receptors with Mannoside Selectivity''**
> K. Palanichamy,  F. Bravo, M. A. Shlain, F. Schiro, Y. Naeem, M. Marianski, A. B. Braunschweig,
>_Chemistry European Journal_, **2018**,  24, pp.~13971–13982
> doi: [10.1002/chem.201803317](https://onlinelibrary.wiley.com/doi/full/10.1002/chem.201803317)


