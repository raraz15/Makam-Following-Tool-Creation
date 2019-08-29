The .ipynb files in this folder are mostly utilizing Essentia Library. 

These notebooks are used for the creating the Makam Following Tool's back end. 

Makam Information is for creating a **Makam Information Dictionary** and saving it in a json file. 
The dictionary includes the **name of the tonic**, the **name of the dominant**, **names of the perdeler** 
( specified in the AEU system) and their corresponding **cents**.

Half_AUtomatic Pitch Track Smoother is for reading a manually edited pitch track and automatically,
Octave Correcting, Smoothing the edited regions, Zeroeing frequencies below a threshold and, Unifying the frame rate.

MakamCollectionDownloader is for downloading available recordings from http://dunya.upf.edu in the OTMM Dataset within a target makam collection.
You need to have an account that is authorized to download these recordings.It can be also used for downloading recordings provided with the MusicBrainz ID. 

MBID_List_to_recordingsInfo takes a list of MBIDs and the necessary parametes, and creates a .json file that is intended to work with the Makam Following Tool. 

MultipleRecordings_PitchDistribution calculates the Pitch Distribution for multiple files using the same distribution extraction parameters for all the recordings and plotting the distributions.

SingleRecording_PitchDistribution This notebook is for experimenting with the the pitch distribution creation and peak detection algorithms and in turn accurately identifying the pitch space of the recording. It works for a single recording at a time.