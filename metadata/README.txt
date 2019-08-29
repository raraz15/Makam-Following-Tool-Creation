This folder contains the metadata that is used for the Makam Following Tool. 

annotations.json contains the Makam and tonic information of recordings together with the MBID from the Ottoman-Turkish Makam Music 
Makam Recognition Dataset. The related paper can be found as: Karakurt,
A., Şentürk S., & Serra X. (2016). MORTY: A Toolbox for Mode Recognition and Tonic Identification. 3rd 
International Digital Libraries for Musicology Workshop. New York, NY.

subset_annotations.json, the metadata of the 4 Makam 6 Usul subset of the above dataset;

Focusing on 4 Makamlar: Rast, Huseyni, Saba, Huzzam and 6 Usuller: Yuruk Semai, Duyek, Aksak, Curcuna, 
Devr-i Hindi and Turk AKsagi; a subset of the above dataset is formed in subset_annotations.json. The Makam and tonic information
is taken from annotations.json and Usul information is taken from http://musicbrainz.org. The availability of the Usul information
for the recordings in 4 Makamlar are given with their MBID in the MAKAMNAME_MBID_USUL.txt files in this folder (Replace MAKAMNAME with
one of the Makamlar).

The Dataset contains more recordings from the target Makamlar and Usuller than there are entries in the subset_annotations.json file
because not all the recordings were downloadable from Dunya even with a Researcher account. In total 70 recordings were available to download
together with their information.

MBID-Makam-Usul.xlsx Excel sheet displays the MBIDs of 70 recordings categorized w.r.t their Makamlar and Usuller and the color code that is used for 
selecting the recordings for the Makam Following tool, https://rafael-caro.github.io/makam-following/ is explained in the sheet also.

Info.json, the information dictionary including the makam, usul, title, artist information and
relevant pointers of the 16 selected recordings for the Makam Following Tool (taken from Dunya);

MBID_tonic.json, the tonic information of the 70 available recordings in the subset;

MakamInformation.json, the tonal information dictionary of the 4 target makamlar: Saba, Rast, Huzzam, Huseyni;

octave_error_boundaries.txt, the time instants where the pitch track extraction algorithm makes errors together with the
factor of error. It exists only for some recordings and it is created as a byproduct. 

 
 



