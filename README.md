# HarmonicaDataset
 Diatonic Harmonica Dataset 

Automatic Music Transcription Harmonica
This paper presents a method for automatic transcription of the diatonic Harmonica instrument. It estimates the multi-pitch activations through a spectrogram factorisation framework. This framework is based on Probabilistic Latent Content Analysis (PLCA) and uses a fixed 4-dimensional tensor with spectral templates extracted from Harmonica’s instrument timbre. Methods based on spectrogram factorisation may suffer from local-optima issues in the presence of harmonic overlapping or considerable timbre variability. To alleviate this issue, we propose a set of harmonic constraints that are inherent to the Harmonica instrument note layout or are caused by specific diatonic Harmonica playing techniques. These constraints help to guide the factorisation process until the convergence into meaningful multi-pitch activations is achieved. This work also builds a new audio dataset containing solo recordings of diatonic Harmonica excerpts and the respective multi-pitch annotations. We compare our proposed approach against multiple baseline techniques for automatic music transcription on this dataset and report the evaluation based on frame-based F-measure statistics.

Link to the article: https://ieeexplore.ieee.org/document/8682334/
