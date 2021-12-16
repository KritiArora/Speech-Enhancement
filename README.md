# Speech-Enhancement

The speech enhancement task usually consists of removing additive noise or reverberation
that partially mask spoken utterances, affecting their intelligibility. However, little
attention is drawn to other, perhaps more aggressive signal distortions like clipping, chunk
elimination, or frequency-band removal. Such distortions can have a large impact not only
on intelligibility, but also on naturalness or even speaker identity, and require careful signal
reconstruction. Current speech enhancement techniques operate on the spectral domain
and/or exploit some higher-level features. The majority of them tackle a limited number of
noise conditions and rely on first-order statistics. To circumvent these issues, deep
networks are being increasingly used, thanks to their ability to learn complex functions
from large example sets Speech enhancement deep learning systems usually require large
amounts of training data to operate in broad conditions or real applications. This makes the
adaptability of those systems into new, low resource environments an important topic.
In this work, an end-to-end speech enhancement method has been implemented within the
generative adversarial framework. The model works as an encoder-decoder fully-convolutional
structure, which makes it fast to operate for denoising waveform chunks. The results show that
not only the method is viable, but it can also represent an effective alternative to current
approaches. Possible future work involves the exploration of better convolutional structures
and the inclusion of perceptual weightings in the adversarial training so that we reduce possible
high-frequency artifacts that might be introduced by the current model.
