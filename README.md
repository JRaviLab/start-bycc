# START-BYCC
Modeling the START transition in the budding yeast cell cycle

## Authors
[Janani Ravi](//github.com/jananiravi)*, [Kewalin Samart](//github.com/kewalinsamart), [Jason Zwolak](//github.com/jzwolak). <br>
*Corresponding author: janani.ravi@cuanschutz.edu.

## How to Cite
Ravi J, Samart K, Zwolak J (2024) Modeling the START transition in the budding yeast cell cycle. PLOS Computational Biology 20(8): e1012048. https://doi.org/10.1371/journal.pcbi.1012048

## Abstract
Budding yeast, Saccharomyces cerevisiae, is widely used as a model organism to study the genetics underlying eukaryotic cellular processes and growth critical to cancer development, such as cell division and cell cycle progression. The budding yeast cell cycle is also one of the best-studied dynamical systems owing to its thoroughly resolved genetics. However, the dynamics underlying the crucial cell cycle decision point called the START transition, at which the cell commits to a new round of DNA replication and cell division, are under-studied. The START machinery involves a central cyclin-dependent kinase; cyclins responsible for starting the transition, bud formation, and initiating DNA synthesis; and their transcriptional regulators. However, evidence has shown that the mechanism is more complicated than a simple irreversible transition switch. Activating a key transcription regulator SBF requires the phosphorylation of its inhibitor, Whi5, or an SBF/MBF monomeric component, Swi6, but not necessarily both. Also, the timing and mechanism of the inhibitor Whi5’s nuclear export, while important, are not critical for the timing and execution of START. Therefore, there is a need for a consolidated model for the budding yeast START transition, reconciling regulatory and spatial dynamics. We built a detailed mathematical model (START-BYCC) for the START transition in the budding yeast cell cycle based on established molecular interactions and experimental phenotypes. START-BYCC recapitulates the underlying dynamics and correctly emulates key phenotypic traits of ~150 known START mutants, including regulation of size control, localization of inhibitor/transcription factor complexes, and the nutritional effects on size control. Such a detailed mechanistic understanding of the underlying dynamics gets us closer towards deconvoluting the aberrant cellular development in cancer.

## Author Summary
Researchers use the budding yeast Saccharomyces cerevisiae as a model to understand how complex eukaryotic cells grow and divide, and how important cell cycle-related diseases like cancer progress. The S. cerevisiae cell cycle entails carefully controlled growth and division determined by the budding yeast genome, as well as factors like the availability of sugars the yeast uses to grow. Scientists have studied these processes for decades and elucidated key details and regulatory mechanisms. Computational models have been built based on this knowledge to analyze and predict the dynamics of the yeast cell cycle and its dependence on environmental factors. Most models to date lack detail at the initial point called the START transition, where cells commit to reproducing by dividing. We designed a new mathematical model called START-BYCC that incorporates the many different regulatory mechanisms by which yeast cells decide whether to enter the START transition. Our model accurately predicts experimental results capturing how ~150 mutant yeast strains (minor variations in genetic background) behave in the START transition. The START-BYCC model can be used to make accurate predictions for the cell cycle and provide insight into the role of this essential transition in diseases like cancer.

## Data Availability and Reuse
All the simulation data and visualizations (for wildtype and 100s of mutants) are available in our interactive online simulator: <http://www.sbmlsimulator.com/simulator/by-start>. Our code, differential equation model, and parameters are available via GitHub: <https://github.com/jravilab/start-bycc>.
