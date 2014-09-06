makam_section_test_dataset
==========================

The section test dataset for classical Ottoman-Turkish makam music

This zip file contains the audio section annotations, score for the paper:

Şentürk, S., Holzapfel, A., and Serra, X. (2014). Linking scores and audio recordings in makam music of Turkey. Journal of New Music Research, 43:34–52.

For more information about the dataset, please refer to the paper.

Remarks:
- If an audio recording is related to multiple works (e.g. multiple compositions are performed in the recording), in the audio_metadata we only keep the work of the score.
- The "title" fields in the audio_metadata might have unicode characters.
- In the original symbTr format the sections are given in the "Soz1" (Lyrics1) field. This field is used for the lyrics of the vocal compositions and the sections of the instrumental compositions. We created another field called "Bolum1" (Section1) for the dedicated to sections. 
In the instrumental compositions, we copied the section names already given in the "Soz1" field and manually corrected any erroneous jumps.
For the vocal compositions, we manually labeled the score sections from the repetitions in the the lyrics and the melody. In the future we plan to automate the extraction from the repetition of the symbolic lyrics and melody repetitions.
