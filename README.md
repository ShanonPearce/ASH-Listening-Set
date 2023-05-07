## Audio Spatialisation for Headphones
The **Audio Spatialisation for Headphones (**ASH**) Listening Set** is a continuation of the [ASH-IR-Dataset](https://github.com/ShanonPearce/ASH-IR-Dataset) project. It includes a set of binaural room impulse responses (BRIRs) suitable for everyday listening, a comprehensive set of headphone correction filters (HpCFs), and a set of configuration files for Equalizer APO. The dataset can be used to create spatial surround sound on headphones by convolving an audio stream with a set of BRIRs and a HpCF.

## Binaural Room Impulse Responses
The dataset includes a set of BRIRs derived from a range of publicly available BRIR datasets. The BRIRs were measured using head and torso simulators (HATS) in a variety of reverberant rooms, each containing unique acoustical properties. For each room, a set of BRIRs are provided for a range of source directions around the head on the horizontal plane. The BRIRs have been equalised to remove undesired spectral colouration and to make the BRIRs compatible with diffuse-field equalised over-ear and on-ear headphones. An additional compatibility filter is supplied to provide compatibility with in-ear headphones. The BRIRs are provided as 2 channel WAV files with a sampling rate of 44100Hz. A set of true stereo BRIRs and HeSuVi compatible BRIRs are also provided.

## Headphone Correction Filters
The dataset also includes correction filters for a wide range of headphones. The filters can be used to equalise individual headphones to the diffuse-field target frequency response. Individual headphone equalisation is recommended to remove undesired spectral colouration introduced by the listener's headphones and to improve the plausibility of the binaural simulations. The filters are provided as single channel WAV files with a sampling rate of 44100Hz. Magnitude response plots of the filters are also provided.

## Equalizer APO Configuration Files
The dataset can be used with [Equalizer APO](https://sourceforge.net/projects/equalizerapo/), an Audio Processing Object (APO) for windows featuring convolution capabilities. Configuration files for BRIR convolution are provided for each room in the dataset and for a range of common speaker configurations. Sample configuration files for HpCF convolution are also provided. Configuration steps for Equalizer APO can be found in the [wiki](https://github.com/ShanonPearce/ASH-Listening-Set/wiki/Equalizer-APO-Configuration).

## License
Unless otherwise stated, all files in this repository are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/

## Further Information
Refer to the [Wiki](https://github.com/ShanonPearce/ASH-Listening-Set/wiki) for more information about the dataset including [configuration instructions](https://github.com/ShanonPearce/ASH-Listening-Set/wiki/Equalizer-APO-Configuration).


