# Signing-in-the-Wild-dataset
This repository contains the **"Signing in the Wild" dataset**, created as part of a research project on sign language video detection via recurrent neural networks

Please read the paper *"Sign Language Detection 'In the Wild' with Recurrent Neural Networks"*.
Also please read the supplementary document for further information about this dataset. This is available here: https://github.com/mark-borg/sld-supp.pdf

File *candidate_video_urls.txt* contains a long list of URLs returned by YouTube in response to keyword-based queries such as 'sign language', 'signing', 'ASL', 'BSL', etc.
These URLs have not been vetted and may contain incorrect, inappropriate, and low-quality content. We have included this file here only for reasons of posterity. We intend to 
go through this list and vet the videos manually for any future enhancement of this dataset. Thus it **SHOULD NOT BE USED**.

File *Signing_in_the_Wild_video_urls.txt* contais the correct vetted list of 1120 videos for the 3 classes we are interested in. This is the list of videos which should be used and
which constitutes this dataset.

We are including the URLs only here, because the original videos are quite large in size: when downloaded, they will take up 53.4GB of disk space.
For downloading the videos, you can use the code we make available at: https://github.com/mark-borg/sign-language-detection.

File *groundtruth.txt* contains the manual annotations that we have performed on this dataset. Annotation was performed on the videos when sampled at 5Hz (5 fps).
groundtruth.txt contains space-separated data with one row per video frame. The first column is the video ID (as assigned by YouTube), the second column is the frame number,
and the thrid column is the label. The labels are as follows:

- S = signing
- P = speaking
- n = other (non-signing, non-speaking)
- ? = unlabelled frame


------
	
For any queries, please send an email to:    mborg2005@gmail.com

