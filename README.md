# study-notes
Study notes for me

# Molecular simulation
## Useful information
- MD Overview
  - 横市
    - http://www.eccse.kobe-u.ac.jp/assets/images/distance_learning/life_science4/1805c332d8393bdb4c7a4e955ebae56fc48165dd.pdf
  - 分子シミュレーションノート
    - https://masatakaym.github.io/Molecular-Simulation/main.pdf
- Method of MD simulation
  - Review: FFM, OFLOOD, PaCS-MD, TBSA
    - https://www.jstage.jst.go.jp/article/jccj/17/1/17_2017-0055/_pdf/-char/ja
  - TRS
    - 初級
      - https://www.jstage.jst.go.jp/article/biophys/54/3/54_167/_pdf
    - 中級
      - https://www.jstage.jst.go.jp/article/biophys/46/5/46_5_275/_pdf/-char/ja
  - String method
    - 入門
      - https://www2.hpci-office.jp/conference/201303/hp120027.pdf
    - 中級
      - https://www.jstage.jst.go.jp/article/mssj/16/1/16_29/_pdf/-char/ja
  - Targeted MD(TMD), Steered MD(SMD)
    - http://molsci.center.ims.ac.jp/area/2012/papers/2P084_w.pdf
- Review: Protein Language Model
  - https://doi.org/10.11234/jsbibr.2023.1
-  Review: Free energy calculation
   -  https://www.jstage.jst.go.jp/article/mssj/17/2/17_83/_pdf/-char/ja
- Review: 祖先型設計法
  - https://www.jstage.jst.go.jp/article/biophys/53/3/53_128/_pdf
- RISM
  - 入門
    - https://www.ssken.gr.jp/MAINSITE/download/newsletter/2012/20120820-sci-1/lecture-02/SSKEN_sci2012-1_yoshida_presentation.pdf
    - https://www.jstage.jst.go.jp/article/biophys/51/5/51_5_222/_supplement/51_222_1.pdf
    - https://www.sbj.or.jp/wp-content/uploads/file/sbj/9308/9308_yomoyama.pdf
  - OZ方程式
    - https://ja.wikipedia.org/wiki/%E3%82%AA%E3%83%AB%E3%83%B3%E3%82%B7%E3%83%A5%E3%82%BF%E3%82%A4%E3%83%B3%E3%83%BB%E3%82%BC%E3%83%AB%E3%83%8B%E3%82%B1%E6%96%B9%E7%A8%8B%E5%BC%8F
- Dynamics analysis method
  - NMA
    - Review
      - https://doi.org/10.3390/molecules24183293
    - 振動解析再入門
      - https://yamlab.net/pdf/note-molvib.pdf
  - PCA
    - ラングランジュの未定乗数法などの観点から
      - https://laid-back-scientist.com/pca-theory
    - PCAとその他の手法との比較(NMA, tICA, RMA)
      - https://doi.org/10.3390/j5020021
  - MSM
    - Markov model lecture written by Noe
      - http://docs.markovmodel.org/
  - tICA
    - 入門
      - https://www.jstage.jst.go.jp/article/mssj/13/4/13_161/_pdf/-char/ja
    - 中級
      - https://www.ism.ac.jp/editsec/toukei/pdf/62-2-243.pdf
  - RMA
    - Review(PhD)
      - https://www.jstage.jst.go.jp/article/mssj/22/4/22_334/_pdf/-char/ja
- Neural Network Potential
  - https://tech.preferred.jp/ja/blog/free-energy-calculation-using-nnp/
  - https://www.biorxiv.org/content/10.1101/2020.07.29.227959v1
  - https://www.slideshare.net/pfi/pfpneural-network-potential-2021104-qcmsr-dlap
- GPCR
  - wiki
    - https://bsd.neuroinf.jp/wiki/G%E3%82%BF%E3%83%B3%E3%83%91%E3%82%AF%E8%B3%AA%E5%85%B1%E5%BD%B9%E5%9E%8B%E5%8F%97%E5%AE%B9%E4%BD%93
  - Ionic lock
    - https://pubmed.ncbi.nlm.nih.gov/20106995/
      - interaction between ARG in TM3(DRY) and negative charge residue in TM6 (D or E)
  - salt bridge
    - https://en.wikipedia.org/wiki/Salt_bridge_(protein_and_supramolecular)
      - In chemistry, a salt bridge is a combination of two non-covalent interactions: hydrogen bonding and ionic bonding (Figure 1). Ion pairing is one of the most important noncovalent forces in chemistry, in biological systems, in different materials and in many applications such as ion pair chromatography.
- MD paramter
  - ESP, RESP
    - https://www.jstage.jst.go.jp/article/ciqs/2016/0/2016_P8/_pdf/-char/ja
- Boss
  - https://www.jstage.jst.go.jp/article/mssj/23/1/23_67/_pdf/-char/ja
- Cell biology by the number
  - http://book.bionumbers.org/
- 酵素の命名法(EC)
  - https://jsag.jp/toushitsu/2745/
- Review: QMMM
  - https://onlinelibrary.wiley.com/doi/full/10.1002/anie.200802019
- Review: CPMD
  - https://www.jstage.jst.go.jp/article/mssj/17/3/17_167/_pdf/-char/ja



## Papers
- AlphaFill
  - https://doi.org/10.1038/s41592-022-01685-y
- GPCR
  - ICL
    - ICL3 regulates activation and inactivation under dynamic equilibrium
      - https://doi.org/10.1038/s41586-023-05789-z
  - A2A
    - Crystallography of A2A with KW6356 and istradefylline
      - https://molpharm.aspetjournals.org/content/early/2023/03/10/molpharm.122.000633
    - A2a with Caffein and ZMA
      - https://pubs.acs.org/doi/10.1021/jp2022049
  - mGlu1
    - mGlu1 allosteric modulator
      - https://www.science.org/doi/10.1126/science.1249489
- Review: GPCR
  - https://doi.org/10.1038/s41594-017-0011-7
- Corona Virus inhibitor
  - https://doi.org/10.1038/s41598-022-07792-2
- iupacGPT
  - https://chemrxiv.org/engage/chemrxiv/article-details/645f49f9a32ceeff2d90c9ae
- Neural network potential
  - https://doi.org/10.1016/j.jmat.2022.12.007
- Modeling
  - OPC
    - https://pubs.acs.org/doi/10.1021/jz501780a


## Tools
- CHARMM-GUI
  - https://www.charmm-gui.org/
- PyEmma
  - http://www.emma-project.org/latest/
- GROMACS
  - Tutorials
    - http://www.mdtutorials.com/gmx/
  - Manuals
    - https://manual.gromacs.org/current/index.html
- GENESIS
  - Tutorial
    - https://www.r-ccs.riken.jp/labs/cbrt/tutorial/
  - Development story
    - https://www.pssj.jp/archives/essay/Es_07/Es_07.html
- Uniprot
  - Align
    - https://www.uniprot.org/align
- AMBER
  - Tutorials
    - https://ambermd.org/tutorials/
  - Manuals
    - https://ambermd.org/Manuals.php
  - QMMM Unofficial Tutorial
    - https://github.com/CCPBioSim/qmmm-workshop
- VMD
  - viewer
    - https://qiita.com/TANATY/items/2fc4bd2044bb6c81e8cc
- PDB
  - Labels
    - https://pdbj.org/help/pdb-brief?lang=ja



## Database
- mGlu1
  - https://www.rcsb.org/3d-view/4OR2
- A2A
  - https://www.rcsb.org/structure/8GNG
- OPM: Orientation of Proteins in Membrane
  - https://opm.phar.umich.edu/


