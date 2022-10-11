
| family        | name            | length protein   |  notes                                                             |
|---------------|-----------------|------------------|--------------------------------------------------------------------|
| attacin       | tenecin 4       | 143 aa           | see note below                                                     |
| attacin       | CAH1377308.1    | 154 aa           | 98% (151/154) attacin-1a, Jo et al. 2018                           |
| attacin       | CAH1377309.1    | 123 aa           |                                                                    |
| attacin       | CAH1377310.1    | 154 aa           | 98% (151/154) attacin-1a, Jo et al. 2018                           |
| attacin       | CAH1377311.1    | 161 aa           |                                                                    |
| attacin       | CAH1377312.1    | 161 aa           |                                                                    |
| attacin       | CAH1377313.1    | 161 aa           |                                                                    |
| attacin       | CAH1370004.1    | 164 aa           | 99% identity (162/164) to attacin-2, jo et al. 1018                |
| attacin       | attacin 1b      | 150 aa           | doesn't appear to be in the genoscope assembly but identical protein is present in our RNAseq (comp38697_c0). Hits a 191-aa protein in the purdue assembly with 98% identity (118/120) |
| coleoptericin | CAH1367453.1    | 119 aa           | 98% identity (117/119) with coleoptericin A                        |
| coleoptericin | CAH1367451.1    | 127 aa           | 98% identity (124/127) with coleoptericin B                        |
| coleoptericin | CAH1367452.1    | 127 aa           | 98% identity (125/127) with coleoptericin B                        |
| coleoptericin | CAH1367454.1    | 134 aa (parital start) | the cognate protein KAH0816279.1 in the purdue assembly is 164 aa  |
| cecropin      | CAH1373192.1    | 96 aa            | identical to cecropin, missing in purdue assembly                  |
| (tenecin 3)   | CAH1364178.1    | 96 aa            | identical to tenecin 3                                             |
| defensin      | CAH1375101.1    | 84 aa            | 99% identity (83/84) with tenecin 1
| defensin      | defensin        | 72 aa | cant find this in either genomes or our RNAseq, in all cases tenecin 1 is the closest hit |
| defensin-like | CAH1378923.1    | 71 aa            | identical to "defensin-like" from Jang et al. 2020, see note       |

protein names CAHXXXXXXX.X refer to the Genoscope assembly. KAHXXXXXXX.X refer to the purdue assembly.

# defensin-like

there seems to be a cluster of these genes.


# coleoptericins

The coleoptericins are also clustered together. In the Genoscope assembly, there are 3 full-length ORFs and one partial ORF. The purdue assembly has resolved things differently, with a single larger mRNA that seems to encode a 871-aa protein with multiple coleoptericins in there as well as a neighbouring protein (CAH1367450.1 in Genoscope). Don't know which is correct. Tenecin 2 seems to CAH1367451.1 and/or CAH1367452.1. Note that the tenecin 2 sequence was never depositied anywhere, as far as I know.

# Tenecin 4/attacins

## CAH1377308.1/CAH1377310.1/Attacin 1a
Note that CAH1377308.1 and CAH1377310.1 are both 98% identical to Attacin 1a, but they are not identical to each other:

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

They are conserved at the nucleotide-level, so chances are that the knockdowns and qPCR cover both genes:

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


The amino acid sequence of Tenecin 4 from Chae et al does not retrieve an identical amino acid sequence from either genome project. There are 5 genes with some similarity to tenecin 4 that are clustered together on scaffold [CAJRHG030000008.1](https://www.ncbi.nlm.nih.gov/genome/gdv/browser/genome/?cfg=NCID_1_54628939_130.14.18.128_9146_1665395600_1361713531). These are consistent with our RNAseq data.

![ten4gb](https://github.com/Perugolate/tm/blob/main/CAJRHG030000008.1%5B13496280..13530935%5D.png)


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

```
Tenecin 4         ----------MLKAVQFALSCTILSSAAPT-ASSETKWDIEDPGKLKIQHSGTIFNNGGH
CAH1377308.1      MQKQLIVSILVFTSLAFATAENKIPPPKPEDGQRETKWKVEDPGIINLQHREKLYESGPH
CAH1377310.1      MQKQLIVSILAFASLAFAMADNKIPPPKPKDGQRETKWKVEDPGIINLQHREKLYESGPH
                             : :: ** : . :... *  .. ****.:**** :::**  .:::.* *

Tenecin 4         KLDGEAYGSKSLVDRRDPAVFGGKLDYNHNSG-SSLSVSAQHKEHRGTRVGVEGKYNLYR
CAH1377308.1      RFDATAAYKKNFVDKMDPARTIARVDYKYLPGDTSLGVQAENIQRFGTVLSAEATRNLYK
CAH1377310.1      RFDATAAYKKNFVDKMDPARTIARVDYKYLPGDTSLGLQAENIQRFGTVLSAEATRNLYK
                  .:*. *  .*.:**. ***   ..:**:: .* :**.:.*:: :. ** :..*.. ***.

Tenecin 4         NGPFHADVSGKYDRTYGG-ASSNPSFSTHLTGTVDF
CAH1377308.1      DRKSSLDVGVNYGQTFSPFVRSEPFFGGFVRGR--F
CAH1377310.1      DRKSSLDVGVNYGQTFSPFVRSEPFFGGFVRGR--F
                  :     **. :*..*:.  . *:* *. .: *   *
```

