---
title: "Graph-based inter-domain consistency maintenance for BIM models"
collection: talks
type: "CBIM research"
permalink: /talks/cbim_prototype
venue: "Technion"
date: 2023-08-04
location: "Haifa, Israel"
---

### [Zijian Wang](https://www.linkedin.com/in/wang-zijian/), [Boyuan Ouyang](https://www.linkedin.com/in/boyuan-ouyang/), [Prof. Rafael Sacks](https://www.linkedin.com/in/rafaelsacks/) 

### [VClab, Technion](https://sacks.net.technion.ac.il/) 

### [Paper link](https://doi.org/10.1016/j.autcon.2023.104979)




Even with modern BIM software, design collaboration across disciplines for building construction remains sequential and siloed. Cloud-based BIM (CBIM) proposes an alternative approach, in which BIM models are stored as discipline-specific graphs whose nodes are linked to support across-domain coordination. 


<img title="CBIM automatic consistency maintenance" alt="Alt text" src="../images/cbim_prototype.gif">



This work presents a theoretical basis for systematic consistency maintenance by 1) defining constraint classes to relate objects across disciplines and 2) devising a mechanism to resolve conflicts. A case study prototype was implemented with federated building models to demonstrate the system's response to design changes made by one discipline that impact others. It detects conflicts that violate design intent, and in simple cases, such as translations, it can resolve inconsistencies by actively propagating corrections subject to users' approvals. 



### Protoype video

[![Introducing BIM](../images/cover_cbim_prototype.jpg)](https://youtu.be/ucsJOsbhB_M "Introducing BIM")


We are persistently delving into the potential of representing BIM models as graphs, and firmly believe that BIM graphs can enable more advanced and intelligent applications in the future. 

If you are interested in our works, here is the [first CBIM position paper](https://doi.org/10.1016/j.aei.2022.101711), [the graph-based data structure](https://cbim2020.net.technion.ac.il/files/2022/09/2022ECPPM_SE_Assoc_Ouyang_etal-28.9.22.pdf) that we store building information, [how we use semantic enrichment to solve the interoperability problem](https://arxiv.org/abs/2304.11672) caused by proprietory schemas, how we use [GNN to enrich BIM graphs](https://doi.org/10.1016/j.autcon.2021.104039) ...




### Aknowledgement

The work is part of the Cloud-based Building Information Modelling (CBIM) project, a European Training Network. The CBIM project receives funding from the European Union's Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant with agreement No 860555.



### Citation

~~~
@article{WANG2023104979,
    title = {Graph-based inter-domain consistency maintenance for BIM models},
    journal = {Automation in Construction},
    volume = {154},
    pages = {104979},
    year = {2023},
    issn = {0926-5805},
    doi = {https://doi.org/10.1016/j.autcon.2023.104979},
    author = {Zijian Wang and Boyuan Ouyang and Rafael Sacks}
}
~~~

~~~
Wang, Z., Ouyang, B. and Sacks, R., 2023. Graph-based inter-domain consistency maintenance for BIM models. Automation in Construction, 154, p.104979.
~~~