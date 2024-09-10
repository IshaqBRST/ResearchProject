# The pH-Dependent Allosteric Response of the Wild-Type SARS-CoV-2 Variant In The Presence of Linoleic Acid

The recent findings of Toelzer et al. highlight a free fatty acid site in-between each receptor-binding domain of the SARS-CoV-2 spike which when bound to by linoleic acid, induce a specific locked conformation by where the receptor-binding domain units of the virion are occluded. Oliveira et al. through using a novel molecular simulation method: D-NEMD, demonstrated upon removal of linoleic acid from the site, the spike undergoes allosteric changes within specific functional domains. Haddrell et al. have also highlighted the effects of pH, particularly alkaline conditions of greater than pH 10 which can reduce the air-borne stability of the virus.

In this novel investigation we consider the aforementioned and utilise the D-NEMD approach to investigate the allosteric response of the Wild-Type SARS-CoV-2 variant's response to high (pH 10) and low pH (pH 5) environments in the presence of linoleic acid.

## Experimental Conditions

(1) SARS-CoV-2 at pH 5 (Apo pH 5)
(2) SARS-CoV-2 at pH 10 (Apo pH 10)
(3) SARS-CoV-2 whilst bound to linoleic acid at pH 5 (LA-Bound pH 5)
(4) SARS-CoV-2 whilst bound to linoleic acid at pH 10 (LA-Bound pH 10)

## Directories

* 'temporal_deviation_analysis_1' : Illustrates the temporal deviation evolution of the SARS-CoV-2 averaged across the three spike monomers at 0.1 nanoseconds (ns), 1.0 ns, 5.0 ns, and 10.0 ns.

* 'temporal_deviation_monomer_2' : Illustrates the temporal deviation evolution of the SARS-CoV-2 for each monomer of the spike at 0.1 nanoseconds (ns), 1.0 ns, 5.0 ns, and 10.0 ns.

* 'peak_deviation_calculator_3' : Determines the peak deviation of backbone alpha-carbon atoms within the spike at time points of 0.1 nanoseconds (ns), 1.0 ns, 5.0 ns, and 10.0 ns.

* 'effect_of_ph_and_la_binding_4' : Illustrates the effect of high and low pH in the presence of linoleic acid and in it's absence at 10.0 ns.

* 'effect_of_ph_monomer_anaysis_5' : Illustrates the effect of high and low pH in the presence of linoleic acid and in it's absence at 10.0 ns for each monomer of the spike.

* 'data_files': Provides the data files for each time point (0.0 ns, 0.1 ns, 0.5 ns, 1.0 ns, 5.0 ns, and 10.0 ns) for each experimental condition. 

## Data Files

* SD_0 (O ns)
* SD_100 (0.1 ns)
* SD_500 (0.5 ns)
* SD_1000 (1.0 ns)
* SD_5000 (5.0 ns)
* SD_10000 (10.0 ns)

The data files are found within their relevant directories. 

## How to Run

Simply clone the repository to your local-host device and upload the directories of interest within a Jupyter notebook environment. We recommend observing the temporal deviation evolutions, and determining the peak deviations of alpha-carbon atoms for each experimental condition before viewing the effects of pH and linoleic acid.

Note: We consider the time point of 10 ns to be of significant interest as the greatest deviations were observed at this time. Our analysis is largely focused on 10 ns as a result. This includes investigating the effects of pH and linoleic acid. If you are interested in visualising the effects of pH and linoleic acid for other time points (i.e. 0.0 ns - 5.0 ns), you MUST first determine the peak deviations of alpha-carbon atoms and use these as inputs for directories 'effect_of_ph_and_la_binding_4' and 'effect_of_ph_monomer_anaysis_5'.

