---
layout: post
title: Mar. '24 Lab Log
categories: Log
tags: 
---

# Mar. '24 Lab Log

## Contents:
- [**March Goals**](#goals)  
- [**Daily Logs**](#log)     


## <a name="goals"></a> **February Goals**

Feb goals I finished: 
- QC_WGS
    - [] Finish Belize extractions (Wait to lib prep until more samples)
    - [x] Make Rmd file for lcWGS data analysis 
    - [x] Analyze genohub data 
- Octo_Rest
    - [] Submit another draft to Carlos 
    - [] Submit draft to review for a journal?
- TLAP
    - [x] Help with modeling 
    - [] Continue reading to fill in gaps in the paper 
- Lab 
    - [] Inventory post PCR freezers
    - [] Create an exit google form for the lab to know where peoples samples are and when they can be disposed of

March goals: 
- QC_WGS
    - [x] Finish BZ and HO extractions
    - [] Run dDocent with mtDNA as ref genome
    - [] Run dDocent with indv from all sub populations
- Octo_Rest
    - [x] Submit draft to Jack
    - [] Submit draft to review for a journal?
- TLAP
    - [x] Help with modeling 
    - [] Continue reading to fill in gaps in the paper 
    - [x] Submit an abstract for Astrangia conference to Carlos by 15/03
- MGPR21
    - [x] Finish protein assays for all heat stress samples 
    - [x] Update volume data so I can analyze protein data
    - [] Finish chlorophyll assays for all heat stress samples
    - [] Send Matias analyzed data 
- Lab 
    - [] Inventory post PCR freezers
    - [] Create an exit google form for the lab to know where peoples samples are and when they can be disposed of

## Mar 29 
- JP suggested to run FreeBayes manually on the mt-DNA becuase there is only 1 chromosome and 1 ploidy. He also said that moving forward I can add a FASTA file to the pseudo reference by making it one of the contigs that way you will know that the pseudo reference has snails in it. He also told me that my test2 run worked and the SNPs are there. The error I am recieving is a batch error and can be ignored
- Sym count with Haley 

## Mar 28 
- Met with Matias to troubleshoot dDocent protocol -- he wants me to ask JP becuase the program is making a BED file but then not reading it. 
- Worked to rclone QC_WGS raw reads, but then Jacob suggested gzip as a better way

## Mar 26
- Prada Meeting -- no notes just continue coding 
- Prada Lab meeting -- JG presented his disertation proposal 
- Tried dDocent troubleshooting but was not successful 
- Mentored Haley 
    - Lab safety walk through and quiz 
    - Did one practice sym count 

## Mar 27 
- Took the day off for grad school interview/tour at Rutgers 

## Mar 22
- Submitted TLAP Quads abstract to Temperate Coral Conference. I will hopefully be giving a talk :)
- Fixed porblems in MGPR21 Protein scripts. These will not work until I have all the SA info from Rachel
- Worked to troubleshoot QC_WGS mt-DNA analysis with dDocent. I cannot find any fixes on the internet or google group so I will have to chat with Matias and maybe Jon to tackle this problem 

## Mar 21
- MGPR21 protien analysis. All the metadata had to be redone because there were repeat sample names from when a bag was lost and then found later on. I then ran the protein script, but currently the script is not working correctly
- Edits for TLAP quads abstract  

## Mar 19
- Started to analyze MGPR21 protein data 
- Prada weekly meeting: 
    - QC_WGS
        - Ask Matias to work through work flow manually instead of using dDocent 
        - Make BCF file --> use Docent to filter BCF file
    - WF
        - Add all data to drive 
    - Octo_rest 
        - Pseudo = sp. because we potentially had more than one sps 
        - Call outplants fragments 
        - submit to restoration ecology 

## Mar 18
- QC_WGS troubleshooting running dDocent for mt-DNA

## Mar 15 
- RIDEM_WFL second extraction for the remaining samples following [Zymo Quick-DNA Mini-prep Plus kit](https://github.com/wdunster/WDPrada_Lab_Notebook/blob/master/RIDEM_WF_WGS/RIDEM_WF_WGS_Extraction_Protocol.md)

    - Notes: 
        - I double the digetion volume so 380uL of molec water and solid tissue buffer
        - Incubated for 2.5 hrs 
        - 1 vol = 700 uL for all samples

| Sample ID | Preserve | Qbit Stock | Qbit Clean | 
|-----------|----------|------------|------------|
| 205_00005 | Dried    |   394      | 113        |
| 158_00004 | Dried    |   456      | 206        |
| 158_00002 | Dried    |   224      | 92.4       |
| Blank     | Blank    |   0        |         0  | 

## Mar 14
We did a writing retreat today at Danielle's house. I finished my abstract for TLAP light gradient project and submitted to TL and CP for edits. I then started working through JG edits on the octo_rest manuscript. I started by addressing JG's questions about flexibility and ensuring it is clear that flexibility is not inherently bad but instead can be a pro or a con depending on the energetics of the system. 

## Mar 12 
- RIDEM_WF_WGS test extraction following [Zymo Quick-DNA Mini-prep Plus kit](https://github.com/wdunster/WDPrada_Lab_Notebook/blob/master/RIDEM_WF_WGS/RIDEM_WF_WGS_Extraction_Protocol.md)

    - Notes: 
        - I double the digestion reaction volume because it did not seem like enough liquid for the size of the fin clippings. 
        - I then added an additional 95uL of Solid Tissue Buffer to 205-00006 because this fin clipping was much larger than the other sample 
        - After 2 hrs 
        - 1 vol = 370 uL for 158_00003 and Blank 
          1 vol = 470 uL for 205_00006 

| Sample ID | Preserve | Qbit Stock | Qbit Clean | 
|-----------|----------|------------|------------|
| 158_00003 | Dried    |   146      |     105    |
| 205_00006 | Dried    |   109      |    83.2    |
| Blank     | Blank    |    0       |         0  | 

Fin clip before digestion
![](https://github.com/wdunster/WDPrada_Lab_Notebook/blob/master/images/RIDEM_WF_WGS_fin.png)

Fin clip after 2.5 hrs of digestion
![](https://github.com/wdunster/WDPrada_Lab_Notebook/blob/master/images/RIDEM_WF_WGS_digestion.png)


## Mar 11
- QC_WGS [extraction 22]((https://github.com/wdunster/QC_WGS_23/blob/main/QC_WGS_Extraction_Log.md))
- Started to look at JG edits to octo_rest MS
- Carlos and I met twice to discuss which kit and protocol to use for the winter-flounder DNA extractions. We are going to use Zymo Quick-DNA mini-prep plus kit (D4069) and follow the [blue workflow](https://files.zymoresearch.com/protocols/_d4068_d4069_quick-dna_miniprep_plus_kit.pdf) for solid tissue

## Mar 8 
- 5 plates for MGPR21 protein assays 
- Shadowed TL for CHL assay 
- Disposed of lab hazardous waste   

## Mar 7
- Read Zymo mini prep kit and nucleo spin soil kit directions

## Mar 5 
- Prada weekly meeting
    - QC_WGS 
        - work through mtDNA using dDocent 
        - Carlos can teach me how to do each part manually if I have everything prepped for next week 
    - RIDEM_WFlounder
        - 5 fin clips in the chest freezer. We need to know if DNA can be extracted successfully for libraries by the end of the month
        - Use whole fin 
        - Try homogenizing with ceramic bead tubes 
        - Use Zymo Quick DNA Miniprep kit 
    - Mentoring 
        - Be very specific 
        - Make sure you are the one giving info so there is a direct pnt of contact 
- Octo_rest edits, writing, fixing figures. I sent a new draft of JG for edits. I need to fix test size on a few graphs

## Mar 4
- QC_WGS [extraction 21](https://github.com/wdunster/QC_WGS_23/blob/main/QC_WGS_Extraction_Log.md) 
- Octo_rest writing

## Mar 1 
- MGPR21 4 protein assays 
- Organized samples and platemaps for easier future work 
- QC_WGS met with Matias to chat about how to use mtDNA as a reference genome and blast against the NCBI database.
    - upload mtDNA FASTA file from NCBI to the cluster 
    - when I already have a ref genome assembly = no in the dDocent .sh file 
    - less_ command allows you to view compressed files such as fastq.gz 

