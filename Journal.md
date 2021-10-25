This document gathers all the reasoning, and steps, followed in the EQAE 2021.

The five samples were analyzed using PikaVirus, with all the viral genomes in Genbank (release XX) and Refseq (release XX).
No results were obtained for Sample 2, as it was obtained through Nanopore sequencing, which requires a different approach.

Pikavirus detected the following viral assemblies on each sample:

Sample1:
|Assembly       |Name                                        |Meandepth|Standarddeviation|Mindepth|Maxdepth|Depthmedian|Sequence %>=1 Depth|Sequence %>=10 Depth|Sequence %>=50 Depth|Sequence %>=100 Depth|
|---------------|--------------------------------------------|---------|-----------------|--------|--------|-----------|-------------------|--------------------|--------------------|---------------------|
|GCA_900187835.1|Cowpox virus genome                         |48.69    |10.27            |0       |84      |49         |99.6               |98.93               |48.07               |0.0                  |
|GCA_900155325.1|Variola virus genome                        |47.82    |12.91            |0       |120     |48         |98.46              |97.62               |45.31               |0.49                 |
|GCA_005280495.1|Vaccinia virus strain=44/47.1 rMVA genome   |46.21    |12.9             |0       |79      |48         |98.81              |96.92               |42.97               |0.0                  |
|GCA_014131225.1|Vaccinia virus strain=Ducapox vaccine genome|44.4     |15.44            |0       |79      |47         |94.95              |93.29               |41.19               |0.0                  |
|GCA_006451195.1|Monkeypox virus genome                      |34.31    |20.6             |0       |79      |41         |86.3               |79.82               |27.09               |0.0                  |
|GCF_000913595.1|Human endogenous retrovirus K113 genome     |118.57   |215.41           |0       |865     |4          |56.61              |46.95               |32.45               |26.01                |

Chosen assemblies for Sample 1 are those covered at least in an 80%:

* GCA_005280495.1	Vaccinia virus strain=44/47.1 rMVA genome
* GCA_006451195.1	Monkeypox virus genome
* GCA_014131225.1	Vaccinia virus strain=Ducapox vaccine genome
* GCA_900155325.1	Variola virus genome
* GCA_900187835.1	Cowpox virus genome


Sample3:
|Assembly       |Name                                        |Meandepth|Standarddeviation|Mindepth|Maxdepth|Depthmedian|Sequence %>=1 Depth|Sequence %>=10 Depth|Sequence %>=50 Depth|Sequence %>=100 Depth|
|---------------|--------------------------------------------|---------|-----------------|--------|--------|-----------|-------------------|--------------------|--------------------|---------------------|
|GCA_014083815.1|uncultured virus genome                     |8.43     |9.31             |0       |44      |5          |56.45              |44.19               |0.0                 |0.0                  |
|GCA_004875485.1|Phage NV18 genome                           |1.42     |2.81             |0       |19      |0          |29.2               |2.5                 |0.0                 |0.0                  |
|GCA_004875545.1|Phage NGI136 genome                         |1.48     |3.08             |0       |16      |0          |24.56              |4.48                |0.0                 |0.0                  |
|GCA_006451195.1|Monkeypox virus genome                      |627.32   |368.84           |0       |1803    |700        |87.64              |86.95               |84.94               |83.25                |
|GCA_004875525.1|Phage NG55 genome                           |0.63     |1.21             |0       |7       |0          |29.34              |0.0                 |0.0                 |0.0                  |
|GCA_014131225.1|Vaccinia virus strain=Ducapox vaccine genome|802.42   |302.75           |0       |2064    |809        |96.16              |95.69               |95.2                |94.68                |
|GCF_000838165.1|Mycoplasma virus P1 genome                  |0.31     |0.67             |0       |4       |0          |20.37              |0.0                 |0.0                 |0.0                  |
|GCF_000857645.1|Staphylococcus virus 42e genome             |3.99     |6.49             |0       |33      |0          |37.51              |21.1                |0.0                 |0.0                  |
|GCA_900187835.1|Cowpox virus genome                         |967.9    |295.64           |0       |2429    |928        |99.72              |99.7                |99.58               |99.51                |
|GCF_002829725.1|Harvey murine sarcoma virus genome          |2.14     |5.61             |0       |29      |0          |35.31              |5.02                |0.0                 |0.0                  |
|GCF_002987775.1|Kirsten murine sarcoma virus genome         |2.16     |4.47             |0       |19      |0          |30.47              |9.03                |0.0                 |0.0                  |

Chosen assemblies for Sample 3 are those covered at least in an 80%:
* GCA_900187835.1	Cowpox virus genome
* GCA_014131225.1	Vaccinia virus strain=Ducapox vaccine genome
* GCA_006451195.1	Monkeypox virus genome

However, mild presence (30-35% coverage) of the Harvey murine sarcoma virus (oncogenic ), and Kirsten murine sarcoma virus suggests the host is a murine. 

Sample4:
|Assembly       |Name                                        |Meandepth|Standarddeviation|Mindepth|Maxdepth|Depthmedian|Sequence %>=1 Depth|Sequence %>=10 Depth|Sequence %>=50 Depth|Sequence %>=100 Depth|
|---------------|--------------------------------------------|---------|-----------------|--------|--------|-----------|-------------------|--------------------|--------------------|---------------------|
|GCA_006451195.1|Monkeypox virus genome                      |13.72    |9.11             |0       |42      |15         |85.37              |67.11               |0.0                 |0.0                  |
|GCF_000913595.1|Human endogenous retrovirus K113 genome     |118.26   |214.79           |0       |862     |4          |57.01              |46.98               |32.43               |25.99                |
|GCA_005280495.1|Vaccinia virus strain=44/47.1 rMVA genome   |18.41    |6.69             |0       |42      |19         |98.39              |91.67               |0.0                 |0.0                  |
|GCA_014131225.1|Vaccinia virus strain=Ducapox vaccine genome|17.64    |7.37             |0       |42      |18         |94.59              |88.45               |0.0                 |0.0                  |
|GCF_000847965.1|Rabbit fibroma virus strain=Kasza genome    |19.83    |5.57             |0       |49      |19         |99.92              |98.3                |0.0                 |0.0                  |
|GCA_900155325.1|Variola virus genome                        |19.24    |6.79             |0       |63      |19         |98.37              |94.28               |0.2                 |0.0                  |
|GCA_900187835.1|Cowpox virus genome                         |19.44    |5.83             |0       |42      |19         |99.49              |96.19               |0.0                 |0.0                  |

Chosen assemblies for Sample 4 are those covered at least in an 80%:

* GCF_000847965.1	Rabbit fibroma virus strain=Kasza genome
* GCA_900187835.1	Cowpox virus genome
* GCA_005280495.1	Vaccinia virus strain=44/47.1 rMVA genome
* GCA_900155325.1	Variola virus genome
* GCA_014131225.1	Vaccinia virus strain=Ducapox vaccine genome
* GCA_006451195.1	Monkeypox virus genome
* GCF_000913595.1	Human endogenous retrovirus K113 genome


Presence of the Rabbit fibroma virus, endemic of the wild rabbit, suggests rabbit is a possible host in this sample. However, the presence of the Human endogenous retrovirus makes this sample rather confusing at first glance.

Sample5:
|Assembly       |Name                                                        |Meandepth|Standarddeviation|Mindepth|Maxdepth|Depthmedian|Sequence %>=1 Depth|Sequence %>=10 Depth|Sequence %>=50 Depth|Sequence %>=100 Depth|
|---------------|------------------------------------------------------------|---------|-----------------|--------|--------|-----------|-------------------|--------------------|--------------------|---------------------|
|GCA_900155325.1|Variola virus genome                                        |25.12    |5.11             |0       |44      |25         |99.92              |99.65               |0.0                 |0.0                  |
|GCA_014131225.1|Vaccinia virus strain=Ducapox vaccine genome                |20.38    |9.85             |0       |43      |23         |89.02              |83.25               |0.0                 |0.0                  |
|GCF_000846425.1|Mouse mammary tumor virus genome                            |1.06     |1.28             |0       |6       |1          |52.14              |0.0                 |0.0                 |0.0                  |
|GCA_006451195.1|Monkeypox virus genome                                      |16.41    |10.94            |0       |44      |19         |81.7               |69.22               |0.0                 |0.0                  |
|GCF_000840245.1|Escherichia virus Lambda genome                             |2.23     |1.98             |0       |14      |2          |78.84              |0.42                |0.0                 |0.0                  |
|GCF_001619015.1|Mus musculus mobilized endogenous polytropic provirus genome|17.79    |12.82            |0       |122     |16         |99.85              |86.58               |2.26                |0.92                 |
|GCF_000864565.1|PreXMRV-1 genome                                            |8.39     |7.0              |0       |32      |7          |87.79              |41.34               |0.0                 |0.0                  |
|GCA_012640425.1|Siphoviridae sp. genome                                     |2.03     |1.8              |0       |9       |2          |76.58              |0.0                 |0.0                 |0.0                  |
|GCF_000848265.1|Abelson murine leukemia virus genome                        |0.05     |0.25             |0       |2       |0          |4.63               |0.0                 |0.0                 |0.0                  |
|GCF_002829725.1|Harvey murine sarcoma virus genome                          |0.12     |0.47             |0       |2       |0          |5.92               |0.0                 |0.0                 |0.0                  |
|GCF_000849885.1|Spleen focus-forming virus genome                           |6.14     |7.98             |0       |39      |2          |62.74              |27.08               |0.0                 |0.0                  |
|GCF_000859085.1|Murine type C retrovirus genome                             |8.51     |7.16             |0       |29      |7          |87.19              |43.18               |0.0                 |0.0                  |
|GCF_002889515.1|Finkel-Biskis-Jinkins murine sarcoma virus genome           |2.15     |3.29             |0       |17      |1          |51.14              |5.88                |0.0                 |0.0                  |

Chosen assemblies for Sample 5 are those covered at least in an 80%:

* GCA_900155325.1	Variola virus genome
* GCF_001619015.1	Mus musculus mobilized endogenous polytropic provirus genome
* GCA_014131225.1	Vaccinia virus strain=Ducapox vaccine genome
* GCF_000864565.1	PreXMRV-1 genome
* GCF_000859085.1	Murine type C retrovirus genome
* GCA_006451195.1	Monkeypox virus genome

This sample displays a higher quantity of murine-related viruses, this points to mouse being the host.

ViralRecon will be used with each of the references found on each of the samples. The kraken database containing the host sequences will be built from the genomes of:

-*Homo sapiens* (GCA_000001405.28), **taxid**: 9606, **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/000/001/405/GCA_000001405.28_GRCh38.p13/GCA_000001405.28_GRCh38.p13_genomic.fna.gz
-*Canis lupus* (GCA_905319855.2), **taxid**: 9612, **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/905/319/855/GCA_905319855.2_mCanLor1.2/GCA_905319855.2_mCanLor1.2_genomic.fna.gz
-*Pipistrellus pipistrellus* (GCA_903992545.1), **taxid**: 59474, **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/903/992/545/GCA_903992545.1_mPipPip1.1/GCA_903992545.1_mPipPip1.1_genomic.fna.gz
-*Chlorocebus sabaeus* (GCA_015252025.1), **taxid**: 60711, **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/015/252/025/GCA_015252025.1_Vero_WHO_p1.0/GCA_015252025.1_Vero_WHO_p1.0_genomic.fna.gz
-*Bos taurus* (GCA_002263795.2 ), **taxid**: 9913, **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/002/263/795/GCA_002263795.2_ARS-UCD1.2/GCA_002263795.2_ARS-UCD1.2_genomic.fna.gz
-*Mus musculus* (GCA_000001635.9), **taxid**: 10090 , **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/000/001/635/GCA_000001635.9_GRCm39/GCA_000001635.9_GRCm39_genomic.fna.gz
-*Oryctolagus cuniculus* (GCA_000003625.1), **taxid**: 9986 , **url**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA/000/003/625/GCA_000003625.1_OryCun2.0/GCA_000003625.1_OryCun2.0_genomic.fna.gz

This choices are based on the results obtained by PikaVirus, and other typical hosts. With these, the kraken 2 (v2.1.2) database is created. The code for the process can be found in the file *create_kraken_db*, in this repository.

Viralrecon also requires a gff file. The gff files for each assembly, which are not included in the PikaVirus database, were downloaded from the NCBI ftp:





Sample 2 was Nanopore technology. Therefore, a different approach was needed. First of all, trimming was performed with porechop (v0.2.4)
