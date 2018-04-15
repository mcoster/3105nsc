---
title: 'Week 6 (16 Apr - 22 Apr): Pericyclic reactions'
published: true
date: '15-04-2018 14:40'
header_image: Diels-Alder_banner.jpg
hide_from_post_list: false
hide_git_sync_repo_link: false
js: 'var initShapes1=function(o){$.get("week-06-pericyclic-rxns/cp.cub",function(e){var a=new $3Dmol.VolumeData(e,"cube");o.addIsosurface(a,{isoval:.01,color:"blue",alpha:.95,smoothness:10}),o.addIsosurface(a,{isoval:-.01,color:"red",alpha:.95,smoothness:10}),o.setStyle({},{stick:{}}),o.zoomTo(),o.render()},"text")};var initShapes2=function(o){$.get("week-06-pericyclic-rxns/ma.cub",function(e){var a=new $3Dmol.VolumeData(e,"cube");o.addIsosurface(a,{isoval:.01,color:"blue",alpha:.95,smoothness:10}),o.addIsosurface(a,{isoval:-.01,color:"red",alpha:.95,smoothness:10}),o.setStyle({},{stick:{}}),o.zoomTo(),o.render()},"text")};'
---

#### Readings - Pericyclic reactions
[Klein, Chapter 16, Sections 16.1-16.10 - Conjugated Pi Systems and Pericyclic Reactions](https://ebookcentral-proquest-com.libraryproxy.griffith.edu.au/lib/griffith/reader.action?docID=4806589&ppg=721)  

===

### Cycle 3: Pericyclic reactions  

#### Before the lectures  

To prepare for this cycle, you should read [Sections 16.1-16.10 from Klein](https://ebookcentral-proquest-com.libraryproxy.griffith.edu.au/lib/griffith/reader.action?docID=4806589&ppg=721), all of which are assessable. The early sections (16.1-16.7) may be familiar from previous organic chemistry courses.  

#### Pi molecular orbitals  

To understand pericyclic reactions, it is important to comprehend conjugated pi systems and particularly the pi molecular orbitals that are produced by combining contiguous p orbitals. Can you arrange the following &pi; molecular orbitals from lowest to highest in energy?  

[h5p url="https://organicchemexplained.com/wp-admin/admin-ajax.php?action=h5p_embed&id=3"]

#### Types of pericyclic reactions  

There are three types of pericyclic reaction, each involving different numbers of &sigma; and &pi; bonds being formed and broken. However, all pericyclic reactions have some key features in common:  

[plugin:youtube](https://youtu.be/cib2EKbny9E)

#### Cycloaddition reactions  
Among cycloaddition reactions, the Diels&ndash;Alder reaction is the most common and most important. There are a number of key features to master:  

[plugin:youtube](https://youtu.be/TvPZvE2wCCY)

However, regioselectivity is sufficiently complex to deserve its own video:  

[plugin:youtube](https://youtu.be/cFGgZ7BtzKY)  

A classic example of the Diels&ndash;Alder reaction is that between cyclopentadiene and maleic anhydride. The reaction is very fast at room temperature due to the high reactivity of both the diene and dienophile. Cyclopentadiene is held in the s-_cis_ conformation with both reactive ends of the diene system held close together by the 5-membered ring. Maleic anhydride is a reactive dienophile due to the two electron-withdrawing carbonyl groups. Here are interactive models of the calculated diene HOMO and dienophile LUMO. Note that they are more complex than the approximations we do on paper by simply adding together p orbitals - real molecular orbitals involve all atoms within the molecule. However, you can see the orbitals are largest at the sites of reaction, and you should also be able to see that the phases of each are suitable for the [4+2]-cycloaddition to occur.  

| Cyclopentadiene HOMO | Maleic anhydride LUMO |
| -------------------- | --------------------- |
| <div style="height: 300px; width: 100%; position: relative;" class='viewer_3Dmoljs' data-href='week-06-pericyclic-rxns/cp.sdf' data-datatype='sdf' data-callback='initShapes1' data-backgroundcolor='0xf6f7f9'></div> | <div style="height: 300px; width: 100%; position: relative;" class='viewer_3Dmoljs' data-href='week-06-pericyclic-rxns/ma.sdf' data-datatype='sdf' data-callback='initShapes2' data-backgroundcolor='0xf6f7f9'></div> |  

Another important feature is the overwhelming selectivity for the _endo_ vs the thermodynamically more stable _exo_ isomer.  

![Cyclopentadiene + maleic anhydride Diels-Alder reaction](endo-vs-exo.png)  

| Endo product | Exo product |
| -------------------- | --------------------- |
| <div style="height: 300px; width: 100%; position: relative;" class='viewer_3Dmoljs' data-href='week-06-pericyclic-rxns/endo.sdf' data-datatype='sdf' data-backgroundcolor='0xf6f7f9' data-style='stick'></div> | <div style="height: 300px; width: 100%; position: relative;" class='viewer_3Dmoljs' data-href='week-06-pericyclic-rxns/exo.sdf' data-datatype='sdf' data-backgroundcolor='0xf6f7f9' data-style='stick'></div> |  

There has been very active debate for decades about why Diels&ndash;Alder reactions are normally selective for the endo products, and several theories have been advanced. One of the most highly accepted has been 'secondary orbital interactions' - see page 2 of [these notes](http://www.massey.ac.nz/~gjrowlan/stereo/lecture8.pdf). However, like many useful theories, it is probably not highly accurate. The bottom line is that the endo products are kinetically favoured and therefore the transition state leading to the endo product must be lower in energy than that leading to the exo product. [Recent density functional theory (DFT) level calculations](http://onlinelibrary.wiley.com/doi/10.1002/jcc.23500) have shed further light on the nature of this selectivity. For this course, we will simply note endo selectivity as a general, empirical rule and move along.  

| Endo transition state | Exo transition state |
| -------------------- | --------------------- |
| <div style="height: 300px; width: 100%; position: relative;" class='viewer_3Dmoljs' data-href='week-06-pericyclic-rxns/endo-ts.sdf' data-datatype='sdf' data-backgroundcolor='0xf6f7f9' data-style='stick'></div> | <div style="height: 300px; width: 100%; position: relative;" class='viewer_3Dmoljs' data-href='week-06-pericyclic-rxns/exo-ts.sdf' data-datatype='sdf' data-backgroundcolor='0xf6f7f9' data-style='stick'></div> |  

#### Electrocyclic reactions  

In electrocyclic reactions, it is important to look at the HOMO of the reactant. To form product, the reacting ends of the &pi; system must rotate in such a way that the orbital lobes of the same phase interact with each other. The same symmetry requirements apply to the reverse reactions - electrocyclic ring openings. This video shows the key factors in the thermal electrocyclization:  

[plugin:youtube](https://youtu.be/oepzwSO7w5Y)  

When electrocyclic reactions are conducted under photochemical conditions, the symmetry of the terminal lobes of the excited state HOMO are opposite to the thermal case:  

[plugin:youtube](https://youtu.be/vwpNN_r9P0A)  

#### Sigmatropic rearrangements  

Sigmatropic rearrangements are generally reversible and involve no change in the total number of &pi; and &sigma; bonds. However, structural features of reactant vs product(s) can result in equilibria favouring certain species over others. This video also shows how to name sigmatropic rearrangements according to an [x,y] naming convention:  

[plugin:youtube](https://youtu.be/_cYOXIMssQc)  

#### Practice question  

Here's a quick question for you as revision - can you drag these labels to the appropriate reactions that they describe?  

[h5p url="https://organicchemexplained.com/wp-admin/admin-ajax.php?action=h5p_embed&id=4"]


### Further information  

#### Cycle 3 Lecture notes  
[Cycle 3: Lecture notes](https://bblearn.griffith.edu.au/bbcswebdav/xid-23820555_1)  

#### Practice problems  
The most relevant problems from Klein (3rd ed.) are 16.39, 16.40, 16.42-16.46, 16.50-16.58, 16.64-16.68, 16.70-16.72 and 16.74-16.76. Problems 16.78-16.81 are good for a challenge!  

#### Further video resources  
If you would like further explanation of these concepts in long-form lecture format, below are the lecture capture recordings for Pericyclic reactions from 2017. _Note:_ You need to be logged in through Griffith University to access.  
[Pericyclic reactions - Lectures 1-2](https://echo360.org.au/media/48fce893-55e9-44e8-9690-aeff12522d96/public)  
[Pericyclic reactions - Lecture 3](https://echo360.org.au/media/2edf0cb9-9d61-42bd-a916-4940131d4e86/public)  

#### Supplemental interactive and video resources  
[An interactive look at endo vs exo at ChemTube3D](http://www.chemtube3d.com/DAendo_vs_exo,cyclopentadiene_and_maleic_anhydride.html)  
[An interactive look at D-A regioselectivity at ChemTube3D](http://www.chemtube3d.com/DARegioselectivity.html)  
[Pericyclic reaction movies](http://csi.chemie.tu-darmstadt.de/ak/immel/tutorials/reactions/index.html) by [Stefan Immel](http://csi.chemie.tu-darmstadt.de/ak/immel/index.html)  

#### Supplemental Readings  
[Recognizing endo vs exo](https://www.masterorganicchemistry.com/tips/recognizing-endo-and-exo/)  
[Exo vs Endo Products In The Diels Alder: How To Tell Them Apart](https://www.masterorganicchemistry.com/2018/02/09/exo-vs-endo-products-in-the-diels-alder-how-to-tell-them-apart/)  
[Molecular orbitals in the Diels-Alder reaction](https://www.masterorganicchemistry.com/2018/03/23/molecular-orbitals-in-the-diels-alder-reaction/)
