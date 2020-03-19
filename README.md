# Some studies of COVID-19 drugs

**Disclaimer: This is not my area of expertise. I'm not a medicinal chemist**

I'm doing some studies on small-molecule drugs for COVID-19. I'll report some of my findings here.

![](https://i.creativecommons.org/p/zero/1.0/88x31.png)

## Log

- 18.3.20
    - 2D structures for 11 antivirals presented [here](http://dx.doi.org/10.1021/acscentsci.0c00272)

![](https://github.com/mrauha/covid19_drugs/blob/master/images/liu_article_antivirals.png)
- 19.3.20
    - For each antiviral, I searched [Pubchem Compound](https://pubchem.ncbi.nlm.nih.gov/) database (103M molecules) for structures that have Tanimoto coefficient of RDKit topological fingerprints > 0.7. 
    - The similar molecules for each antiviral are in similar_mols.tar.gz, similar_mols/<antiviral_name>.sims. 
    - The code is hacky & uncommented, will clean later on

![Lopinavir_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Lopinavir_sim.png) ![Lopinavir_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Lopinavir.png)

![Ritonavir_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Ritonavir_sim.png) ![Ritonavir_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Ritonavir.png)

![Darunavir_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Darunavir_sim.png) ![Darunavir_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Darunavir.png)

![Favipiravir_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Favipiravir_sim.png) ![Favipiravir_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Favipiravir.png)

![Remdesivir_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Remdesivir_sim.png) ![Remdesivir_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Remdesivir.png)

![Ribavirin_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Ribavirin_sim.png) ![Ribavirin_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Ribavirin.png)

![Galidesivir_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Galidesivir_sim.png) ![Galidesivir_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Galidesivir.png)

![Arbidol_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Arbidol_sim.png) ![Arbidol_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Arbidol.png)

![Chloroquine_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Chloroquine_sim.png) ![Chloroquine_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Chloroquine.png)

![Nitazoxanide_dist](https://github.com/mrauha/covid19_drugs/blob/master/images/Nitazoxanide_sim.png) ![Nitazoxanide_mol](https://github.com/mrauha/covid19_drugs/blob/master/images/Nitazoxanide.png)
