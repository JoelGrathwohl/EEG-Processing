# EEG-Processing
Processing pipeline for mobile EEG data from the CoMoCut study.




**01:** 
- _Annot: Process Raw files together with force plate data to get events (RS: direction signal; IC: initial contact). Also concatenate all data from one session (usually 4 blocks)

**02:**
- _newProcess: Use classic preprocessing (filter, average ref) and pyPREP, ASR and AMICA for rejecting artifacts
- _GEDAI: Use classic preprocessing (filter, average ref) and GEDAI and AMICA for rejecting artifacts
