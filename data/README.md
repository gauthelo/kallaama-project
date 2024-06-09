# Data

## Description
This directory contains the whole data curated during the KALLAAMA project.    
It is composed of texts gathered from the Web, orthographic transcriptions of audio, and a phonetic transcriptions of words in the 3 most widely spoken languages in Senegal: Wolof, Pulaar and Sereer. 

### Folder tree
Folder is organized as follows:    

    .    
    ├── lexicons/    
    ├── text_corpora/    
    └── transcriptions/    

       
### Composition
- **lexicons/**    
    - This folder contains the data relative to word pronunciation.     
    The file is a pronunciation lexicon, often used in ASR and TTS modeling.     
    Each line consists of a word followed by its phonetic transcription (the pronunciation).    
    We also provide the Grapheme-to-Pronunciation (G2P) model that were trained to generate  phonetic transcriptions from a list of words.    
    
- **text_corpora/**    
    - This folder contains texts gathered from the Web.    
    There is one file per language.    
    
- **transcriptions/**    
    - This folder contains transcriptions of recordings.     
    Transcriptions validated by supervisors (someone other than the transcriber) are in *checked/* subfolder.    
    Original transcriptions made by native speaker linguists are in *raw/* subfolder.    
    
## Audio Set 
Audio recordings are only hosted on external platforms.     
Data sets can be downloaded from OpenSLR or Zenodo:
- OpenSLR: https://www.openslr.org/151/
- Zenodo: https://zenodo.org/records/10892569     
     
### Metadata
For details about the speech data sets, see [metadata.md](./metadata.md).


## Notes
- Textual dataset creation was carried out by Boubacar DIALLO (Assane Seck University, Ziguinchor, Senegal) during its final year intership in NLP during the summer 2023 at Jokalante (Dakar, Senegal). Boubacar speaks Pulaar and Wolof.   
 
- Transcription work was carried out by Maimouna DIALLO for Wolof, Houleye Amadou KANE for Pulaar and Fatou DIOUF for Sereer, during their summer internship, as part of their linguistics studies at Cheikh Anta Diop University (Dakar, Senegal), in 2023 at Jokalante.    
