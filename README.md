# mfccgan
mfccgan is A Novel MFCC-Based Speech Synthesizer Using Adversarial Learning 

we introduce MFCCGAN as a novel speech synthesizer based on adversarial learning that adopts MFCCs as input and generates raw speech waveform. Benefiting from GAN model capabilities, it generates speech with higher intelligibility than a rule-based MFCC-based speech synthesizer WORLD. We evaluated the model based on a very popular intrusive objective speech intelligibility measure (STOI) and also quality (NISQA score). Experimental results show that our proposed system outperforms Librosa MFCC-inversion (by increase about 26% up to 53% in STOI and 16% up to 78% in NISQA score) and an increase about 10%  in intelligibility and about 4% in naturalness in comparison with conventional rule-based vocoder WORLD that is used in the CycleGAN-VC family, while WORLD needs additional data like F0. Finally using perceptual loss in discriminators based on STOI, could improve the quality some more. WebMUSHRA-based subjective tests also shows the quality of the proposed approach.

You can easily run the code using 4_MFCCGAN_mrh020615.ipynb
but you have to change path to your own local dataset path
