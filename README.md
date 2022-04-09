# Glyco-Decipher: glycan database-independent peptide matching enables discovery of modified glycans and in-depth characterization of site-specific N-glycosylation #

[![Github all releases](https://img.shields.io/github/downloads/DICP-1809/Glyco-Decipher/total.svg)](https://github.com/DICP-1809/Glyco-Decipher/releases/)
[![GitHub version](https://img.shields.io/github/v/release/DICP-1809/Glyco-Decipher.svg)](https://github.com/DICP-1809/Glyco-Decipher/releases/tag/v1.0.2)

Glyco-Decipher is a freely available software tool aimed at sensitive intepretation of tandem mass spectrometry (MS/MS) spectra of N-glycopeptides fragmented by higher-energy collisional dissociation (HCD) in stepped energy mode. It conducts glycan database-independent peptide search for N-glycopeptide spectra and provides comprehensive profiling of N-glycans in complex systems, which enalbes the discovery of unexpected N-glycans that not present in databases and potential modifications on them.

Glyco-Decipher is written in Java programming language, with a graphical user interface (GUI) written in JavaFX. Glyco-Decipher could be downloadeded and executed as a packed .exe application. Instructions on software installation, operation, common problems and other issues could be found in the documentations.

## Cite ##
[Glyco-Decipher enables glycan database-independent peptide matching and in-depth characterization of site-specific N-glycosylation](https://www.nature.com/articles/s41467-022-29530-y)

Zheng Fang; Hongqiang Qin; Jiawei Mao; Zhongyu Wang; Na Zhang; Yan Wang; Luyao Liu; Yongzhan Nie; Mingming Dong & Mingliang Ye

*Nature Communications* **13**, 1900 (2022).

## Tutorial ##
- YouTube: [https://youtu.be/Q6mYwpL7OpU](https://youtu.be/Q6mYwpL7OpU)
- Bilibili (Mainland of China): [https://www.bilibili.com/video/BV1n94y1Z7bV/](https://www.bilibili.com/video/BV1n94y1Z7bV/)

## Download Glyco-Decipher ##
It is recommended to use Glyco-Decipher of the latest version, which could be downloaded [here](https://github.com/DICP-1809/Glyco-Decipher/releases), where previous version can also be acquired. The user manual is also included.

## System Requirements ##
**Environment:** Java Runtime Environment or Java Development Kit with 11 or higher, which could be downloaded [here](https://www.oracle.com/java/technologies/downloads/#java11).

## Run Glyco-Decipher ##
Double click the icon of Glyco-Decipher.exe and a graphical user interface will be shown.

## License Application for Glyco-Decipher ##
A license code is needed for the first time running Glyco-Decipher. User can fill in the table, copy the information and sent it to glyco_decipher@163.com to apply the license code.

![image](https://user-images.githubusercontent.com/84326485/160044627-a955b0c6-141c-43df-84d1-ef24ae8e1e12.png) 
![image](https://user-images.githubusercontent.com/84326485/160045091-12582d7c-8961-49d3-b145-517b555fb169.png)

## Basic Usage ##
- **Interpretation of N-glycopeptide Spectra**

Click the "New Task" button in "File" tab to build a new glycopeptide identificaion task. Edit the search parameter and add the acquired mass spectrometry file into the file list. Click "Start" button to start intact glycopeptide searching.

- **Visualization of Identificaiton Results**

Click the "Open" button in "File" tab to open and visualize the identification results (.gpid). The results are presented at the levels of spectrum, peptide and protein, respectively. With the GUI, users can perform the analysis of fragment ion matching in MS2, the RT distributions of glycopeptides and relative abundance distributions of site-specific glycans.

- **MS1-Based Label Free Quantification**

Click "Export Quantification" button in "Tool" tab and the quantificaiton for each glycopeptide was performed based on the elution curve of the precursor. In addition, the quantification reuslts are also mappped to the site level for site-specific glycan analysis.

## Configuration of Glyco-Decipher ##
Settings in the "configuration.txt" file could be changed for customized glycopeptide identification and quantification. Detailed explanation for each configuration setting could be found in the user manual of Glyco-Decipher.

## Exception Handling ##
Information of errors will be provided when the software is running. If errors are encountered, users can submit issues on https://github.com/DICP-1809/Glyco-Decipher or send email to glyco_decipher@163.com.

## Other Software ##
For other software developed by the Mingliang Ye's Lab, please see [https://github.com/DICP-1809](https://github.com/DICP-1809).

## Contact Us ##
- **Group leader:** Mingliang Ye

**e-mail:** mingliang@dicp.ac.cn

- **Developer:** Zheng Fang

**e-mail:** zhengfang@dicp.ac.cn
