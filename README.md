# Master-s-Thesis
This repository contains the code and dataset for the master's thesis "The Speculum Scribe's copy of the Middle Dutch translation of the four gospels: A computational comparison of Vienna, ÖNB, SN, 12.857 and its potential exemplars" by Anouck Kuypers.

- Alignment: The Python library by Folgert Karsdorp necessary to apply the Needleman-Wunsch algorithm to create the alignment tables. (also available here: https://github.com/fbkarsdorp/alignment)
- dataset: contains chunked alignments in "V_SP_alignment" and "V_B_alignment", as well as Excel files of the full alignment tables ("V_SP_gospels_alignment" & "V_B_gospels_alignment"). The transcriptions of all three manuscripts are also available as raw text. The folders called "txt files" contain .txt files for each page, while the folders called "txt volledig" contain the entire transcription in one .txt file. The transcriptions of Vienna, ÖNB, SN 12.857 and Brussels, KBR, 2979 were made as part of the *Silent Voices* project and were also made available by Wouter Haverals and Mike Kestemont (2023b) on Zenodo as XML files (https://zenodo.org/records/10005366). The Saint Petersburg, BAN, O 256 transcription was made by a specialised HTR model for this thesis.
- graphics: The plots that were created in Jupyter notebook
- Code Master_s thesis - Anouck Kuypers.ipynb: the notebook that contains the necessary code for this master's thesis.
- Output_KBR.txt, Output_SP.txt, Output_V.txt: The filtered transcriptions of the three manuscripts as .txt files

# Abstract
The purpose of this master’s thesis is to reveal if the Speculum Scribe used both Saint Petersburg, BAN, O 256 and Brussels, KBR, 2979 as an exemplar when he constructed Vienna, ÖNB, SN 12.857. These three manuscripts all contain the complete Middle Dutch translation of the four gospels. In previous research, Kwakkel (2002) manually compared specific lines from the three manuscripts (pp. 48-51), while Vandyck, Haverals, and Kestemont (2024a) computationally analysed mean abbreviations densities and plotted bag-of-words models for their corpus, which included these three codices. The current research will perform an in-depth analysis based on concepts from the field of scribal profiling in order to develop a more detailed understanding of the relationship between these manuscripts. The corpus consists of automatic transcriptions created by HTR-models; the model used for the Saint Petersburg manuscript was trained specifically for this research. Distinctive linguistic traits of the manuscripts will be uncovered and the orthograpic variation between the Viennese manuscript and its potential exemplars will be diachronically analysed. These computational methods revealed that the Speculum Scribe likely used the Saint Petersburg and Brussels manuscripts as exemplars, although this can only be said with confidence for certain segments of the texts, specifally the gospel of Matthew and Mark for the Viennese manuscripts, but only the gospel of Mark for the Brussels manuscript. Additionally, a number of specific linguistic traits of the Speculum Scribe could be identified.



# Citations (for this README)
Haverals, Wouter and Mike Kestemont. 2023a. From exemplar to copy: the scribal appropriation of a hadewijch manuscript computationally explored. *Journal of Data Mining & Digital Humanities*, 23, On the Way to the
  Future of Digital Manuscript Studies.

Haverals, Wouters and Mike Kestemont. 2023b. The middle dutch manuscripts surviving from the carthusian monastery of herne (14th century): Constructing an open dataset of digital transcriptions. *Proceedings of the Computational Humanities Research Conference 2023*, 3558:135–152
  
Kwakkel, Erik. 2002. *Die dietsche boeke die ons toebehoeren: de kartuizers van Herne en de productie van Middelnederlandse handschriften in de regio Brussel (1350-1400)*, volume 27. Peeters Publishers.

Vandyck, Caroline, Wouter Haverals, and Mike Kestemont. 2024. Making characters count. a computational approach to scribal profiling in 14th-century middle dutch manuscripts from the carthusian monastery of herne
  monastery. In *Approaches to Digital Codicology: Interdisciplinarity and intersections*. Brepols Publishers.
