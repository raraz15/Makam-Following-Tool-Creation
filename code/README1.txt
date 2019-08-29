The .ipynb files here do not utilize Essentia and they are for retrieving Usul information and string processing. 
Thus they can be used with any Python environment.

Subset  Annotations adds an usul key to the Makam dictionary and outputs a json file including the old annotations and the usul information.
Makam and Usul names are encoded with Turkish Alphabet.

Usul Finder from MBID retrieves the usül of a recording from https://musicbrainz.org/, using the makam collection 
of https://dunya.upf.edu/ using the MBID.

Usul Name Correcter replaces Turkish usül names written in an unreadable form with their Turkish Alphabet versions.

I chose to use Turkish Characters to respect the original names.

Outputs containing the MBID, Makam, Usul and tonic information are in the metadata folder inside the data folder.
