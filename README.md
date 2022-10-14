# Contents
- [Table 1. AMPs in *Tenebrio molitor*](#table-1-amps-in-tenebrio-molitor)
- [attacins/tenecin 4](#attacinstenecin-4)
  - [tenecin 4/CAH1377309.1/CAH1377311.1/CAH1377312.1/CAH1377313.1](#tenecin-4CAH1377309.1CAH1377311.1CAH1377312.1CAH1377313.1)
  - [CAH1377308.1/CAH1377310.1/Attacin 1a](#cah13773081cah13773101attacin-1a)
  - [attacin 1b](#attacin-1b)
- [coleoptericins](#coleoptericins)
  - [coverage of coleoptercins in genoscope assembly](#coverage-of-coleoptercins-in-genoscope-assembly)
- [thaumatin](#thaumatin)
  - [coverage of thaumatins in genoscope assembly](#coverage-of-thaumatins-in-genoscope-assembly)
  - [CAH1379328.1](#cah13793281)
- [RNAseq validation](#rnaseq-validation)
  - [alignment](#alignment)
- [References](#references)

# Table 1. AMPs in *Tenebrio molitor*.

| Family        | Protein name      | Gene name     | protein length        | 2014 RNAseq  | notes                                                             |
|---------------|-------------------|---------------|------------------------|--------------|-------------------------------------------------------------------|
| attacin       | CAH1377308.1      | TMOL_7.1463.1 | 154 aa                 | comp42299_c0 | 98% identity (151/154) with attacin-1a, see [below](#cah13773081cah13773101attacin-1a)                           |
| attacin       | CAH1377309.1      | TMOL_7.1464.1 | 123 aa                 | comp44607_c0 | See [below](#tenecin-4CAH13773091CAH13773111CAH13773121CAH13773131)                                                                   |
| attacin       | CAH1377310.1      | TMOL_7.1465.1 | 154 aa                 | comp42299_c0 | 98% identity (151/154) with attacin-1a, see [below](#cah13773081cah13773101attacin-1a)                           |
| attacin       | CAH1377311.1      | TMOL_7.1466.1 | 161 aa                 | comp44607_c0 | See [below](#tenecin-4CAH13773091CAH13773111CAH13773121CAH13773131)                                                                   |
| attacin       | CAH1377312.1      | TMOL_7.1468.1 | 161 aa                 | comp44607_c0 | See [below](#tenecin-4CAH13773091CAH13773111CAH13773121CAH13773131)                                                                   |
| attacin       | CAH1377313.1      | TMOL_7.1467.1 | 161 aa                 | comp44607_c0 | See [below](#tenecin-4CAH13773091CAH13773111CAH13773121CAH13773131)                                                                   |
| attacin       | CAH1370004.1      | TMOL_4.173.1 | 164 aa                 | comp38945_c1 m.23374 | 99% identity (162/164) with attacin-2, jo et al. 2018, in 2014 we called this attacin 1 |
| attacin       | attacin 1b        |  | 150 aa                 | comp38697_c0 m.22078 | See [below](#attacin-1b) |
| coleoptericin | CAH1367453.1      | TMOL_3.1704.1 | 119 aa                 | comp40251_c0 m.33071 | 98% identity (117/119) with coleoptericin A, see [below](#coleoptericins)      |
| coleoptericin | CAH1367451.1      |  TMOL_3.1700.1| 127 aa                 | comp42114_c0 m.56211 | 98% identity (124/127) with coleoptericin B                                    |
| coleoptericin | CAH1367452.1      | TMOL_3.1703.1 | 127 aa                 | comp42114_c0 m.56211 | 98% identity (125/127) with coleoptericin B                                    |
| coleoptericin | CAH1367454.1      | TMOL_3.1705.1 | 134 aa (partial start) | comp39661_c0 m.28138 | the cognate protein KAH0816279.1 in the purdue assembly is 164 aa        |
| cecropin      | CAH1373192.1      | TMOL_1.2590.1 | 96 aa                  | comp41995_c0 m.54728 | identical to cecropin, missing in purdue assembly                              |
| (tenecin 3)   | CAH1364178.1      | TMOL_2.541.1 | 96 aa                  | comp39311_c1 m.25826 | identical to tenecin 3                                                         |
| defensin      | CAH1375101.1      | TMOL_6.484.1 | 84 aa                  | comp40599_c0 | 99% identity (83/84) with tenecin 1                                            |
| defensin      | defensin          |  | 72 aa                  |              | missing in genomes and our RNAseq. In all cases tenecin 1 is the closest hit. not in any databases, so transcribed the aa sequence from Jang et al. 2020 |
| defensin-like | CAH1378923.1      | TMOL_9.489.1 | 71 aa                  | comp44757_c0 | identical to "defensin-like" from Jang et al. 2020. Seems to be in a cluster of related genes |
| thaumatin-like | CAH1379328.1     | TMOL_10.8.1 | 222 aa                 | comp35996_c0 | Possibly undescribed thaumatin-like protein but see [below](#cah13793281)      |
| thaumatin-like | CAH1373168.1     | TMOL_1.2565.1 | 587 aa                 | comp39444_c0, comp40771_c0 | See [below](#coverage-of-thaumatins-in-genoscope-assembly)                                                               |
| thaumatin‐like | CAH1373167.1     | TMOL_1.2564.1 | 187 aa                 | comp140556_c0 | Sits right next to the above. Possibly undescribed.                                     |

protein names CAHXXXXXXX.X refer to the Genoscope assembly. <br/>
KAHXXXXXXX.X refer to the purdue assembly. <br/>
compXXXXXX_cX refer to transcript sequences assembled from our RNAseq. <br/>
m.XXX refer to proteins predicted from the assembled RNAseq transcripts. <br/>
TMOL_X.XXXX refers to the gene name (locus tag) in the genoscope assembly. 

# attacins/tenecin 4

There seems to be 8 attacin genes in total. CAH1377309.1, CAH1377311.1, CAH1377312.1, CAH1377313.1 are very similar to each other and are hard to distinguish ([see below](#cah13773081cah13773101attacin-1a)). The same is true of CAH1377308.1 and CAH1377310.1 ([see below](#cah13773081cah13773101attacin-1a)). These six genes (CAH1377308.1, CAH1377309.1, CAH1377310.1, CAH1377311.1, CAH1377312.1, CAH1377313.1) are clustered together on scaffold CAJRHG030000008.1:

![ten4gb](https://github.com/Perugolate/tm/blob/main/CAJRHG030000008.1%5B13496280..13530935%5D.png)

A seventh attacin is found outside of this cluster on scaffold CAJRHG030000004.1.

There is evidence for an eighth attacin that is missing from the genoscope assembly but is suppported by our RNAseq data (Johnston et al. 2014) and by Jo et al. 2018 and also purdue assembly ([see below](#attacin-1b)).

## tenecin 4/CAH1377309.1/CAH1377311.1/CAH1377312.1/CAH1377313.1

The amino acid sequence of Tenecin 4 from Chae et al does not retrieve an identical amino acid sequence from either genome project. These four genes (CAH1377309.1, CAH1377311.1, CAH1377312.1, CAH1377313.1) are basically tenecin 4.


```
Tenecin 4         MLKAVQFALSCTILSSAAPT------------------ASSETKWDIEDPGKLKIQHSGT
CAH1377309.1      --------------------------------------MFRETEWNIQDPGKLKIQHSGT
CAH1377313.1      MQKVLIVASLCLVVALALPYDLVEDEQGQHYYLVPVSRVRRETKWDIENPGKLKIQHSGT
CAH1377311.1      MQKVLIVASLCLAVALALPYDLVEDEQGQHYYLVPVSRVRRETKWDIEDPGKLKIQHSGT
CAH1377312.1      MQKVLIVASLCLAVALASPYDLVEDEQGQHYYLVPVSRVRRETKWDIEDPGKLKIQHSGT
                                                           **:*:*::***********

Tenecin 4         IFNNGGHKLDGEAYGSKSLVDRRDPAVFGGKLDYNHNSGSSLSVSAQHKEHRGTRVGVEG
CAH1377309.1      IFNNGDHKLKGEAYGSKSLVDRRDSAVFGGKLDYNHNSGSGLSVSALHKEHRGTRVGVEG
CAH1377313.1      IFNNGDHKLKGEAYGSKSLVDRRDPAVFGGKLDYNHNSGSSLSVSAQHKEHRGTRVGVEG
CAH1377311.1      IFNNGDHKLDGEAYGSKSLVDRRDPAVFGGKLDYNHNSGSSLSVSAQHKEHRGTRVGVEG
CAH1377312.1      IFNNGDHKLDGEAYGSKSLVDRRDPAVFGGKLDYNHNSGSSLSVSAQHKEHRGTRVGVEG
                  *****.***.**************.***************.***** *************

Tenecin 4         KYNLYRNGPFHADVSGKYDRTYGGASSNPSFSTHLTGTVDF
CAH1377309.1      KYNLYRNVPFHADISGKYDRTYGGASSNPSFSTHLTGRVDF
CAH1377313.1      KYNLYRNGPFHADVSGKYDRTYGGASSNPSFSTHLTGTVDF
CAH1377311.1      KYNLYRNGPFHADVSGKYDRTYGGASSNPSFSTHLTGTVDF
CAH1377312.1      KYNLYRNGPFHADVSGKYDRTYGGASSNPSFSTHLTGTVDF
                  ******* *****:*********************** ***
```

The nucleotide sequence is similar enough that the RNAi and qPCR probably covers the all but note the difference in the 5-prime end of the CAH1377309.1 cds:

```
CLUSTAL multiple sequence alignment by MUSCLE (3.8)


TMOL_7.1464.1_CAH1377309.1      ------------------------------------------------------------
TMOL_7.1467.1_CAH1377313.1      ATGCAAAAAGTACTAATTGTTGCATCTCTCTGCTTGGTTGTGGCCTTGGCCTTGCCTTAT
TMOL_7.1466.1_CAH1377311.1      ATGCAAAAAGTACTAATTGTTGCATCTCTCTGCTTGGCTGTGGCCTTGGCCTTGCCTTAT
TMOL_7.1468.1_CAH1377312.1      ATGCAAAAAGTACTAATTGTTGCATCTCTCTGCTTGGCTGTGGCCTTGGCCTCGCCTTAT
                                                                                            

TMOL_7.1464.1_CAH1377309.1      ---------------------------------------------ATGTTT---------
TMOL_7.1467.1_CAH1377313.1      GATCTCGTCGAAGATGAGCAAGGTCAACATTATTATCTAGTACCGGTGTCTCGTGTAAGG
TMOL_7.1466.1_CAH1377311.1      GATCTCGTCGAAGATGAGCAAGGTCAACATTATTATCTAGTACCGGTGTCTCGTGTAAGA
TMOL_7.1468.1_CAH1377312.1      GATCTCGTCGAAGATGAGCAAGGTCAACATTATTATCTAGTACCGGTGTCTCGTGTAAGG
                                                                              *** *         

TMOL_7.1464.1_CAH1377309.1      AGGGAAACCGAATGGAACATTCAAGATCCAGGAAAGTTGAAAATTCAACACAGCGGTACC
TMOL_7.1467.1_CAH1377313.1      AGGGAAACCAAATGGGACATTGAAAACCCAGGAAAGTTGAAAATTCAACACAGTGGTACC
TMOL_7.1466.1_CAH1377311.1      AGGGAAACCAAATGGGACATTGAAGATCCAGGAAAGTTGAAAATTCAACACAGTGGTACC
TMOL_7.1468.1_CAH1377312.1      CGGGAAACCAAATGGGACATTGAAGATCCAGGAAAGTTGAAAATTCAACACAGTGGTACC
                                 ******** ***** ***** ** * ************************** ******

TMOL_7.1464.1_CAH1377309.1      ATTTTCAACAACGGCGACCACAAATTAAAAGGTGAAGCTTATGGTTCTAAGAGTTTGGTC
TMOL_7.1467.1_CAH1377313.1      ATTTTCAACAACGGCGACCACAAATTAAAAGGTGAAGCTTATGGTTCTAAGAGTTTGGTT
TMOL_7.1466.1_CAH1377311.1      ATTTTCAACAACGGCGACCACAAATTAGATGGGGAAGCTTATGGTTCTAAGAGTTTGGTC
TMOL_7.1468.1_CAH1377312.1      ATTTTCAACAACGGCGACCACAAATTAGATGGGGAAGCTTATGGTTCAAAGAGTTTGGTT
                                *************************** * ** ************** *********** 

TMOL_7.1464.1_CAH1377309.1      GACAGACGTGATTCCGCAGTCTTCGGTGGGAAGCTGGATTATAATCACAACTCTGGATCT
TMOL_7.1467.1_CAH1377313.1      GACAGACGTGATCCCGCAGTCTTCGGTGGGAAGCTGGATTACAATCACAACTCTGGATCA
TMOL_7.1466.1_CAH1377311.1      GACAGACGTGATCCTGCGGTCTTCGGTGGGAAACTGGATTACAATCACAACTCTGGATCA
TMOL_7.1468.1_CAH1377312.1      GACAGACGTGATCCTGCGGTCTTCGGTGGGAAGCTGGATTACAATCACAACTCTGGATCC
                                ************ * ** ************** ******** ***************** 

TMOL_7.1464.1_CAH1377309.1      GGTCTTAGTGTGTCAGCTCTACATAAGGAACACCGTGGTACTAGAGTTGGAGTCGAAGGG
TMOL_7.1467.1_CAH1377313.1      AGTCTGAGTGTGTCAGCTCAACATAAGGAACACCGTGGTACTAGAGTTGGAGTTGAAGGA
TMOL_7.1466.1_CAH1377311.1      AGTTTGAGTGTGTCAGCTCAACATAAGGAACACCGTGGTACCAGAGTTGGAGTTGAAGGA
TMOL_7.1468.1_CAH1377312.1      AGTTTGAGTGTGTCAGCTCAACATAAGGAACACCGTGGTACTAGAGTTGGAGTTGAAGGG
                                 ** * ************* ********************* *********** ***** 

TMOL_7.1464.1_CAH1377309.1      AAATACAATCTGTACAGGAATGTCCCTTTCCATGCAGATATTTCTGGCAAATACGATAGA
TMOL_7.1467.1_CAH1377313.1      AAATACAATCTGTACAGGAATGGACCTTTCCATGCAGATGTTTCTGGCAAATACGATAGA
TMOL_7.1466.1_CAH1377311.1      AAATACAATCTGTACAGGAATGGACCTTTCCATGCAGATGTTTCTGGCAAATATGATAGA
TMOL_7.1468.1_CAH1377312.1      AAATATAATCTGTACAGGAATGGACCTTTCCATGCAGATGTTTCTGGAAAATACGACAGA
                                ***** ****************  *************** ******* ***** ** ***

TMOL_7.1464.1_CAH1377309.1      ACGTATGGTGGTGCATCGTCCAATCCGTCTTTCAGTACTCATCTAACCGGAAGAGTAGAT
TMOL_7.1467.1_CAH1377313.1      ACGTATGGTGGTGCATCGTCCAATCCGTCTTTCAGTACTCATCTAACCGGAACTGTAGAT
TMOL_7.1466.1_CAH1377311.1      ACGTATGGTGGTGCATCGTCCAATCCGTCTTTCAGTACTCACCTCACAGGAACAGTAGAT
TMOL_7.1468.1_CAH1377312.1      ACGTATGGTGGTGCATCGTCCAATCCGTCTTTCAGTACTCACCTCACAGGAACAGTAGAT
                                ***************************************** ** ** ****  ******

TMOL_7.1464.1_CAH1377309.1      TTTTGA
TMOL_7.1467.1_CAH1377313.1      TTTTAA
TMOL_7.1466.1_CAH1377311.1      TTTTAA
TMOL_7.1468.1_CAH1377312.1      TTTTAA
                                **** *
```

![attacins](https://github.com/Perugolate/tm/blob/main/20221013_attacins.jpg)

There is decent read support for attacins CAH1377308.1, CAH1377309.1, CAH1377310.1, CAH1377311.1, CAH1377312.1, and CAH1377313.1 in our RNAseq data. Their similarity complicates the interpretation though. Would probably have to look in more detail at the UTRs and upstream to really tell them apart in the RNAseq.

## CAH1377308.1/CAH1377310.1/Attacin 1a
Note that CAH1377308.1 and CAH1377310.1 are both 98% identical to Attacin 1a (Jo et al. 2018), but they are not identical to each other:

```
CAH1377308.1      MQKQLIVSILVFTSLAFATAENKIPPPKPEDGQRETKWKVEDPGIINLQHREKLYESGPH
CAH1377310.1      MQKQLIVSILAFASLAFAMADNKIPPPKPKDGQRETKWKVEDPGIINLQHREKLYESGPH
Attacin-1a        MQKQLIVSILAFASLAFATADNKIPPPKPEDGQRETKWKVEDPGIINLQHREKLYESGPH
                  **********.*:***** *:********:******************************

CAH1377308.1      RFDATAAYKKNFVDKMDPARTIARVDYKYLPGDTSLGVQAENIQRFGTVLSAEATRNLYK
CAH1377310.1      RFDATAAYKKNFVDKMDPARTIARVDYKYLPGDTSLGLQAENIQRFGTVLSAEATRNLYK
Attacin-1a        RFDATAAYKKNFVDKMDPARTIARVDYKYLPGDTSLGVQAENIQRFGTVLSAEATRNLYK
                  *************************************:**********************

CAH1377308.1      DRKSSLDVGVNYGQTFSPFVRSEPFFGGFVRGRF
CAH1377310.1      DRKSSLDVGVNYGQTFSPFVRSEPFFGGFVRGRF
Attacin-1a        DRKSSLDVGVNYGQTFSPFVRSEPFFGGFVRGRF
                  **********************************
```

Similar to the case of CAH1377309.1/CAH1377311.1/CAH1377312.1/CAH1377313.1, alignments show that CAH1377308.1 and CAH1377310.1 are conserved at the nucleotide-level so chances are that the knockdowns and qPCR cover both genes:

```
lcl|CAJRHG030000008.1_cds_CAH137      ATGCAGAAACAACTCATTGTCTCAATTCTCGTATTCACCTCTTTGGCGTTTGCCACGGCG
lcl|CAJRHG030000008.1_cds_CAH137      ATGCAGAAACAACTCATTGTCTCAATTCTCGCATTCGCCTCTTTGGCGTTTGCCATGGCG
                                      ******************************* **** ****************** ****

lcl|CAJRHG030000008.1_cds_CAH137      GAAAATAAAATTCCTCCTCCCAAGCCGGAAGATGGTCAAAGGGAAACGAAATGGAAGGTG
lcl|CAJRHG030000008.1_cds_CAH137      GACAATAAAATTCCTCCTCCCAAACCGAAAGATGGTCAAAGGGAAACGAAATGGAAGGTG
                                      ** ******************** *** ********************************

lcl|CAJRHG030000008.1_cds_CAH137      GAAGATCCCGGAATCATAAATCTTCAGCACCGCGAGAAGCTTTACGAAAGTGGTCCTCAC
lcl|CAJRHG030000008.1_cds_CAH137      GAAGATCCCGGAATCATAAATCTTCAGCACCGCGAGAAGCTTTACGAAAGTGGTCCTCAC
                                      ************************************************************

lcl|CAJRHG030000008.1_cds_CAH137      CGATTCGACGCCACTGCTGCTTACAAGAAGAACTTTGTTGATAAAATGGATCCTGCCAGG
lcl|CAJRHG030000008.1_cds_CAH137      CGATTCGACGCCACTGCTGCTTACAAGAAGAACTTTGTTGATAAAATGGATCCTGCCAGG
                                      ************************************************************

lcl|CAJRHG030000008.1_cds_CAH137      ACCATTGCGAGAGTCGACTACAAATACCTTCCAGGAGATACTAGTCTGGGTGTACAAGCC
lcl|CAJRHG030000008.1_cds_CAH137      ACCATTGCGAGAGTCGACTACAAATACCTTCCAGGAGATACTAGTCTAGGTCTACAAGCC
                                      *********************************************** *** ********

lcl|CAJRHG030000008.1_cds_CAH137      GAAAACATTCAGCGCTTCGGTACTGTATTGTCTGCCGAAGCAACACGGAATCTCTACAAG
lcl|CAJRHG030000008.1_cds_CAH137      GAAAACATTCAGCGCTTCGGTACTGTATTGTCTGCCGAAGCAACACGTAATCTCTATAAG
                                      *********************************************** ******** ***

lcl|CAJRHG030000008.1_cds_CAH137      GATCGAAAGAGTTCTTTGGATGTTGGTGTCAACTACGGACAAACTTTTTCACCGTTTGTC
lcl|CAJRHG030000008.1_cds_CAH137      GATCGAAAGAGTTCTTTGGATGTTGGTGTCAACTACGGACAAACGTTCTCACCGTTTGTC
                                      ******************************************** ** ************

lcl|CAJRHG030000008.1_cds_CAH137      AGAAGCGAACCTTTCTTTGGAGGATTCGTCAGAGGAAGATTCTAA
lcl|CAJRHG030000008.1_cds_CAH137      AGAAGCGAACCTTTCTTTGGTGGCTTTGTCAGAGGAAGATTTTAA
                                      ******************** ** ** ************** ***
```

## attacin 1b

This is missing from the genoscope assembly. There is a 191-aa protein in the purdue assembly with 98% identity (118/120). As far as I can tell, we were the first to describe it in 2014, where we called it attacin 2. Jo et al. 2018 describe it as attacin 1b. Our RNAseq agrees with Jo et al. on the length of 150 aa.

The cds of the purdue gene does not retrieve a decent hit in the genoscope assembly. In fact the purdue contig that contains this gene is very small at around 9kb. Could find about half of the contig in the genoscope assembly but not the gene. I'm assuming that this attacin is in a difficult region. 

The N-terminal end of the purdue version is different to the sequence of the korean attacin 1b and our predicted protein from the RNAseq. I think the purdue version is probably not complete:

```
attacin                   -------MNMQTVYIIALCCLASALARPGNTKPEDQSQTK--------------------
comp38697_c0_m.22078      -------MNMQTVYIIALCCLASALARPGNTKPEDQSQTK--------------------
KAH0813379.1              MLELATDSDSGDRLATANRCLEGPLMVDINARLKKKTQTKLQGDKSGERALYYKLPLIEV
                                  :       *  ** ..*    *:. :.::***                    

attacin                   --------------WGVRDGVLNVEHHGNLYKNDNHRFDGTASVTKNFVDNKDPLLVGGR
comp38697_c0_m.22078      --------------WGVRDGVLNVEHHGNLYKNDNHRFDGTASVTKNFVDNKDPLLVGGR
KAH0813379.1              RLQFFVLSHSRQTKWGVRDGVLNVEHHGNIYKNDNHRFDGTASVTKNFVDNKDPLLVGGR
                                        ***************:******************************

attacin                   VDYKHLPSNSAIGLGAVNAGQFGTKVDLEASRTLFKDRFSQFDAGVSYGQRFGGPFGNSE
comp38697_c0_m.22078      VDYKHLPSNSAIGLGAVNAGQFGTKVDLEASRTLFKDRFSQFDAGVSYGQRFGGPFGNSE
KAH0813379.1              VDYKHVPSNSAIGLGAVNAGQFGTKVDLEASRTLFKDRFSQFDAGVSYGQRFGGPFGNSE
                          *****:******************************************************

attacin                   PVFGGFIRGRF
comp38697_c0_m.22078      PVFGGFIRGRF
KAH0813379.1              PVFGGFIRGR-
                          ********** 
```

# coleoptericins

The coleoptericins are also clustered together. In the Genoscope assembly, there are 3 full-length ORFs and one partial ORF. The purdue assembly has resolved things differently, with a single larger mRNA that seems to encode a 871-aa protein with multiple coleoptericins in there as well as a neighbouring protein (CAH1367450.1 in Genoscope). Don't know which is correct but from our RNAseq data (see figure below) I think it looks like three separate transcripts rather than a giant one. There is some linkage of reads between the genes but I think this is probably because they are so similar. Tenecin 2 seems to CAH1367451.1 and/or CAH1367452.1. Note that the tenecin 2 sequence was never depositied anywhere, as far as I know.

## coverage of coleoptercins in genoscope assembly

![coleoptericins](https://github.com/Perugolate/tm/blob/main/20221012_coleoptericins.jpg)

# thaumatin

## coverage of thaumatins in genoscope assembly

The two thaumatin-like proteins described by Noh et al. 2016 and Kim et al. 2017 seem to be present as parts of a single protein in both assemblies. The sizes differ - 587 aa in genoscope CAH1373168.1, and 647 aa in purdue KAH0809363.1. In both assemblies TmTLP2 seems to be the N-terminus (but with some differences, see alignment), with TmTLP1 at the C-terminus. The difference in length between CAH1373168.1 and KAH0809363.1 seems to be to do with the sequence between the tmTLPs but to be honest I don't know what is going on there. So far I couldn't find any transcripts in the RNAseq that support tmTLP1 and tmTLP2 as a single gene. Alignment of our RNAseq to the genoscope assembly supports the Noh et al. 2016 description of 2 separate genes/transcripts. There is only coverage of the region encoding the c-terminal portion, which corresponds to TmTLP1. There is no coverage at all for the N-terminus (TmTLP2).

![thaumatins](https://github.com/Perugolate/tm/blob/main/20221012_thaumatin.jpg)

Green shows the region corresponding to TmTLP1, red shows TmTLP2. No support for a single transcript encoding both proteins.

There is also a second thaumatin‐like protein CAH1373167.1 encoded right next to this strange giant thaumatin too.

## CAH1379328.1

When trying to find the Korean thaumatin sequences (couldn't find them in any databases so transcribed them from a figure in the paper) I came accross a 222-aa protein (KAH0809933.1) with a "Thaumatin family" Pfam annotation in the Purdue assembly, which was the only occurence of "thaumatin" in any *T. molitor* GenPept record. The Genoscope version has no Pfam annotation but they both retrieve hits against other thaumatin‐like proteins of insects. 

Other than the two thaumatin‐like proteins described by Noh et al. 2016, I don't know if any of these other two have been described. At least they haven't been submitted to ncbi, so perhaps not.

```
tmTLP2            MFAFVTLFALLAAAQAVEFEVINNEGGPVWLGVLGNPGHTNLNNGGVILNQGQSVTLQAE
CAH1373168.1      MFAFVTLFALLAAAQAVEFEVINNEGGPVWLGVLGNPGHTNLNNGGVILNQGQSVTLQAE
                  ************************************************************

tmTLP2            EDWAGRFWPRTWCNPDTNHCDTGDCGNVLECNGAGGVPPGVSGRDHPQRLGQPRLLRYFP
CAH1373168.1      EDWAGRFWPRTWCNPDTNHCDTGDCGNVLECNGAGGVPPVSLAEITLKGWGN---LDYYD
                  ***************************************   .    :  *:   * *: 

tmTLP2            WWTVTISGYLWSRLMDKVT----GSEYSCRKCECAVNLLDSCPQELKVTNGEGAVVACNS
CAH1373168.1      --ISLVDGYNIRISLEPINGQGDGSEYSCRKCECAVNLLDSCPQELKVTNGEGAVVACNS
                       :.**     :: :.    *************************************

tmTLP2            ACGAFNTDEYCCRGDHGTPETCKSSDWPVDYPAFFKQNCPDAYSYAYDDHKSTFTCQAEK
CAH1373168.1      ACGAFNTDEYCCRGDHGTPETCKSSDWPVDYPAFFKQNCPDAYSYAYDDHKSTFTCQAEK
                  ************************************************************

tmTLP2            YVITF-------------------------------------------------------
CAH1373168.1      YVITF (truncated)
                  *****          
```

# RNAseq validation

This is just a reminder for myself of how I aligned the RNAseq data to the genoscope assembly.

## alignment

Need to use the genome instead of the transcripts. 

```bash
mkdir /srv/public/users/paul/20221007_tm/genoscope/data/GCA_907166875.3/star_idx/
/srv/public/shared/software/src/STAR-2.6.0a/bin/Linux_x86_64/STAR --runThreadN 6 \
--runMode genomeGenerate \
--genomeDir  /srv/public/users/paul/20221007_tm/genoscope/data/GCA_907166875.3/star_idx \
--genomeFastaFiles /srv/public/users/paul/20221007_tm/genoscope/data/GCA_907166875.3/GCA_907166875.3_Tenebrio_molitor_v3_genomic.fna \
--sjdbGTFfile /srv/public/users/paul/20221007_tm/genoscope/data/GCA_907166875.3/genomic.gff \
--sjdbGTFtagExonParentTranscript Parent \
--sjdbOverhang 99
```

Had to specify `Unsorted` otherwise `STAR` segfaults on the sorting step. Will sort it directly with `samtools`.

```bash
mkdir -p results/star
# note the threads
/srv/public/shared/software/src/STAR-2.6.0a/bin/Linux_x86_64/STAR --runThreadN 80 \
--genomeDir  /srv/public/users/paul/20221007_tm/genoscope/data/GCA_907166875.3/star_idx \
--readFilesIn /srv/public/users/paul/20221007_tm/all.fastq \
--outFileNamePrefix results/star/all \
--outSAMtype BAM Unsorted \
--outSAMunmapped Within \
--outSAMattributes Standard
```

```bash
samtools sort -l 9 -m 2G -o allAligned.sorted.out.bam -@ 80 allAligned.out.bam
```

```bash
igvtools count -z 5 -w 25 -e 250 allAligned.sorted.out.bam  allAligned.sorted.out.tdf  ../../GCA_907166875.3_Tenebrio_molitor_v3_genomic.fna
```

# References

Jang HA, Park KB, Kim BB, Ali Mohammadie Kojour M, Bae YM, Baliarsingh S, Lee YS, Han YS, Jo YH. In silico identification and expression analyses of Defensin genes in the mealworm beetle Tenebrio molitor. Entomological Research. 2020 Dec;50(12):575-85.

Jo YH, Park S, Park KB, Noh MY, Cho JH, Ko HJ, Kim CE, Patnaik BB, Kim J, Won R, Bang IS. In silico identification, characterization and expression analysis of attacin gene family in response to bacterial and fungal pathogens in Tenebrio molitor. Entomological research. 2018 Jan;48(1):45-54.

Johnston PR, Makarova O, Rolff J. Inducible defenses stay up late: temporal patterns of immune gene expression in Tenebrio molitor. G3: Genes, Genomes, Genetics. 2014 Jun 1;4(6):947-55.
Noh MY, Jo YH. Identification and sequence analysis of two thaumatin‐like protein (TmTLP) genes from Tenebrio molitor. Entomological Research. 2016 Nov;46(6):354-9.

Kim DH, Noh MY, Park KB, Jo YH. Expression profiles of two thaumatin‐like protein (TmTLP) genes in responses to various micro‐organisms from Tenebrio molitor. Entomological Research. 2017 Jan;47(1):35-40.

